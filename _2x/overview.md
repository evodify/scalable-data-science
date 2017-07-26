---
title: Overview 
permalink: /2x/overview/
---

# SDS2x - Scalable Data Science from Atlantis

There are two parts to the course *SDS2x, Scalable Data Science 2x from Atlantis*:

1. Introduction to Data Science
2.  Fundamentals of Data Science

**This is under construction!!!**

## Introduction to Data Science

## Course Description
Data Science is the study of the generalizable extraction of knowledge from data in a practical and scalable manner.  A data scientist is characterized by an integrated skill set spanning mathematics, statistics, machine learning, artificial intelligence, databases and optimization along with a deep understanding of the craft of problem formulation to engineer effective solutions ([DOI:10.1145/2500499](http://dl.acm.org/citation.cfm?id=2500499), [DOI: 10.1126/science.aaa8415](http://science.sciencemag.org/content/349/6245/255.full-text.pdf+html)).  This course will introduce students to this rapidly growing field and equip them with some of its basic principles and tools.  

Students will learn concepts,  techniques and tools they need to deal with various facets of data science  practice, including collecting, extracting, transforming, loading, exploring, integrating and analyzing data.  The emphasis will be on predictive modeling, descriptive modeling, model tuning and evaluation, data product creation and effective communication.
The focus in the treatment of these topics will be on multi-disciplinary breadth required for data science, rather than technical depth in a particular aspect of the topic.  The emphasis will be on integration and synthesis of concepts and their practical application to solving problems.  To make the learning concrete, real datasets from a variety of disciplines will be used throughout the course.  

## Learning Outcomes -- Introduction to Data Science (5 points)

At the conclusion of the course, students should be able to:
- Describe what Data Science is and the skill sets needed to be a data scientist.
- Explain in basic terms what probability models are and how statistical inference and learning can go from data to the model (model fitting).  
- Understand common probability distributions and simulate from them.
- Describe the Data Science Process and how its components interact.
- Understand the fundamental conceps in distributed storage, in-memory computing and fault-tolerance.
- Use a working knowledge of the core languages used by data scientists (shell/noSQL/python/scala/R) to carry out various elements/stages of the data science process in Apache Spark's scalable and production-ready pipeline:
  - Extract, transform and load (ETL) into distributed filestore
  - Explore data (visually using plots and structurally using SQL)
  - Understand the process of training, validating and testing models for prediction

## Learning Outcomes -- Applied Data Science (10 points)

Introduction to Data Science (5 points) is a pre-requisite for this course.

At the conclusion of the course, students should be able to:
- Use a working knowledge of the core languages used by data scientists (shell/noSQL/python/scala/R) to carry out various elements/stages of the data science process in Apache Spark's scalable and production-ready pipeline:
  - Collect data (scrape from web, use Twitter API, etc.)
  - Anonymize data (for privacy or security)
  - Extract, transform and load (ETL) into distributed filestore
  - Explore data (visually using plots and structurally using SQL)
  - Train, validate and test for prediction
  - Serve the model's predictions to the client
- Apply the Data Science process in a case study of their own (course project).
- Apply  basic  machine  learning  algorithms for predictive modeling (unsupervised and supervised).  
- Explain fundamental mathematical and algorithmic ingredients underpinning the learning algorithms (using concepts from linear algebra, multivatiate calculus and statistics)
- Build their own predictions from data: classifier, recommender, regressor.
- Create meaningful visualization and communicate persuasively (both orally and through github pages).
- Work effectively in teams of 2 or 3 on data science project (course project).
- Understand the ethical and privacy issues in the data science process and apply ethical practices.
- Prepare better for the industry-certified examinations for Data Scientists.
  
## Audience
The course sequence is suitable for upper-level undergraduate (or beginning graduate) students in computer science, computer engineering, electrical  engineering, physics, chemistry, applied  mathematics, statistics, business, computational sciences (computational biology, computational sociology, etc.), and related analytic/quantitative fields in Science and Technology.

## Prerequisites
Students are recommended to have basic knowledge of algorithms and some programming experience (equivalent to completing an introductory course in computer science), and some familiarity with basic linear algebra and basic probability and statistics. These basic concepts will be introduced quickly and one could take the course by putting extra effort on these basics as the course progresses.  

The course consists of lectures (three times a week, 45x2=90 minutes each), and involves a set of assignments (about 4) and a substantial project.  The course project could take one of the following forms:
- analyzing an interesting dataset  using  existing  methods 
- obtaining your own dataset and analyzing it using existing methods 
- building  your  own  data  product  
- focussing on the theoretical properties of an algorithm, etc.
  
Students are encouraged to work in teams of two or three for a project.  
Assignments, on the other hand, are to be completed individually.

## Grading
Your final grade will be determined based on your performance on each of the following items: 

- Class participation and comprehensive quizzes (10%)
- Assignments (40%) -- to be done individually (4 x 10% in python/scala/R/SQL)
- Project (50%) -- to be done in groups of two or three 
  - Written part of Project  (20%)
  - Oral Presentation (10%)
  - Technical Accuracy and Originality (10%)
  - Synergetic Team-work (10%) -- peer-graded

## Topics and course outline:
1.  Introduction:  What is Data Science?
	-  Big Data and Data Science - beyond buzz-words
		- fault tolerance and distributed file-stores
		- distributed in-memory processing in Apache Spark
	-  History and latest landscape of research and practice
	-  Skill sets of a data scientist (maths, stats, computer science and software engineering)
	-  The Data Science Process
2. Basics of Probability, Statistics, Linear Algebra, Calculus and Programming
	-  Populations and samples - basic concepts (random variables, density and distribution functions)
	-  Simulate from basic discrete and continuous distributions (python/scala/R)
	-  Refresher in Linear Algebra (numpy, scala-breeze, R)
	-  concepts in model selection and tuning via cross-validation and testing
	-  Statistical modeling and fitting a model (linear regression, least squares/maximum likelihood, gradient descent)
	-  Shell command-line and crash-course/refresher in basic programming (python/scala/R)
3. Introduction to Map-Reduce and Distributed Computing
	-  Resilient Distributed datasets
	-  Transformations and Actions in Apache Spark (Introduction)
	-  Basics of Functional programming (python lambda functions and scala closures)
	-  Case Study 0: Word-count of US State of the Union Addresses
4. Ingest, Extract, Transform, Load and Explore with noSQL
	-  Case Study 0: US State of the Union Addresses
	-  Case Study 1: Power-plant data 
	-  Case Study 2: 1 Million Songs
	-  SQL basics - select, filter, join, group by, aggregate, etc. using SparkSQL
5. Two Basic Supervised Machine Learning Algorithms
	-  Linear Regression (power-plant data)
	-  Decision Trees for Classification (hand-written digit recognition)
6. Two Basic Unsupervised Machine Learning Algorithms 
	-  k-means (1 million songs dataset)
	-  Gaussian Mixture Models and EM Algorithm
7. Unstructured to Semi-structured text data
	-  Supervised: Sentiment analysis with Support vector Machine (twitter dataset)
	-  Unsupervised: Latent Dirichlet Allocation (news groups dataset)
	- Assignment: Build your own sentiment detector
8. Dimensionality Reduction
	- Distributed Linear Algebra -- basic concepts
	- Singular value Decomposition
	- Principal Component Analysis 
9. Collaborative Filtering for Recommendation Systems
	-  Matrix completion via Alternative Least Squares
	-  Assignment:  build your own recommendation system
10. Neural networks
	- Linear and logistic regression as neural networks
	- Back propagation for gradient descent
	- Use of pre-trained neural networks from google/Baidu/facebook in your machine learning pipeline
11. Mining Networks and Graphs
	-  Social networks as graphs (twitter data)
	-  Extract, transform and loading of network data
	-  Discovery of communities in graphs (wikipedia click streams)
	-  label and belief propagation
	-  querying sub-structures in graphs (US Airport network)
12. Data Science and Ethical Issues
	-  Discussions on ethics, privacy and security
	-  Case studies from the field
13. Project Presentations

## Reading Supplements

We will be supplementing the lecture notes with reading assignments from original sources.  

Here are some resources that may be of further help.

### Mathematical Statistical Foundations
- Avrim Blum, John Hopcroft and Ravindran Kannan.  Foundations of Data Science. Freely available from: [https://www.cs.cornell.edu/jeh/book2016June9.pdf](https://www.cs.cornell.edu/jeh/book2016June9.pdf). It is  intended as a modern theoretical course in computer science and statistical learning.
- Kevin P. Murphy.  Machine Learning:  A Probabilistic Perspective.  ISBN 0262018020.  2013.
- Trevor  Hastie,  Robert  Tibshirani  and  Jerome  Friedman.   Elements  of  Statistical  Learning, Second Edition.  ISBN 0387952845.  2009.  Freely available from: [https://statweb.stanford.edu/~tibs/ElemStatLearn/](https://statweb.stanford.edu/~tibs/ElemStatLearn/).

### Data Science / Data Mining at Scale
- Jure Leskovek,  Anand Rajaraman and Jeffrey Ullman.  Mining of Massive Datasets.  v2.1, Cambridge University Press.  2014.  Freely available from: [http://www.mmds.org/#ver21](http://www.mmds.org/#ver21).
- Foster Provost and Tom Fawcett.  Data Science for Business:  What You Need to Know about Data Mining and Data-analytic Thinking.  ISBN 1449361323.  2013.
- Mohammed J. Zaki and Wagner Miera Jr.  Data Mining and Analysis: Fundamental Concepts and Algorithms.  Cambridge University Press.  2014.
- Cathy  O’Neil  and  Rachel  Schutt.   Doing  Data  Science,  Straight  Talk  From  The  Frontline. O’Reilly.  2014.

Here are some free online courses if you need quick refreshers or want to go indepth into specific subjects.

### Maths/Stats Refreshers
* [Linear Algebra Refresher Course (with Python)](https://www.udacity.com/course/linear-algebra-refresher-course--ud953)
* [Intro to Descriptive Statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
* [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)

### Apache Spark / shell / github / Scala / Python / R
- Learning Spark : lightning-fast data analytics by Holden Karau, Andy Konwinski, Patrick Wendell, and Matei Zaharia, O'Reilly, 2015.
- Advanced analytics with Spark : patterns for learning from data at scale, O'Reilly, 2015.
- Command-line Basics
	* [Linux Commnad-line Basics](https://www.udacity.com/course/linux-command-line-basics--ud595)
	* [Windows Command-line Bascis](https://www.lynda.com/-tutorials/Windows-command-line-basics/497312/513424-4.html)

- [How to use Git and GitHub: Version control for code](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
- [Intro to Data Analysis: Using NumPy and Pandas](https://www.udacity.com/course/intro-to-data-analysis--ud170)
- [Data Analysis with R by facebook](https://www.udacity.com/course/data-analysis-with-r--ud651)
- [Data Visualization and D3.js](https://www.udacity.com/course/data-visualization-and-d3js--ud507)
- [Scala Programming](http://www.scala-lang.org/documentation/)
- [Scala for Data Science, Pascal Bugnion, Packt Publishing, 416 pages, 2016](http://shop.oreilly.com/product/9781785281372.do). 

### Computer Science Refreshers
* [Intro to Computer Science (with Python)](https://www.udacity.com/course/intro-to-computer-science--cs101)
* [Intro to Python Programming](https://www.udacity.com/course/programming-foundations-with-python--ud036)
* [Intro to Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197)
