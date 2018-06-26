+++
title = "Tutorials"
+++

The tutorials will take place on 10-11 July 2018. Click the tutorial for more information and register [here](https://user2018.r-project.org/registration/).

**There is a late-breaking change.** Heather Turner will not be able to make it to Australia. Her tutorial notes are available at  https://github.com/hturner/gnm-day-course. We are lucky that Max Kuhn from RStudio has stepped in to provide an alternative tutorial for that time slot. Details are below.

**Information on handling preferences:** Thank you if you entered your tutorial preferences in our form. This has helped us keep tabs on numbers for each tutorial, and allocate presenters to room based on these numbers. We are now quite sure that we can handle all preferences with our room sizes. You can change your mind now! **We are not checking the records of your preferences, you can simply go to the tutorial of your choice in the session. No need to enter any new preferences.**

**You will need your badge to get into the tutorial. It will be colour-coded depending on what session you have registered for.**

<table id="reg-sum">
  <col width="60">
  <col width="60">
  <col width="60">
  <col width="160">
  <col width="160">
  <th>Presenter</th>
  <th>Title</th>
  <th>Venue</th>
  <th>Target audience</th>
  <th>What to bring</th>
  <tr><th colspan="6">Tuesday Morning 9:00-12:30  Break 10:30-11:00 </th> </tr>
  <tr class="clickable" data-toggle="collapse" id="68" data-target=".68collapsed">
    <td>Paula Moraga</td>
    <td>Disease risk modeling and visualization using R</td>
    <td>P8</td>
    <td>People who are interested in health surveillance or any subject that deals with spatially referenced data</td>
    <td>Please come to the tutorial with R and RStudio installed, and ensure you have installed the following packages:"dplyr", "ggplot2", "leaflet", "geoR", "rgdal", "raster", "sp", "spdep", "SpatialEpi", "SpatialEpiApp". The package rgdal may take a long time to install depending on the system so best done ahead of time. We will also need the R package INLA, install it typing this:
<p>
<em>install.packages("INLA", repos = "https://inla.r-inla-download.org/R/stable", dep = TRUE)</em> </p>
</td>
  </tr>
  <tr class="collapse out budgets 68collapsed">
    <td colspan="6"><p>
    In this tutorial we will learn how to estimate disease risk and quantify risk factors using areal and geostatistical data. We will also create interactive maps of disease risk and risk factors, and introduce presentation options such as interactive dashboards and shiny apps. We will work through two disease mapping examples using data of malaria in the Gambia and cancer in Pennsylvania, United States. We will focus on disease risk, but the approaches covered are also applicable to other fields such as climate, ecology or crime. We will cover the following topics:

      <ul>
      <li> Model disease risk in different settings
      <li> Manipulate and transform point, areal and raster data using the spatial packages `sp`, `spdep`, `raster`, `rgdal`, `geoR`, `SpatialEpi` and `SpatialEpiApp`,
      <li> Retrieve high resolution spatially referenced environmental data using `raster`,
      <li> Fit and interpret spatial models using `INLA`,
      <li> Map disease risk and risk factors using `leaflet` and `ggplot2`,
      <li> Communicate results with interactive dashboards using `flexdashboard` and shiny apps using `shiny`.
      </ul>
    </p></td>
  </tr>
  <tr class="clickable" data-toggle="collapse" id="71" data-target=".71collapsed">
   <td>Simon Jackson</td>
    <td>Wrangling data in the Tidyverse</td>
    <td>Auditorium</td>
    <td>Beginner-to-intermediate R users who want to improve the day-to-day quality and efficiency of their data wrangling skills</td>
    <td>Please remember to bring a laptop with R and RStudio installed. To speed things up, please also install the tidyverse package and familiarise yourself with RStudio projects. Data files will be made available online at the workshop.</td>
</tr>
  <tr class="collapse out budgets 71collapsed">
    <td colspan="6"><p>
 	This hands-on tutorial will help beginner-to-intermediate R users take their data wrangling skills to the next level with an introduction to the Tidyverse: a collection of data science packages including dplyr, tidyr, purrr, ggplot2, and more. Using provided data sets and practical examples, you will learn how to efficiently import, tidy, and transform data to more quickly focus on tasks like visualization and modeling.
    </p></td>
  </tr>
  <tr class="clickable" data-toggle="collapse" id="74" data-target=".74collapsed">
    <td>Elizabeth Stark</td>
    <td>Production-ready R: Getting started with R and docker</td>
    <td>P9</td>
    <td>Experience with using the command line and running basic scripts is helpful but not necessary. Some prior exposure to docker, git and cloud computing is helpful but no in depth knowledge is required.</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 74collapsed">
    <td colspan="6"><p>
    We will present some real-world data science scenarios and use these as a basis to walk participants through the process of building and deploying R-docker apps. Participants will gain experience in writing R scripts to run as stand-alone docker applications through examples, discussion and activities. We will provide code that can be used as a basis for participants' own projects.
    </p></td>
  </tr>
  <tr class="clickable" data-toggle="collapse" id="77" data-target=".77collapsed">
    <td>Scott Came</td>
    <td>Applications with R and Docker</td>
    <td>P6</td>
    <td>Attendees with some exposure to Docker interested in building multi-container networked applications using Docker and R</td>
    <td>Attendees should plan to complete Part 1 of the Docker Getting Started orientation at https://docs.docker.com/get-started/ prior to the tutorial. And no worries if you are not planning to bring a laptop to the tutorial, as you can just pair up with someone else for the exercises.</td>
  </tr>
  <tr class="collapse out budgets 77collapsed">
  <td colspan="6"><p>
  In this tutorial we will explore several "advanced" scenarios of using Docker and R together to ease deployment of R applications. Attendees will gain hands-on experience building and deploying docker images for Shiny, databases, plumber, and keras. We will also look at cloud deployment and scaling applications with Kubernetes.
    </p></td>
  </tr>
  <tr class="clickable" data-toggle="collapse" id="80" data-target=".80collapsed">
    <td>Przemyslaw Biecek </td>
    <td>DALEX: Descriptive mAchine Learning EXplanations.  Tools for exploration, validation and explanation of complex machine learning models</td>
    <td>P10</td>
    <td>Applied data scientists, analysts interested in machine learning models.</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 80collapsed">
    <td colspan="6"><p>Complex machine learning models are frequently used in predictive modelling. There are a lot of examples for random forest like or boosting like models in medicine, finance, agriculture etc.
      In this workshop we will show why and how one would analyse the structure of the black-box model.
      <p>
      This will be a hands-on workshop with four parts. In each part there will be a short lecture (around 20-25 minutes) and then time for practice and discussion (around 20-25 min).
      <p>
      * Introduction
      <p>
      Here we will show what problems may arise from blind application of black-box models. Also we will show situations in which the understanding of a model structure leads to model improvements, model stability and larger trust in the model.
      <p>
      During the hands-on part we will fit few complex models (like xgboost, randomForest) with the mlr package and discuss basic diagnostic tools for these models.
      <p>
      * Conditional Explainers
      <p>
      In this part we will introduce techniques for understanding of marginal/conditional response of a model given a one- two- variables.
      We will cover PDP (Partial Dependence Plots) and ICE (Individual Conditional Expectations) packages for continuous variables and MPP (Merging Path Plot from factorMerger package) for categorical variables.
      <p>
      * Local Explainers
      <p>
      In this part we will introduce techniques that explain key factors that drive single model predictions. This covers Break Down plots for linear models (lm / glm) and tree-based models (randomForestExplainer, xgboostExplainer) along with model agnostic approaches implemented in the live package (an extension of the LIME method).
      <p>
      * Global Explainers
      <p>
      In this part we will introduce tools for global analysis of the black-box model, like variable importance plots, interaction importance plots and tools for model diagnostic.
      <p>
      * Literature
      <p>
      Staniak, Mateusz, and Przemysław Biecek. 2017. Live: Local Interpretable (Model-Agnostic) Visual Explanations.
      <p>
      Sitko, Agnieszka, and Przemyslaw Biecek. 2017. FactorMerger: Hierarchical Algorithm for Post-Hoc Testing. https://github.com/MI2DataLab/factorMerger.
      <p>
      Greenwell, Brandon M. 2017. “Pdp: An R Package for Constructing Partial Dependence Plots.” The R Journal 9 (1): 421–36. https://journal.r-project.org/archive/2017/RJ-2017-016/index.html.
      <p>
      Goldstein, Alex, Adam Kapelner, Justin Bleich, and Emil Pitkin. 2015. “Peeking Inside the Black Box: Visualizing Statistical Learning with Plots of Individual Conditional Expectation.” Journal of Computational and Graphical Statistics 24 (1): 44–65. doi:10.1080/10618600.2014.907095.
      <p>
      Apley, Dan. 2017. ALEPlot: Accumulated Local Effects (Ale) Plots and Partial Dependence (Pd) Plots. https://CRAN.R-project.org/package=ALEPlot.
      <p>
      Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. 2016. “‘Why Should I Trust You?’: Explaining the Predictions of Any Classifier.” In, 1135–44. ACM Press. doi:10.1145/2939672.2939778.
      <p>
      Biecek, Przemyslaw. 2017. BreakDown: BreakDown Plots. https://CRAN.R-project.org/package=breakDown.
    </p></td>
  </tr>
  <tr class="clickable" data-toggle="collapse" id="83" data-target=".83collapsed">
    <td>Hanjo Odendaal</td>
    <td>The ultimate online collection toolbox: Combining RSelenium and Rvest</td>
    <td>P7</td>
    <td>Intermediate R users looking to explore online data collection</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 83collapsed">
    <td colspan="6"><p>Rvest from Hadley Wickham has become the go to package for all online collection or website interaction (web-scraping) tasks in R. Although the package is amazing, it is not able to interact with a webpage when the page is dynamically loaded through javascript. For the latter, we need to have a browser that we 'drive' around the website to collect/load and interact with objects. Welcome to Rselenium from John Harrison. The package provides the necessary tools that allows the user to drive a web-browser, from R using script commands. In this tutorial, we will be looking at installing RSelenium, learning basic commands, look at javascript tips and how to play well with others like rvest.
    </p></td>
  </tr>
  <tr><th colspan="6">Tuesday Afternoon 1:30-5:00  Break 3:00-3:30 </th> </tr>
  <tr class="clickable" id="78" data-toggle="collapse" data-target=".78collapsed">
    <td>Thomas Lumley</td>
    <td>fasteR: ways to speed up R code</td>
    <td>P10</td>
    <td>Intermediate R programmers interested in speeding up their code</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 78collapsed">
    <td colspan="6"><p>
    This workshop will cover some intermediate and advanced techniques for optimising R code. We will look at both processing speed and  memory use, but will not cover converting your code into other languages (eg C).
    </p></td>
  </tr>
  <tr class="clickable" id="69" data-toggle="collapse" data-target=".69collapsed">
    <td>Max Kuhn</td>
    <td>Recipes for Data Processing</td>
    <td>P9</td>
    <td>The tutorial is for people who do feature engineering or need to include preprocessing with their models. 
    <td>TBA</td>
</td>
 </tr>
  <tr class="collapse out budgets 69collapsed">
    <td colspan="6"><p>
    R has an excellent framework for specifying models using formulas. While elegant and useful, it was designed in a time when models had small numbers of terms and complex preprocessing of data was not commonplace. As such, it has some limitations. In this tutorial, a new package called `recipes` is shown where the specification of model terms and preprocessing steps can be enumerated sequentially. The recipe can be estimated and applied to any dataset. Current options include simple transformations (log, Box-Cox, interactions, dummy variables, ...), signal extraction (PCA, PLS, ICA, MDS, ...), basis functions (splines, polynomials, ...), imputation methods, and others. An example is used to demonstrate the functionality. 
    </p></td>
  </tr>
  <tr class="clickable" id="72" data-toggle="collapse" data-target=".72collapsed">
    <td>Kevin Kuo</td>
    <td>Deep learning with TensorFlow and Keras</td>
    <td>Auditorium</td>
    <td>Anyone interested in deep learning</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 72collapsed">
  <td colspan="6"><p>
  We begin with a quick introduction of deep learning concepts, just enough to have a working vocabulary to facilitate construction of neural networks during the tutorial. The TensorFlow suite of R packages will be covered, including keras, tfestimators, and tfdatasets. Together with the participants, we build end-to-end workflows to perform classification and regression tasks using neural networks. We discuss the data pre-processing needs specific to neural network models, architectural choices, and best practices. Examples will be chosen to span a wide range of interests, including learning on structured data, time series, and unstructured text and image data.
    </p></td>
  </tr>
  <tr class="clickable" id="75" data-toggle="collapse" data-target=".75collapsed">
    <td>Johann Gagnon-Bartsch</td>
    <td>Looking to clean your data? Learn how to Remove Unwanted Variation with R</td>
    <td>P8</td>
    <td>Data analysis, Statistics, Bioinformatics and Computational Biology</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 75collapsed">
    <td colspan="6"><p>High-dimensional data often suffer from unwanted variation; for example, gene expression data commonly contain batch effects, and fMRI data commonly suffer from various systematic errors as well.  Removing this unwanted variation while preserving the true signal in the data is essential to deriving the right scientific conclusions.  A major complication, however, is that the factors causing the unwanted variation are often unknown and must be inferred from the data.  In this tutorial we present the RUV (remove unwanted variation) package.  RUV methods cover a range of approaches for removing unwanted variation depending on the purpose of the study: differential expression analysis, global data normalisation and visualisation, or classification.  We also demonstrate an R shiny application that provides an overview of the methods, along with interactive options for data visualisation and method diagnostics. 
    </p></td>
  </tr>
  <tr class="clickable" id="81" data-toggle="collapse" data-target=".81collapsed">
    <td>Stephanie Kovalchik</td>
    <td>Statistical Models for Sport in R</td>
    <td>P6</td>
    <td>Beginner to intermediate R users with an interest in sports</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 81collapsed">
    <td colspan="6"><p>The workshop will cover a number of skills and statistical models that are common in sports statistics and show how each can be implemented in R. The workshop will introduce participants to a range of R packages and real sports
examples.
    </p></td>
  </tr>
  <tr class="clickable" id="84" data-toggle="collapse" data-target=".84collapsed">
    <td>Dale Bryan-Brown and Brett Parker</td>
    <td>Spatial modelling using ‘raster’ package</td>
    <td>P7</td>
    <td>People interested in spatial modelling using satellite images, or other raster data sets. Worked examples will revolve around environmental modelling.</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 84collapsed">
    <td colspan="6"><p>The topics covered in this workshop include; an introduction to 1) using R as a GIS (5 minutes), 2) point-type data (5 minutes), and 3) raster data (5 minutes). We will then build on the basic knowledge of using R as a GIS by creating raster data (10 minutes) and exploring its basic features (10 minutes). After that we will import raster data into R (10 minutes) and begin to manipulate its extent, resolution, projection and values (45 minutes) and visualise the data (15 minutes). After the group is comfortable with editing the features of raster data we will discuss summarising raster data using point data (45 minutes). Finally, we will use this summarised data in a simple generalised linear model (45 minutes). The outline in dot-points follows. Times are rough estimates.
    </p></td>
  </tr>
  <tr><th colspan="6">Wednesday Morning 9:00-12:30  Break 10:30-11:00 </th> </tr>
  <tr class="clickable" id="76" data-toggle="collapse" data-target=".76collapsed">
    <td>Julie Josse</td>
    <td>Missing values imputation</td>
    <td>P10</td>
    <td>People who want to know more about how dealing with missing values in their analysis and what is the available methods implemented - Basic knowledge of PCA and linear models are required</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 76collapsed">
    <td colspan="6"><p>
    The ability to easily collect and gather a large amount of data from different sources can be seen as an opportunity to better understand many processes. It has already led to breakthroughs in several application areas. However, due to the wide heterogeneity of measurements and objectives, these large databases often exhibit an extraordinary high number of missing values. Hence, in addition to scientific questions, such data also present some important methodological and technical challenges for data analyst. In this tutorial, we give an overview of the missing values literature as well as the recent improvements that caught the attention of the community due to their ability to handle large matrices with large amount of missing entries. We will illustrate the methods on medical, environmental and survey data. 
    </p></td>
  </tr>
  <tr class="clickable" id="79" data-toggle="collapse" data-target=".79collapsed">
    <td>Carson Sievert</td>
    <td>Interactive data visualization on the web with R</td>
    <td>Auditorium</td>
    <td>Anyone interested in interactive data visualization</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 79collapsed">
    <td colspan="6"><p>
    This tutorial teaches practical workflows for creating interactive web graphics which support common data analysis tasks. Through a series of examples, demos, exercises, and lecture, attendees will gain a foundation for navigating through common barriers of productivity associated with both the creation (e.g. start-up cost, iteration cost, dead-end cost) and distribution (e.g., deployment cost, scaling cost, latency cost) of interactive web graphics.
    </p></td>
  </tr>
  <tr class="clickable" id="70" data-toggle="collapse" data-target=".70collapsed">
    <td>Matteo Fasiolo</td>
    <td>Quantile Generalized Additive Models: moving beyond Gaussianity</td>
    <td>P6</td>
    <td>The attendees should have a basic understanding of regression models and of the basic concepts underlying statistics and machine learning (e.g. probability densities, quantiles, etc).</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 70collapsed">
    <td colspan="6"><p>Generalized Additive Models (GAMs) models are an extension of traditional parametric regression models, which have proved highly useful for both predictive and inferential purposes in a wide variety of scientific and commercial applications. One reason behind the popularity of GAMs is that they strike an interesting balance between flexibility and interpretability, while being able to handle large data sets. The mgcv R package is arguably the state-of-the-art tool for fitting such models, hence the first half of this tutorial will introduce GAMs and mgcv, in the context of electricity demand forecasting. The second part of the tutorial will show how traditional GAMs can be extended to quantile GAMs, and how the latter can be fitted using the qgam R package. By the end of the tutorial the attendees should be able to build, fit and visualize traditional or quantile GAM models, using a combination of the mgcv, qgam and mgcViz R packages. This tutorial is aimed at a broad audience of statistical modellers, interested in using GAMs for predictive or inferential purposes. The models which will be presented in the tutorial have a very wide range of applicability, hence they should be of interest to practitioners in business intelligence, ecology, linguistics, epidemiology and geoscience to name a few.
    </p></td>
  </tr>
  <tr class="clickable" id="73" data-toggle="collapse" data-target=".73collapsed">
    <td>Maria Prokofieva</td>
    <td>Follow Me: Introduction to social media analysis in R</td>
    <td>P7</td>
    <td>The tutorial will aim at the broad range of participants from various backgrounds (business, academics, etc.)</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 73collapsed">
    <td colspan="6"><p>The tutorial will review a range of R packages in social media analysis in R and will aim at teaching general principles of working with social media platforms
 and analysing information there. The social media platform covered are Facebook, Twitter, Instagram and Youtube. Topics covered during the tutorial include: 1. Structure of the social media data (e.g. user-related data, posting related data, hashtags) 2. Benefits
 and challenges working with social media data (textual/non-textual information, large data volume, API limitations, 3. Connecting to a social media platform (e.g. authentication) and downloading data 4. Data analysis of the profile information (e.g. followers,
 likes, dislikes, favorites - platform dependent) 5. Data analysis of textual information (e.g. user posts, comments, dynamics, sentiment analysis, word clouds, etc.) 6. Visualisation of the social media data.
    </p></td>
  </tr>
  <tr class="clickable" id="85" data-toggle="collapse" data-target=".85collapsed">
    <td>Tong He</td>
    <td>xgboost and MXNet</td>
    <td>P11</td>
    <td>TBA</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 85collapsed">
    <td colspan="6"><p> TBA
    </p></td>
  </tr>
  <tr class="clickable" id="82" data-toggle="collapse" data-target=".82collapsed">
    <td>Dirk Eddelbuettel</td>
    <td>Extending R with C++: Motivation, Introduction and Examples</td>
    <td>P8</td>
    <td>Beginning to intermediate users of R who want to go further and farther</td>
    <td>TBA</td>
  </tr>
  <tr class="collapse out budgets 82collapsed">
    <td colspan="6"><p> Rcpp has become the principal venue for extending R with compiled
code. It makes it easy to extend R with C or C++ spanning the
range from simple one-liners to larger routines and bindings of
entire external libraries. We will motivate and introduce Rcpp as
a natural extension to R that provides an easy-to-use and
powerful interface.  Helper functions and tools including RStudio
will be used to easy creation of R extensions.  Several examples
will introduce basic use cases including writing code with
RcppArmadillo which is the most widely-used package on top of
Rcpp.  This provides a natual bridge to the more recent
RcppMLPACK package (which combines the MLPACK machine learning
library with the Armadillo linear algebra library) from which we
will study one or two examples.
    </p></td>
  </tr>
  <tr class="clickable" id="82" data-toggle="collapse" data-target=".82collapsed">
    <td>Charles Gray</td>
    <td>Are you R Curious? (** This is a FREE tutorial.)</td>
    <td>P9</td>
    <td>Beginning users</td>
    <td>Your laptop and enthusiasm</td>
  </tr>
  <tr class="collapse out budgets 82collapsed">
    <td colspan="6"><p> 

Been meaning to quit excel and learn R for ages but not managed to find the time? Or maybe you are just not quite sure what this R thing that everyone is talking about is? This is the workshop for you. 

Or, have you had someone say, “It’s easy to use R. Just type R.”  or “Oh, I just use the lm() function.” and thought, huh? Sometimes R users can trivialise the process of getting started. 

In this workshop, we aim to equip new R users with the confidence to problem-solve their way through getting set up with R and RStudio, and importing and exploring data in R. Developed through discussions amongst RLadies who also teach and communicate, we aim to visit the biggest potential pitfalls of your first data analysis in R. From installation issues with packages, to different data structures, to beginning exploratory data analysis and visualisation in R. 
    </p></td>
  </tr>
</table>
