# MA5953 - Creating Your Own Data: Survey Design & Analysis; Web Scraping &amp; Text Mining

## Course Introduction

The course provides an introduction to different methods on how to create data. Specifically, the module will teach you how to generate data from surveys and how to scrape data from the web and conduct text analysis using some of the most common methods of supervised and unsupervised classification. 

### Core Readings

* Groves, R. M., Fowler Jr, F. J., Couper, M. P., Lepkowski, J. M., Singer, E., & Tourangeau, R. (2011). Survey methodology (Vol. 561). John Wiley & Sons. [Available here](https://librarysearch.kent.ac.uk/client/en_GB/kent/search/detailnonmodal/ent:$002f$002fSD_ILS$002f0$002fSD_ILS:1525940/ada)
* Munzert, S., Rubba, C., Meißner, P., & Nyhuis, D. (2014). Automated data collection with R: A practical guide to web scraping and text mining. John Wiley & Sons.

The specific chapters and further additional resources will be outlined in the description of each class below.

### Assessment
(1) You will have to design an original survey question and pre-test it via (1) cognitive interviews (with 2-3 people); and via (2) a pilot survey (with 10-20 people). You will then produce a 1,000 words report outlining the process, results and the lessons learned and a recommendation on an improved, final survey question. IMPORTANT: You **cannot** ask sensitive or distressing questions, and you **cannot** interview people without their consent or under the age of consent or incapable of giving consent. The first step is therefore to complete the [ethics checklist](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/blob/main/Class%205). This will have to be attached as an appendix. Failure to do so will mean a deduction in your grade. Remember that for the cognitive interview exercise and for the pilot survey you need to include a consent form at the beginning of your questionnaire. Click here to download [the consent form](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%205). After designing your question and completing the ethics checklist, you can move on to perform the cognitive testing (explained in detail in class 2). After analysing the responses to the cognitive interviewing task, you move on to drafting and sending out the pilot survey questionnaire (we're going to learn how to use R and [Google Forms](https://www.google.co.uk/forms/about/) to collect our own survey data in class 3). In the pilot survey you are expected to add a couple of survey items from existing surveys (capturing theoretical correlates - see lecture 2) to help you perform some validity checks. A good survey question data-bank can be found [here](https://www.icpsr.umich.edu/web/pages/ICPSR/ssvd/). The 1,000 report should include: (a) a synthesis of the concept/phenomenon measured by the original survey item you created and why it matters; (b) a description of the cognitive interviewing method and process as well as its results; (c) an explanation of the steps taken to validate key survey items with the pilot survey (with the appropriate visualisations - tables & figures); (d) a discussion of recommendations for the final survey item wording and recommendations on the parameters of the final survey (sampling, ways to minimise survey bias). You need to also include your ethical approval and your cognitive probing and survey questionnaires as an appendix. The appendix and tables/figures and R code do not count towards the word limit. PLEASE include a word count at the top of your report. Website to count words [here](https://wordcounter.net). 

Submit your report on Moodle in the relevant submission folder. The submission will have to be in pdf format. Please Knit your .Rmd file and it will be automatically converted to pdf (as shown in lecture videos 1 and 3). Add any separate appendix material, appropriately converted into pdf format (i.e. ethics checklist, consent form message, cognitive interview question list, final survey question list), using pdf merge online tools - such as [this one](https://smallpdf.com/merge-pdf). 

Also: no need to attach the cognitive interview/final interview datasets to the submission.

(2) In this task you will have to scrape tweets from 2 politicians of your choice and carry out either a sentiment analysis or a topic model analysis, on the basis of a research question of your choosing. The 1,000 words report will include (a) a section describing/justifying the choice of research question and describing the text data scraped; (b) a section where the text mining method is presented, and (c) a section where the results from the comparison are presented (with visualisations and/or numerical summaries). The appendix and tables/figures and R code do not count towards the word limit. PLEASE include a word count at the top of your report. Website to count words [here](https://wordcounter.net).

For both assessments, [R Markdown](http://rmarkdown.rstudio.com) will need to be used to generate the reports. The snippets of R code will need to be visible and will not count towards the word limit. The appendix will also not count towards the word limit. +/- 10% of the word limit is allowed.

Please submit your assessments in the relevant folder on the MA5953 Moodle page.

### Requirements

You need to have installed the most up-to-date versions of [R](https://www.r-project.org) and  [RStudio](https://rstudio.com/products/rstudio/download/)

Some prior knowledge of R and [R Markdown](http://rmarkdown.rstudio.com) is a must, make sure you understand the language basics (packages, objects/vectors, core functions and vector + basic data management operations), and that you know how to trouble-shoot errors and install packages. We will cover R Markdown in class as well, since assessments will need to be submitted using R Markdown.

**Introductory Resources - R**:

* R Manual: [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)

* Adler, Joseph. 2009. R in a Nutshell. A Desktop Quick Reference. O’Reilly

* Teetor, Paul. 2011. R Cookbook. O’Reilly.

* I recommend the following website for tutorials: https://stats.idre.ucla.edu/r/



### Course Structure

The course will run for 5 weeks in the Autumn term and for 6 weeks in the Spring term. We will cover survey design and analysis in the Autumn and web scraping and text mining in the Spring.

***Autumn Term: Survey Design & Analysis***

5 Lecture-Seminars of 2 hours each

***Spring Term: Web Scraping & Text Mining***

6 Computer Labs of 2 hours each. NOTE: the class will be split into two groups in the second term!




## Detailed Course Schedule



### ***Autumn Term: Survey Design & Analysis*** ###

### 10 NOV 2021 - Class 1: Introduction to the Course, Resources and to RMarkdown

This class will introduce the whole module, its assessment, requirements and the resources offered. We will also have a look at R Markdown and how to generate a report with it - as R Markdown files are required for submitting the two assessments. We will briefly introduce various survey types, and the advantages and disadvantages of various survey methods.

***Readings***

* [The R Markdown CheatSheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
* Groves et al. (2011) - Chapters 1 & 5 (only section 5.1)

***Additional Resources***
* Pew Research Centre [Survey Mode and Sample Design](https://www.pewresearch.org/our-methods/international-surveys/survey-mode-and-sample-design/)
* Wolf, C., Joye, D., Smith, T. E., Smith, T. W., & Fu, Y. C. (Eds.). (2016). The SAGE handbook of survey methodology. Sage.
* Heeringa, S. G., West, B. T., & Berglund, P. A. (2017). Applied survey data analysis. CRC Press. (esp. Chapters 1-5)

***Lecture Notes & Computer Lab Material***

See folder ["Class 1 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%201)

### 17 NOV 2021 - Class 2: Principles of Survey Question Design 

This class will introduce practical advice on how best to design survey questions and will cover the cognitive model behind survey responses, cognitive interviewing and a discussion on how to properly pre-test and validate new survey items.


***Readings***

* Groves et al. (2011) - Chapters 2, 7 & 8
* William Davidson Institute, University of Michigan ["Cognitive Interview Guide Developed by the Performance Measurement Initiative"](https://wdi.umich.edu/wp-content/uploads/Cognitive-Interview-Guide.pdf)

***Additional Resources***

* Wolf, C., Joye, D., Smith, T. E., Smith, T. W., & Fu, Y. C. (Eds.). (2016). The SAGE handbook of survey methodology. Sage.
* Heeringa, S. G., West, B. T., & Berglund, P. A. (2017). Applied survey data analysis. CRC Press. (esp. Chapters 1-5)

***Lecture Notes & Computer Lab Material***

[In-class cognitive interviewing exercise](https://docs.google.com/forms/d/e/1FAIpQLSfRnb7fYKvpQh0xrPQSZy1L6t5kIqx05BIsYmH34EtdsjUMZA/viewform?usp=sf_link)

See folder ["Class 2 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%202)


### 24 NOV 2021 - Class 3: Sampling & Data Collection Methods

In this class, we will discuss the issue of representativeness: i.e. whether the survey's results are likely to represent the target population or not. We will talk about various types of sampling methods, and we will go over practical advice on how to collect survey responses and record them in appropriately formatted files. We will have a look at how to collect survey data by leveraging [Google Forms](https://www.google.co.uk/forms/about/), and also cover best practices for collecting, coding and storing survey responses.

***Readings***

* Groves et al. (2011) - Chapters 4, 5 (section 5.3 only) & 10 (until section 10.4 inclusive + section 10.8)
* Schneider, D., & Harknett, K. (2019). [What’s to like? Facebook as a tool for survey data collection](https://journals.sagepub.com/doi/full/10.1177/0049124119882477). *Sociological Methods & Research*.

***Additional Resources***

* R for the Rest of Us ["Using R to Automate Survey Administration"](https://rfortherestofus.com/2019/07/using-r-to-automate-survey-administration/)
* Wolf, C., Joye, D., Smith, T. E., Smith, T. W., & Fu, Y. C. (Eds.). (2016). The SAGE handbook of survey methodology. Sage.
* Heeringa, S. G., West, B. T., & Berglund, P. A. (2017). Applied survey data analysis. CRC Press. (esp. Chapters 1-5)

***Lecture Notes & Computer Lab Material***

See folder ["Class 3 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%203)


### 01 DEC 2021 - Class 4: Survey Error & Bias Correction

This class will cover survey error and topics such as unrepresentative samples, non-response bias, measurement error and interviewer/interview mode effects. We will discuss practical solutions to correct for such biases, and discuss survey weighting.


***Readings***

* Groves et al. (2011) - Chapters 6 & 10 (only sections 10.5 and 10.6).

***Additional Resources***

* Pew Research Centre ["How different weighting methods work"](https://www.pewresearch.org/methods/2018/01/26/how-different-weighting-methods-work/)
* Data Science Central ["Difference Between Stratified Sampling, Cluster Sampling, and Quota Sampling"](https://www.datasciencecentral.com/profiles/blogs/difference-between-stratified-sampling-cluster-sampling-and-quota)
* EES ["Weighting"](https://www.europeansocialsurvey.org/methodology/ess_methodology/data_processing_archiving/weighting.html)
* Wolf, C., Joye, D., Smith, T. E., Smith, T. W., & Fu, Y. C. (Eds.). (2016). The SAGE handbook of survey methodology. Sage.
* Heeringa, S. G., West, B. T., & Berglund, P. A. (2017). Applied survey data analysis. CRC Press. (esp. Chapters 1-5)

***Lecture Notes & Computer Lab Material***

See folder ["Class 4 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%204)


### 08 DEC 2021 - Class 5: Ethical Issues, Recap and Assessment Q&A

This class will discuss ethical issues in the collection of survey data, will provide templates for consent forms, and provide a re-cap of the survey design and analysis process. You will also have an opportunity to discuss the requirements of the assessment.


***Readings***

* Groves et al. (2011) - Chapter 11

***Additional Resources***

* Wolf, C., Joye, D., Smith, T. E., Smith, T. W., & Fu, Y. C. (Eds.). (2016). The SAGE handbook of survey methodology. Sage.
* Heeringa, S. G., West, B. T., & Berglund, P. A. (2017). Applied survey data analysis. CRC Press. (esp. Chapters 1-5)

***Lecture Notes & Computer Lab Material***

See folder ["Class 5 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%205)





### ***Spring Term: Web Scraping & Text Mining*** ###

### 19 JAN 2021 - Class 6: Data Science – Data Collection Strategies & Primer on Web Technologies

This class will introduce you to data science, best practices in data collection and management as well as the most important markup languages that form the building blocks of websites and web applications - i.e.  HTML, XML, and JSON. The class will introduce web scraping via an applied example on endangered cultural and natural sites. Data on such sites will be scraped from Wikipedia and then visualised using maps and histograms.

In the problem set and computer lab, we will practice with webpage analysis by using the Element Inspector. We will reinforce our knowledge of HTML tags by manually reproducing a webpage using such tags. We will also reproduce the endangered sites analysis from the lecture. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapters 2 & 3 & 16.4

***Additional Resources***

* [HTML Explained in 4 Minutes (by 24G)](https://www.youtube.com/watch?v=ofox_6_-gGo)
* [HTML, CSS, JavaScript Explained](https://www.youtube.com/watch?v=gT0Lh1eYk78&feature=youtu.be)

***Lecture Notes & Computer Lab Material***

See folder ["Class 6 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%206)



### Class 7: Web Scraping & Regular Expressions

This class will introduce you to webscraping from static webpages. Dynamic webpage scraping will also be briefly introduced. You will learn about node query scraping, scraping via regular expressions, and scraping via APIs. You will then learn how to parse webpages, scrape tables, texts and links using R. You will also learn how to loop over URL lists and/or lists of links to scrape multiple webpages at once. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture and will do a practical exercise which will entail scraping and cleaning Covid data for several countries from the European Centre for Disease Prevention and Control. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapters 8 & 9

***Additional Resources***

* [Installing & Using the Selector GadgetLink](https://www.youtube.com/watch?v=oqNTfWrGdbk)
* [What are APIs?](https://www.youtube.com/watch?v=OVvTv9Hy91Q)

***Lecture Notes & Computer Lab Material***

See folder ["Class 7 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%207)



### Class 8: Scraping Social Media Data

This class will introduce you to webscraping in Twitter. You will see some empirical applications of Twitter data from the political science, finance and public health fields. You will learn about the functioning of APIs more in depth, and how to gain access to Twitter rest and streaming APIs. The class will introduce the most important R packages and functions to scrape and clean Twitter data. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture in order to scrape from the Twitter rest and streaming APIs. We will also do practical exercises and search for Tweets on Brexit and on the 2020 Presidential Elections. We will also look at Obama's tweets and introduce the quanteda text analysis package by building our very first wordcloud. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapter sections: 9.1.10, 9.2.3 & Chapter 14

***Additional Resources***

* [Steps to Access the Twitter API](https://www.youtube.com/watch?v=PqqXjwoDQiY)
* Chen, K., Duan, Z., & Yang, S. (2021).[Twitter as research data: Tools, costs, skill sets, and lessons learned.](https://www.cambridge.org/core/journals/politics-and-the-life-sciences/article/twitter-as-research-data/6B31D18C5E2F9B8F9C0301BFB05F1C27)Politics and the Life Sciences, 1-17. doi:10.1017/pls.2021.19

***Lecture Notes & Computer Lab Material***

See folder ["Class 8 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%208)


### Class 9: Text Mining I - Text Pre-Processing and the Document-Term Matrix 

This class will provide you with an overview of various text mining methods, from supervised to unsupervised ones, from classification to scaling ones. You will see some empirical applications of the various methods from the political science field. You will learn about corpora, tokens, stemming, stop-words, keywords-in-context, the td-idf measure, and - crucially - about the document-feature matrix (dfm) and the bag of words assumption. The lecture will also discuss the core functions from the quanteda package to clean and trim the dfm. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by summarising the corpuses of Biden and Trump tweets and by comparing their top words. The group exercise will reproduce the entire code using tweets from Labour and Conservative MPs.


***Readings***

* Grimmer, Justin and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21(3):267–297.

* Munzert et al. 2015 Automated Data Collection with R – Chapter sections: 10.1 & 10.2 & 10.3

***Additional Resources***

* [Ken Benoit Interview on Converting Texts to Numbers](https://www.youtube.com/watch?v=9B14nsEIsUs)
* [Ken Benoit - Quanteda Tutorial](https://www.youtube.com/watch?v=UAACR3OAvxM)

***Lecture Notes & Computer Lab Material***

See folder ["Class 9 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%209)



### Class 10: Text Mining II - Sentiment Analysis: Dictionaries and the Naïve Bayes Classifier

In this class you will learn about dictionaries and about the Naïve Bayes (NB) classifier, their advantages and disadvantages. You will see some empirical applications from the political science field and learn about some of the most important existing dictionaries. You will learn how to build your own bespoke dictionary as well. The lecture will also discuss the core functions from the quanteda package to perform dictionary and NB classification.

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by comparing Starmer and Corbyn's sentiment towards immigrants. The group exercise will reproduce the entire code and will challenge you to apply the sentiment analysis on Starmer's and Corbyn's tweets on the European Union instead.


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapter 17


***Additional Resources***

* [Introduction to the Confusion Matrix](https://www.youtube.com/watch?v=wpp3VfzgNcI)
* [Introduction to Precision, Recall and F1](https://www.youtube.com/watch?v=jJ7ff7Gcq34)

***Lecture Notes & Computer Lab Material***

See folder ["Class 10 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%2010)



### Class 11: Text Mining III - Topic Models

In this class you will learn about topic model analysis, as well as its advantages and disadvantages and the various validation steps required. The lecture will also discuss the core functions from the quanteda and seededlda packages to perform topic model.

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by comparing and visualising the topics discussed by Starmer and Corbyn in their tweets.

***Readings***

* Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77-84.

* Munzert et al. 2015 Automated Data Collection with R – Chapter section: 10.4     


***Lecture Notes & Computer Lab Material***

See folder ["Class 11 Material"](https://github.com/miriamsorace/MA5953-Creating-Your-Own-Data/tree/main/Class%2011)

