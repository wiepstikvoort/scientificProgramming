# Scientific Programming
Course about scientific programming, from algorithm to implementation.

## Course Description

Scientific programming is quite like performing a wetlab experiment: there is a
research question, an experimental design, materials, and results. Of course,
one important difference is once you run your experiment once, repeating the
experiment becomes a lot easier. This course assumes programming experience
and covers various aspects of using scientific programming for development
of software to answer biological questions. During this course the students will
using professional software development standards and values for research
integrity, particularly around reproducibility. Regarding algorithm development,
the course focuses on programming approaches like parallel computing,
client-server communication, and automating statistical analysis using
interactive notebooks.


## Course Objectives

1. Create software to implement an algorithm answering a biological question
2. Learn about parallel computing
3. Learn about server-client interaction
4. Learn about making multivariate statistics reproducible
5. Apply version control in software development
6. Explain algorithms and implementations in software in appropriate
   documentation

## Topics

Week 1 provides a lecture introducing the course, and the practical
is a GitHub 101 (students are free to use GitLab or another alternative).

1. Week 2,3: Server-Client Interaction
2. Week 4,5: Making multivariate statistics reproducible
3. Week 6,7: Parallel computing

### Introduction (week 1)

#### Lecture

The lectures outlines the format of the course, topics, assessment,
and grading.

#### Practical

* making a GitHub account (or GitLab)
* creating a repository (private or public)
* creating files
* writing commit messages
* adding all required files (LICENSE, AUTHORS, README, etc)
* making a tag and matching release (with release notes)

##### Additional resources

* [Open Science MOOC](https://opensciencemooc.eu/): [Task 1: How to set up a repository on GitHub](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/content_development/Task_1.md)
* [Markdown for common license](https://github.com/IQAndreas/markdown-licenses)

### Server-Client Interaction

#### Lectures

Lecture 1 discusses these topics:

* application programming interfaces (APIs)
* history of web APIs: SOAP, XMPP, REST
* synchronous versus asynchronous API calls
* the JavaScript + HTML powerhouse
* Wikidata and SPARQL

Lecture 2 discusses these topics:

* JSON format
* d3.js

#### Practicals

Practical 1 has the following aspects as main topic:

* look at the [Wikidata Query Service](https://query.wikidata.org/) and learn from the examples (click the `Examples` button)
* set up a GitHub repository for the first assignment (see the practical of Week 1)
* use the two JavaScript examples ([htmljs.template.html](htmljs.template.html) and [wikidata.template.html](wikidata.template.html)) to create a simple, running HTML example that runs a simple SPARQL query
* learn how to use the web browser console

##### Javascript Library

Wikibase SDK javascript library is used in the template file [wikidata.template.html](wikidata.template.html)
as a dependency to provide the functionality of executing a SPARQL query over WikiData SPARQL endpoint and retrieve the data
as json in the browser.
Wikibase SDK library is released under MIT License. For additional information, plase visit <https://github.com/maxlath/wikibase-sdk> repository.

##### Additional resources

* [Programming in the Life Sciences #4: communication from within HTML](https://chem-bla-ics.blogspot.com/2013/10/programming-in-life-sciences-4.html)
* [Programming in the Life Sciences #5: converting the results into HTML](https://chem-bla-ics.blogspot.com/2013/10/programming-in-life-sciences-5.html)
* [Programming in the Life Sciences #10: JavaScript Object Notation (JSON)](https://chem-bla-ics.blogspot.com/2013/10/programming-in-life-sciences-10.html)
* [Programming in the Life Sciences #11: HTML](https://chem-bla-ics.blogspot.com/2013/10/programming-in-life-sciences-11-html.html)
* [Programming in the Life Sciences #19: debugging](https://chem-bla-ics.blogspot.com/2014/11/programming-in-life-sciences-19.html)
* [Programming in the Life Sciences #20: extracting data from JSON](https://chem-bla-ics.blogspot.com/2014/11/programming-in-life-sciences-20.html)
* [How to learn D3.js](https://wattenberger.com/blog/d3)

Practical 2 ...

#### Assignment 1

Programming languages and file formats used: HTML, JavaScript, REST API, SPARQL, JSON

### Making multivariate statistics reproducible

#### Lectures

Lecture 1 discusses these topics:

* boiling points of alkanes
* the concept of QSAR
* molecular descriptors (and rcdk)
* Partial Least Squares
* R Markdown

Lecture 2 discusses these topics:

* 

#### Practicals

Practical 1 ...

Practical 2 ...

#### Assignment 2

Programming languages and file formats used: R, Markdown, multivariate statistics

### Parallel computing

#### Lectures

Lecture 1 discusses these topics:

Lecture 2 discusses these topics:

#### Practicals

Practical 1 ...

Practical 2 ...

#### Assignment 3

Programming languages and file formats used: Nextflow, Groovy
