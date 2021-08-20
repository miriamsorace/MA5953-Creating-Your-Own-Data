# MA5953 - Creating Your Own Data: Web Scraping &amp; Text Mining

## Course Introduction

The course provides an introduction to different methods on how to create data. Specifically, the module will teach you how to scrape data from the web and conduct text analysis using some of the most common methods of supervised and unsupervised classification. 

### Assessment

You will have to scrape tweets from 2 politicians of your choice and carry out either a sentiment analysis or a topic model analysis, on the basis of a research question of your choosing. The 1,000 words report will include (a) a section describing/justifying the choice of research question and describing the text data scraped; (b) a section where the text mining method is presented, and (c) a section where the results from the comparison are presented (with visualisations and/or numerical summaries). You will need to submit your R script together with the report (the R script does not count towards the word limit). 

### Requirements

You need to have installed the most up-to-date versions of [R](https://www.r-project.org) and  [RStudio](https://rstudio.com/products/rstudio/download/)

Some prior knowledge of R and [R Markdown](http://rmarkdown.rstudio.com) is a must, make sure you understand the language basics (packages, objects/vectors, core functions and vector + basic data management operations), and that you know how to trouble-shoot errors and install packages.

􏰀**Introductory Resources - R **:

* R Manual: [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)
􏰀
* Adler, Joseph. 2009. R in a Nutshell. A Desktop Quick Reference. O’Reilly
􏰀
* Teetor, Paul. 2011. R Cookbook. O’Reilly.
􏰀
* I recommend the following website for tutorials: https://stats.idre.ucla.edu/r/

### Course Structure

The course will have weekly lectures and computer labs. The lecture will introduce the core concepts and the relevant R code for the week whereas the computer lab provides an opportunity for students to flag issues / ask questions about the lecture, the code, and the problem set. It is highly recommended that you attend the lecture/watch the lecture videos for the relevant week and practice with the problem set *before* the computer lab, to exploit the Q&A session to the fullest. The lab will also feature applied group work exercises.


## Detailed Course Schedule

### Class 1: Data Science – Data Collection Strategies & Primer on Web Technologies

This class will introduce you to data science, best practices in data collection and management as well as the most important markup languages that form the building blocks of websites and web applications - i.e.  HTML, XML, and JSON. The class will introduce web scraping via an applied example on endangered cultural and natural sites. Data on such sites will be scraped from Wikipedia and then visualised using maps and histograms.

In the problem set and computer lab, we will practice with webpage analysis by using the Element Inspector. We will reinforce our knowledge of HTML tags by manually reproducing a webpage using such tags. We will also reproduce the endangered sites analysis from the lecture. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapters 2 & 3 & 16.4

***Additional Resources***

* [HTML Explained in 4 Minutes (by 24G)](https://www.youtube.com/watch?v=ofox_6_-gGo)
* [HTML, CSS, JavaScript Explained](https://www.youtube.com/watch?v=gT0Lh1eYk78&feature=youtu.be)

***Lecture Notes & Computer Lab Material***

See folder ["Class 1 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%201%20Material)



### Class 2: Web Scraping & Regular Expressions

This class will introduce you to webscraping from static webpages. Dynamic webpage scraping will also be briefly introduced. You will learn about node query scraping, scraping via regular expressions, and scraping via APIs. You will then learn how to parse webpages, scrape tables, texts and links using R. You will also learn how to loop over URL lists and/or lists of links to scrape multiple webpages at once. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture and will do a practical exercise which will entail scraping and cleaning Covid data for several countries from the European Centre for Disease Prevention and Control. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapters 8 & 9

***Additional Resources***

* [Installing & Using the Selector GadgetLink](https://www.youtube.com/watch?v=oqNTfWrGdbk)
* [What are APIs?](https://www.youtube.com/watch?v=OVvTv9Hy91Q)

***Lecture Notes & Computer Lab Material***

See folder ["Class 2 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%202%20Material)



### Class 3: Scraping Social Media Data

This class will introduce you to webscraping in Twitter. You will see some empirical applications of Twitter data from the political science, finance and public health fields. You will learn about the functioning of APIs more in depth, and how to gain access to Twitter rest and streaming APIs. The class will introduce the most important R packages and functions to scrape and clean Twitter data. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture in order to scrape from the Twitter rest and streaming APIs. We will also do practical exercises and search for Tweets on Brexit and on the 2020 Presidential Elections. We will also look at Obama's tweets and introduce the quanteda text analysis package by building our very first wordcloud. 


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapter sections: 9.1.10, 9.2.3 & Chapter 14

***Additional Resources***

* [Steps to Access the Twitter API](https://www.youtube.com/watch?v=PqqXjwoDQiY)

***Lecture Notes & Computer Lab Material***

See folder ["Class 3 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%203%20Material)


### Class 4: Text Mining I - Text Pre-Processing and the Document-Term Matrix 

This class will provide you with an overview of various text mining methods, from supervised to unsupervised ones, from classification to scaling ones. You will see some empirical applications of the various methods from the political science field. You will learn about corpora, tokens, stemming, stop-words, keywords-in-context, the td-idf measure, and - crucially - about the document-feature matrix (dfm) and the bag of words assumption. The lecture will also discuss the core functions from the quanteda package to clean and trim the dfm. 

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by summarising the corpuses of Biden and Trump tweets and by comparing their top words. The group exercise will reproduce the entire code using tweets from Labour and Conservative MPs.


***Readings***

* Grimmer, Justin and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21(3):267–297.

* Munzert et al. 2015 Automated Data Collection with R – Chapter sections: 10.1 & 10.2 & 10.3

***Additional Resources***

* [Ken Benoit Interview on Converting Texts to Numbers](https://www.youtube.com/watch?v=9B14nsEIsUs)
* [Ken Benoit - Quanteda Tutorial](https://www.youtube.com/watch?v=UAACR3OAvxM)

***Lecture Notes & Computer Lab Material***

See folder ["Class 4 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%204%20Material)



### Class 5: Text Mining II - Sentiment Analysis: Dictionaries and the Naïve Bayes Classifier

In this class you will learn about dictionaries and about the Naïve Bayes (NB) classifier, their advantages and disadvantages. You will see some empirical applications from the political science field and learn about some of the most important existing dictionaries. You will learn how to build your own bespoke dictionary as well. The lecture will also discuss the core functions from the quanteda package to perform dictionary and NB classification.

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by comparing Starmer and Corbyn's sentiment towards immigrants. The group exercise will reproduce the entire code and will challenge you to apply the sentiment analysis on Starmer's and Corbyn's tweets on the European Union instead.


***Readings***

* Munzert et al. 2015 Automated Data Collection with R – Chapter 17


***Additional Resources***

* [Introduction to the Confusion Matrix](https://www.youtube.com/watch?v=wpp3VfzgNcI)
* [Introduction to Precision, Recall and F1](https://www.youtube.com/watch?v=jJ7ff7Gcq34)

***Lecture Notes & Computer Lab Material***

See folder ["Class 5 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%205%20Material)



### Class 6: Text Mining III - Topic Models

In this class you will learn about topic model analysis, as well as its advantages and disadvantages and the various validation steps required. The lecture will also discuss the core functions from the quanteda and seededlda packages to perform topic model.

In the problem set and computer lab, we will practice with the R code introduced in the lecture. We will also get our hands dirty by comparing and visualising the topics discussed by Starmer and Corbyn in their tweets.

***Readings***

* Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77-84.

* Munzert et al. 2015 Automated Data Collection with R – Chapter section: 10.4     


***Lecture Notes & Computer Lab Material***

See folder ["Class 6 Material"](https://github.com/miriamsorace/MA5953/tree/main/Class%206%20Material)

