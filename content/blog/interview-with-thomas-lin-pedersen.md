+++
title = "Interview with Thomas Lin Pedersen"
date = "2018-04-18"
tags = ["interview"]
categories = ["interview"]
author = "Nicholas Tierney"
description = "A conversation with Thomas while he's at the rstudio::conf"
+++

*This interview took place at the [rStudio::conf in San Diego](https://www.rstudio.com/conference/), in
January, 2018. Some things cannot be translated from audio to text - and
one thing that was hard to fully capture is Thomas’s upbeat, friendly,
and positive attitude about just about everything.*

**Nick: **

**What is your name and occupation, and where do you live?**

Thomas:

My name is [Thomas Lin Pedersen](https://www.data-imaginist.com/). I live in Denmark, and am currently
working at [SKAT](https://skat.dk/), the Danish taxation authority, where I’m developing
tools for our other data scientists. I don’t do a lot of modelling
myself, but I make sure the framework and the pipeline is up and
running, so that is really really cool.

**Nick:**

**That’s awesome, so you’re writing tools for other people to use, and
thinking about the framework.**

Thomas:

Yeah, so it’s actually a really really interesting place to be at the
moment. We have access to all this data about everyone in Denmark and
are in the center of everything that comes through the Danish
government.

We’re trying to be more proactive about the knowledge that comes in and
through. We have legal requirements with the EU and Denmark, so there
are a lot of interesting things regarding how to actually apply machine
learning in that context, all this responsibility for the citizens of
Denmark. So, how do make sure that we can be agile, in the sense that we
don’t want to take 20 years to develop something new, we want to get
things out there, but we still want to comply with all the regulations
and so on. I need to develop tools that remove the many of
responsibilities from the actual data scientist, so that they can focus
on doing what they do best - doing the modelling, training the models
and so on, and then they should be able to put it back into the
pipeline.

We have a very software centric view in our data science team, so we
have a continuous delivery platform using [Jenkins](https://jenkins.io). And we are going to
provide all our models as micro-services in docker containers, but still
we want to make sure that everything is running as it should - so we
need to build in monitoring, we need to have full traceability of
every decision that we make. In fact, this year, there are going some
new regulations from the EU, the GDPR, which requires that every
decision on citizens that are based on algorithms to be explained to
citizens that they affect. So, every citizen should be able to say, why
did you do this, why did you choose this? This is one of the reasons why
I developed [lime](https://github.com/thomasp85/lime). For any model that we are using, give
a sense of how this model works for each observation.

There are other ways of explaining machine learning tools, and I think
that there is going to be more research done on this, but if the
explainability part of this, if it is part of the model itself, then we
constrain our model developers to say - you can only use these two or
three models, otherwise we are going to be hurt by this legal
requirement.

**Nick:**

**That’s a really interesting approach! I have heard this has happened
in other companies, where they’ve had to pull out certain models that
they want to use, which to them makes them feel like they are developing
a product that is "less good". So, it’s interesting to hear that the
answer to that CAN be in software and it can be in an analytical
framework. Because [lime](https://github.com/thomasp85/lime) uses some metamodelling framework.**

Thomas:

That’s right, lime does add some overhead. But, if you have full
reproducibility in your framework, then you can reproduce the
prediction, and then you can run lime on request, because lime itself is
quite heavy --- you are training a model to fit for every observation,
training and adding feature selection. It can add an overhead for each
prediction on 1-2 seconds, then if you have 1-2 million rows, it’s going
to be horrible.

But it is interesting, from a data science point of view, these rules
and regulations might seem annoying, but from a public servant point of
view, sure they are annoying, but we have to keep in mind who we are
actually trying to help, and these regulations are here for the citizens
that we actually serving. So, maybe we can’t achieve that extra 0.09%
accuracy, because we can’t use that model that is complex,
but then again, is that really WHY we are doing it? I mean, are we doing
the modelling for our own academic desire, or we actually trying to
solve a problem? And if that problem entails an explainable part, well
then that’s part of the problem spec, and we’re going to solve it in the
best way we can.

**Nick:**

**It is nice to have some grounding - what does this work actually mean,
and who is using it. That is really cool.** **OK, so, how did you first
hear about R, and when did you start using it?**

Thomas:

So during my bachelor degree, the university I went to had decided a few
years before that they were going to use R, as their framework for doing
the base level statistics and mathematics. So, the first mathematics
course that we had, we were introduced to R. And everyone hated it. Because, well, it’s a capable calculator, but for
someone who hasn’t done any programming, it feels kind of horrible. And
the impact of R was not really apparent, when you’re just doing bachelor
level mathematics.

We took up R again in the statistics course, and it was kinda cool,
because you can just type `anova()` and `summary()`, and get all these nice
things. And it was not such a huge burden, because we had some of the
idiosyncrasies put into our head when we did the math. But then after we
took a few more statistics courses, we drifted away from R,
because we didn’t need to do any statistical analysis with R. It was
there, but it was not used.

Then, I went on an internship in Paris, and there was another Danish guy
working there. I needed to do some visualisation, and I was talking to
him about it. We didn’t really use R for visualisation during the
statistics courses, and so I was asking him whether he had something
that was better than excel, and he said:

> *Colleague: "Well, I do have something, but it’s based on this
> programming language called ‘R’, so you might not want to-"*
>
> *Thomas: "Ah, well, I know R, so no problems."*

And then he showed me the [ggplot2 book](https://www.amazon.com.au/ggplot2-Elegant-Graphics-Data-Analysis/dp/331924275X/ref=dp_ob_title_bk), which had just been released
there. I began learning [ggplot2](https://github.com/tidyverse/ggplot2). And that was really where it
started. But I think visualisation is a good way to get
introduced to R. It involves a lot of the things that you need to do,
but you still have this nice feeling of a tangible end product. So you
need to get your data into R, you need some I/O (reading in and writing
out), you need to have some transformation of your data before you can
plot it. So you’ve got all these data transformation steps. You might
need to model something as well, and then make the visualisation. So,
there are a lot of steps, but it’s all with a clear goal of "I want to
make this graph".

So, it preps you well for working onwards with R. Also, that’s
the feeling I’ve had when doing all this other stuff with ggplot2, it
didn’t feel so bad.

**Nick:**

**You are renowned for rapid development of R packages. Are there any
tools or methodologies you attribute this ability to?**

Thomas: 

I think I had this discussion with [Miles McBain](http://milesmcbain.xyz/).
I don't know if I'm renowned, but it's true that I'm
probably rather productive in the sense of publishing R packages. I'm
horribly unstructured, and I have no system at all. People should not
follow my lead if they want to do a lot of R packages. I'm a horrible
front figure for that idea.

Creating an R package, for me, now is natural. This comes
after a couple times. I mean, it's just file naming and doing things the
correct way. So you learn that. It is kind of nice to be
able to internalize this idea that package development is
something that happens in my head while I'm not at the computer. So a lot of the time-consuming part is
about architecture; it's about what I want to solve, how I want to
solve it. Not kind of problems about programming.

This (package development) is something that can rummage in my head
while I do everything else. I can sit down at my computer --- not that I get my code perfect the first time, but debugging is also
something that comes easier with time. So I can perfect my idea of what
I want to do while I'm not in front of the computer, and then make the
best out of the time that I have in front of the computer.

A lot of my development happens during my commute or just in the
evening, because, more or less, everything I do is spare time. I have a
limited amount of time in front of my computer, self-imposed, of course.
I could ignore my family but I don't want to do that.

**Nick: **

**Yeah, it's funny. At least to me, like, a lot of time, you know, I
could still be in the shower and be like "ah, okay. I could try things
this way".**

Thomas:

So I think that's my "methodology". Then, I think I'm a rather creative
person. If I get a good idea,
it can rummage in my head for a long time, maybe subconsciously. Like, I
wouldn't think about it, but then, at some point, it would be so
annoying that I haven't made something out of that idea that I'm kinda
forced to make a package out of it. And this happens quite a lot. So
it's kind of a mix between a bit of methodology and just me being kind
of compulsory about R development.

**Nick: So, I know what you mean about the package development, in the
sense that, I feel like the first time I made an R package it was really
scary. Eventually, you get to the point you're like, "Ah, easy way to
solve this, write these functions, they're all related, they go in a
package." I'll write a package. Once you've worked out how to manage all
those steps that sort of don't really involve, like, thinking, like
heavy thinking, I think that really improves things. I was gonna ask if
you have any thoughts or processes that you go through to develop an
API? Because I feel like that's... So, like, say, for example, with
ggraph, or tidygraph, did it take a lot of time to arrive at that?**

Thomas:

It probably did. And I do think about it. When I was in academia, when I
wanted to describe my academic goals, it was really to make human data
interfaces. This is all about API, sometimes about visualizations. But
APIs and visualization, they are both just interfaces to your data.

It concerns me a lot, but it's one of those things that rummage in
my head. I can't really put a kind of a timestamp on how much time has
been spent. I feel that when I sit down and write the code, there is not
a lot of iteration. Like, I haven't had a version, a lesser version of
the tidygraph API. It was like that when I decided to make the
[tidygraph](https://github.com/thomasp85/tidygraph). I don't begin the journey before I have something that I can
kind of say, "Well, this is what I want to do."

Tidygraph came out of a discussion with Hadley. He's a tidy data guy. I
had the audacity to build something untidy, networks, on top of one of
ggplot2 ([ggraph](https://github.com/thomasp85/ggraph)). And I think he enjoys plotting networks, but then you
had to have the data part that we talked about. You have to have the
step before plotting.

He was kind of annoyed with how that works, so we began talking about
how a new thing might end up looking. We talked about whether we we
wanted to make, like, separate functions for edges and nodes. That would
be another perfectly valid idea, to have `mutate_edges()`,
`mutate_nodes()`, transfer all of these things. And it didn't seem as
elegant in some way, because the code would be very graph specific, in a
sense.

And then, I don't know who thought of it, we thought about switching the
context using a verb (`activate()`). It reinforced the idea that a graph
can just be thought of a two tidy data sets. And also, another kind of
thing that hasn't really materialized, but we're talking about, that
this `activate()` have more general capabilities than just in the graph
context. So, you could easily think about having a tidy approach to
working with databases. Because currently that's still just concerned
with a single table in a database. But with `activate()` you can have this
connection to your database and you just activate the different tables,
work with them. So it would be a more kind of a universal approach to
that. So that's why we ended there. But I hadn't made any code at that
point. It was just talking about how to do it.

And then, the whole idea of graph algorithms, how to do the algorithms
in a tidy way, was something that came after that fact, but it was also
something that was not necessary for the first part of the API to
materialize. So I was just thinking about how do you get access to all
these things in a tidy way, and I knew I wanted that because the
different graph algorithms are a huge part of doing network analysis.

Without the algorithm part there’s really not much to do. Sure, you can
add attributes and stuff to your network, but really want to use is the
network structure for something more than just being there. You want to
add centralities. You want to have ways to do searches in your graph and
so on. And how would that translate into something that fit into
`mutate()`? Because that's really how you add information in a tidy way.
So you want all algorithms to return vectors.

And you wanted the vectors to match with the order of the nodes and
edges and so on. And then it just kinda became apparent, well, you don't
really want to specify, "I want this algorithms for these nodes of this
graph." Inside `mutate()` that part is there already. And then, because we
have the `n()` function in dplyr it is kind of the same as the tidygraph
algorithms, in the sense that it knows its context.

`n()` knows where it's called from, so it will always just give the number
of rows. And it was kind of the schematics that was going forward. You
know, when you're inside mutate, you know the graph, you know which node
or edges you're working with, so you don't...you shouldn't need to
specify these.

**Nick: Do you have any process for developing code? Do you write
pseudo-code for the first pass, and then you sort of work backwards from
there?**

Thomas: No. Well, I sometimes call a function I haven't defined yet.

Thomas: So I think, for a long time, I was becoming better and better at
not writing a function in a thousand lines, but multiple small
functions. And the process at the start was to have a long function, and
then take out code chunks into their own functions. Now, I'm more like I
know what this function should do, so I start writing it and then I
recognise, well, this part seems involved and should go into a separate
function.

I'll just make up a function name and call it, and kind of define in my
head how the syntax and return value should be. And then, just get on
with what I'm doing right now. And then, underneath it, I'll begin to
kind of fill out the blanks. But never in real pseudo-code like that. I
mean, I'm always writing a plain R code.

**Nick: So the process of getting to this point is spending a lot of
time doing the small stuff. Once you get practiced with this, you can
think more broadly about how to solve a task more broadly.**

Thomas:

Yeah, so first you write a horribly long function and you find out that
that's not a really good idea. And then, the next time, you write a new
package or a new function, you might start with a thousand line, but
then you say, "Well, this kinda fits together so we'll refactor it".

And now I can anticipate when this is going to be a bigger thing, so I
know when it has its own function. In terms of kind of how it all ties
together, I think I’m unstructured, but I am kind of good at keeping a
lot of things in my head. I also don’t really write notes - all of my
schoolbooks are completely clean - I’ve had a lot of practice juggling
things in my head simultaneously. I kind of have the feeling of the
number of files, and "which functions should go where" just in my head,
and I can just kind of begin materializing these thoughts without
planning it.

**Nick**:

**Wow, that is amazing, thank you. Changing topic now, have you been to
Australia before?**

Thomas:

No, I have not. But I'm really looking forward to! When I was a kid, I
was traveling in France with my parents a lot, so I've been all over
France and lying in tents, camping. I've filled out a lot of blanks in
Europe as well. But I've never really been that much around the globe.
My wife's family is from Hong Kong, so I've been to Hong Kong and
Beijing. And then, I've been to the USA a couple of times, for
conferences. Now I'm going to Australia, so that's really cool.

**Nick:** **I was gonna ask, do you have any favorite R packages?**

Thomas:

I think [ggplot2](https://github.com/tidyverse/ggplot2) is probably an obvious answer for me, because a lot of
my tools are built on top of that. I'm more of a developer than an R
user. I also use R to solve problems, but being a toolmaker rather than
a tool user kind of gives you another appreciation of some of the
underlying tools. So, [devtools](https://github.com/r-lib/devtools) and [roxygen](https://github.com/klutometis/roxygen) - I couldn't live without
them. They are fantastic. And [Rccp](https://github.com/RcppCore/Rcpp), I mean, I would probably never have
gone into writing compiled code had it not been for Rcpp. So these are
kind of the hidden heroes of R packages. But, if you're just a user, you
wouldn't really care about them.

**Nick**:

**I feel like I don't appreciate Rcpp as much as I should, because I've
never written C++ code outside of R, and when I did do it, I had to run
a function on pairs of values in matrices, it wasn’t very complex, and
it kind of "just worked". I feel like the elegance of everything that
was going on was really what stunned me, because it was too easy.**

Thomas:

It just shows the greatness of the team around Rcpp. I have not had any
formal programming training at all. So, the fact that I can get in and
get comfortable, at least writing rudimentary C++ code, and go "that
didn't feel so bad, let’s dive in a bit deeper". That's a huge win for a
package like that. Especially because R developers are usually not
trained programmers. Starting from scratch with a C++ program is just...
I mean, the amount of craziness that goes into regular software
development, like, we are completely unaware of because we have tooling
that makes the whole compiling step just happens kind of automatically.

So, I have a lot of favorite R packages, but the ones I use the most are
those kind of the underlying heroes. [Rcpp](https://github.com/RcppCore/Rcpp), [knitr](https://github.com/yihui/knitr), [rmarkdown](https://github.com/rstudio/rmarkdown) or [devtools](https://github.com/r-lib/devtools) and [roxygen](https://github.com/klutometis/roxygen). They are fantastic.

**Nick**:

**Many of your public R postings have an artistic flavor. Do you explore
your artistic side using other mediums? **

Thomas:

Every time I've been asked, "If you weren’t doing what you were now,
what would you be doing?" My go-to answer is I would be a photographer
or graphic designer. I have an artistic side, or a graphic side, at
least. I've been taking a lot of photographs when I was younger, I hope
to take it up again.

Last summer, I think, I began fiddling with generative algorithms. I
follow a couple of generative artists on Twitter, and I have always been
impressed how they can use code to generate impressive or intriguing
visualization. Not in the sense of a data visualization, but just
visualizing something. So I got into that, and I have a package not yet
on CRAN called [particles](https://github.com/thomasp85/particles) (on [CRAN](https://cran.r-project.org/web/packages/particles/index.html) now), which is an implementation of
the D3-force algorithm and then some. But, more generally, it's just a
framework for handling particle interactions, and forces, and
constraints in a system. And I kind of did that partly because D3-force
would be nice to have in ggraph but also, partly, because I wanted an
outlet for experimenting with setting up systems that generate something
interesting. And a lot of the things that I have posted on my generative
art has been based on particles, mainly, but also, of course, a lot of
other packages has helped to put that on paper, in a sense.

**Nick**:

**That's really cool. So it's like there's this awesome meta aspect to
this, you want to make art, but to do that, you have to create the tools
so you can make art.**

Thomas:

Yeah, that's kind of it. It's fun to be able to say that, "Well, I made
the algorithm, or I made the system that defines this, but I also built
a tool that helped me make it, and I also built a tool that helped me
put it on paper, and program it." So it's kind of nice. And it's a nice
way to have an outlet for this creativity that I feel I have inside.
That when I develop packages that are not purely kind of artistic or
visual in the sense that it can still help me pursue that.

And then I have all the stickers and logos, which is kind of my little
vise of doing at least some graphic design, which I really enjoy. It's
nice to have purpose to doing that. I mean, if you're not a graphic
designer that are handed assignments, then it can be difficult to just
sit down in front of Illustrator or whatever and say, "Well, what should
I do now?"

**Nick:**

**It's really hard when you don't have a starting point!**

Thomas:

Yeah. So, it’s really nice to have this idea that I want to have some
kind of logo or some kind of visual identity for some of my packages,
and I can just sit down and fiddle with it. I would like to get more
into drawing as well. I haven't really had much time for that, but it'd
be nice to be a better drawer.

**Nick: I would like to get into drawing. I feel like the ability to be
able to put what's in your head onto paper, it's a very fun experience
when you're doing it with code because you can write it out and see it
happen. It's different to have that in a more, I guess, like, permanent
sense.**

Thomas:

Yes. I get it a bit with the generative work that I'm doing. But there's
still this kind of surprise, even for me, because there's a certain
randomness built into my algorithm. So I define the system, and I have
some expectancies about what it will show - I'm putting boundaries,
putting forces into it. But I would never know, precisely, what comes
out of it before the whole rendition process is done. I just go, "Oh,
well, that looks nice."

But it is not the same as going from mind, through arm, down to paper.
That's a completely different thing. Photography is more imminent and
that's also really nice. I really enjoy photography and doing fantastic
things with color and light. But, on the other hand, what I was doing a
lot was kind of architecture and nature photography. And it can still
feel a bit like you're just reproducing someone else's work. Like, a
fantastic photograph of some architecture is just as much a compliment
to the architect that drew the building. And fantastic photography of
nature is a compliment to Mother Nature. And sometimes it feels like
every nice spot has been photographed, like, a million times. So the
feeling of "this is new, this is just me, this is purely me" can be
difficult to achieve in photography as well. You have the immediateness, but you don't have the same sense of
uniqueness.

**Nick**:

**OK, changing topic, how do you see your role in the R community, if
you were to put a name on it?**

Thomas:

Well, I'm a developer of tools. I'm surprised that people care about
what I do, I would say, and it continues to surprise me. I'm surprised
that you invited me as keynote speaker. That blew my mind. So my role
would be a "surprised developer in the corner". I think I'm quite active
on Twitter, and I interact a lot with people through Twitter and
participating in the general discourse. But in my day-to-day life, I'm
just this single developer.

So there's plenty of R users around me in my work now. It's the first
time I've really been in a setting where there's other people doing
things in R. But there’s still the feeling, like, I'm a tool developer.
I don't interact directly with other people during development, so I'm
still kind of a guy that has an idea and makes a package. And then,
people care, somehow. And that's great, of course, but I don't know.
It's kind of still difficult for me to put myself in a role.

**Nick:**

**I think it is always hard to define that role. I've heard this
numerous times from other people who are very good at R programming.
Oftentimes they're the only R programmer, or one of a few in an area.
And it's sort of interesting to see they're by themselves but there's
this community around them that helps them or gives them drive. **

**OK, next question. What is your favorite thing about R?**

Thomas:

I love the expressiveness. R is also my first language. So I think
people, unless they're kind of multilingual in an extreme sense, then
the first language always has special place in their heart. Especially
if they continue to work with it. When I think programming, I think in
R. So for me, R really expressive, because it's what my programming mind
is wired to. So if I decompose a problem, I will decompose it into R.

I think that the second language that I'm mainly familiar with is
JavaScript because I do some D3 as well. But the vectorized idea of R
really sticks with me. And when I think about problems, I predominantly
think about data. That's also why I don’t particularly like Python,
because I don't think data is particularly elegant, even with pandas and
so on. I think it's tacked on. Compare that to R where it’s just, it's a
first-class citizen. I mean, I would even say that it's the main
citizen. So you have data and then you can do stuff with it. For me,
that's a really natural approach to doing data science.

**Nick**

**Yeah that makes sense. For me, I feel like R is all about data first.
There's this approach strongly reflected in the tidyverse about data
being first. It's the first argument and it's the thing that comes out
as well.**

Thomas:

Yeah. And we care about how it looks. It's really an important thing.
It's not so much about algorithms and how they are implemented. Of
course, that can have a huge effect, but as a user, as a programmer, we
want to take care of our data. We are data scientists. We're not algorithm, we're not computer scientists. We're data
scientists. We care about our data.

**Nick: Yeah. Awesome. Okay, can you describe a typical day in your
life?**

Thomas:

Yeah. So, I will wake in the morning at around quarter past six. And I
will get up, and I will try to wake my kids and my wife. We're kind of a
sleepy family, so it's not our kids that wake us up. They have to be
ruffled out of bed. Our family is particularly fond of eating together,
so at breakfast and dinner we will sit together. So we will sit down.
We'll have breakfast together.

And I will either drop them off or my wife will drop them off at
daycare. And then I will go to work. I will probably either just sit by
and empty my head or I'll do some R programming on the commute. I take
the train so I can sit there and fix stuff up. Then I'll get to work, and my mind will be in what we talked about, so I
will develop. I will continue developing R packages and whatever, but,
of course, in a different context. I'll be to not that many meetings,
but in my mind, sometimes too many meetings. Our group is rather young
group and we're really fond of tabletop football. So we built a shiny app to keep track of our ranking, powered by the
Xbox ranking algorithm (TrueSkill). We have a game during the day and have some nice talks. I'll get
home, probably begin preparing dinner, and, yeah.

That’s a standard family kind of day. Pick up the kids, potentially.
Make dinner for the kids. Put the kids to bed. Then I'll have a couple
of hours to share with my wife, or just relax, or do R programming. So
that's kind of it.

**Nick**:

**Great, that's cool. We play ping pong at work and a bit, but we
haven't thought to have a ranking system, that sounds fun!**

Thomas:

So, we have a web app for the phone where you can say which four people
will play. And it will generate the teams, and will give a ranking to
the potential outcome, and how many points will each person get,
depending on whether they win or lose, and all this. And then will be
put into our big board where you have all sorts of statistics.

**Nick**:

**That's awesome. Okay. Do you listen to music while you work or code?
And if so, what sort of music?**

Thomas:

Yes, I do. I listen to a lot of music. It can be anything, really. I
remember having a Twitter discussion with someone about that. Like, that
they wanted music without vocal in it, because it kind of distracts
them. For me, it doesn't really matter. My mind get distracted by
ambient noise. So I'm called auditive, in the sense that my ears pick up
everything, more or less. So it's nice to kind of put a lid on it, and
just be engulfed in programming.

But for me, there's no problem in vocal. I hum along with the vocal. I
can code as well, and so on. I cannot be in a room where a TV is on. I
can sit with my back on the TV, but it doesn't matter. If there is kind
of dialog, if there is some kind event unfolding, then my ears will pick
it up. Even if I hate the show, I will not be able to ignore it. It's
horrible for me. But that also means that I quickly get a song under my
head, and I quickly learn the lyrics to a song.

So it doesn't really bother my mind that there is lyrics because I know
it already, so I can just kind of subconsciously sing along. And the
type of music is everything. I listen to a lot of hip-hop, and a lot of
electronic music, and rock, and indie, and whatever. So, really, kind of
broad spectrum.

**Nick**:

Is there anything particularly exciting that you're working on at the
moment for 2018?

Thomas:

So **patchwork** was never meant to be more than a tech demo, but it
kind of caught on and people seem to be really happy about it. So it's
almost done, more or less. It's just a lot of my packages are waiting
for the next ggplot version to be released. So that's just kind of
sitting there right now. I have some more features that I want to put
in, but it was always meant to be kind of this stupidly simply package
that kind of had a bit of feature creep, but not that much.

Then, I really want to make a package wrapping the SNAP library, which
is a C++ network analysis library. Focused on very high performance.
Nothing bad about igraph, but SNAP is really designed to work with
networks the size of 100,000 nodes and billions of edges, so it's really
cool.

David Robinson has also kindly asked me to take over **gganimate**, which I
have sort of agreed on, on the terms that I rewrite it completely.
Because I have some different thoughts on how the best API is going to
be. And then I want to write books. I say that a lot.

So I think, just around New Year, I made three GitHub repositories for
three books I want to write. I will never know if...or at some point I
will know, if I get the time to do that. With spare time things, it's
kind of...if I begin writing a book, I will not have time to develop
packages.

**Nick: Mm-hmm, sometimes, they can inform each other. Like, as you
flesh out an idea, you start getting better at it.**

Thomas:

Absolutely, absolutely. No doubt about it. It's just, it's a big
project. I mean, I blog a bit. Usually, my blog is just package
announcement right now. I begin to think that my blog will just be that,
because other people are good at making kind of tutorial blogs, and
that's not...I'm not as good at that, but I'm good at writing R
packages. So maybe it's just going to be a collection of announcements.
But a book will be much more than that.

**Nick**:

**So you said three books?**

Thomas:

Yeah, so I would like to write a ggplot2 book. There is a lot of ggplot2 books. 
The reason for this one would be I think ggplot2 is an amazing
piece of work, like the code. It's evolved code over a long time, so it
has not necessarily completely beautiful source code to read, but it's a
fantastic example of a really, really involved package, where you just
have, like, a huge system that interacts with each other.

So what I would like to write is actually the mechanics of ggplot2,
what actually happens. Not how do you build a plot, but what happen when
you press enter. Where does your data flow through? Both as a kind of an
example of a complex R package, how would you approach this problem, but
also just I feel there is a lot of people that actually want to build
ggplot2 extensions but it's daunting to kind of poke at.

I would like to kind of have a book that really described the nerdy,
underlying, nitty-gritty details. Not for one that just want to make
plots, but want to know how this work. So that's one of them. The other
is I want to write a book about [tidygraph](https://github.com/thomasp85/tidygraph) and [ggraph](https://github.com/thomasp85/ggraph), like a tidy
approach to network analysis.

So just how these two packages interacts, how can you use them to kind
of work with network data? Kind of like the tidy text analysis book.

So I have this other kind of ecosystem that I'm managing, which is
[fiery](https://github.com/thomasp85/fiery), which is a web server framework in R. And there is [routr](https://github.com/thomasp85/routr),
and [reqres](https://github.com/thomasp85/reqres) right now, which kind of extended the functionality or
add additional functionality. And I would like to write a book about
back end server architecture, seen from the R perspective.

So both because R programmers are not back end developers, they are not
necessarily very well versed in how the internet works underneath. I
wasn't, either. I decided to write a server framework so I could learn
how.

So, I would like to write a book about just explaining how does the
internet work. How can you exploit that in R? Both from fiery point of
view, but also going to [OpenCPU](https://www.opencpu.org/), and [shiny](http://github.com/rstudio/shiny), and all of these other
tools, and discuss what the differences are, when you want to use one,
and the other.

**Nick**:

That's so cool. I think that's it. Thank you for your time!
