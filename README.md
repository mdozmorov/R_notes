# R related notes

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

R learning and data analysis resources. Please, [contribute and get in touch](CONTRIBUTING.md)! See [MDmisc notes](https://github.com/mdozmorov/MDmisc_notes) for other programming and genomics-related notes.

# Table of content

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [General](#general)
- [Cheatsheets](#cheatsheets)
- [Courses](#courses)
  - [Conference material](#conference-material)
- [R Package Development](#r-package-development)
  - [Bioconductor](#bioconductor)
- [R Data Analysis](#r-data-analysis)
  - [Imputation](#imputation)
  - [Visualization](#visualization)
    - [Genomics](#genomics)
  - [Clustering, Dimensionality reduction](#clustering-dimensionality-reduction)
- [R Misc](#r-misc)
- [R tips & tricks](#r-tips--tricks)
- [R questions](#r-questions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## General

- [Tips how to configure RStudio](https://drdoane.com/my-rstudio-configuration/)

- [rstudio.cloud](https://rstudio.cloud) - a web-based instance of R/RStudio. [RStudio cloud cheatsheet and notes](https://docs.google.com/presentation/d/1Lc0_hLgLUh0KSS5DIEZBUfE4KzeU8kH25nGY4w2kE1o/edit#slide=id.g606317e658_0_167), from [Twitter](https://twitter.com/lobrowR/status/1295114281428684806?s=20) source. [RStudio Cloud for education - Mel Gregory](https://youtu.be/PviVimazpz8) - 24 min video with all the essense of using RStudio cloud for education

## Cheatsheets

- [RStudio Cheatsheets](https://www.rstudio.com/resources/cheatsheets/) - PDFs, PowerPoint, Keynote formats. [GitHub](https://github.com/rstudio/cheatsheets)

- [RStudio Webinars](https://github.com/rstudio/webinars) - Code and slides for RStudio webinars

- [stat133-cheatsheets](https://github.com/ucb-stat133/stat133-cheatsheets) - Cheat sheets on R, RStudio, tidyverse, ggplot2, plotly,  shiny, git, and moreucb-stat133/stat133-cheatsheets)

- [ardeeshany/Parallel_Computing](https://github.com/ardeeshany/Parallel_Computing) - A CheatSheet for Parallel Computation in R

- [awesome-R](https://github.com/qinwf/awesome-R) - A curated list of awesome R packages, frameworks and software

- [awesome-rshiny](https://github.com/grabear/awesome-rshiny) - a list of resources to learn R Shiny

- [Awesome ggplot2](https://github.com/erikgahner/awesome-ggplot2) - A curated list of awesome ggplot2 tutorials, packages etc.

- [awesome-r-dataviz](https://github.com/krzjoa/awesome-r-dataviz) - Curated resources for Data Visualization, Drawing & Publishing in R

- [awesome-r-pkgtools](https://github.com/IndrajeetPatil/awesome-r-pkgtools) - A curated list of awesome resources for R package development

- [introverse](https://spielmanlab.github.io/introverse/index.html) - alternate documentation for commonly-used functions and concepts in Base R and in the tidyverse. [Tweet](https://twitter.com/stephspiel/status/1430200830527950856?s=20)

- [awesome-r-pkgtools](https://github.com/IndrajeetPatil/awesome-r-pkgtools) - A curated list of awesome resources for R package development

## Courses

- [swirl](http://swirlstats.com/) - R package for interactive R leaning

- [learnR4free](https://www.learnr4free.com/en/index.html) - all sorts of resources (books, videos, interactive websites, papers) to learn R. [Tweet](https://twitter.com/icymi_r/status/1325021727412334592?s=20)

- [A very short R introduction](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf)

- [Data Science: A First Introduction](https://ubc-dsci.github.io/introduction-to-datascience/) - bookdown by Tiffany-Anne Timbers, Trevor Campbell, Melissa Lee. From basics of data wrangling to classification/regression/clustering/statistical inference. [Tweet](https://twitter.com/TiffanyTimbers/status/1339243967917985792?s=20)

- [Big Book of R](https://bigbookofr.netlify.app/), by Oscar Baruffa. A bookdown bookmarking links to everything R for data science, from basics, visualization, tidyverse to distributed computing, spatial data science, machine learning, and more. [GitHub](https://github.com/oscarbaruffa/BigBookofR)

- [A Complete Tutorial to learn Data Science in R from Scratch](http://www.analyticsvidhya.com/blog/2016/02/complete-tutorial-learn-data-science-scratch/) - Basics of R, with short and conscise examples

- [teach-r](https://github.com/coatless/teach-r) - List of Resources for Teaching R

- [List of courses teaching R](https://github.com/rstudio-education/rstats-ed)

- [The learnr tutorials in RStudio Cloud's primers](https://github.com/rstudio-education/primers), avaliable on [RStudio Cloud](https://rstudio.cloud/projects)

- [FasteR](https://github.com/matloff/fasteR) - Fast Lane to Learning R, learn R language in R console by following examples, by Norm Matloff

- [Hands-On Programming with R](https://rstudio-education.github.io/hopr) - introductory book how to program in R, with hands-on examples, by Garrett Grolemund

- [R for Data Science](https://r4ds.had.co.nz/) - a Tidyverse-oriented introduction to R online book, by Garrett Grolemund and Hadley Wickham

- [Advanced R](https://adv-r.hadley.nz/) and [Advanced R Solutions](https://advanced-r-solutions.rbind.io) - Advanced R programming, book and solutions, by Hadley Wickham and others

- [R Cookbook, 2nd Edition](https://rc2e.com) - statistics-oriented R introduction, by James Long and Paul Teetor

- [Efficient R programming](https://bookdown.org/csgillespie/efficientR/) - advanced concepts for efficient (R) programming, by Colin Gillespie & Robin Lovelace

- [SDS 375 Data Visualization in R](https://wilkelab.org/SDS375/schedule.html) by Claus Wilke. [GitHub: wilkelab/SDS375](https://github.com/wilkelab/SDS375). [Tweet](https://twitter.com/ClausWilke/status/1378853537237585924?s=20)

- [RMarkdown from RStudio](https://rmarkdown.rstudio.com/lesson-1.html) - illustrated guide to RMarkdown 

- [Rmarkdown for Scientists](https://rmd4sci.njtierney.com/) book by Nicholas Tierney. [GitHub](https://github.com/njtierney/rmd4sci)

- [Mastering Shiny](https://mastering-shiny.org/) book by Hadley Wickham. [GitHub](https://github.com/jcheng5/shiny-book)

- [Yet another ‘R for Data Science’ study guide](https://brshallo.github.io/r4ds_solutions/), by Bryan Shalloway. Tidyverse-oriented introduction to R

- [One Page R](https://togaware.com/onepager/) book "Data Science Quick Start: Knowledge Discovery Through R" by Togaware, includes pdf slides and R code templates for various machine learning tasks

- [Data Analysis and Prediction Algorithms with R](https://rafalab.github.io/dsbook/) book by Rafael Irizarry. Data science, statistics topics in R. [GitHub](https://github.com/rafalab/dsbook). [Old version](https://genomicsclass.github.io/book/), [Labs](https://github.com/genomicsclass/labs), and [Videos](http://lorainelab.org/statistics-and-r-for-the-life-sciences/)

- [R & Bioconductor Manual](http://manuals.bioinformatics.ucr.edu/home/R_BioCondManual) - One of the best R manual to brush up all major steps in data analysis/visualization. And links to other resources there. By Thomas Girke, UC Riverside

- [RProgrammingForResearch](https://github.com/geanders/RProgrammingForResearch) - course notes for R Programming for Research. R learning from ground up to tidyverse, with lectures, homeworks, data, source files

- [biostat561](https://github.com/adw96/biostat561) - Computational Skills for Biostatistics, from version control, R programming, ggplot, shiny, to Unix, LaTeX, Markdown, Python. By Amy Willis

- [THRIV datasci 2018](https://thriv.github.io/biodatasci2018/) - THRIV Data Science course by Stephen Turner. Comprehensive coverage from R/RStudio introduction, RMarkdown, dplyr, ggplot2, shiny to all practical and statistical aspects of data cleaning, visualization, predictive modeling, survival analysis. [Workshops](https://stephenturner.github.io/workshops/index.html)

- [Introduction to Data Science](https://datasciencelabs.github.io/) by Rafael Irizarry and Stephanie Hicks. The GitHub repo https://github.com/datasciencelabs/2020 has the latest course material, previous material for the course is available by changing the year number, e.g. https://github.com/datasciencelabs/2019. [Data for the course](https://github.com/datasciencelabs/data)

- [R Programming for Data Science](https://leanpub.com/rprogramming) by Roger Peng. Fundamentals of R programming and data science. [GitHub](https://github.com/rdpeng/rprogdatascience/)

- [Mastering Software Development in R](https://bookdown.org/rdpeng/RProgDA/), book by Roger D. Peng, Sean Kross, and Brooke Anderson. From R basics to package development

- [Statistical Computing](https://rdpeng.github.io/Biostat776/) - Biostatistics 140.776 course by Roger Peng. [Youtube Playlists](https://www.youtube.com/c/RogerPeng/playlists)

- [DataScienceSpecialization](https://github.com/DataScienceSpecialization/courses) - Course materials for the Data Science Specialization from JHU folks. Detailed lectures on each topic

- [ds4stats](https://github.com/rafalab/ds4stats) - Data Science for Statisticians Workshop. Tidyverse, Data wrangling, visualization, ggplot2, machine learning. Rmds, lab exercises, links to ready-to-view lectures. 

- [master-the-tidyverse](https://github.com/rstudio-education/master-the-tidyverse/) - the Master the Tidyverse Workshop, `tidyverse`-oriented tutorials. [Instructor's material](https://github.com/rstudio-education/master-the-tidyverse-instructors)

- [Statistical Inference via Data Science, A ModernDive into R and the Tidyverse](https://moderndive.com/)  - bookdown, statistics and data science using tidyverse. [GitHub](https://github.com/moderndive/moderndive_book)

- [Statistical Thinking for the 21st Century](https://statsthinking21.org/) - bookdown, statistics theory illustrated with R. [GitHub material](https://github.com/statsthinking21)

- [R (BGU course)](http://www.john-ros.com/Rcourse/) by Jonathan D. Rosenblatt. From R basics to regression, machine learning, graphics, shiny, advanced computing. [GitHub](https://github.com/johnros/RAMR-R-Course)

- [online-courses](https://github.com/rsquaredacademy-education/online-courses/) - Free courses by RSquareAcademy. From data import to tidyverse, web scraping, regex, databases. Videos, slides, code, data. 

- [SISBID](https://github.com/SISBID) - several modules covering various aspects of data science. Summer Institute in Statistics for Big Data. Lectures, exercises, data. [Module 1, Big Data](https://github.com/SISBID/Module1), [Module 2, Visualization of Biomedical Big Data](https://github.com/SISBID/Module2), [Module 3, Reproducible research](https://github.com/SISBID/Module3), [Module 4](https://github.com/SISBID/Module4), [Module 5](https://github.com/SISBID/Module5)

- [Ted Laderas](https://laderast.github.io/) and his [Ready for R](https://ready4r.netlify.app/) course, the accompanying [Ready for R: Notebook Reference](https://ready4r.netlify.app/labbook/) bookdown, and the [R Bootcamp](https://r-bootcamp.netlify.app) tidyverse exercises

- [R Programming For Research](https://geanders.github.io/RProgrammingForResearch/index.html) course by Brooke Anderson, Rachel Severson, and Nicholas Good, Colorado State University. Basic, intermediate, and advanced data analysis in R. [GitHub](https://github.com/geanders/RProgrammingForResearch), [Youtube playlist](https://www.youtube.com/playlist?list=PLuGPtwgRXxqK1d-3V2MKCad24h-v75k8P) with short videos on R-related topics

- [R for the Rest of Us](https://rfortherestofus.com) free R courses by David Keyes.

- [Text Mining with R](http://tidytextmining.com/), by Julia Silge and David Robinson

- [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/), by Claus O. Wilke

- [Effective graphs with Microsoft R Open](http://www.joyce-robbins.com/wp-content/uploads/2016/04/effectivegraphsmro1.pdf) - plots using base R graphics. [Blog post about the book](http://www.r-bloggers.com/free-e-book-effective-graphs-with-microsoft-r-open/), [GitHub](https://github.com/nbrgraphs/mro)

- [idem_viz](https://github.com/jschoeley/idem_viz) - Materials for the course IDEM 181 "Visualizing Data" 

- [Network visualization with R](https://github.com/kateto/R-Network-Visualization-Workshop), workshop by Katherine Ognyanova. [Blog post](http://kateto.net/network-visualization)

- [bigdataclass](https://github.com/rstudio/bigdataclass) - Big Data with R class by RStudio

### Conference material

- [R Consortium playlists](https://www.youtube.com/channel/UC_R5smHVXRYGhZYDJsnXTwg/playlists) - useR! conferences and more

- [Bioconductor 2020 workshops](https://bioc2020.bioconductor.org/workshops)

- [e-Rum2020 Conference Materials](https://2020.erum.io/rewatch/), [e-Rum2020 Program GitHub](https://github.com/Milano-R/erum2020program)


## R Package Development

- [Package Building](http://laderast.github.io/2019/02/12/package-building-description-namespace/) - How `DESCRIPTION`, `NAMESPACE`, `roxygen`, and `devtools::document` work together. By Ted Laderas
- [Automate testing of your R package using Travis CI, Codecov, and testthat](https://jef.works/blog/2019/02/17/automate-testing-of-your-R-package/), by Jean Fan
- [MangoTheCat/goodpractice](https://github.com/MangoTheCat/goodpractice) - An R package to check for good coding practices when building R packages. Syntax to avoid, package structure, code complexity, code formatting, etc. 
- [pkgdown](https://pkgdown.r-lib.org/) - an R package for making a website for your package
- [Hexmake](https://connect.thinkr.fr/hexmake/) - This app allows the user to build its own hex stickers. [RStudio note](https://community.rstudio.com/t/hexmake-2020-shiny-contest-submission/59122)
- [GuangchuangYu/hexSticker](https://github.com/GuangchuangYu/hexSticker) - Hexagon sticker in R, R package
- [neurodata/hyppo](https://github.com/neurodata/hyppo) - an example of well-documented software, informative README, badges

### Bioconductor

- [Bioc package list](https://csoneson.github.io/BiocPkgList/) - Summary and analysis of popular Bioconductor packages, by Charlotte Soneson. R/tidyverse code, [GitHub](https://github.com/csoneson/BiocPkgList)

- [S4-Bioconductor](https://github.com/MalteThodberg/S4-Bioconductor) - Online resources for learning programming with S4 in R in general, and the particular implementation in Bioconductor (BiocGenerics, S4Vectors, IRanges, GRanges, SummarizedExperiment, Biostrings, etc.).

- [code.bioconductor.org](https://code.bioconductor.org) -  Browse the contents and git history of all @Bioconductor software packages, Search for across all software packages at once, and filter results by file names, types, or packages #rstats. [Tweet](https://twitter.com/grimbough/status/1387386008799518724?s=20)
- [Developer's page](https://www.bioconductor.org/developers/)
- [Steps to contribute packages to Bioconductor](https://github.com/Bioconductor/Contributions)
- [Common Bioconductor Methods and Classes](http://bioconductor.org/developers/how-to/commonMethodsAndClasses/)
- [Develop Bioconductor packages with Docker container](https://divingintogeneticsandgenomics.rbind.io/post/develop-bioconductor-packages-with-docker-container/)
    - [Bioconductor/bioconductor_full](https://github.com/Bioconductor/bioconductor_full) - Docker Images which include a complete installation of all software needed to build all Bioconductor packages
- [BiocPkgTools](https://bioconductor.org/packages/BiocPkgTools/) - R package for queueing Bioconductor package statistics, downloads, dependencies, visualization as graphs.
    - Su, Shian, Vincent J. Carey, Lori Shepherd, Matthew Ritchie, Martin T. Morgan, and Sean Davis. “[BiocPkgTools: Toolkit for Mining the Bioconductor Package Ecosystem](https://doi.org/10.12688/f1000research.19410.1).” F1000Research 8 (May 29, 2019)
- [The package build reports](https://www.bioconductor.org/checkResults/)

- [seandavi/BuildABiocWorkshop2020](https://github.com/seandavi/BuildABiocWorkshop2020) - template for building a bioconductor workshop package using GitHub actions

- [How to run a Bioconductor Workshop on a Google Cloud Instance](https://gist.github.com/seandavi/5da4a73d94bc24236cf204196feddc85) by Sean Davis

- [Orchestra](https://github.com/seandavi/Orchestra) - workshop platform provider for running docker containers on kubernetes, by Sean Davis

## R Data Analysis

- [autoEDA-resources](https://github.com/mstaniak/autoEDA-resources) - A list of software and papers related to automatic/fast Exploratory Data Analysis


### Imputation

- [missMDA](https://CRAN.R-project.org/package=missMDA) - Imputation of incomplete continuous or categorical datasets; Missing values are imputed with a principal component analysis (PCA), a multiple correspondence analysis (MCA) model or a multiple factor analysis (MFA) model; Perform multiple imputation with and in PCA or MCA. By Francois Husson
    - Josse, Julie, and François Husson. “[MissMDA : A Package for Handling Missing Values in Multivariate Data Analysis](https://doi.org/10.18637/jss.v070.i01).” Journal of Statistical Software 70, no. 1 (2016). 

- [imputeTS](https://CRAN.R-project.org/package=imputeTS) - Imputation (replacement) of missing values in univariate time series. Offers several imputation functions and missing data plots. Available imputation algorithms include: 'Mean', 'LOCF', 'Interpolation', 'Moving Average', 'Seasonal Decomposition', 'Kalman Smoothing on Structural Time Series models', 'Kalman Smoothing on ARIMA models'
    - Moritz, Steffen, and Thomas Bartz-Beielstein. “[ImputeTS: Time Series Missing Value Imputation in R](https://journal.r-project.org/archive/2017/RJ-2017-009/index.html).” The R Journal, 2017

- [softImpute](https://CRAN.R-project.org/package=softImpute) - matrix completion (imputation). A combination of two algorithms, nuclear-norm-regularized matrix approximation and maximum-margin matrix factorization. R package, distributed version using Spark cluster. By Trevor Hastie
    - Hastie, Trevor, Rahul Mazumder, Jason Lee, and Reza Zadeh. “[Matrix Completion and Low-Rank SVD via Fast Alternating Least Squares](http://arxiv.org/abs/1410.2596).” ArXiv:1410.2596 [Stat], October 9, 2014. 

- [missForest](https://CRAN.R-project.org/package=missForest) - Nonparametric Missing Value Imputation using Random Forest. Handles continuous and categorical data. Training RF on the complete data, then predicting the missing values iteratively. 
    - Stekhoven, D. J., and P. Buhlmann. “[MissForest--Non-Parametric Missing Value Imputation for Mixed-Type Data](https://doi.org/10.1093/bioinformatics/btr597).” Bioinformatics 28, no. 1 (January 1, 2012)

- [mice](https://CRAN.R-project.org/package=mice) - Multivariate Imputation using Fully Conditional Specification (FCS). By Stef van Buuren
    - Buuren, Stef van, and Karin Groothuis-Oudshoorn. “[Mice : Multivariate Imputation by Chained Equations in R](https://doi.org/10.18637/jss.v045.i03).” Journal of Statistical Software 45, no. 3 (2011). 


### Visualization

- [circlize](https://CRAN.R-project.org/package=circlize) - Circular Visualization in R. [Documentation](http://zuguang.de/circlize_book/book/index.html)

- [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) - Graph and network visualization using tabular data in R. 

- [ggbreak](https://github.com/YuLab-SMU/ggbreak) - set axis breaks for ‘ggplot2’

- [ggfortify](https://CRAN.R-project.org/package=ggfortify) - Enhanced plotting for commonly usedstatistics, such as GLM, time series, PCA families, clustering and survival analysis

- [ggord](https://github.com/fawda123/ggord) - PCA and other dim reduction methods plotting with ellipses

- [ggpointdensity](https://github.com/LKremer/ggpointdensity) - A Cross Between a Scatter Plot and a 2D Density Plot.

- [ggridges](https://github.com/wilkelab/ggridges) - Ridgeline plots in ggplot2. [Introduction to ggridges](https://cran.r-project.org/web/packages/ggridges/vignettes/introduction.html)

- [ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot) - Enhancing `{ggplot2}` plots with statistical analysis. Examples on the [website](https://indrajeetpatil.github.io/ggstatsplot/).

- [ggstream](https://github.com/davidsjoberg/ggstream) - A package to make streamplots

- [ggsci](https://CRAN.R-project.org/package=ggsci) - Scientific Journal and Sci-Fi Themed Color Palettes for 'ggplot2'

- [MetBrewer](https://github.com/BlakeRMills/MetBrewer) - Color palette package in R inspired by works at the Metropolitan Museum of Art in New York

- [paletteer](https://github.com/EmilHvitfeldt/paletteer) - Collection of most color palettes in a single R package

- [pcaExplorer](https://bioconductor.org/packages/pcaExplorer/) - Interactive Visualization of RNA-seq Data Using a Principal Components Approach. [Tweet](https://twitter.com/chelysheva_i/status/1434488110990102531?s=20)

- [PCAtools](https://bioconductor.org/packages/PCAtools/) - set of tools performing common PCA-related tasks, by Kevin Blighe and Aaron Lun. [GitHub](https://github.com/kevinblighe/PCAtools)

- [RainCloudPlots](https://github.com/RainCloudPlots/RainCloudPlots) - Code and tutorials to visualise your data in a way that is both beautiful and statistically valid. R, Python, Matlab examples. <details>
  <summary>Paper</summary>
  Allen M, Poggiali D, Whitaker K et al. Raincloud plots: a multi-platform tool for robust data visualization [version 2; peer review: 2 approved]. Wellcome Open Res 2021, 4:63. DOI: 10.12688/wellcomeopenres.15191.2
</details>

- [scattermore](https://github.com/exaexa/scattermore) - very fast scatterplots for R. [CRAN](https://CRAN.R-project.org/package=scattermore)

- [visNetwork](https://CRAN.R-project.org/package=visNetwork) - an R package for network visualization, using vis.js javascript library. 

- [UpSetR](https://CRAN.R-project.org/package=UpSetR) - stretched and aligned Venn and Euler diagrams. [Slides by Nils Gehlenborg](https://www.bioconductor.org/help/course-materials/2017/BioC2017/Day1/InvitedSpeakers/relaxation-techniques-upset-data-scientist.pdf)
    - Conway, Jake R, Alexander Lex, and Nils Gehlenborg. “[UpSetR: An R Package for the Visualization of Intersecting Sets and Their Properties](https://doi.org/10.1093/bioinformatics/btx364).” Bioinformatics 33, no. 18 (September 15, 2017)

- [How to Create a Bar Chart Race in R](https://michaeltoth.me/how-to-create-a-bar-chart-race-in-r-mapping-united-states-city-population-1790-2010.html) - Mapping United States City Population 1790-2010. 

- [Simple Gantt charts in R with ggplot2 and Microsoft Excel](https://www.molecularecologist.com/2019/01/simple-gantt-charts-in-r-with-ggplot2-and-the-tidyverse/)

#### Genomics

- [ChromoMap](https://CRAN.R-project.org/package=chromoMap) - an R package and a Shiny app for multi-omics data visualization over the genome/chromosome plots. Input - BED files, with annotations (point annotations and segment annotations). D3 JavaScript implementation allows for interactivity. Single function, customizable. ChromLinks - link regions across chromosomes, undirected and directed, Sankey-like. [Tweet](https://twitter.com/razoralign/status/1481252549290184705?s=20), [Website](https://lakshay-anand.github.io/chromoMap/index.html). <details>
  <summary>Paper</summary>
  Anand, Lakshay, and Carlos M. Rodriguez Lopez. “ChromoMap: An R Package for Interactive Visualization of Multi-Omics Data and Annotation of Chromosomes.” BMC Bioinformatics 23, no. 1 (December 2022): 33. https://doi.org/10.1186/s12859-021-04556-z.
</details>

- [ngsplot](https://github.com/shenlab-sinai/ngsplot) - Quick mining and visualization of NGS data by integrating genomic databases. Average profiles and heatmaps of ChIP-seq-like signals.

- [RIdeogram](https://CRAN.R-project.org/package=RIdeogram) - an R package for whole-genome overlay of genomic data on an ideogram. Plot continuous and discrete data as heatmaps and track labels. GC content, gene and repeat density, DNA methylation distribution, genomic synteny. Similar functionality: [ggbio](https://bioconductor.org/packages/ggbio/), [IdeoViz](https://bioconductor.org/packages/IdeoViz/), [chromPlot](https://bioconductor.org/packages/chromPlot/), [chromDraw](https://bioconductor.org/packages/chromDraw/), [karyoploteR](https://bioconductor.org/packages/karyoploteR/), [chromoMap](https://CRAN.R-project.org/package=chromoMap), JavaScript [Ideogram.js](https://github.com/eweitz/ideogram) and [karyotypeSVG](https://github.com/andreasprlic/karyotypeSVG). Distinctive feature - visualizing changes between two or more genomes using Bezier curves (synteny, genomic rearrangements).
    - Hao, Zhaodong, Dekang Lv, Ying Ge, Jisen Shi, Dolf Weijers, Guangchuang Yu, and Jinhui Chen. “[RIdeogram: Drawing SVG Graphics to Visualize and Map Genome-Wide Data on the Idiograms](https://doi.org/10.7717/peerj-cs.251),” 2020, 11.

- [volcano3D](https://github.com/KatrionaGoldmann/volcano3D) - An R package to plot interactive three-way differential expression analysis. A polar coordinate space to plot Z-scores or fold changes of genes amond three groups, z-axis is -log10 p-value. [CRAN](https://CRAN.R-project.org/package=volcano3D), [website](https://katrionagoldmann.github.io/volcano3D/index.html), [Olnile demo](https://peac.hpc.qmul.ac.uk/). <details>
  <summary>Paper</summary>
  Lewis, Myles J., Michael R. Barnes, Kevin Blighe, Katriona Goldmann, Sharmila Rana, Jason A. Hackney, Nandhini Ramamoorthi, et al. “Molecular Portraits of Early Rheumatoid Arthritis Identify Clinical and Treatment Response Phenotypes.” Cell Reports 28, no. 9 (August 2019): 2455-2470.e5. https://doi.org/10.1016/j.celrep.2019.07.091.
</details>


### Clustering, Dimensionality reduction

- [ClusterEnG](http://education.knoweng.org/clustereng/) - online clustering and interactive visualization (D3). Seven algorithms: k-means, k-medoids, affinity propagation, spectral clustering, Gaussian mixture model, hierarchical clustering and DBSCAN. Clustering validation metrics. Tutorials using NCI60 data and B-cell lymphoma gene expression. R backend. [GitHub](https://github.com/KnowEnG/ClusterEnG).
    - Manjunath, Mohith, Yi Zhang, Steve H. Yeo, Omar Sobh, Nathan Russell, Christian Followell, Colleen Bushell, Umberto Ravaioli, and Jun S. Song. “[ClusterEnG: An Interactive Educational Web Resource for Clustering and Visualizing High-Dimensional Data](https://doi.org/10.7717/peerj-cs.155).” PeerJ. Computer Science 4 (2018). 

- [bigcor](https://www.rdocumentation.org/packages/propagate/versions/1.0-6/topics/bigcor) - Creating Very Large Correlation/Covariance Matrices. [Tweet](https://twitter.com/neilfws/status/1341602291070038016?s=20)

- [GLM-PCA](https://CRAN.R-project.org/package=glmpca) - multinomial distribution-based analysis methods for UMI counts in scRNA-seq data. Details of scRNA-seq data properties, analysis steps. [GitHub](https://github.com/willtownes/glmpca)
    - Townes, F. William, Stephanie C. Hicks, Martin J. Aryee, and Rafael A. Irizarry. “[Feature Selection and Dimension Reduction for Single Cell RNA-Seq Based on a Multinomial Model](https://doi.org/10.1101/574574).” BioRxiv, March 11, 2019.

- [PCA course using FactoMineR](https://francoishusson.wordpress.com/2017/07/13/course-on-pca-with-factominer/), with videos, by François Husson, the creator of [FactoMineR](https://CRAN.R-project.org/package=FactoMineR) - Multivariate Exploratory Data Analysis and Data Mining
    - [Multiple Factor Analysis to analyse several data tables](https://francoishusson.wordpress.com/2017/07/18/multiple-factor-analysis-to-analyse-several-data-tables/)
    - [Correspondence Analysis with FactoMineR](https://francoishusson.wordpress.com/2017/07/13/correspondence-analysis-with-factominer/)
    - [Multiple Correspondence Analysis with FactoMineR](https://francoishusson.wordpress.com/2017/07/18/multiple-correspondence-analysis-with-factominer/)

## R Misc

- [Rcpp for everyone](https://teuder.github.io/rcpp4everyone_en/) - Rcpp bookdown. [GitHub](https://github.com/teuder/rcpp4everyone_en)

- [R-parallel](https://github.com/tobigithub/R-parallel) - Using R with many CPUs. [Wiki](https://github.com/tobigithub/R-parallel/wiki) with overview, examples, snippets, links, and more

- [containerit](https://github.com/o2r-project/containerit) - an R package to create a Docker file from R session. Similar functionality provided by `dockerfiler`, `liftr`, `automagic`. 
    - Nüst, Daniel, and Matthias Hinz. “[Containerit: Generating Dockerfiles for Reproducible Research with R](https://doi.org/10.21105/joss.01603).” Journal of Open Source Software 4, no. 40 (August 21, 2019)

- [disk.frame](https://CRAN.R-project.org/package=disk.frame) - an R package for larger-than-RAM Disk-Based Data Manipulation Framework. [blog post about disk.frame usage](https://www.brodrigues.co/blog/2019-09-03-disk_frame/)

- [ppcor](https://CRAN.R-project.org/package=ppcor) - Partial and Semi-Partial (Part) Correlation

- [corpcor](https://CRAN.R-project.org/package=corpcor) - Efficient Estimation of Covariance and (Partial) Correlation

- [ymlthis](https://ymlthis.r-lib.org/index.html) - write YAML for R Markdown, bookdown, blogdown, and more. [The YAML Fieldguide](http://ymlthis.r-lib.org/articles/yaml-fieldguide.html)

- [googledrive](https://googledrive.tidyverse.org) - an R package interface to Google Drive. Alternative: Google Drive direct download of big files, [gdown.pl](https://github.com/circulosmeos/gdown.pl)

- [philentropy](https://CRAN.R-project.org/package=philentropy) - Similarity and Distance Quantification Between Probability Functions. Computes 46 optimized distance and similarity measures for comparing probability functions

- [mkdocs](http://www.mkdocs.org) Project documentation with Markdown, [GitHub](https://github.com/mkdocs/mkdocs/)

- [gt](https://github.com/rstudio/gt) - Easily generate information-rich, publication-quality tables from R

- [gtsummary](https://github.com/ddsjoberg/gtsummary) Presentation-Ready Data Summary and Analytic Result Tables


## R tips & tricks

- Install R as a user. [Slack](https://community-bioc.slack.com/archives/CLUJWDQF4/p1635267812035500)

```bash
$ curl -O https://cran.r-project.org/src/base/R-4/R-4.1.1.tar.gz
$ tar xzf R-4.1.1.tar.gz
$ cd R-4.1.1
$ mkdir -p "$HOME/software/R-4.1.1"
$ ./configure --prefix="$HOME/software/R-4.1.1"
$ make
$ make install
# Then add:
export PATH=$HOME/software/R-4.1.1/bin:$PATH
# and you've got R / Rscript (=R 4.1.1) ready to go.
```


- Convert continuous to categorical value

````
data(iris)
vari <- iris$Sepal.Length
nb.clusters <- 3
breaks <- quantile(vari, seq(0,1,1/nb.clusters))
Xqual <- cut(vari,breaks, include.lowest=TRUE)
summary(Xqual)
````

- Barplot with StdErr using standard R graphics

````
dat = agridat::lasrosas.corn
means.nf = tapply(dat$yield, INDEX=dat$nf, FUN=mean)  
StdErr.nf = tapply(dat$yield, INDEX=dat$nf, FUN= std.error)  
BP = barplot(means.nf, ylim=c(0,max(means.nf)+10))  
segments(BP, means.nf - (2*StdErr.nf), BP, means.nf + (2*StdErr.nf), lwd = 1.5)  
arrows(BP, means.nf - (2*StdErr.nf), BP,  means.nf + (2*StdErr.nf), lwd = 1.5, angle = 90,  code = 3, length = 0.05)  
````

- HDF5Array
````
library(HDF5Array)
a0 <- array(runif(15000000), dim=c(10000, 300, 5))
A0 <- as(a0, "HDF5Array")  
library(pryr) 
object_size(A0)
#> 1.94 kB
object_size(a0)
#> 120 MB #rstats
````

- Convert a vector to normally distributed one
````
interactions <- log2(interactions) # If highly right-skewed, log2-transform beforehand
# Inverse normal conversion
interactions <- sapply(interactions, function(x) {
  rank <- rank(x, na.last = "keep")
  P <- (rank - 0.5) / length(x[ !is.na(x)] )
  x <- qnorm(P)
})
````

## R questions

- Why vcd package is used? vcd package provides different methods for visualizing multivariate categorical data.
- What is iPlots? It is a package which provide bar plots, mosaic plots, box plots, parallel plots, scatter plots and histograms.
- What is fitdistr() function? It is used to provide the maximum likelihood fitting of univariate distributions. It is defined under the MASS package.
- Define loglm() function. Loglm() function is used to create log-linear models.
- How to create scatterplot matrices? Pair() or splom() function is used for create scatterplot matrices.
- Define leaps(). It is used to perform the all-subsets regression and it is defined under the leaps package.
- Define cluster.stats(). It is define in fpc package which provide a method for comparing the similarity of two clusters solution using different validation criteria.
