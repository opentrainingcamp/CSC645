# Welcome to GCSC645

## TODO ... 
- [x] Start the forked project
- [ ] validate the idea
- [ ] Complete the intro
- [ ] Develop fundamentals of text mining as part of data mining
- [ ] Develop the lab (how-to spark+python, and the example)

## Two parts Neural Network for Machine Learning and Text mining as part of Data mining

### Part 1 : [Neural Network for Machine Learning](NN). 

It is meant to be a hands-on course without sacrificing the conceptual background. As such the first few code examples are developed (using numpy or cupy) from basic principles without using any ML framework. After that we use Tensorflow v2 for almost all examples.

[see for more details](https://github.com/hikmatfarhat-ndu/CSC645)

TODO: complete this intro

### Part 2: Data mining, text mining and Big Data Concepts applications with Spark and Python

Notwithstanding its fame as only a scripting language, Python exposes several programming paradigms like array-oriented programming, object-oriented programming, asynchronous programming, and many others. One paradigm that is of particular interest for Big Data processing is functional programming.

**Functional programming** is a common paradigm when you are dealing with Big Data. Writing in a functional manner makes easier parallel code. This means it’s easier to take your code and have it run on several CPUs or even entirely different machines. You can work around the physical memory and CPU restrictions of a single host by running on multiple systems at once.

This is the power of the PySpark ecosystem, allowing you to take functional code and automatically distribute it across an entire cluster of computers.

Many of the core ideas of functional programming are available in Python’s standard library and built-ins. *You can learn many of the concepts needed for Big Data processing without ever leaving the comfort of Python!*

The core idea of functional programming is that data should be manipulated by functions without maintaining any external state. This means that your use ummutable data and always returns new data instead of manipulating the data in-place.

Another common idea in functional programming is anonymous functions (lambda). Python exposes anonymous functions using the lambda keyword.


**Data mining** can be defined as the “non-trivial process of extracting implicit, previously unknown and potentially useful information (in the form of rules, constraints, regularities) from data from databases” (Gregory Piatetsky- Shapiro). While this field is far from new, it is only in recent years that practitioners have faced new challenges related to a significant increase in the volume of data. This increase has in some cases been much faster than the continued growth in the compute and storage capacities of individual servers, with the resulting volumes incompatible with centralized processing. This is generally referred to as “big data”.

But volume isn't the only (relatively) new challenge for data mining. In a 2001 report the META Group (now Gartner) spoke of 3V: volume, variety, velocity. Indeed, big data is no longer simply relational but often comes in a great diversity (variety) of semi-structured (XML, JSON) or unstructured (e.g. text, images, video) formats, which require to the point of suitable excavation (or at least pre-treatment) methods. You can watch the latest surveys on the KDnuggets site (surveys to be taken with care because there is nothing to assess their representativeness). Velocity corresponds to the fact that in many cases new data arrives as a stream and must be processed in real time (or within timelines consistent with the streams), which places new demands on the latency of mining operations. Finally, various players in this field are happy to add other Vs: veracity, value, visibility, etc. We must also mention another characteristic that should not be overlooked, the "low information density", which severely limits the usefulness of work carried out on a small sample size or on a reduced number of variables.

**We will be interested in this part by (as a simple exemple of text mining):**

Learning how to examine, with Spark, the content of a fairly large text base, using Latent Semantic Analysis (LSA). The primary goal is to explore the data by determining which "concepts" (or semantic classes) best explain the data. We will also extract representative documents and make queries that find documents in the database that mention certain terms or that are similar to a query document.

LSA aims to better represent a corpus of documents by exploring the relationships between words in documents. The aim is to “distil” from the corpus a set of relevant “concepts”. Each concept captures a direction of variation in the data, which often corresponds to a subject addressed in the corpus. Broadly speaking, each concept is described by three characteristics: the relevance of the concept for each document in the corpus, the affinity with the terms present in the corpus and the usefulness of the concept in describing the variance of the data. By selecting only the most important concepts, LSA can describe the data with a rough representation that employs fewer concepts, eliminates "noise", and merges similar topics.

We will briefly present the fundamentals behind text mining then make a lab about the specific example installing and using standalone spark on Linux and/or Windows 10 with Python 

* [Fundamentals](Fundamentals)
* [Lab spark python](Labs)


