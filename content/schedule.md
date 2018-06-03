+++
title = "Talk Schedule"
+++

**The talks will take place on 11-13 July 2018. Click the talk for more details.**

<!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openWday(event, 'Wednesday')" id="defaultOpen">Wednesday (July 11)</button>
  <button class="tablinks" onclick="openWday(event, 'Thursday')">Thursday (July 12)</button>
  <button class="tablinks" onclick="openWday(event, 'Friday')">Friday (July 13)</button>
</div>

<!-- Tab content -->
<div id="Wednesday" class="tabcontent">
  <table id="reg-sum">
    <col width="40"> <col width="40"> <col width="40"> <col width=40"> <col width="280">
    <th>Time</th> <th>Session</th> <th>Presenter</th> <th>Venue</th> <th>Title</th>
<tr class="clickable" data-toggle="collapse" id="28" data-target=".28collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Maria Holcekova</td>
  <td>TBD</td>
  <td>The dynamic approach to inequality: Using longitudinal trajectories of young women and their parents in determining their socio-economic positions within the contemporary Western society</td>
</tr>
<tr class="collapse out budgets 28collapsed">
  <td colspan="6"> Intensified globalisation and ensuing increased affluence of Western populations has changed the composition of traditional social class system in England. This does not imply the disappearance of socio-economic (SE) classes and inequalities, but rather their redefinition. Unfortunately, limited research has considered the dynamic nature of SE positions, especially in understanding youth transitions from parental to personal SE classes. I address this problem using nationally representative longitudinal data in the Next Steps 1990 youth cohort study in England. Firstly, I explore the parental transition patterns using longCatPlot. Secondly, I visualise missing data through the missmap function in Amelia and impute these values using random forests in missForest. Thirdly, I employ the daisy function within the cluster to create SE groups based on Gower distance, partitioning around medoids, and silhouette width. Finally, I visualise these results using ggplot2. In doing so, I establish five distinct SE groups of young women that contributes to the understanding of new forms of inequality, and I discuss its implications in terms of access to educational and labour market resources. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="171" data-target=".171collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Kevin Kuo</td>
  <td>TBD</td>
  <td>Claims reserving in general insurance with R and Keras</td>
</tr>
<tr class="collapse out budgets 171collapsed">
  <td colspan="6"> In loss reserving, actuaries are concerned with estimating liabilities from current and future, yet to be reported, claims. In this session, we first provide an overview of the loss reserving problem and current techniques. We then frame the loss reserving problem as a predictive modeling problem, and propose a deep learning approach to solve it. We benchmark the model against existing techniques, then discuss applications of deep learning to other problems in actuarial science and insurance. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="232" data-target=".232collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Sangeeta Bhatia</td>
  <td>TBD</td>
  <td>Big Brother is Watching - Using Digital Disease Surveillance Tools for Near Real-Time Forecasting</td>
</tr>
<tr class="collapse out budgets 232collapsed">
  <td colspan="6"> In our increasingly interconnected world, it is crucial to understand the risk of an outbreak originating in one country/region and  spreading to the rest of the world. Digital disease surveillance tools such as ProMed, HealthMap etc. have the potential to serve as important early warning systems as well as complement the field surveillance data during an ongoing outbreak. While there are a number of systems that carry out digital disease surveillance, there is as yet a lack of tools that can compile and analyse the generated data to produce easily understood actionable reports. I will present a flexible statistical model that uses different streams of data (such as disease surveillance data, mobility data etc.) for short-term incidence trend forecasting. I will also highlight an example of disaggregating aggregated data to obtain incidence information at a fine spatial scale. This could be particularly important in instances where information at sub-national levels is lacking or incomplete. The model has been developed in R and will be made available as a R package as well as through a website for use by non-technical stakeholders. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="59" data-target=".59collapsed">
  <td>15:45</td>
  <td>bioinformatics/big data</td>
  <td>Liam Crowhurst</td>
  <td>TBD</td>
  <td>scIVA: Single Cell Interactive Visualisation and Analysis</td>
</tr>
<tr class="collapse out budgets 59collapsed">
  <td colspan="6"> Technological advances enable measurements of gene expression at single cell resolution, creating datasets for investigating biological processes in life science research. Gene Expression data is commonly represented as a matrix of tens of thousands of genes and up to millions of cell, which has created a demand amongst biologists for quick visualisation and analysis. We developed scIVA, a Shiny web app that is designed to be used as an interactive visualisation tool of gene expression datasets, intended for those with little R experience and for users to gain preliminary insights into datasets for further exploration and analysis. The web app will also be available for download as a standalone R package. The web app performs various visualisations, all of which are interactive and downloadable through use of Plotly, integrated with d3 Javascript, as graphing tools. Moreover, scIVA allows for users to search for specific genes, subset by clusters and subpopulations, generate heatmaps and perform statistical analyses. The presentation will include a demonstration of the web app’s key features. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="61" data-target=".61collapsed">
  <td>15:45</td>
  <td>bioinformatics/big data</td>
  <td>Claus Ekstrøm</td>
  <td>TBD</td>
  <td>Using mommix for fast, large-scale genome-studies in the presence of gene-environment and gene-gene interaction</td>
</tr>
<tr class="collapse out budgets 61collapsed">
  <td colspan="6"> The majority of disorders and outcomes analysed in genome-wide association studies are believed to multi-factorial and influenced by gene-environment (GxE), gene-gene (GxG) interactions, or both. However, including GxE or GxG increases the computational burden by several orders of magnitude which makes the inclusion of interactions prohibitively cumbersome.

Finite mixtures of regression models provide a flexible modeling framework for many phenomena. Using moment-based estimation of the regression parameters, we develop unbiased estimators with a minimum of assumptions on the mixture components. In particular, only the average regression model for one of the components in the mixture model is needed and no requirements on any of the distributions.

We present a new R package, mommix, for moment-based mixtures of regression models, which implements this new approach for regression mixtures. We illustrate the use of the moment-based mixture of regression models with an application to genome-wide association analysis, and show that the implementation is fast, which makes large-scale genetic analysis with gene-environment and gene-gene interactions feasible. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="20" data-target=".20collapsed">
  <td>15:45</td>
  <td>bioinformatics/big data</td>
  <td>Florian Rohart</td>
  <td>TBD</td>
  <td>mixOmics: An R package for ‘omics feature selection and multiple data integration</td>
</tr>
<tr class="collapse out budgets 20collapsed">
  <td colspan="6"> The mixOmics R-package contains a suite of multivariate methods that model molecular features holistically and statistically integrate diverse types of data (e.g. ‘omics data as transcriptomics, proteomics, metabolomics) to offer an insightful picture of a biological system.
Our two latest frameworks for data integration; N-integration with DIABLO combines different ‘omics datasets measured on the same N samples or individuals; P-integration with MINT combines studies measured on the same P features (e.g., genes) but from independent cohorts of individuals. Both frameworks are introduced in a discriminative context for the identification of relevant and robust molecular signatures across multiple data sets. 
mixOmics is a well-designed, user-friendly package with attractive graphical outputs. It represents a significant contribution to the field of computational biology which has a strong need for such toolkits to mine and integrate datasets. 
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="32" data-target=".32collapsed">
  <td>15:45</td>
  <td>bioinformatics/big data</td>
  <td>Jacob Bergstedt</td>
  <td>TBD</td>
  <td>﻿Quantifying the immune system with the MMI package</td>
</tr>
<tr class="collapse out budgets 32collapsed">
  <td colspan="6"> The blood composition of immune cells provide a key indicator of human health and disease. To identify the sources of variation in this composition, we combined standardized flow cytometry and a questionnaire investigating demographical factors in 816 French individuals. The study is published in the Nature immunology article “Natural variation in innate immune cell parameters is preferentially driven by genetic factors”.

To facilitate the study, we developed the R package MMI (https://github.com/jacobbergstedt/mmi), which defines a framework to specify a family of models. Operations are implemented for models in the family, such as doing tests, computing confidence intervals or AIC measures and investigating residuals, the results of which are collected in a MapReduce-like pattern. The software keeps track of variables, parameter transformations, multiple testing and selective inference adjustments.

With the package we release the dataset of 816 observations of 166 immune cell parameters and 44 demographical variables. We hope that this resource can be used to generate hypotheses in immunology, but also be of benefit to the broader community, in education and benchmarking. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="60" data-target=".60collapsed">
  <td>15:45</td>
  <td>community/education</td>
  <td>Jonathan Carroll</td>
  <td>TBD</td>
  <td>Volunteer Vignettes; A Case-Study in Enhancing Documentation</td>
</tr>
<tr class="collapse out budgets 60collapsed">
  <td colspan="6"> Vignettes; long-form documentation for a package. Often a use-case, discussion, or scientific article. These are incredibly useful to both users and developers. In 2017, Julia Silge scraped CRAN and found most packages don't have one [1].

At the start of 2018, I decided to give back to the community by 'being the change I wanted to see in the world' and writing a Volunteer Vignette a month, for the entire year. Yet all the new and interesting packages I could think to write something for already had vignettes.

The solution came to me in February; have the community nominate packages. I made the call via Twitter [2] and received an encouraging response. I set about writing the first Volunteer Vignette and immediately discovered bugs and other issues, all of which have lead to positive discussions with the author and updates to the package.

In this talk I will present my first six months of the Volunteer Vignettes Project. I will demonstrate why vignettes are an invaluable step in making a robust R package.

[1] https://juliasilge.com/blog/mining-cran-description/
[2] https://twitter.com/carroll_jono/status/961139524901527552 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="46" data-target=".46collapsed">
  <td>15:45</td>
  <td>community/education</td>
  <td>Lorna Maria Aine</td>
  <td>TBD</td>
  <td>Content For the Community:Leveraging Rmarkdown.</td>
</tr>
<tr class="collapse out budgets 46collapsed">
  <td colspan="6"> It is nightmare to solve an R problem when you cannot find any cheat sheets on the internet. Although many people tend to shy away from the fact that programming with R is so powerful in the data science field, its high time we face it.Data science is becoming more popular and in the next few years and we need to learn beyond the traditional languages of the web and mobile. When I got a chance to start learning R, it was a personal decision that I took with my whole heart until I realised how challenging it was to find content built around R.Either it was too complex for me as a newbie or it was hard to find or none existent or there were no examples to work with. This stirred my need to build simple fun yet educative and example-based content for the next generation of data scientists. It has always been passion to build better for the next generation In this talk, I take us through the pains of building in R while relying on free courses (self-taught R programmer) the journey to documenting my own experience while maximising use of Rmarkdown, and how you too can make a contribution to R content around the globe. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="160" data-target=".160collapsed">
  <td>15:45</td>
  <td>community/education</td>
  <td>DENNIS IRORERE</td>
  <td>TBD</td>
  <td>R labs Africa</td>
</tr>
<tr class="collapse out budgets 160collapsed">
  <td colspan="6"> In this century there is a pent-up demand for “the next big thing”, and R labs Africa is at the right time to lead what is important to many in the areas of big data, data science, machine learning and artificial intelligence. I will reference the quote, “Talent is everywhere, it only needs opportunity to emerge” and this is what the R labs Africa will be about. That is, providing opportunity to marginalized and at risk communities all over Africa to learn about Data science with R through group mentor-ship, real world challenges and providing regular meet up. There will be an Annual R converge where everyone meets to talk about the future of R, share ideas and motivate one another.

When access to knowledge is democratized, we see meaningful social development, because it takes a brilliant mind from a disadvantage background to create transformation solutions that solve problems within his or her domains of life experiences. When brilliance and naïve context find a nexus, true local solutions are created. These are the opportunities R labs Africa will bring to Africa. 

Already, the Akure R user group has reached out to about 62 young minds in the spans of 3 months.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="185" data-target=".185collapsed">
  <td>15:45</td>
  <td>community/education</td>
  <td>Sam Clifford</td>
  <td>TBD</td>
  <td>Classes without dependencies</td>
</tr>
<tr class="collapse out budgets 185collapsed">
  <td colspan="6"> Although important, learning statistics isn’t generally why students choose to study science. To engage a cohort of first year Bachelor of Science students with diverse backgrounds and interests, we decided to design their core first year quantitative methods unit (with no math or programming prerequisites) around R.

The course is designed to be practical; using RStudio and tidyverse packages rather than statistical tables, students can quickly engage in visualisation, data wrangling, writing functions, and modelling as part of a coherent workflow for scientific inquiry.

In this talk, we discuss the learning and teaching principles and activities, outlining the use of blended and problem based learning to teach both the quantitative topic and the use of R, developing students' data analysis skills and confidence.

We discuss how workshop activities , quizzes, problem solving tasks, and the final project (a collaborative scientific article) not only assess students' skills but prepare them for work as a professional scientist. We will discuss students’ feedback on their experience in their journey from novice student to young scientist. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="34" data-target=".34collapsed">
  <td>15:45</td>
  <td>algorithms/models</td>
  <td>Kasey Jones</td>
  <td>TBD</td>
  <td>rollmatch: An R Package for Rolling Entry Matching</td>
</tr>
<tr class="collapse out budgets 34collapsed">
  <td colspan="6"> The gold standard of experimental research is the randomized-control trial. However, many healthcare interventions are implemented without a randomized control group for practical or ethical reasons. Propensity score matching (PSM) is a popular method for approximating a randomized experiment from observational data by matching members of a treatment group to similar candidates of a control group that did not receive the intervention. However, traditional PSM is not designed for studies that enroll participants on a rolling basis, a common practice in healthcare interventions where delaying treatment may impact patient health. Rolling Entry Matching (REM) is a new matching method that addresses the rolling entry problem by selecting comparison group members who are similar to intervention members with respect to both static, unchanging characteristics (e.g., race, DOB) and dynamic characteristics that change over time (e.g., health conditions, health care use). This presentation will introduce both REM and rollmatch, an R package for performing REM to assess rolling entry interventions. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="57" data-target=".57collapsed">
  <td>15:45</td>
  <td>algorithms/models</td>
  <td>Charles T. Gray</td>
  <td>TBD</td>
  <td>varameta': Meta-analysis of medians</td>
</tr>
<tr class="collapse out budgets 57collapsed">
  <td colspan="6"> Meta-analyses bring together summary statistics from multiple sources; which are reported in various ways. In this talk I will introduce the `varameta` package, which will provide an underlying (and reproducible) framework for understanding skewed meta-analysis data and reporting. The `varameta` package accompanies a couple of theoretical meta-analysis papers I am working on for meta-analysis of medians. This package is also designed to be an adjunct to the well-established conventional `metafor` package. In this package I have collated the existing techniques for meta-analysing skewed data reported as medians and interquartile ranges (or ranges). The `varameta` package will also include reproducible simulation documentation (in .Rmd) of existing methods in meta-analysis benchmarked against our proposed estimator for the standard error of the sample median. In this talk I will demonstrate the package, the web interface for clinicians, as well as how it can be implemented in everyday systematic reviews. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="45" data-target=".45collapsed">
  <td>15:45</td>
  <td>algorithms/models</td>
  <td>Teck Kiang Tan</td>
  <td>TBD</td>
  <td>Doubly Classified Models with R</td>
</tr>
<tr class="collapse out budgets 45collapsed">
  <td colspan="6"> When we look at a cross tabulation, could we see any pattern out from it? When the table is big, it is extremely hard to discovery pattern by examining the cell frequencies. Doubly classified models are a set of statistical models aim to reveal patterns out from a cross classification table. There are substantial applications of these models. For instance, social researchers who are interested to find out intergenerational social mobility will find this way of analysing refreshing. These models are not new-fangled, but standard textbooks cover only a few of them, and journal articles are usually too technical to grasp the idea behind the model. For those with little mathematical statistic background, it causes great difficult to understand them. The talk focuses on conveying these models using a new graphical table tool called symbolic tables to give the basic idea about the models. Together, using a few standard R functions, mainly generalized linear model, doubly classified models can be set up easily. Real life examples will be illustrated, extracted mainly from the book titled “Doubly Classified Model with R”, written by the author. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="120" data-target=".120collapsed">
  <td>15:45</td>
  <td>algorithms/models</td>
  <td>Sevvandi Kandanaarachchi</td>
  <td>TBD</td>
  <td>Does normalizing your data affect outlier detection?</td>
</tr>
<tr class="collapse out budgets 120collapsed">
  <td colspan="6"> It is common practice to normalize data before using an outlier detection method. But which method should we use to normalize the data? Does it matter? The short answer is yes, it does. The choice of normalization method may increase or decrease the effectiveness of an outlier detection method on a given dataset. In this talk we investigate this triangular relationship between datasets, normalization methods and outlier detection methods. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="4" data-target=".4collapsed">
  <td>15:45</td>
  <td>applications/reproducibility</td>
  <td>Le Zhang</td>
  <td>TBD</td>
  <td>Build scalable Shiny applications for employee attrition prediction on Azure cloud</td>
</tr>
<tr class="collapse out budgets 4collapsed">
  <td colspan="6"> Voluntary employee attrition may negatively affect a company in various aspects. Identifying employees with inclination of leaving is therefore pivotal to save potential loss. Data-driven techniques, assisted by a machine learning model, exhibit high accuracy in prediction for employee attrition and offer company executives insightful information for decision making.
The talk will cover a step-by-step tutorial about how to build a model for employee attrition prediction and deploy such analytical solution as Shiny-based web service on Azure cloud. R is used as the primary programming language and method for the development. Novel R packages such as AzureSMR and AzureDSVM that allow data scientists and developers to programmatically operate cloud resources and seamlessly operationalize the analytics within an R session, will also be introduced in the talk. Shiny application of the analytics including interactive data visualization and model creation is designed and deployed on Docker containers orchestrated by Kubernetes. Parameters of the deployment environment are carefully tuned to favor scalability of the application. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="107" data-target=".107collapsed">
  <td>15:45</td>
  <td>applications/reproducibility</td>
  <td>Bryan Galvin</td>
  <td>TBD</td>
  <td>Moving from Prototype to Production in R: A Look Inside the Machine Learning Infrastructure at Netflix</td>
</tr>
<tr class="collapse out budgets 107collapsed">
  <td colspan="6"> Machine learning helps inform decision making on just about every aspect of the business at Netflix, so it is important to empower our data scientists with tooling that makes them more effective. To accomplish this, we developed Metaflow-a platform written in Python for data scientists to develop, run, and deploy projects without getting in their way. Some key design features include: 

* Ability to work with the R packages we all know and love with no restrictions
* Scale up seamlessly from local development to the almost infinite resources in the cloud 
* Automatic checkpointing of data and code with immutable snapshots created at each step of the modeling pipeline 
* Deployment made easy with built-in hosting service and scheduling

In this talk, I will present an overview of some of the best practices that are baked into Metaflow, focusing especially on those that can be applied effectively at organizations that are not at Netflix scale. Additionally, I will cover some of the lessons learned from using reticulate to interface R with a large Python project. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="121" data-target=".121collapsed">
  <td>15:45</td>
  <td>applications/reproducibility</td>
  <td>Jason Gasper</td>
  <td>TBD</td>
  <td>Integrating R into a production data environment: A case example of using Oracle database services and R for fisheries management in Alaska.</td>
</tr>
<tr class="collapse out budgets 121collapsed">
  <td colspan="6"> Catch and economic information from fisheries off Alaska are critical for the management and conservation of marine resources. The National Marine Fisheries Service, Alaska Regional Office, uses an Oracle database to monitor and store federal fishery catch data off Alaska. Annually, the system processes over 2 million+ fishery catch transactions, and it currently houses over 25 years of historical fishery data. Information in the database includes details on harvested fish, estimates of bycatch, at-sea observations of discards, electronic monitoring of catch (video-derived estimates), geospatial information, and complex business rules to monitor catch allocations to ensure overfishing does not occur.  Our paper provides an high-level overview of the system architecture, with a focus on our use of R-Cran for both development (e.g., simulation and testing) and production (e.g., statistical features) within our Oracle database. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="172" data-target=".172collapsed">
  <td>15:45</td>
  <td>applications/reproducibility</td>
  <td>Joseph Rickert</td>
  <td>TBD</td>
  <td>Connecting R to the "Good Stuff"</td>
</tr>
<tr class="collapse out budgets 172collapsed">
  <td colspan="6"> In his book, Extending R, John Chambers writes: 

One of the attractions of R has always been the ability to compute an interesting result quickly. A key motivation for the original S remains as important now: to give easy access to the best computations for understanding data.

R developers have taken the challenge implied in John’s statement to heart, and have integrated R with some really “good stuff’ while providing easy access that conforms to natural R workflows. Rcpp and Shiny, for example, are both spectacularly successful projects in which R developers expanded the reach of R by connecting to external resources.

In this talk, I will survey the ongoing work to connect R to “good stuff” such as the CVX optimization software, the Stan Bayesian engine, Spark, Keras and TensorFlow; and provide some code examples including using the  sparlkyr package to run machine learning models on Spark and the keras package to run deep learning and other models on TensorFlow.
 </td>
</tr>
  </table>
</div>

<div id="Thursday" class="tabcontent">
  <table id="reg-sum">
    <col width="40"> <col width="40"> <col width="40"> <col width=40"> <col width="280">
    <th>Time</th> <th>Session</th> <th>Presenter</th> <th>Venue</th> <th>Title</th>
<tr class="clickable" data-toggle="collapse" id="99" data-target=".99collapsed">
  <td>10:30</td>
  <td>bioinformatics</td>
  <td>Zachary Foster</td>
  <td>TBD</td>
  <td>Taxa and metacoder:  R packages for parsing, visualization, and manipulation of taxonomic data</td>
</tr>
<tr class="collapse out budgets 99collapsed">
  <td colspan="6"> Modern microbiome research is producing datasets that are difficult to manipulate and visualize due to the hierarchical nature of taxonomic classifications. The “taxa” package provides a set of classes for the storage and manipulation of taxonomic data. Classes range from simple building blocks to project-level objects storing multiple user-defined datasets mapped to a taxonomy. It includes parsers that can read in taxonomic information in nearly any form. It also provides functions modeled after dplyr for manipulating a taxonomy and associated datasets such that hierarchical relationships between taxa as well as mappings between taxa and data are preserved. We hope taxa will provide a basis for an ecosystem of compatible packages. We have also developed the metacoder package for visualizing hierarchical data. Metacoder implements a novel visualization called heat trees that use the color and size of nodes and edges on a taxonomic tree to quantitatively depict up to 4 statistics. This allows for rapid exploration of data and information-dense, publication-quality graphics. This is an alternative to the stacked barcharts typically used in microbiome research. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="35" data-target=".35collapsed">
  <td>10:30</td>
  <td>bioinformatics</td>
  <td>Asya Shklyar</td>
  <td>TBD</td>
  <td>Building an HPC Infrastructure at a Liberal Arts college</td>
</tr>
<tr class="collapse out budgets 35collapsed">
  <td colspan="6"> The buildout of an HPC infrastructure for a Liberal Arts college, from design stage to implementation, with the technology stack, the reasoning behind choosing the technologies, and some interesting use cases. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="184" data-target=".184collapsed">
  <td>10:30</td>
  <td>bioinformatics</td>
  <td>Ramyar Molania</td>
  <td>TBD</td>
  <td>improved normalization of the Nanostring nCounter gene expression data</td>
</tr>
<tr class="collapse out budgets 184collapsed">
  <td colspan="6"> The NanoString nCounter gene expression assay uses molecular barcodes and single molecule imaging to detect and count hundreds of unique transcripts in a single reaction. These counts need to be normalized to adjust for variations in assay efficiency, the amount of sample, and other factors. Most users adopt one of the options described in the nSolver analysis software, which involve background correction based on the observed values for 8 negative control probes, a within sample normalization using the observed values for 6 positive control probes, and normalization across samples using reference (“housekeeping”) genes. Including technical replicates is not recommended by the assay developers, but some users do so anyway.  Here we present a new normalization called RUV3 which makes vital use of technical replicates and suitable control genes.  We illustrate its effectiveness on four quite different datasets, and offer suggestions on the design and analysis of studies involving this technology. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="260" data-target=".260collapsed">
  <td>10:30</td>
  <td>bioinformatics</td>
  <td>Abdul Abdulmonem A. Alsaleh</td>
  <td>TBD</td>
  <td>Identifying methylation biomarkers for childhood leukaemia from human 450k DNA methylation array data using ABC.RAP R package</td>
</tr>
<tr class="collapse out budgets 260collapsed">
  <td colspan="6"> To date, the majority of the available 450k DNA methylation analysis tools focus on single CpG methylation differences. The array based CpG region analysis pipeline (ABC.RAP) R package was developed to analyse normalised human 450k DNA methylation array datasets and applies Student’s t-test and delta beta analysis to identify candidate genes containing multiple differentially methylated CpG sites. In addition, ABC.RAP can profile DNA methylation for any gene of interest, providing a powerful feature for comparison between datasets. We analysed nine publicly available acute leukaemia datasets and identified a panel of 11 genes that were consistently methylated across different cohorts. We used targeted DNA methylation sequencing (MiSeq; Illumina) to sequence blood samples from healthy adults and newborns and also leukaemia xenograft samples and cell lines. The selected panel of genes showed dense DNA methylation in leukaemia samples compared to low-level methylation in control samples consistent with the publicly available 450k array data. ABC.RAP was accepted by the CRAN, and can be accessed on the following site: https://cran.r-project.org/package=ABC.RAP </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="85" data-target=".85collapsed">
  <td>10:30</td>
  <td>community/education</td>
  <td>François Michonneau</td>
  <td>TBD</td>
  <td>Lessons learned from developing R-based curricula across disciplines</td>
</tr>
<tr class="collapse out budgets 85collapsed">
  <td colspan="6"> The Carpentries is a non-profit volunteer organization that teaches scientists with no or little programming experience foundational skills in coding, data science, and best-practices for reproducible research. We offer 2-day workshops for a variety of disciplines including Ecology, Genomics, Geospatial analysis, and Social Sciences. With 1300+ instructors who have taught 500+ workshops on all continents, we worked with our community of instructors to assemble evidence-based curricula using results from research on teaching and learning. We have developed detailed short- and long-term assessments to evaluate the effectiveness and level of satisfaction of our learners after attending a workshop, as well as the impact on their research and careers 6 months or more afterwards. We find that workshop participants program more often, are more confident, and use programming practices that the report make them more efficient and reproducible. Here, we will present the lessons we learned about developing curricula based on teaching R to novices across diverse disciplines, and the strategies we use to instill the desire to continue learning after attending our workshops. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="19" data-target=".19collapsed">
  <td>10:30</td>
  <td>community/education</td>
  <td>Matthias Gehrke</td>
  <td>TBD</td>
  <td>Student Performance and Acceptance of Technology in a Statistics Course Based on R mosaic - Results from a Pre- and Post-Test Survey</td>
</tr>
<tr class="collapse out budgets 19collapsed">
  <td colspan="6"> In the last years there is movement towards simulation-based inference (e.g., bootstrapping and randomization tests) in order to improve students' understanding of statistical reasoning (see e.g. Chance et al. 2016). The R package mosaic was developed with a "minimal R" approach to simplify the introduction of these concepts (Pruim et al. (2017)). 

With a pre and post survey we analysed whether students improved in understanding as well as in acceptance of R during a one semester statistics course in economically related Bachelor and Master programs. These courses were held by different lecturers at multiple locations in Germany. At our private university of applied sciences for professionals studying while working the use of R is compulsory in all statistical courses.

While conceptual understanding was evaluated by a subset of the modified CAOS inventory (like Chance et al. (2016)) the acceptance and use of technology was collected by using an adopted version of UTAUT2 (Venkatesh et al. (2012)).
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="25" data-target=".25collapsed">
  <td>10:30</td>
  <td>community/education</td>
  <td>Mette Langaas</td>
  <td>TBD</td>
  <td>Teaching statistics - with all learning resources written in R Markdown</td>
</tr>
<tr class="collapse out budgets 25collapsed">
  <td colspan="6"> In applied courses in statistics it is important for the student to see a mix of theory, practical examples and data analyses. Being able to study the R code used to produce the data analyses, and to run and modify the R code will give the student hands on experience, which again may lead to increased theoretical understanding.
I will tell about my experiences with producing and using learning material written in R Markdown in two courses in statistics at the Norwegian University of Science and Technology. One course is at the master level (Generalized linear models) with few students (35) and a mix of plenary and interactive lectures. The other course is at the bachelor level (Statistical learning) with more students (70). 
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="164" data-target=".164collapsed">
  <td>10:30</td>
  <td>community/education</td>
  <td>Peter Dalgaard</td>
  <td>TBD</td>
  <td>What's in a name?  20 years of R release management</td>
</tr>
<tr class="collapse out budgets 164collapsed">
  <td colspan="6"> In this talk, I will go through the history of R releases since 1997. I will  discuss the role of the R Core Team with special emphasis on development principles and release management issues. A few "war stories" will also be included.  Some light will be thrown on the choice of release names since 2011. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="66" data-target=".66collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Chester Ismay</td>
  <td>TBD</td>
  <td>Statistical Inference: A Tidy Approach using R</td>
</tr>
<tr class="collapse out budgets 66collapsed">
  <td colspan="6"> How do you code-up a permutation test in R? What about an ANOVA or a chi-square test? Have you ever been uncertain as to exactly which type of test you should run given the data and questions asked? The `infer` R package was created to unite common statistical inference tasks into an expressive and intuitive framework to alleviate some of these struggles and make inference more intuitive. This talk will focus on developing an understanding of the design principles of the package, which are firmly motivated by Hadley Wickham's tidy tools manifesto. It will also discuss the implementation, centered on the common conceptual threads that link a surprising range of hypothesis tests and confidence intervals. Lastly, we'll dive into some examples of how to implement the code of the `infer` package via different data sets and variable scenarios. The package is aimed to be useful to new students of statistics as well as seasoned practitioners. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="81" data-target=".81collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Thomas Lumley</td>
  <td>TBD</td>
  <td>Subsampling and one-step polishing for generalised linear models</td>
</tr>
<tr class="collapse out budgets 81collapsed">
  <td colspan="6"> Using only a commodity laptop it's possible to fit a generalised linear model to a dataset from about a million to a billion rows by first fitting to a subset and then doing a one-step update. The method depends on a bit of asymptotic theory, some sampling, the Fisher scoring algorithm, efficient R-database interfaces, and a little of the tidyverse. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="159" data-target=".159collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>James Hester</td>
  <td>TBD</td>
  <td>Glue strings to data in R</td>
</tr>
<tr class="collapse out budgets 159collapsed">
  <td colspan="6"> String interpolation, evaluating a variable name to a value within a string, is
a feature of many programming languages including Python, Julia, Javascript,
Rust, and most Unix Shells. R's `sprintf()` and `paste()` functions provide
some of this functionality, but have limitations which make them cumbersome to
use. There are also some existing add on packages with similar functionality,
however each has drawbacks.

The glue package <http://glue.tidyverse.org/> performs robust string
interpolation for R. This includes evaluation of variables and arbitrary R code,
with a clean and simple syntax. Because it is dependency-free, it is easy to
incorporate into packages. In addition, glue provides an extensible interface
to perform more complex transformations; such as `glue_sql()` to construct
SQL queries with automatically quoted variables.

This talk will show how to utilize glue to write beautiful code which is
easy to read, write and maintain. We will also discuss ways to best use glue when
performance is a concern. Finally we will create custom glue functions tailored
towards specific use cases, such as JSON construction, colored messages, emoji
interpolation and more. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="132" data-target=".132collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Max Kuhn</td>
  <td>TBD</td>
  <td>Data Preprocessing using Recipes</td>
</tr>
<tr class="collapse out budgets 132collapsed">
  <td colspan="6"> The recipes package can be used as a replacement for model.matrix as well as a general feature engineering tool. The package uses a dplyr-like syntax where a specification for a sequence of data preprocessing steps are created with the execution of these steps deferred until later. Data processing recipes can be created sequentially and intermediate results can be cached. An example is used to illustrate the basic recipe functionality and philosophy. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="100" data-target=".100collapsed">
  <td>10:30</td>
  <td>models</td>
  <td>John Fox</td>
  <td>TBD</td>
  <td>New Features in the car and effects Packages</td>
</tr>
<tr class="collapse out budgets 100collapsed">
  <td colspan="6"> The widely used car and effects packages are associated with Fox
and Weisberg, An R Companion to Applied Regression, the third
edition of which will be published this year. In preparation, we
have released the substantially revised version 3.0-0 of the car
package and version 4.0-1 of the effects package.

The car package focuses on tools, many of them graphical, that are
useful for applied regression analysis (linear, generalized linear, mixed-effects models, etc.), including tools for preparing, examining, and transforming
data prior to specification of a regression model, and tools that
are useful for assessing regression models that have been fit to
data. The effects packages focuses on graphical methods for
interpreting regression models that have been fit to data.

Among the many changes and improvements to the packages are a
reconceptualization of effect displays, which we call "predictor
effects"; the ability to add partial residuals to effect plots of
arbitrary complexity; simplification to the arguments of plotting
functions; new and improved functions for summarizing and testing
statistical models; and improved methods for selecting variable
transformations. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="106" data-target=".106collapsed">
  <td>10:30</td>
  <td>models</td>
  <td>Rainer Hirk</td>
  <td>TBD</td>
  <td>mvord: An R Package for Fitting Multivariate Ordinal Regression Models</td>
</tr>
<tr class="collapse out budgets 106collapsed">
  <td colspan="6"> The R package mvord implements composite likelihood estimation in the class of multivariate ordinal regression models with probit and a logit link. A flexible modeling framework for multiple ordinal measurements on the same subject is set up, which takes into consideration the dependence among the multiple observations by employing different error structures. Heterogeneity in the error structure across the subjects can be accounted for by the package, which allows for covariate dependent error structures. In addition, regression coefficients and threshold parameters are varying across the multiple response dimensions in the default implementation. However, constraints can be defined by the user if a
reduction of the parameter space is desired. The proposed multivariate framework is illustrated by means of a credit risk application. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="97" data-target=".97collapsed">
  <td>10:30</td>
  <td>models</td>
  <td>Heather Turner</td>
  <td>TBD</td>
  <td>PlackettLuce: Modelling Rankings Data</td>
</tr>
<tr class="collapse out budgets 97collapsed">
  <td colspan="6"> This talk introduces the CRAN package PlackettLuce for fitting the Plackett-Luce model to rankings. This model estimates the worth of items being ranked by viewing a ranking as a set of consecutive choices and modelling the probability of an item being chosen above others as the ratio of that item's worth to the total worth of the items from which the choice is made.

PlackettLuce offers several advantages over competing approaches to fit the Plackett-Luce model in R. Firstly it is flexible in the type of rankings that can be handled, in particular it can handle ties, partial rankings and sets of rankings that do not satisfy the conditions for maximum likelihood estimation, for example because one item always comes first in its rankings. Secondly it enables inference on the worth estimates by providing model-based standard errors along with a method for obtaining quasi-standard errors, which don't depend on the identifiability constraints. Finally it provides a method to to work with the psychotree package to fit Plackett-Luce trees.

This presentation will include a novel application of Plackett-Luce trees to data from a citizen science project in agricultural development. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="103" data-target=".103collapsed">
  <td>10:30</td>
  <td>models</td>
  <td>Joachim Schwarz</td>
  <td>TBD</td>
  <td>Partial Least Squares with formative constructs and a binary target variable</td>
</tr>
<tr class="collapse out budgets 103collapsed">
  <td colspan="6"> During the last years, the use of PLS became more and more important for the modelling of dependencies between latent variables as an alternative to classical structural equation modelling. However, a non-metric target variable in combination with formatively measured constructs is still a particular challenge for the PLS-approach.
By using the plspm package (Sanchez/Trinchera/Russolillo 2017), we tested a model from the human resources management field. Main goal of this model is to examine the moderating and mediating role of meaning at work for the relationship between several social, personal, environmental and motivational job characteristics and the intention to quit as a manifest binary target variable. 
Coping with the complexity of the model, consisting of more than 70 latent variables, all formatively measured, many of them one indicator constructs, there are some pitfalls in the application of the plspm package, but due to the flexibility of R, it is possible even to evaluate such a complex model.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="50" data-target=".50collapsed">
  <td>10:30</td>
  <td>algorithms/applications</td>
  <td>David Cooley</td>
  <td>TBD</td>
  <td>Starting with geospatial data in Shiny, and knowing when to stop</td>
</tr>
<tr class="collapse out budgets 50collapsed">
  <td colspan="6"> Theme:
Coupling R with geospatial databases to reduce the calculations and data in R and improve shiny app speed


Like any web page, Shiny apps need to be quick and responsive for a better user experience. Doing complex calculations and storing large data objects will slow the app.  Therefore, it's often desirable to remove as much of this as possible from the app.  

The talk will demonstrate

- Using MongoDB as a geospatial database
- Querying & returning geospatial data to R from MongoDB
- Comparison and benchmarking of geospatial operations in R vs on the database server
- Applying this to a shiny app with a demonstration, highlighting the pros & cons
- Introducing the latest updates to the `googleway` package for displaying data and using Google Map tools through R
- Using Google Maps to trigger database queries and operations </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="68" data-target=".68collapsed">
  <td>10:30</td>
  <td>algorithms/applications</td>
  <td>Jeffrey O. Hanson</td>
  <td>TBD</td>
  <td>prioritizr: Systematic conservation prioritization in R</td>
</tr>
<tr class="collapse out budgets 68collapsed">
  <td colspan="6"> Biodiversity is in crisis. To prevent further declines, protected areas need to be established in places that will achieve conservation objectives for minimal cost. However, existing decision support tools tend to offer limited customizability and can take a long time to deliver solutions. To overcome these limitations and help prioritize conservation efforts in a transparent and reproducible manner, here we present the prioritizr R package. Inspired by the tidyverse principles, this R package provides a flexible interface for articulating, building and solving conservation planning problems. In contrast to existing tools, the prioritizr R package uses integer linear programming (ILP) techniques to mathematically formulate and solve conservation problems. As a consequence, the prioritizr R package can find solutions that are guaranteed to be optimal and in record time. By finding solutions to problems that are relevant to the species, ecosystems, and economic factors in areas of interest, conservation scientists, planners, and decision makers stand a far greater chance at enhancing biodiversity. For more information, visit https://github.com/prioritizr/prioritizr. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="173" data-target=".173collapsed">
  <td>10:30</td>
  <td>algorithms/applications</td>
  <td>Remy Gavard</td>
  <td>TBD</td>
  <td>Using R to pre-process ultra-high-resolution mass spectrometry data of complex mixtures.</td>
</tr>
<tr class="collapse out budgets 173collapsed">
  <td colspan="6"> Scientists are able to determine over hundreds of thousands of components in crude oil using Fourier transform ion cyclotron resonance mass spectrometry (FTICR-MS). The statistical tools required to analyse the mass spectra struggle to keep pace with advancing
instrument capabilities and increasing quantities of data. Today most ultrahigh resolution analyses for complex mixture samples are based on single, labour-intensive, experiments.
We present a new algorithm developed in R named Themis to jointly pre-process replicate measurements of a complex sample analysed using FTICR-MS. This improves consistency as a preliminary step to assigning chemical compositions, and the algorithm has a quality control criterion. Through the use of peak alignment and an adaptive mixture model-based strategy, it is possible to distinguish true peaks from noise.
Themis demonstrated a more effective removal of noise-related peaks and the preservation and improvement of the chemical composition profile. Themis enabled the isolation of peaks that would have otherwise been discarded using traditional peak picking (based upon signal-to-noise ratio alone) for a single spectrum.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="192" data-target=".192collapsed">
  <td>10:30</td>
  <td>algorithms/applications</td>
  <td>Murray Cameron</td>
  <td>TBD</td>
  <td>Exceeding the designer's expectation</td>
</tr>
<tr class="collapse out budgets 192collapsed">
  <td colspan="6"> Statistical methods and their software implementation are generally designed for a particular class of applications. However, the nature of data, analysis and statisticians is that uses of the methods are envisaged that extend the application.  Sometimes the reason is the nature of the data, sometimes it is a new type of model and sometimes it is the limitations of the software available. Software for regression and for generalised linear models have regularly been used in 'non-standard' ways.

We will discuss some examples, considering some changepoint models in particular and emphasise some old lessons for software developers. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="23" data-target=".23collapsed">
  <td>10:30</td>
  <td>space/time/algorithms</td>
  <td>Matt Moores</td>
  <td>TBD</td>
  <td>bayesImageS: an R package for Bayesian image analysis</td>
</tr>
<tr class="collapse out budgets 23collapsed">
  <td colspan="6"> There are many approaches to Bayesian computation with intractable likelihoods, including the exchange algorithm, approximate Bayesian computation (ABC), thermodynamic integration, and composite likelihood. These approaches vary in accuracy as well as scalability for datasets of significant size. The Potts model is an example where such methods are required, due to its intractable normalising constant. This model is a type of Markov random field, which is commonly used for image segmentation. The dimension of its parameter space increases linearly with the number of pixels in the image, making this a challenging application for scalable Bayesian computation. My talk will introduce various algorithms in the context of the Potts model and describe their implementation in C++, using OpenMP for parallelism. I will also discuss the process of releasing this software as an open source R package on the CRAN repository. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="90" data-target=".90collapsed">
  <td>10:30</td>
  <td>space/time/algorithms</td>
  <td>Jin Li</td>
  <td>TBD</td>
  <td>A new R package for spatial predictive modelling: spm</td>
</tr>
<tr class="collapse out budgets 90collapsed">
  <td colspan="6"> Accuracy of spatial predictions is crucial for evidence-informed environmental management and conservation. Improving the accuracy by identifying the most accurate predictive model is essential, but also challenging as the accuracy is affected by multiple factors. Recently developed hybrid methods of machine learning methods and geostatistics have shown their advantages in spatial predictive modelling in environmental sciences, with significantly improved predictive accuracy. An R package, ‘spm: Spatial Predictive Modelling’, has been developed to introduce these methods and recently released for R users. This presentation will briefly introduce spm, including: 1) spatial predictive methods, 2) new hybrid methods of geostatistical and machine learning methods, 3) assessment of predictive accuracy, 4) applications of spatial predictive models, and 5) relevant functions in spm. It will then demonstrate how to apply some functions in spm to relevant datasets and to show the resultant improvements in predictive accuracy and modelling efficiency. Although in this presentation, spm is applied to data in environmental sciences, it can also be applied to data in other relevant disciplines. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="162" data-target=".162collapsed">
  <td>10:30</td>
  <td>space/time/algorithms</td>
  <td>Nicholas Tierney</td>
  <td>TBD</td>
  <td>Maxcovr: Find the best locations for facilities using the maximal covering location problem</td>
</tr>
<tr class="collapse out budgets 162collapsed">
  <td colspan="6"> Want better wifi at the office? Improved access to healthcare? The maximal covering location problem (MCLP) can help! The MCLP finds optimal locations of facilities to improve their coverage on a set of targets. This means better placed wifi routers and healthcare facilities. Although the MCLP was described in the 1970s, it can be daunting to actually implement as you need to know how to:

1) Formulate an optimisation problem
2) Make it talk to a solver engine
3) Get the data into the appropriate format for the solver to recognise
4) Translate the model output into a usable format

It is challenging, particularly if you are not familiar with optimisation, or techniques such as linear programming. It is, however, a great use case for an R package to abstract away detail you don’t need to worry about. The R package maxcovr provides a set of tools to perform, summarise, and visualise the MCLP, so that you can move on with your analysis, place better cellphone towers, and create better access to health facilities.

In this talk, I describe why the MCLP is useful, where it can be applied, and demonstrate of the use of maxcovr, before finally discussing future directions. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="56" data-target=".56collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Anqi Fu</td>
  <td>TBD</td>
  <td>Disciplined Convex Optimization with CVXR</td>
</tr>
<tr class="collapse out budgets 56collapsed">
  <td colspan="6"> CVXR is an R package that provides an object-oriented modeling language for convex optimization, similar to CVX, CVXPY, YALMIP, and Convex.jl. It allows the user to formulate convex optimization problems in a natural mathematical syntax rather than the restrictive standard form required by most solvers. The user specifies an objective and set of constraints by combining constants, variables, and parameters using a library of functions with known mathematical properties. CVXR then applies signed disciplined convex programming (DCP) to verify the problem's convexity. Once verified, the problem is converted into standard conic form using graph implementations and passed to a cone solver such as ECOS or SCS. We demonstrate CVXR's modeling framework with applications in engineering, statistical estimation, and machine learning. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="24" data-target=".24collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Giuseppe Bruno</td>
  <td>TBD</td>
  <td>Stochastic Gradient Descent: boosting its performances in R</td>
</tr>
<tr class="collapse out budgets 24collapsed">
  <td colspan="6"> Despite the tremendous improvements in HW&SW technologies, the requirements for training Machine Learning models keep growing.  With standard loss functions the Gradient Descent (GD) provides a simple approach.

The whole gradient is the sum of the gradients of each component function:

∇ F(w) =2 = Σ(xiT w - yi) xi.

The complexity per iteration is O(n d). Here we gauge the Stochastic Gradient Descent (SGD) where the gradient is approximated with one observation. When the  stopping criterium is|w_{k+1}-w_k|<ε we have that GD requires O(log(1/ ε)) iteration while SGD needs O(1/ ε).

Albeit the iterative nature of the SGD prevents its straightforward parallelization, a few alternatives have been proposed in the literature for carrying out its parallel implementation. In this paper we provide different benchmark examples of parallel implementation through standard shared memory and Spark distributed computing framework to boost the SGD performances. Preliminary results, under given conditions show significant performance improvements. The possibility to take advantage of these speed up is open to practitioners and not just computer specialists.

 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="14" data-target=".14collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Melina Ribaud</td>
  <td>TBD</td>
  <td>Robustness criterion for the derivative kriging-based optimization</td>
</tr>
<tr class="collapse out budgets 14collapsed">
  <td colspan="6"> In the context of robust shape optimization, the estimation cost of some numerical models is reduced with a kriging metamodel. The function, the first and second derivatives are provided by the majority of industrial codes. We propose a robust optimization procedure that leans on the prediction function and its derivatives. Those predictions are given by the kriging. The use of the derivatives improves the metamodel quality. We rely on Rccp and nloptr packages of R to estimate, predict and simulate the kriging with derivatives. Taylor theorem that is calculated with the prediction of the function and its derivatives is applied on each used point to approximate the variation of the function. This cheap criterion is used as the replacement of a full computation of the second moment from the model. A Pareto front of robust solutions (minimization of the function and the robustness criterion) is then generated by the NSGA-II genetic algorithm through the nsga2r package from R. This algorithm efficiently produces a Pareto front with no regard to the model complexity. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="166" data-target=".166collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Andrew Locke</td>
  <td>TBD</td>
  <td>Augmented Lagrangian for constrained optimizations in Empirical Likelihood estimations</td>
</tr>
<tr class="collapse out budgets 166collapsed">
  <td colspan="6"> Empirical Likelihood is a useful tool for inference as it does not require knowledge about where the data comes from. It can be extended in many ways including regression or adding constraints using estimating equations.
The positivity constraint has often been overlooked or ignored but this means existing methods may not be applicable for some data. We look at enforcing this constraint by applying the Karush-Kuhn-Tucker conditions and using a multiplicative iterative optimization method of updating parameters which ensures movement towards the maximum. We have programmed this method in R and use simulations to demonstrate the model works </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="48" data-target=".48collapsed">
  <td>14:00</td>
  <td>applications</td>
  <td>Richard Layton</td>
  <td>TBD</td>
  <td>Data, methods, and metrics for studying student persistence</td>
</tr>
<tr class="collapse out budgets 48collapsed">
  <td colspan="6"> This paper introduces R users to data and tools for investigating undergraduate persistence metrics using the midfieldr package and its associated data packages. The data are the student records (registrar's data) of approximately 200,000 undergraduates at US institutions from 1990 to 2016. midfieldr provides functions for determining persistence metrics such as graduation rates and for grouping and displaying findings by program, institution, race/ethnicity, and sex. These packages provide an entry to this type of intersectional research for anyone with basic proficiency in R and familiarity with packages from the tidyverse. The goal of the paper is to introduce the packages and to share our data, methods, and metrics for intersectional research in student persistence. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="33" data-target=".33collapsed">
  <td>14:00</td>
  <td>applications</td>
  <td>Ansgar Wenzel</td>
  <td>TBD</td>
  <td>A closer look at UK MOT results - Why does my car always fail?</td>
</tr>
<tr class="collapse out budgets 33collapsed">
  <td colspan="6"> We present an analysis of the last 10 years of MOT results in the UK, with a particular focus on when cars fail and why. This is based on an open data set provided by the UK Government on the MOT, an annual car check mandatory for all vehicles older than three years.
    We hope that the results of this can inform customer choice when purchasing used (or new) vehicles as well as provide some interesting results.
    In particular, we consider geographical, vehicle, owner data, and interactions between these groups to identify the main drivers for a car to fail an MOT. We also consider the severity of a fail, eg. a non-working number plate light versus unsafe brake discs.
    We use these results to inform the training and design of a model that we train to predict failure (or passing) of a given vehicle.
    Additionally, we present results that were found using some less-common techniques.
    We also consider whether there are significant regional differences in pass or fail rates for different car brands or models. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="15" data-target=".15collapsed">
  <td>14:00</td>
  <td>applications</td>
  <td>Frank C.S. Liu</td>
  <td>TBD</td>
  <td>The Second Wing of Polls: How Multiple Correspondence Analysis using R Advances Exploring Associated Attitudes in Smaller-Data</td>
</tr>
<tr class="collapse out budgets 15collapsed">
  <td colspan="6"> Polls and surveys have been used for better forecasting voter preferences and understanding consumer behavior. Academically we employ the strength of these smaller but representative data to confirm theory, including identifying associations between theoretically identified variables. However, researchers who like to explore new patterns for better understanding voters' behavior and attitudes are hardly satisfied by the current practice of survey data analysis. While we turn to bigger data, little attention has been preserved to the value of such smaller data for their potential to achieve the same goal. This talk will demonstrate how the use of "FactorMineR" package of R assists exploration of associated concepts and attitudes and patterns that could not be identified by theories in the first place. Implications for the practice of survey data collection and MCA's connection to association rules mining will be discussed. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="71" data-target=".71collapsed">
  <td>14:00</td>
  <td>applications</td>
  <td>Meryam Krit</td>
  <td>TBD</td>
  <td>Modelling Rift Valley Fever</td>
</tr>
<tr class="collapse out budgets 71collapsed">
  <td colspan="6"> Rift Valley Fever (RVF) is one of the major viral zoonoses in Africa, affecting man and several domestic animal species. The epidemics generally involve a 5 – 15 year cycle marked by abnormally high rainfall (El Niño/Southern Oscillation phenomenon (ENSO)), but there is more and more evidence of inter-epidemic transmission.

A flexible model describing RVF transmission dynamics in six species (human, domestic animal, four vectors) in three different areas will be presented. The model allows for migration, flooding, variation in climate, seasonal effects on vector egg hatching, transhumance, alternative wildlife hosts and increased susceptibility of animals.

User-friendly shiny interface and optimized Rcpp implementation allow the epidemiological researchers to study different scenarios and adapt it to other situations. Application of the model  to the specific situation in Tanzania and Algeria will be discussed. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="58" data-target=".58collapsed">
  <td>14:00</td>
  <td>algorithms/models</td>
  <td>Ilia Karmanov</td>
  <td>TBD</td>
  <td>Teach yourself deep-learning with R</td>
</tr>
<tr class="collapse out budgets 58collapsed">
  <td colspan="6"> R's concise matrix algebra and calculus functionality makes it easy to create machine learning-models from scratch. Creating models from scratch is a great way to learn how they actually work. We show how R can be used to create a linear regression, MLP and CNN from scratch (see blog: http://blog.revolutionanalytics.com/2017/07/nnets-from-scratch.html) and thus how one may go about teaching themselves about DNNs. We believe this "hands-on" approach to learning is more effective because it exposes the user to all the "leaky abstractions" that modern frameworks hide and helps them understand what makes the models fragile. R's simple interface lets us easily "play" with the created models to understand further (potentially abstract) topics, e.g: (i) visualise the classification boundary and thus investigate what effect number of neurons (and layers) have. (ii) Visualise different CNN filter-maps. (iii) Solve a neural-net deterministically through linear-programming (without SGD) by working through "Proof of Theorem 1" in "Understanding deep learning requires re-thinking generalization" by Zhang 2017 (as a mirror to solving linear regression with SGD). </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="43" data-target=".43collapsed">
  <td>14:00</td>
  <td>algorithms/models</td>
  <td>Angus Taylor</td>
  <td>TBD</td>
  <td>Deep learning at scale with Azure Batch AI</td>
</tr>
<tr class="collapse out budgets 43collapsed">
  <td colspan="6"> In recent years, R users have been increasingly exploring the use of deep learning methods to solve difficult problems from computer vision to natural language processing. However, developing deep learning models is a time-consuming and compute-intensive task. To obtain good performance on many datasets, it is necessary to test many combinations of network structures and hyperparameters. In this talk, we will discuss how Microsoft Azure Batch AI can be used to perform this tuning task at scale on clusters of GPU-enabled virtual machines in the cloud. Developers create a single R script to define tests of multiple different network configurations, using the popular deep learning frameworks mxnet or Keras. We explain how to build a simple Docker image that can be deployed across multiple machines and defines the necessary installation dependencies. Batch AI will scale VM clusters as necessary to parallelize the tasks and obtain the optimal network configuration efficiently, saving hours or even days of the developer’s time. We will demonstrate the value of Batch AI with a live demo of training a deep learning model, implemented in R, on the classic MNIST computer vision dataset. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="109" data-target=".109collapsed">
  <td>14:00</td>
  <td>algorithms/models</td>
  <td>Timothy Wong</td>
  <td>TBD</td>
  <td>Modelling Field Operation Capacity using Generalised Additive Model and Random Forest</td>
</tr>
<tr class="collapse out budgets 109collapsed">
  <td colspan="6"> In any customer-facing business, accurately predicting demand ahead of time is of paramount importance*. Workforce capacity can be flexibly scheduled at local area accordingly. In this way, we can ensure having sufficient workforce to meet volatile demand.

In this case study, we focus on the gas boiler repairing field operation in the UK. We have developed a prototype capacity forecasting procedure which uses a mixture of machine learning techniques to achieve its goal. Firstly, it uses Generalised Additive Model approach to estimate the number of incoming work requests. It takes into account the non-linear effects of multiple predictor variables. The next stage uses a large random forest to estimate the expected number of appointments for each work request by feeding in various ordinal and categorical inputs. At this stage, the size of the training set is considerable large and does not fully-fit in memory. In light of this, the random forest model was trained in chunks / parallel to enhance computational performance. 

Once all previous steps have been completed, probabilistic input such as the ECMWF Ensemble weather forecast to give a view of all predicted scenarios. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="203" data-target=".203collapsed">
  <td>14:00</td>
  <td>algorithms/models</td>
  <td>Bernd Bischl</td>
  <td>TBD</td>
  <td>iml: A new Package for Model-Agnostic Interpretable Machine Learning</td>
</tr>
<tr class="collapse out budgets 203collapsed">
  <td colspan="6"> iml implements model-agnostic interpretability methods to explain the functional behavior and individual predictions of machine learning models. A large advantage of model-agnostic interpretability methods over model-specific ones is their flexibility, as often not one but many types of machine learning models are evaluated for solving a task. Anything that is build on top of an interpretation such an interpretation, e.g., a visualization or graphical user interface, now also becomes independent of the underlying model.

Currently implemented are:
Feature importance, Partial dependence plots, Individual conditional expectation plots (ICE), Tree surrogate, LocalModel: Local Interpretable Model-agnostic Explanations, Shapley value for explaining single predictions.

The talk will cover the basic concepts behind model-agnostic interpretations, and demonstrate the functionality of the package through applied examples in R.
Link to CRAN release: 
https://cran.r-project.org/web/packages/iml/index.html
Link to Github page: 
https://github.com/christophM/iml </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="119" data-target=".119collapsed">
  <td>14:00</td>
  <td>applications/models</td>
  <td>Helena Kotthaus</td>
  <td>TBD</td>
  <td>Optimizing Parallel R Programs via Dynamic Scheduling Strategies</td>
</tr>
<tr class="collapse out budgets 119collapsed">
  <td colspan="6"> We present scheduling strategies for optimizing the overall runtime of parallel R programs. Our proposal improves upon the existing mclapply function of the parallel package, which already offers a load balancing option that dynamically allocates tasks to worker processes. However, this mechanism has shortcomings when used on heterogeneous hardware architectures, where different CPU cores might have vastly different performance characteristics. 
We thus propose to enhance mclapply with a new parameter that allows mapping tasks to specific CPUs. The new affinity.list parameter, already available on the R-devel branch, allows setting a so-called CPU affinity mask that specifies on which CPU a given task is allowed to run. 
We demonstrate the benefits of the new mclapply version by showing how it can speed up parallel applications like parameter tuning. In this case study, we develop a regression model that guides the scheduling by estimating the runtime of a task for each processor type based on previous executions. 
In a series of code examples, we explain how this approach can be generalized to develop efficient scheduling strategies for parallel R programs. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="3" data-target=".3collapsed">
  <td>14:00</td>
  <td>applications/models</td>
  <td>Mauricio Sarrias</td>
  <td>TBD</td>
  <td>Comparing Implementations of Logit Models with Individual Heterogeneity</td>
</tr>
<tr class="collapse out budgets 3collapsed">
  <td colspan="6"> This paper discusses different specifications for Multinomial Logit models that include individual-heterogeneity (Mixed Logit Model, Latent Class MNL, GMNL model, MM-MNL). Due to the ability of these models to include unobserved heterogeneity, they have become quite popular for the empirical analysis of choice decisions.  However, due to the complex estimation of these models using simulated maximum likelihood (SML) is quite difficult to compare or even replicate results from different software implementations, even using the same database.  For example, the estimates depend on the optimization algorithm, the way on how random numbers are generated; the prime number used if Halton draws are selected, etc.  Despite the now widespread use of these methods and these consideration, there appears to be no systematic investigation of the accuracy of these models or a comparison of the performance of the SML estimation routines that now exist in several software. In this article, I compare different implementation (R, Stata, Matlab) of these models by focusing in their ability to retrieve the true parameters from different data generating process and different default setup. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="140" data-target=".140collapsed">
  <td>14:00</td>
  <td>applications/models</td>
  <td>Daniel Putler</td>
  <td>TBD</td>
  <td>Optimally Locating Opioid Treatment Centers in Under Served Areas Using R and Alteryx</td>
</tr>
<tr class="collapse out budgets 140collapsed">
  <td colspan="6"> In 2016 there were nearly 64,000 drug overdose deaths in the US, most of these due to opioids. Treatment of opioid addiction is one of the primary tools for addressing this situation. However, many of the areas hardest hit by opioid use are under served from a treatment perspective. An issue currently impeding the location of treatment facilities is the lack of fine grained location data of opioid abusers.

We present a Web application that assists decision makers in locating opioid treatment facilities in under served areas. To do this, estimates of the number of adult opioid abusers at the census tract level are developed using R, based on data from the National Survey on Drug Use and Health and both census tract and microdata sample data from the American Community Survey. The census tract estimates of adult opioid abusers is used, along with data on the locations of existing opioid treatment facilities, to locate new facilities in areas that are further than ten miles from existing facilities, and maximizes the estimated number of abusers within a ten mile radius of the new facilities. The optimization is done using an evolutionary algorithm that is implemented in Alteryx. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="154" data-target=".154collapsed">
  <td>14:00</td>
  <td>applications/models</td>
  <td>Brianna Hitt</td>
  <td>TBD</td>
  <td>Optimal group testing algorithms for infectious disease detection with the binGroup package</td>
</tr>
<tr class="collapse out budgets 154collapsed">
  <td colspan="6"> Group testing is the process of amalgamating clinical specimens from individuals (e.g., blood, urine, or saliva) into groups to test for an infectious disease. When disease prevalence is small, the majority of these groups will test negatively. For positive testing groups, there are many algorithmic retesting procedures available to differentiate positive individuals from negative ones. The appeal of group testing to laboratories is that the number of tests needed is significantly less than testing each individual separately.
 
Both estimating the probability of disease infection and identifying positive/negative individuals are goals of group testing. Unfortunately, no package has been available to address the identification goal for the most common group testing algorithms. We present the first functions for identification and make these available in the binGroup package to complement its large set of estimation functions. Our new functions calculate operating characteristics for algorithms and choose the optimal set of group sizes for user specified settings. These new functions allow laboratories to understand how well an algorithm is expected to perform before implementation. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="94" data-target=".94collapsed">
  <td>14:00</td>
  <td>reproducibility</td>
  <td>John Blischak</td>
  <td>TBD</td>
  <td>The workflowr R package: a framework for reproducible and collaborative data science</td>
</tr>
<tr class="collapse out budgets 94collapsed">
  <td colspan="6"> The workflowr R package helps scientists organize their research in a way that promotes effective project management, reproducibility, collaboration, and sharing of results. workflowr combines literate programming (knitr and rmarkdown) and version control (Git, via git2r) to generate a website containing time-stamped, versioned, and documented results. Any R user can quickly and easily adopt workflowr, which includes four key features: (1) workflowr automatically creates a directory structure for organizing data, code, and results; (2) workflowr uses the version control system Git to track different versions of the code and results without the user needing to understand Git syntax; (3) to support reproducibility, workflowr automatically includes code version information in webpages displaying results and; (4) workflowr facilitates online Web hosting (e.g. GitHub Pages) to share results. Our goal is that workflowr will make it easier for scientists to organize and communicate reproducible research results. Documentation and source code are available at https://github.com/jdblischak/workflowr. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="157" data-target=".157collapsed">
  <td>14:00</td>
  <td>reproducibility</td>
  <td>Peter Baker</td>
  <td>TBD</td>
  <td>Efficient data analysis and reporting: DRY workflows in R</td>
</tr>
<tr class="collapse out budgets 157collapsed">
  <td colspan="6"> When analysing data for different projects, do you often find yourself repeating the same steps? Typically, these steps follow a familiar pattern of reading, cleaning, summarising, plotting and analysing data then producing a report. To aid reproducibility, naive examples using Rmarkdown are often presented. However, I  routinely employ a modular approach combining GNU Make, R, Rmarkdown and/or Sweave files tracked under git. This system helps to implement a don't repeat yourself (DRY) approach and scales up well as projects become more complex.


To aid automation, I have developed generic R, Rmarkdown, STATA, SAS and other pattern rules for GNU Make as well as R packages to generate a project skeleton consisting of initial directories, Makefiles, R syntax files for basic data cleaning and summaries; move data files and documents to standard directories; use codebook information to specify factors and check data; and finally initialise and add these to a local git repository. Comparisons will be made with alternate approaches such as ProjectTemplate and drake.


GNU Make pattern rules and R software are available at https://github.com/petebaker. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="98" data-target=".98collapsed">
  <td>14:00</td>
  <td>reproducibility</td>
  <td>Filip Krikava</td>
  <td>TBD</td>
  <td>Automated unit test generation using genthat</td>
</tr>
<tr class="collapse out budgets 98collapsed">
  <td colspan="6"> Your package has examples and vignettes of its overall functionality but no unit tests for individual functions. Writing those is no fun. Yet, when something goes wrong, unit tests are your best tool to quickly pinpoint errors. The genthat package can generate unit tests for you in the popular testthat format. Moreover, it can also be used to create reproductions when you find a bug in someone else’s code. There, instead of generating passing test cases it will generate the smallest, purposefully failing, one.
Genthat does not magically create new tests out of the blue, instead it simply extracts the smallest possible test fragments from existing code. It does that by recording the input arguments and return values of all function called by clients of your package. The generated tests concentrate on single functions and test them independently of each other. Therefore a failing test usually locates the error more precisely that a failing chunk of application code. Trying it out on random set of 1500 CRAN packages, genthat managed to reproduce 80% of all function calls, increasing the unit test coverage from 19% to 54%. In this talk we present genthat and discuss testing R code. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="145" data-target=".145collapsed">
  <td>14:00</td>
  <td>reproducibility</td>
  <td>Dan Wilson</td>
  <td>TBD</td>
  <td>Practical R Workflows</td>
</tr>
<tr class="collapse out budgets 145collapsed">
  <td colspan="6"> Learn how R can be used to create reproducible workflows for practical use in business. As analysts and data scientists we often need to repeat our work time and time again. Sometimes this will be the exact same task, other times it may be a slight variation for another client or stakeholder. 

This talk will demonstrate a real-world set of workflows established at The Data Collective designed to reduce the amount of copy/paste type actions to a few function calls that get the repetitive actions out of the way, so you can focus on the important parts of your job. Find out how to overcome the challenges of a repeatable workflow and make your life easier.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="122" data-target=".122collapsed">
  <td>15:45</td>
  <td>bioinformatics/applications</td>
  <td>Rudradev Sengupta</td>
  <td>TBD</td>
  <td>High Performance Computing Using R for High Dimensional Surrogacy Applications in Drug Development</td>
</tr>
<tr class="collapse out budgets 122collapsed">
  <td colspan="6"> Identification of genetic biomarkers is a primary data analysis task in the context of drug discovery experiments. These experiments consist of several high dimensional datasets which contain information about a set of new drugs under development. This type of data structure introduces the challenge of multi-source data integration which is needed in order to identify the biological pathways related to the new set of drugs under development. In order to process all the information contained in the datasets, high performance computing techniques are required. Currently available R packages, for parallel computing, are not optimized for a specific setting and data structure. We proposed a new “master-slave” framework, for data analysis using R in parallel, in a computer cluster. The proposed data analysis workflow is applied to a multi-source high dimensional drug discovery dataset and a performance comparison is made between the new framework and existing R packages for parallel computing. Different configuration settings,  for parallel programming in R, are presented  to show that the computation time, for the specific application under consideration, can be reduced by 534.62%. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="149" data-target=".149collapsed">
  <td>15:45</td>
  <td>bioinformatics/applications</td>
  <td>Momeneh (Sepideh) Foroutan</td>
  <td>TBD</td>
  <td>Singscore: a single-sample gene-set scoring method for analysing molecular signatures</td>
</tr>
<tr class="collapse out budgets 149collapsed">
  <td colspan="6"> Several single sample gene-set enrichment analysis methods have been introduced to score samples against gene expression signatures, such as ssGSEA, GSVA, PLAGE and combining z-scores. Although these methods have been proposed to generate single-sample scores, they use information from all samples in a dataset to calculate scores for individual samples. This leads to unstable scores which are influenced by sample size and composition in datasets.  We have proposed singscore, a ranked-based and truly single-sample scoring method implemented as an R/Bioconductor package singscore. We compare singscore to other methods and show that our approach performs as well as other methods for large datasets in terms of stability, while outperforming them in small datasets. Singscore is fast and generates easily-interpretable scores. We show the application of this method in cancer biology, where the dependence between distinct molecular signatures can be investigated across samples. Singscore has potential applications in personalised medicine, as it calculates replicable scores for individual samples regardless of the sample size or composition in the data. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="139" data-target=".139collapsed">
  <td>15:45</td>
  <td>bioinformatics/applications</td>
  <td>Luke Zappia</td>
  <td>TBD</td>
  <td>clustree: a package for producing clustering trees using ggraph</td>
</tr>
<tr class="collapse out budgets 139collapsed">
  <td colspan="6"> Clustering analysis is commonly used in many fields to group together similar samples. Many clustering algorithms exist, but all of them require some sort of user input to set parameters that affect the number of clusters produced. Deciding on the correct number of clusters for a given dataset is a difficult problem that can be tackled by looking at the relationships between samples at different resolutions. Here I will present clustree, an R package for producing clustering tree visualisations. These visualisations combine information from multiple clusterings with different resolutions, showing where new clusters come from and how samples change clusters as the number of clusters increases. Summarised information describing the samples in each cluster can be overlaid on the tree to give additional insight. I will also describe my experience developing clustree, particularly how I have made use of the ggraph package. The clustree package is available at https://github.com/lazappi/clustree and a preprint describing clustering trees can be read at https://www.biorxiv.org/content/early/2018/03/02/274035. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="151" data-target=".151collapsed">
  <td>15:45</td>
  <td>bioinformatics/applications</td>
  <td>Sarah Williams</td>
  <td>TBD</td>
  <td>Celaref: Annotating single-cell RNAseq clusters by similarity to reference datasets</td>
</tr>
<tr class="collapse out budgets 151collapsed">
  <td colspan="6"> Single-cell RNA sequencing (scRNAseq) is a way of measuring gene expression of many individual cells simultaneously, and is often used on samples which contain a mix of different cell types.  In an scRNAseq analysis individual cells are typically clustered to group them by cell type. After clustering, identifying what type of cell is in each cluster (e.g. neurons) usually needs domain-specific knowledge of marker genes and function.
 
The celaref package accepts pre-computed cell-clusters and aims to suggest cell-types for each cluster via similarity to reference datasets (scRNAseq experiments or microarrays) from similar samples. Briefly, within-dataset differential expression is calculated to identify the most enriched genes for each cluster, then their rankings are examined in reference datasets. Kolmogorov–Smirnov tests are used to decide if multiple matches should be reported. Initial experiments on brain, lacrimal gland and blood PBMC samples show sensible matching between similar cell types without overreaching on dissimilar cells.
 
Celaref will be submitted to Bioconductor and is available at https://github.com/MonashBioinformaticsPlatform/celaref
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="54" data-target=".54collapsed">
  <td>15:45</td>
  <td>models</td>
  <td>Bachmann Patrick</td>
  <td>TBD</td>
  <td>Estimating individual Customer Lifetime Values with R: The CLVTools Package</td>
</tr>
<tr class="collapse out budgets 54collapsed">
  <td colspan="6"> Valuing customers is key to any firm. Customer lifetime value (CLV) is the central metric for valuing customers. It describes the long-term economic value of customers and gives managers an idea of how customers will evolve over time. To model CLVs in continuous non-contractual business settings such as retailers, probabilistic customer attrition models are the preferred choice in literature and practice. 
Our R package CLVTools provides an efficient and easy to use implementation frameworks for probabilistic customer attrition models. Building up on the learnings of other implementations, we adopt S4 classes to allow constructing rich and rather complex models that nevertheless still are easy to apply for the end user. In addition, the package includes recent model extensions, such as the option to consider contextual factors, that are not available in other packages.
This article will focus on both, the theory of the underlying statistical framework as well as about the practical application using real world data. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="64" data-target=".64collapsed">
  <td>15:45</td>
  <td>models</td>
  <td>Sam Brilleman</td>
  <td>TBD</td>
  <td>simsurv: A Package for Simulating Simple or Complex Survival Data</td>
</tr>
<tr class="collapse out budgets 64collapsed">
  <td colspan="6"> The simsurv package allows users to simulate simple or complex survival data. Survival data refers to a variable corresponding to the time from a defined baseline until occurrence of an event of interest. Depending on the field, the analysis of survival data can be known as survival, duration, reliability, or event history analysis. It has been common to make simplifying parametric assumptions when simulating survival data, e.g. assuming survival times follow an exponential or Weibull distribution. However, such assumptions are unrealistic in many settings. The simsurv package provides additional flexibility by allowing users to simulate survival times from 2-component mixture distributions or a user-defined hazard function. The mixture distributions allow for a variety of flexible baseline hazard functions. Moreover, a user-defined hazard function can provide even greater flexibility since the cumulative hazard does not require a closed-form solution. This means it is possible to simulate survival times under complex statistical models such as those for joint longitudinal-survival data. The package is modelled on the survsim package in Stata (Crowther and Lambert, 2012, Stata J). </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="88" data-target=".88collapsed">
  <td>15:45</td>
  <td>models</td>
  <td>Raju Rimal</td>
  <td>TBD</td>
  <td>R-package for simulating linear model data (simrel)</td>
</tr>
<tr class="collapse out budgets 88collapsed">
  <td colspan="6"> Data science is generating enormous amounts of data, and new and advanced analytical methods are constantly being developed to cope with the challenge of extracting information from such “big-data”. Researchers often use simulated data to assess and document the properties of these new methods. Here we present an R-package `simrel`, which is a versatile and transparent tool for simulating linear model data with an extensive range of adjustable properties. The method is based on the concept of relevant components and a reduction of the regression model. The concept was first implemented in an earlier version of `simrel` but only for single response case. In this version we introduce random rotations of latent components spanning a response space in order to obtain a multivariate response matrix Y. The properties of the linear relation between predictors and responses are defined by a small set of input parameters which allow versatile and adjustable simulations. In addition to the R-package, user-friendly shiny application with elaborate documentation and an RStudio gadget provide an easy interface for the package.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="179" data-target=".179collapsed">
  <td>15:45</td>
  <td>models</td>
  <td>Andrés Villegas</td>
  <td>TBD</td>
  <td>StMoMo: An R Package for Stochastic Mortality Modelling</td>
</tr>
<tr class="collapse out budgets 179collapsed">
  <td colspan="6"> In this talk we use the framework of generalised (non-)linear models to define the family of generalised Age-Period-Cohort stochastic mortality models which encompasses the vast majority of stochastic mortality projection models proposed to date, including the well-known Lee-Carter and Cairns-Blake-Dowd models.  We also introduce the R package StMoMo which exploits the unifying framework of the generalised Age-Period-Cohort family to provide tools for fitting stochastic mortality models, assessing their goodness of fit and performing mortality projections. We illustrate some of the capabilities of the package by performing a comparison of several stochastic mortality models applied to the Australian mortality experience. The R package StMoMo is available at http://CRAN.R-project.org/package=StMoMo. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="118" data-target=".118collapsed">
  <td>15:45</td>
  <td>performance</td>
  <td>Stepan Sindelar</td>
  <td>TBD</td>
  <td>FastR: an alternative R language implementation</td>
</tr>
<tr class="collapse out budgets 118collapsed">
  <td colspan="6"> R is a highly dynamic language that employs a unique combination of data type immutability, lazy evaluation, argument matching, large amount of built-in functionality, and interaction with C and Fortran code. It is therefore a challenging task to develop an alternative R runtime that is both compatible with GNU R and can provide performance of R code comparable to static programming languages like C.

FastR is an open source alternative R implementation that is trying to achieve this. The talk will introduce FastR and demonstrate the performance improvements it can offer, compatibility with GNU R by being able to run unmodified popular complex CRAN pacakges like ggplot2 or Shiny, and FastR unique features, for example in-process multi-threaded execution, and tools like CPU sampler or viewing R memory dumps with VisualVM. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="129" data-target=".129collapsed">
  <td>15:45</td>
  <td>performance</td>
  <td>Stepan Sindelar</td>
  <td>TBD</td>
  <td>Combining R and Python with GraalVM</td>
</tr>
<tr class="collapse out budgets 129collapsed">
  <td colspan="6"> GraalVM is a multi-language runtime that allows to run and combine multiple programming languages in one process and operating on the same data without the need to copy the data when crossing language boundaries. Moreover, the dynamic just-in-time compiler included in GraalVM is capable of applying optimizations across the languages boundaries. The languages implemented on top of GraalVM include FastR, an alternative R implementation, C, Ruby, JavaScript, and recently added GraalPython.

The talk will present interesting ways how R and Python can be combined into a polyglot application running on GraalVM, for example using R package from Python or vice versa, and briefly explain how this interoperability works on the technical level. One of the most important parts of a language ecosystem is tooling and especially interactive debugger. The talk will also present how one can debug multiple GraalVM languages at the same time in the Google Chrome Dev Tools, for instance stepping from R into C code. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="133" data-target=".133collapsed">
  <td>15:45</td>
  <td>performance</td>
  <td>David Smith</td>
  <td>TBD</td>
  <td>Speeding up computations in R with parallel programming in the cloud</td>
</tr>
<tr class="collapse out budgets 133collapsed">
  <td colspan="6"> There are many common workloads in R that are "embarrassingly parallel":  group-by analyses, simulations, and grid-based computations are just a few examples. In this talk, I'll provide a review of tools for implementing embarrassingly parallel computations in R, including the built-in "parallel" package and extensions such as the "foreach" package. 

I'll also demonstrate how you can dramatically reduce the time for a complex computation -- optimizing hyperparameters for a predictive model with the "caret" package -- by using a cluster of parallel R session in the cloud. With the "doAzureParallel" package, I'll show how you can create a cluster of virtual machines running R in Azure, parallelize the problem by registering backend to "foreach", and shut down the cluster when the computation is complete, all with just a few lines of R code. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="169" data-target=".169collapsed">
  <td>15:45</td>
  <td>performance</td>
  <td>Romain François</td>
  <td>TBD</td>
  <td>rrrow: an R front end to Apache Arrow</td>
</tr>
<tr class="collapse out budgets 169collapsed">
  <td colspan="6"> Apache Arrow is a cross-language development platform for in-memory data. It specifies a standardized language-independent columnar memory format for flat and hierarchical data, organized for efficient analytic operations on modern hardware. It also provides computational libraries and zero-copy streaming messaging and interprocess communication. Languages currently supported include C, C++, Java, JavaScript, Python, and Ruby.

R support is currently being implemented and in this talk we will discuss the various challenges, and our short, medium and long term vision for the connection between R and Apache Arrow. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="144" data-target=".144collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Robert Nguyen</td>
  <td>TBD</td>
  <td>USING AUSTRALIAN RULES FOOTBALL TO BROADEN THE APPEAL OF R AND STATISTICS AMONG YOUTH AND PUBLIC WITHOUT A STEM BACKGROUND</td>
</tr>
<tr class="collapse out budgets 144collapsed">
  <td colspan="6"> Our talk explores how sports analytics can be used to encourage those without a STEM background into the application of statistics and programming to a real world environment. Through the use of a R package (fitzRoy) related to AFL we aim to both lower the barrier to entry for data access while also increasing analytical fan engagement in AFL. We will also talk about common issues that arise for the first time R package builder.
A key barrier to entry for the growth of the AFL community is data access which prevents not only people having a go at writing, but it also prevents current media having reproducible work. By having an R package with online lessons on creating common fan rating systems like ELO, Pythagorean and Massey this will engage people who otherwise might have put learning statistical modelling and R into their personal *this is too hard* bucket. 
Commonly users are taught from a cleaned dataset and jump straight into modelling. This misses a key part which is cleaning. Our package, we aim to use tangible examples of scraped, raw AFL data from afltables and footywire to teach users how to clean scraped data themselves to get it into a tidy format for modelling. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="193" data-target=".193collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Alex Fun</td>
  <td>TBD</td>
  <td>Using TMB (Template Model Builder) to predict the winner of a ping pong match</td>
</tr>
<tr class="collapse out budgets 193collapsed">
  <td colspan="6"> In a recent and popular stats.stackexchange post, the following question was asked:

“I bet with my colleague that I will beat him in fifty consecutive ping pong games. So far I have won 15, what are my chances of winning the next 35 games?”

-- from https://stats.stackexchange.com/questions/329521/

To answer this question, I propose the following data generation process for the score-line in each game: The OP (original poster) is a far superior player who still wishes to make the game fun for their opponent (they are colleagues after all). This leads to a regression problem for the OP’s probability of winning a point, that cannot be fit using standard regression packages. This introductory talk will demonstrate how to use the TMB (Template Model Builder) package with an optimisation algorithm to find maximum likelihood estimates for the regression coefficients. This will show that TMB is a very useful and efficient tool, that allows the practictioner a lot of flexibility in exploring novel data generation processes and objective functions. I will also briefly touch upon using C++ from R, and automatic differentiation, which is great for those that dislike multivariate calculus.

 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="174" data-target=".174collapsed">
  <td>15:45</td>
  <td>applications/models</td>
  <td>Sayani Gupta</td>
  <td>TBD</td>
  <td>CricketData: An R package for international cricket data</td>
</tr>
<tr class="collapse out budgets 174collapsed">
  <td colspan="6"> The CricketData package provides convenient scraper functions for downloading data from ESPNCricinfo into tibbles. Functions are provided for obtaining data on the performance of male and female players across Test, One Day International and Twenty20 formats, and for batting, bowling and fielding. Tidyverse packages can then be used to explore, visualise and analyse the data. 

The package enables a user to answer simple questions such as 
-What is the highest number of catches taken by a wicket keeper?
-What is the maximum number of catches taken by a fielder in a particular 
 innings?
-How many batsmen have scored consecutive 100’s in two matches or more?
-What is the maximum number of maiden overs by a bowler in a specific 
  innings?

It will also allow for deeper questions to be addressed such as
-Do batsman tend to get run out more frequently when they are about to score a 
  century?
-How does the performance of cricketers change in the 12 months before 
  he/she retires?
-When is the period of peak performance during a cricketer’s career?

Finally, it makes it easy to produce visual comparisons of player performance across different statistics.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="38" data-target=".38collapsed">
  <td>15:45</td>
  <td>web app/applications</td>
  <td>Katie Sasso</td>
  <td>TBD</td>
  <td>Shiny meets Electron:  Turn your Shiny app into a standalone desktop app in no time</td>
</tr>
<tr class="collapse out budgets 38collapsed">
  <td colspan="6"> Using Shiny in consulting can be challenging, as all deployment options involve either sending intellectual property and data to the cloud or IT involvement. When providing consultative like services to extremely large, risk-averse, enterprises this can greatly restrict one’s ability to quickly get Shiny apps into users’ hands, as engagement of IT can take months if approved at all. We’ll share how the Columbus Collaboratory team overcame these barriers to rapid deployment by coupling R Portable and Electron, a framework for creating native applications with a variety of web technologies. All the tools needed to use Electron for desktop deployment of Shiny apps will be reviewed. We’ll highlight a specific example in which these technologies were used within a large enterprise to completely automate a weekly report. We’ll also share how the app used R Packages such as openxlsx, shinydashboard, RODBC, and Zoo to query an internal database, cleanse data, calculate key metrics, and create a downloadable excel file for dissemination. The best part? This Shiny app was delivered to the end business user as a stand-alone executable. https://github.com/ksasso/Electron_ShinyApp_Deployment </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="113" data-target=".113collapsed">
  <td>15:45</td>
  <td>web app/applications</td>
  <td>Adrian Barnett</td>
  <td>TBD</td>
  <td>Saving time for researchers by creating publication lists using shiny</td>
</tr>
<tr class="collapse out budgets 113collapsed">
  <td colspan="6"> Researchers are often asked by funders or employers to list their publications, but funders often have different requirements (e.g., all papers versus only those in the last five years) and researchers waste a lot of time formatting papers. To save time for researchers I made a shiny application (https://aushsi.shinyapps.io/orcid/) that takes a researcher’s ORCID ID and outputs their papers in alternative formats. It uses crossref and pubmed (rentrez) to supplement the ORCID data. 

The app was included in the Australian Research Council’s instructions to applicants and has been well used with many good suggestions for improvements. However, the ORCID data is relatively messy and papers can be in multiple formats, making it difficult to create a standardised paper that can be flexibly manipulated. For example, the publication’s author data are in different fields and formats. Google Scholar publications are nicely standardised, but there are authentication issues when using shiny.

I will describe how the app has developed and canvass how it could be improved, including adding the percent of publications that are open access or other alternative research metrics. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="78" data-target=".78collapsed">
  <td>15:45</td>
  <td>web app/applications</td>
  <td>Gergely Daroczi</td>
  <td>TBD</td>
  <td>Managing database credentials and connections: an easy and secure approach</td>
</tr>
<tr class="collapse out budgets 78collapsed">
  <td colspan="6"> Although the `DBI` R package family already provides a standardized way of opening connections to various databases and querying data, and eg the `config` package allows to store the database connection default parameters in a central file, maybe some of the sensitive fields encrypted via `keyring` or the `secret` packages -- but there is no convenient and secure wrapper around these for the actual R end-users. This talk introduces a new package taking care of opening connections in the background to the databases specified in a secured and encrypted YAML file, so that the R user can simply specify the SQL command without the need to think about what DB backend and credentials are used. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="175" data-target=".175collapsed">
  <td>15:45</td>
  <td>web app/applications</td>
  <td>Ian Hansel</td>
  <td>TBD</td>
  <td>Large Scale Data Visualisation with Deck.gl and Shiny</td>
</tr>
<tr class="collapse out budgets 175collapsed">
  <td colspan="6"> deck.gl is a WebGL-powered framework for visual exploratory data analysis of large datasets' - https://uber.github.io/deck.gl/#/

Combining deck.gl and shiny allows for rich interactive graphics of large datasets, in particular visualising GeoSpatial data. We will review how to integrate deck.gl with shiny using the upcoming R package 'deck.gl'. The talk will:
- Review the underlying technologies; WebGL, Mapbox and React.js
- Dive into an example exploring the latest Census from the Australian Beureau of Statistics
- Compare to existing visualisation capabilities in the 'rthreejs' and 'leaflet' packages
- Discuss how further integrations with React.js can enable more browser based interfaces to data and analytics

After the talk the attendees should:
- Know how Deck.gl works
- Understand how to visualise data in deck.gl from R using the 'deck.gl' package
- Want to use deck.gl in their own work :)

The talk is aimed at those with some experience (or interest) in GeoSpatial analysis. </td>
</tr>

  </table>
</div>

<div id="Friday" class="tabcontent">
  <table id="reg-sum">
    <col width="40"> <col width="40"> <col width="40"> <col width=40"> <col width="280">
    <th>Time</th> <th>Session</th> <th>Presenter</th> <th>Venue</th> <th>Title</th>
    <tr class="clickable" data-toggle="collapse" id="72" data-target=".72collapsed">
  <td>10:30</td>
  <td>applications/bioinformatics</td>
  <td>Peter Hickey</td>
  <td>TBD</td>
  <td>DelayedArray: A tibble for arrays</td>
</tr>
<tr class="collapse out budgets 72collapsed">
  <td colspan="6"> High-throughput genomics data are commonly summarised in a feature-by-sample matrix or higher-dimensional array. In R, these have traditionally been stored in-memory, but this is becoming prohibitive for large, contemporary datasets, such as those generated using new genomics technologies like single-cell RNA-seq. Instead, these arrays may be stored on-disk, using the Hierarchical Data Format 5 (HDF5), for example. 

The Bioconductor project has developed the DelayedArray, which supports different 'backends' to wrap around an in-memory, on-disk, or remotely served representation of an array, providing a unified interface to the data that is familiar to users of ordinary R arrays. In this sense, a DelayedArray is to an array as a tibble is to a data frame. 

I will provide an overview of the DelayedArray framework, explain the requirements for developing a new backend for a DelayedArray, and highlight example backends for on-disk and remotely served data. I will also demonstrate how user-created packages can extend the capabilities of the DelayedArray and how this has enabled us to analyse large genomics datasets in R that were previously infeasible. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="124" data-target=".124collapsed">
  <td>10:30</td>
  <td>applications/bioinformatics</td>
  <td>Ido Bar</td>
  <td>TBD</td>
  <td>Shinotate: an R-based shiny server for annotation and analysis of RNA-Seq transcriptome assemblies</td>
</tr>
<tr class="collapse out budgets 124collapsed">
  <td colspan="6"> Assembly of transcriptome data in non-model species has become common practice in the last decade thanks to the advent of high-throughput RNA-sequencing platforms and accompanying bioinformatics tools. Trinity is one of the most commonly used tools for transcriptome assembly from Illumina RNA-Seq data and its accompanying functional annotation framework, Trinotate, offers a pipeline for running the various annotation tools and consolidating the results into a single database. Trinotate also includes a web-based graphical user interface for querying the annotations and provide basic visualisation, but its Perl implementation makes it difficult to customise and deploy. 
Shinotate was developed to provide a modern graphical interface for the analysis of transcriptome annotations, utilising the Trinotate annotation framework to deliver summarised results and insights to users of all skill levels. Shinotate is written in R and uses the `tidyverse` approach to summarise and visualise the data stored in Trinotate and thus can be easily adapted to accommodate custom annotation tables. It serves interactive annotation tables and plots, with search, selection and data export functions. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="86" data-target=".86collapsed">
  <td>10:30</td>
  <td>applications/bioinformatics</td>
  <td>Saswati Saha</td>
  <td>TBD</td>
  <td>Multiple testing approaches for evaluating the effectiveness of a drug combination in a multiple-dose factorial design.</td>
</tr>
<tr class="collapse out budgets 86collapsed">
  <td colspan="6"> Drug combination trials are often motivated from the fact that using existing drugs in combination might prove to be more productive than the existing drug alone and less expensive than producing an entirely new drug. Several approaches have been explored for developing statistical methods that compare fixed (single) dose combinations to its component.  However, the extension of these approaches to a multiple dose combination clinical trial is not always so simple. Considering these facts we have proposed three approaches by which we can provide confirmatory assurance that combination of two or more drugs is more effective than the component drug alone. These approaches involved multiple comparisons in multilevel factorial design where the type 1 error is controlled by bonferroni test, bootstrap test, and a union intersection test where the least favorable null configuration has been considered. We have also built a R package implementing the above approaches and in this presentation we would like to  demonstrate how this R package can be used in a drug combination trial. We will also demonstrate how these three approaches are performing when benchmarked with an existing approach. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="31" data-target=".31collapsed">
  <td>10:30</td>
  <td>applications/bioinformatics</td>
  <td>Bill Lattner</td>
  <td>TBD</td>
  <td>Modeling Heterogeneous Treatment Effects with R</td>
</tr>
<tr class="collapse out budgets 31collapsed">
  <td colspan="6"> Randomized experiments have become ubiquitous in many fields. Traditionally, we have focused on reporting the average treatment effect (ATE) from such experiments. With recent advances in machine learning, and the overall scale at which experiments are now conducted, we can broaden our analysis to include heterogeneous treatment effects. This provides a more nuanced view of the effect of a treatment or change on the outcome of interest. Going one step further, we can use models of heterogeneous treatment effects to optimally allocate treatment.

In this talk will provide a brief overview of heterogeneous treatment effect modeling. We will show how to apply some recently proposed methods using R, and compare the results of each using a question wording experiment from the General Social Survey. Finally, we will conclude with some practical issues in modeling heterogeneous treatment effects, including model selection and obtaining valid confidence intervals. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="104" data-target=".104collapsed">
  <td>10:30</td>
  <td>cloud computing/finding bugs in packages</td>
  <td>Tomas Kalibera</td>
  <td>TBD</td>
  <td>Preventing and Detecting Memory Protection Bugs in Packages</td>
</tr>
<tr class="collapse out budgets 104collapsed">
  <td colspan="6"> R's garbage collector (GC) ensures that memory used for R values is automatically reclaimed when they become unreachable via pointers and hence no longer needed. R code is handled automatically, but C code must protect from the GC the R values it needs and unprotect them after. Forgetting to protect and/or to unprotect (protect bug) often makes R crash but also can lead to incorrect results. It is not uncommon that old protect bugs are uncovered much later by inconsequential code changes. These bugs are common and hard to find, and thus R offers tools to detect them. `gctorture` helps testing by increasing the chance a protect bug will crash R and will do so sooner after the code with the bug executes. `rchk` is a static analysis tool that identifies potential protect bugs in C code without executing it; it is used regularly to check incoming CRAN packages. Finally, protect bugs can be prevented by following several simple programming rules. The talk is intended for package developers and everyone who write C code to work with R. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="197" data-target=".197collapsed">
  <td>10:30</td>
  <td>cloud computing/finding bugs in packages</td>
  <td>Kelly O'Briant</td>
  <td>TBD</td>
  <td>How to Play with and Integrate DevOps Technologies in an R Data Science Workflow</td>
</tr>
<tr class="collapse out budgets 197collapsed">
  <td colspan="6"> Over the last year I’ve become obsessed with trying to encourage the data science community to explore and exploit DevOps and cloud computing technology. This isn’t often an easy undertaking. Most people (data scientists or not) are skeptical of deviating from the tools and workflows they’ve come to rely on. This talk will feature case studies in developing data science products and workflows in the cloud, and how working with these tools can open up a world of new possibilities within the intersection of DevOps and Data Analytics.


KEYS Topics to discuss:
- How DataOps can address the growing scope of data science tasking
- Where to start when you start exploring cloud services
- How to work through functionality/engineering challenges in a cloud environment
- Case studies in data science product engineering and deployment
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="128" data-target=".128collapsed">
  <td>10:30</td>
  <td>applications/community/education</td>
  <td>John Mertic</td>
  <td>TBD</td>
  <td>Improve your R package quality with R Hub</td>
</tr>
<tr class="collapse out budgets 128collapsed">
  <td colspan="6"> R Hub is a project designed to help package developers ensure broad support of their packages across multiple platforms ( Windows, Linux, Mac, Solaris ), which in turn ensures higher user satisfaction and makes it more likely for the package to be accepted to CRAN.

In this talk, you will learn about the tool, how and when to use it, and how to integrate it into your package development workflow. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="10" data-target=".10collapsed">
  <td>10:30</td>
  <td>applications/community/education</td>
  <td>Simon Jackson</td>
  <td>TBD</td>
  <td>R from academia to commercial business</td>
</tr>
<tr class="collapse out budgets 10collapsed">
  <td colspan="6"> A 2017 report by StackOverflow showed that the use of R is greatest and growing fastest in academia. Commercial industries like tech, media, and finance, however, show the smallest usage and lowest adoption rates of the language. Yet learnings regarding the use of R and data science in academia and commercial settings complement each other. This presentation will share my experience as an R user moving from academia into commercial business; the transition moving from cognitive scientist at an Australian University to being a data scientist at one of the world’s largest travel e-commerce sites, Booking.com. I’ll discuss how the cutting-edge R skills used in academia can improve commercial product development. I will also identify the knowledge gaps I had moving into commercial business. This will be relevant to academics looking to move into industry, and business employers looking to hire data scientists from academia. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="41" data-target=".41collapsed">
  <td>10:30</td>
  <td>applications/community/education</td>
  <td>John Mertic</td>
  <td>TBD</td>
  <td>Sustainable community investment in action - a look at some of the R Consortium Funded Grant Projects and Working Groups.</td>
</tr>
<tr class="collapse out budgets 41collapsed">
  <td colspan="6"> R Consortium has funded over $500,000 USD to R community members improving the community and technical infrastructure for the benefit of the R ecosystem. In addition, the working groups program has worked to drive discussion and alignment on key areas such as industry adoption, package health, and educational standards.

In this talk, we will showcase several of the working groups and funded projects stewarded by R Consortium. This will provide an opportunity for the audience to understand the work being done, and also opportunities on how they could take part. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="170" data-target=".170collapsed">
  <td>10:30</td>
  <td>applications/community/education</td>
  <td>Lisa Chen</td>
  <td>TBD</td>
  <td>Using R to help industry clients – The benefits and Opportunities</td>
</tr>
<tr class="collapse out budgets 170collapsed">
  <td colspan="6"> Dr Lisa Chen is Chief Analytics Officer for Harmonic Analytics.  She is a highly qualified and experienced data scientist, with a PhD in Statistics and a Bachelor of Science in Computer Science and Statistics.  Lisa has extensive experience using R including designing solution-based models for complex optimisation problems, and analysing large-scale datasets in R.  Harmonic has helped customers globally to address business challenges, across sectors including; agriculture, aviation, banking, energy, government, health, telecommunications and utilities.  We use R in our daily project work and also help clients with data science team development and R Training.  We will outline how we have used R, and RShiny and the benefits realised.   We will discuss our journey, data-driven approach, workflow and industry observations. We will discuss our learning with R, e.g. observations regarding Big Data with R, version control and some of the pain points & work-arounds.  We will share our observations on how clients are starting to adapt open source and R for their analytical work, plus the trends and opportunities.    Lisa will demonstrate examples of our interactive client dashboards. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="13" data-target=".13collapsed">
  <td>10:30</td>
  <td>text analysis/nlp</td>
  <td>Aneesha Bakharia</td>
  <td>TBD</td>
  <td>Topic Modeling with LDA and NMF from a Qualitative Content Analysis Perspective</td>
</tr>
<tr class="collapse out budgets 13collapsed">
  <td colspan="6"> The Latent Dirichlet Allocation (LDA) and Non Negative Matrix Factorisation (NMF) algorithms are able to find the latent topics within a document collection. Although LDA is specifically designed as a topic modeling algorithm, NMF is able to produce more coherent topics for smaller domain specific document collections. Both algorithms map documents to topics and topics to words and perform soft clustering (i.e., documents and words can belong to multiple topics), making them particularly suitable as qualitative content analysis aids. In this presentation the mathematical underpinning of both algorithms along with their relevant R packages (Topic Models and NMF) will briefly be introduced. The main focus of the presentation however will be on using R to address issues that qualitative researchers encounter when using topic modeling algorithms which include trust, topic quality/coherence, topic interpretation, evidence gathering and model parameter selection. Various tools to visualise the output of topic model will be discussed (i.e., LDAVis) and an intuitive user interface to explore topic models and gather evidence will be built using Shiny. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="8" data-target=".8collapsed">
  <td>10:30</td>
  <td>text analysis/nlp</td>
  <td>JeongMin Kwon</td>
  <td>TBD</td>
  <td>From humble data to training data</td>
</tr>
<tr class="collapse out budgets 8collapsed">
  <td colspan="6"> There are lots of imperfect data. User feedback is not trustworthy, and implicit data is not unlabelled and hard to wrangle - and it is hard to use for machine learning and many other ways. But we can use them with changing thinking and data wrangling. In this presentation, I suggest some new ideas for wrangling data to use in machine learning and show our case studies. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="77" data-target=".77collapsed">
  <td>10:30</td>
  <td>text analysis/nlp</td>
  <td>Talia Beech</td>
  <td>TBD</td>
  <td>Strategic Capability Analysis for CANSOFCOM</td>
</tr>
<tr class="collapse out budgets 77collapsed">
  <td colspan="6"> To enhance Canada Special Operations Forces Command competitive advantage in deterring and defeating adversaries as well as collaborating with allies, a strategic capability assessment was conducted to identify current and future capability gaps using concepts from the forecasted future operating environment. Military capability implications are identified and assessed using a wargame-based survey approach across a range of units within the Command. Data collected included ordinal data as well as supplementary comments.
Ordinal data is analyzed using the Likert package, with an emphasis on the visualization of the data using stacked bar plots. Comment data is evaluated using  R text mining packages with some emphasis on preprocessing steps to simplify text mining tasks. Results are used as a foundation for implementing constructive institutional change across the Command. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="165" data-target=".165collapsed">
  <td>10:30</td>
  <td>text analysis/nlp</td>
  <td>Thomas Klebel</td>
  <td>TBD</td>
  <td>jstor: An R package for Analysing Scientific Articles</td>
</tr>
<tr class="collapse out budgets 165collapsed">
  <td colspan="6"> The interest in the (quantitative) analysis of textual data has increased considerably over the last few years. For researchers investigating the scholarly literature the full text archive of JSTOR (http://www.jstor.org) offers a rich and diverse set of journal articles and other texts. Through its service Data for Research (http://www.jstor.org/dfr/), JSTOR gives researchers the opportunity to analyse this data, by delivering metadata, n-grams and, upon special request, full-text materials. jstor (https://tklebel.github.io/jstor/) enables researchers to easily import the supplied metadata to R. These metadata can either be analysed on their own, or be used in conjunction with n-grams or full-text-data. The presentation will show how jstor supports investigations of scholarly literature, covering the analysis of n-grams and citation analysis. Besides introducing possible applications, the paper will also discuss limitations regarding data quality and possible solutions thereof. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="73" data-target=".73collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Sourav Das</td>
  <td>TBD</td>
  <td>A routine for measuring the nonstationarity of a time series</td>
</tr>
<tr class="collapse out budgets 73collapsed">
  <td colspan="6"> Since the 1960's nonstationary
time series have been
investigated extensively. Methodology and theory have
evolved rapidly since Dahlhaus' construction of locally
stationary processes in the 1990's. However much of the
theory in above constructions rely on assumptions of
smoothness on the time varying transfer function. However
when modelling real data, tools for assessing such regularity
conditions are yet to be developed. We have proposed a methodology that allows a domain expert to measure the non-stationarity of a time series using principles of non-parametric regression. In this talk we present a R routine that can be used to easily compute the proposed non-stationarity index. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="112" data-target=".112collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Mitchell O'Hara-Wild</td>
  <td>TBD</td>
  <td>fasster: Forecasting multiple seasonality with state switching</td>
</tr>
<tr class="collapse out budgets 112collapsed">
  <td colspan="6"> Forecasting time-series which contain multiple seasonal patterns requires flexible modelling approaches, and the need for continuously updating models emphasises the importance of fast model estimation. 

In response to shortcomings in current models, a new model is proposed which brings the desirable qualities of speed, flexibility and support for exogenous regressors into a state space model. This proposed model also introduces state switching, which captures groups of irregular multiple seasonality by switching between states. 

The functionality of the proposed model extends beyond forecasting, by allowing for model based time-series decomposition, imputation of missing values, and support for streaming data.

This model is available as an R package (mitchelloharawild/fasster), which provides formula based model specification, and uses tidy data structures (tsibble) and APIs which will later become familiar in forecast's next iteration: tidyforecast. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="150" data-target=".150collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Rob Hyndman</td>
  <td>TBD</td>
  <td>Tidy forecasting in R</td>
</tr>
<tr class="collapse out budgets 150collapsed">
  <td colspan="6"> The forecast package in R is widely used and provides good tools for monthly, quarterly and annual time series. But it is not so well-developed for daily and sub-daily data, and it does not interact easily with modern tidy packages such as dplyr, purrr and tidyr.

I will describe our plans and progress in developing a collection of packages to provide tidy tools for time series and forecasting, which will interact seamlessly with tidyverse packages, and provide functions to handle time series at any frequency.

 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="181" data-target=".181collapsed">
  <td>10:30</td>
  <td>algorithms/models</td>
  <td>Thiyanga Talagala</td>
  <td>TBD</td>
  <td>seer: R package for feature-based forecast-model selection</td>
</tr>
<tr class="collapse out budgets 181collapsed">
  <td colspan="6"> The seer package provides a novel framework for forecast model selection using time series features. We call this framework FFORMS (Feature-based FORecast Model Selection). The underlying approach involves computing a vector of features from the time series which are then used to select the forecasting model. The model selection process is carried out using a classification algorithm -- we use the time series features as inputs, and the best forecasting algorithm as the output. The classification algorithm can be built in advance of the forecasting exercise (so it is an “offline” procedure). Then, when we have a new time series to forecast, we can quickly compute its features, use the pre-trained classification algorithm to identify the best forecasting model, and produce the required forecasts. Thus, the “online” part of our algorithm requires only feature computation, and the application of a single forecasting model, with no need to estimate large numbers of models within a class, or to carry out a computationally-intensive cross-validation procedure. This framework is compared against several benchmarks and other commonly used forecasting methods. </td>
</tr>

<tr class="clickable" data-toggle="collapse" id="84" data-target=".84collapsed">
  <td>14:00</td>
  <td>applications/big data</td>
  <td>Mark Padgham</td>
  <td>TBD</td>
  <td>tRansport tools for the World (Health Organization)</td>
</tr>
<tr class="collapse out budgets 84collapsed">
  <td colspan="6"> The World Health Organization (WHO) contracted us to provide actionable evidence for the redesign of urban transport policies to help rather than hinder human health. That means more active transport.  Designing cost-effective policies to get people walking and cycling requires insight into where, when, how, and why people currently travel.  This is challenging, especially in cities with limited resources, data, or analysis capabilities.  We briefly describe some technical details of our 'Active Transport Toolkit' (ATT), but the primary focus will be the context that led to the WHO contract and where we plan to go next.  We argue that useRs are well-placed to provide openly available, global-scale, transparent tools for policy making.  It was the flexibility of the R language and the supportiveness of its community - notably including ROpenSci, which hosts two of our packages - that enabled us to develop the ATT in a way that makes it flexible enough to capture citys' unique characteristics while providing a consistent user interface.  The talk will conclude with a outline of lessons learned from the perspective of others wanting to create R tools to inform policy. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="62" data-target=".62collapsed">
  <td>14:00</td>
  <td>applications/big data</td>
  <td>Philip Dyer</td>
  <td>TBD</td>
  <td>Models of global marine biodiversity: an exercise in mixing R markdown, parallel processing and caching on supercomputers</td>
</tr>
<tr class="collapse out budgets 62collapsed">
  <td colspan="6"> R has become the standard language in ecology for statistics and modelling. If a technique has been published in mathematical ecology it has an R package. Even the data sets have an R package! The size of data sets in ecology has been growing to the point where global analysis of ecological data can be considered. At the same time powerful statistical techniques that rely on randomly permuting the data, such as bootstrapping, have become more popular. These are exciting times, but how do we get R to process our large data sets with computationally expensive algorithms without waiting forever to get results? For those new to R, or at least new to big data in R, I have some tips, techniques and packages to help you get going. I have benefited from using R markdown and Knitr to make short transcript files. I have also made use of caching to avoid recalculating big models and using parallel processing to calculate the models faster in the first place. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="177" data-target=".177collapsed">
  <td>14:00</td>
  <td>applications/big data</td>
  <td>Chris Hansen</td>
  <td>TBD</td>
  <td>Enabling Analysts: Embracing R in a National Statistics Office</td>
</tr>
<tr class="collapse out budgets 177collapsed">
  <td colspan="6"> Stats NZ has recently adopted R as an approved analytical tool, and more recently for use in production of official outputs.  Since adoption, R has had significant uptake, and has been a great enabler for analysts.  R is more expressive and flexible than the existing tools, allowing them to more easily solve a variety of problems.  R is deployed on powerful servers, so users have a generous supply of memory and cores, meaning large datasets can be handled, and long-running computations parallelised.  Analysts access R using R Studio Server, and this IDE itself has had a number of positive impacts--the use of RStudio projects and R markdown documents in particular helps analysts work in a more organised way, and ensures work is reproducible.  Our statistical platforms can now also use R.  This is done via OpenCPU which enables remote exection of function via an HTTP API.  That is, OpenCPU can be used to call functions in internally developed packages as web services. This has proven useful as we transition to a more service oriented architecture.  In this talk we describe the R environment at Stats NZ, it’s implications for analysts, and provide examples of its use in practice. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="231" data-target=".231collapsed">
  <td>14:00</td>
  <td>applications/big data</td>
  <td>Tracy Huang</td>
  <td>TBD</td>
  <td>Developing an Uncertainty Toolbox for Agriculture: a closer look at Sensitivity Analysis</td>
</tr>
<tr class="collapse out budgets 231collapsed">
  <td colspan="6"> Digiscape is one of 8 Future Science Platforms in CSIRO focussed on delivering new analytics in the digital age to better inform agricultural systems in the face of uncertainty. The Uncertainty Toolbox is one of 15 projects within Digiscape trying to make a difference to the way models are interpreted, reported and communicated in practice for decision-making. Uncertainty is front and centre of every modelling problem but it is sometimes difficult to quantify and challenging to communicate. 
The Sensitivity Analysis workflow focuses on developing a general framework for sensitivity analysis to inform the modeller about key parameters of interest and refine the model so it can be used in a robust way to make predictions and forecasts with uncertainties. We focus on methods applicable for large scale, non-monotonic problems that develop variance based approaches to sensitivity analysis using emulators. As such, the framework for developing this workflow in R becomes important for transparency and usability.  We will outline the design steps for constructing this workflow using the latest object oriented systems available in R and give a demonstration of the tool using Shiny. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="52" data-target=".52collapsed">
  <td>14:00</td>
  <td>big data/visualisation</td>
  <td>Miguel Gonzalez-Fierro</td>
  <td>TBD</td>
  <td>Spark on demand with AZTK</td>
</tr>
<tr class="collapse out budgets 52collapsed">
  <td colspan="6"> Apache Spark has become the technology of choice for big data engineering. However, provisioning and maintaining Spark clusters can be challenging and expensive. To address this issue, Microsoft has developed the Azure Distributed Data Engineering Toolkit (AZTK). This talk describes how AZTK Spark clusters can be provisioned in the cloud from a local machine with just a few commands. The clusters are ready to use in under 5 minutes and come with R and R Studio Server pre-installed, allowing R users to start developing Spark applications immediately. Users can apply their own Docker image to customize the Spark environment. ATZK clusters, composed of low priority Azure virtual machines, can be created on demand and run only as needed allowing for large cost savings. We will show a short demo of how the pre-installed sparklyr package can be used to perform data engineering tasks using dplyr syntax, and machine learning using the Spark MLlib library. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="76" data-target=".76collapsed">
  <td>14:00</td>
  <td>big data/visualisation</td>
  <td>Benjamin Ortiz Ulloa</td>
  <td>TBD</td>
  <td>Graphs: Datastructures to Query</td>
</tr>
<tr class="collapse out budgets 76collapsed">
  <td colspan="6"> When people think of graphs, they often think about mapping out social media connections. While graphs are indeed useful for mapping out social networks, they have many other practical applications. Data in the real world resemble vertices and edges more than they resemble rows and columns.  This allows researchers to intuitively grasp the data modeled and stored within a graph. Graph exploration -- also known as graph traversal -- is traditionally done with a traversal language such as Gremlin or Cypher. The functionality of these traversal languages can be duplicated by combining the  igraph and magrittr packages. Traversing a graph in R gives useRs access to a myriad of simple, but powerful algorithms to explore their data sets. 

This talk will show why data should be explored as a graph as well as show how a graph can be traversed in R. I will do this by going through a survey of different graph traversal techniques and by showing the code patterns necessary for each of those techniques. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="147" data-target=".147collapsed">
  <td>14:00</td>
  <td>big data/visualisation</td>
  <td>Amy Stringer Amy Stringer</td>
  <td>TBD</td>
  <td>Automated Visualisations for Big Data</td>
</tr>
<tr class="collapse out budgets 147collapsed">
  <td colspan="6"> The Catlin Seaview project is a large scale reef survey for estimating coral
cover at various locations around the world. Upon re-surveying, it is possible
to track changes in, and predict the future condition of, these reefs over time.
The survey collects hundreds of thousands of images from 2km transects of
reef, which are then sent to a neural network for automatic annotation of reef
communities. Annotations are completed in such a way that the resulting data
have hierarchical spatial scales; going up from image, to transect, to reef, to
subregion, to region.
Here, we present an efficient method for extracting, summarising and visu-
alising the big and complex data with Rmarkdown, dplyr and ggplot2. The use
of Rmarkdown, for report generation, allows for the introduction of parameters
into the construction of the document, allowing for entirely unique reports to be
developed from the one source script. This approach has resulted in a system
for compiling 22 reproducible reports, extracting, summarising and visualising
data at multiple spatial scales, from over 600 000 images, in a matter of minutes;
leaving machines to do the work so that people have time to think. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="199" data-target=".199collapsed">
  <td>14:00</td>
  <td>big data/visualisation</td>
  <td>Snehalata Huzurbazar</td>
  <td>TBD</td>
  <td>:  Visualizations to guide dimension reduction for sparse high-dimensional data</td>
</tr>
<tr class="collapse out budgets 199collapsed">
  <td colspan="6"> Dimension reduction for high-dimensional data is necessary for descriptive data analysis. Most researchers restrict themselves to visualizing 2 or 3 dimensions, however, to understand relationships between many variables in high-dimensional data, more dimensions are needed. This talk presents several new options for visualizing beyond 3D. These are illustrated using 16S rRNA microbiome data. We will show intensity plots developed to highlight the changing contributions of taxa (or subjects) as the number of principal components of the dimension reduction or ordination method  are changed. And secondarily revive Andrews curves, connected with a tour algorithm for viewing 1D projections of multiple principal components, to study group behavior in the high-dimensional data. The plots provide a quick visualization of taxa/subjects that are close to the `center' or that contribute to dissimilarity. They also allow for exploration of patterns among related subjects or taxa not seen in other visualizations. All code is written in R and available on Github. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="91" data-target=".91collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Christoph Bergmeir</td>
  <td>TBD</td>
  <td>ssc: An R Package for Semi-Supervised Classification</td>
</tr>
<tr class="collapse out budgets 91collapsed">
  <td colspan="6"> Semi-supervised classification has become a popular area of machine learning, where both labeled and unlabeled data are used to train a classifier. This learning paradigm has obtained promising results, specifically in the presence of a reduced set of labeled examples. We present the R package ssc (https://cran.r-project.org/package=ssc) that implements a collection of self-labeled techniques to construct a classification model. This family of techniques enlarges the original labeled set using the most confident predictions to classify unlabeled data. The techniques implemented in the ssc package can be applied to classification problems in several domains by the specification of a suitable learning scheme. At low ratios of labeled data, it can be shown to perform better than classical supervised classifiers. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="130" data-target=".130collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Przemyslaw Biecek</td>
  <td>TBD</td>
  <td>DALEX will help you to understand this complex predictive model</td>
</tr>
<tr class="collapse out budgets 130collapsed">
  <td colspan="6"> Complex machine learning models (random forest/gradient boosting machines/other ensembles) are frequently used in predictive modeling and  have many successful applications in predictive and prognostic modeling.  Yet in many cases these models are perceived as ,,black-boxes’’ with good accuracy but very complex, hard to understand, structure.
 
In this talk I will present the methodology for exploration, validation and explanation of complex machine learning models. The methodology is implemented in the DALEX library for the R (Descriptive mAchine Learning EXplanations). 
The methodology contains three sets of explainers:
-	explainers for individual model predictions, that may be used to better understand key variables that drive model predictions,
-	explainers for individual variables, that may be used to better understand how model predictions are related with values of a selected feature,
-	explainers for global model structure, that may be used to assess globally important variables or important structures in the model.

Find more about DALEX here: https://pbiecek.github.io/DALEX/
I will give a workshop about this package. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="142" data-target=".142collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Roel Henckaerts</td>
  <td>TBD</td>
  <td>Tree-Based Machine Learning for Insurance Pricing</td>
</tr>
<tr class="collapse out budgets 142collapsed">
  <td colspan="6"> The goal of this paper is to apply machine learning techniques to insurance pricing, thereby leaving the actuarial comfort zone of generalized linear models (GLMs) and generalized additive models (GAMs). We focus on developing full tariff plans, built from both the frequency and severity of claims. We adapt the cost functions and performance measures used in the algorithms such that the specific characteristics of insurance data are carefully incorporated: highly unbalanced count data with excess zeros on the frequency side and scarce, but potentially heavy-tailed and right-censored data on the severity side. One of the key requirements is the need for transparent, interpretable pricing models which are easily explainable to all stakeholders. We therefore shy away from black box models such as neural networks and rather focus on tree-based machine learning models. Starting from single recursive trees we work towards more advanced ensembles such as bagged trees, random forests and boosted trees. We also present visualization tools to obtain insights from the models by assessing the importance of the different risk factors and their impact on the price of an insurance contract. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="204" data-target=".204collapsed">
  <td>14:00</td>
  <td>models/algorithms</td>
  <td>Lubomír Štěpánek</td>
  <td>TBD</td>
  <td>Classification and evaluation of facial attractiveness and emotions for purposes of plastic surgery using machine-learning methods and R</td>
</tr>
<tr class="collapse out budgets 204collapsed">
  <td colspan="6"> Current plastic surgery deals with aesthetic indications such as an improvement of the attractiveness of a smile or other facial emotions. In this work, we have applied machine-learning methods and R to explore how accurate classification of photographed faces into sets of facial emotions (based on Ekman-Friesen FACS scale) is, and furthermore which facial emotions are associated with highest facial attractiveness, measured using Likert scale by a board of observers. Facial image data collected for each of a patient, exposed to an emotion incentive, were processed, landmarked and analyzed using R. Neural networks (neuralnet package) in comparison to Bayesian naive classifiers (e1071 package) and regression trees (rpart package) manifested the highest predictive accuracy of a new face categorization into facial emotions. Decision trees identified that the geometry of a mouth, eyebrows and eyes, respectively, affect in descending order an intensity of a classified emotion. We performed machine-learning analyses using R to point out which facial emotions and their geometry affect facial attractiveness the most, and therefore should preferentially be addressed within plastic surgeries. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="127" data-target=".127collapsed">
  <td>14:00</td>
  <td>space/time/visualisation</td>
  <td>Daniel Fryer</td>
  <td>TBD</td>
  <td>rcosmo: Statistical Analysis of the Cosmic Microwave Background</td>
</tr>
<tr class="collapse out budgets 127collapsed">
  <td colspan="6"> The Cosmic Microwave Background (CMB) is remnant electromagnetic radiation from the epoch of recombination. It is the most ancient important source of data about the early universe and the key to unlocking the mysteries of the Big Bang and the structure of time and space. Spurred on by a wealth of satellite data, intensive investigations in the past few years have resulted in many physical and mathematical results to characterise CMB radiation. It can be modelled as a realisation of a homogeneous Gaussian random field on the sphere. But, what does any of this matter for statisticians if they cannot play with the CMB data in their favourite programming language?
A new R package, rcosmo, provides easy access to the CMB data and various tools for exploring geometric and statistical properties of the CMB. This talk will be a quick introduction to rcosmo by one of its developers, followed by an invitation for discussions and suggestions.

This research was supported under the Australian Research Council's Discovery Project DP160101366.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="135" data-target=".135collapsed">
  <td>14:00</td>
  <td>space/time/visualisation</td>
  <td>Robin Hankin</td>
  <td>TBD</td>
  <td>Special and general relativity in R</td>
</tr>
<tr class="collapse out budgets 135collapsed">
  <td colspan="6"> Although mostly used for statistics, R is a general purpose tool and
here I discuss how the R programming language can be used in the
context of physics education.  Here I introduce two R packages that
have been used in the teaching of Einstein's theories of special and
general relativity.

The 'gyrogroup' package implements the Lorentz boosts for relativistic
velocity addition.  It provides dramatic visualization of the
little-known fact that relativisitic Lorentzian velocity addition is
neither commutative nor associative.  The 'schwarzschild' package
presents visualization of black hole physics, and gravitational waves.

In this presentation I discuss these two packages and also the more
general issue of R used as a teaching tool in the context of physics
more generally.
 </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="74" data-target=".74collapsed">
  <td>14:00</td>
  <td>visualisation</td>
  <td>Paul Murrell</td>
  <td>TBD</td>
  <td>The Minard Paradox</td>
</tr>
<tr class="collapse out budgets 74collapsed">
  <td colspan="6"> Charles Joseph Minard's depiction of Napoleon's 1812 Russian campaign
might be described as the best statistical graphic ever drawn ... by
hand.  Minard did not have the benefit of modern computer technology
to help with his drawing; he did not have the option of importing a
Google map tile; and he probably did not even consider the possibility
of interactive tooltips.  However, there are aspects of what Minard
produced by hand that are very challenging for modern graphical
software, particularly the thick bands that represent the size of
Napolean's army over time.  This talk will describe the 'vwline'
package for R and explore some of the interesting challenges that
arise when attempting to render variable-width lines with software. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="158" data-target=".158collapsed">
  <td>14:00</td>
  <td>visualisation</td>
  <td>Natalia da Silva</td>
  <td>TBD</td>
  <td>Interactive Graphics for Visually Diagnosing Forest Classifiers in R</td>
</tr>
<tr class="collapse out budgets 158collapsed">
  <td colspan="6"> This paper describes structuring data and constructing plots to explore forest classification models interactively. A forest classifier is an example of an ensemble since it is produced by bagging multiple trees. The process of bagging and combining results from multiple trees produces numerous diagnostics which, with interactive graphics, can provide a lot of insight into class structure in high dimensions. Various aspects are explored in this paper, to assess model complexity, individual model contributions, variable importance and dimension reduction, and uncertainty in prediction associated with individual observations. The ideas are applied to the random forest algorithm (Breiman, 2001)  and projection pursuit forest (da Silva et al., 2017), but could be more broadly applied to other bagged ensembles. Interactive graphics are built in R (R Core Team, 2016) using the ggplot2( Wickham, 2016),  plotly (Sievert et al., 2017), and shiny (Chang et al., 2015) packages. </td>
</tr>
<tr class="clickable" data-toggle="collapse" id="141" data-target=".141collapsed">
  <td>14:00</td>
  <td>visualisation</td>
  <td>Chun Fung (Jackson) Kwok</td>
  <td>TBD</td>
  <td>Rjs: Going hand in hand with Javascript</td>
</tr>
<tr class="collapse out budgets 141collapsed">
  <td colspan="6"> Many of the popular data visualisation packages in R, e.g. Plotly, Leaflet and DiagrammeR, are powered by JavaScript. I will demonstrate how far a little JavaScript can go towards creating animated and interactive visualisations from within R. This is done with the package, Rjs, which provides a simple interface between R and JavaScript. It allows you to seamlessly combine R modelling packages with JavaScript interactive visualisation libraries. This talk is for researchers, data analysts, and intermediate R users looking to extend their skills in interactive data visualisation. </td>
</tr>

  </table>
</div>

<br>