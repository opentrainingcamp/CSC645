# Welcome to GCSC645

## TODO ... 
- [x] Start the forked project
- [x] Validate the idea
- [ ] Validate Pedagogical methodologie
- [ ] Validate the planning (sessions)
- [ ] Complete the intro
- [ ] Develop asynchronous lectures (vidéo and assessment of each item of Session1 fundamentals of Big data, MAL and text mining as part of data mining
- [ ] Develop the lab (how-to spark+python, and the examples)

## Proposed methodology (Pedagogie)

Some sessions could be asynchronous and be freely accessible by registered students (or even public with a creative common licence). This king of sessions will contain small parts: (small videos 1015mn, the assessment for each part, Tools to communicate with the instructor: forum or chat). Each asynchronous session ends with an asynchronous online class for debriefing and some complements based on the results of assessments and learner questions)

_**Platforms:**  google classroom, google drive, github, Windows 10 or Linux, Spark, Python, PySpark and Jupyter Notebook._


## Proposed palnning

| Date | Instructor | Title |
|  ---- |  ----------|   ------|
| Session 1 | Pascal | BigData, Machine Learning and text mining by exemple. Using PySpark (Spark+Python). <ul><li>Why Spark for BigData and ML,</li><li>Basic knowledge for Text Mining:<ul><li>LSA</li><li>DSA</li>TF-IDF<li>Word2Vec</li></ul></li><li>installing pyspark on Windows or Linux and first basic exemples</li></ul>|
| Session 2 | Pascal | Implementing 1 or 2 relalistics Text Mining exemples  |
| Session 3 | Hikmat | Logistic Regression (Identifying Shipts), Shallow Network (Movie Reviews)|
| Session 4 | Hikmat | Feedforward Networks (MNIST digits), Tensorflow and Keras|
| Session 5 | Hikmat | Convolution Networks (MNIST digits), ??|
| Session 6 | Hikmat | Recurrent Networks, Autoencoders|
| Session 7 | Walid | Title 1 |
| Session 8 | Walid | Title 2 |



## Two parts Neural Network for Machine Learning and Text mining as part of Data mining

### Part 1 : [Neural Network for Machine Learning](README). 

It is meant to be a hands-on course without sacrificing the conceptual background. As such the first few code examples are developed (using numpy or cupy) from basic principles without using any ML framework. After that we use Tensorflow v2 for almost all examples.

[see for more details](https://github.com/hikmatfarhat-ndu/CSC645)

TODO: complete this intro

### Part 2: Data mining, text mining and Big Data Concepts applications with Spark and Python


**Data mining** can be defined as the “non-trivial process of extracting implicit, previously unknown and potentially useful information (in the form of rules, constraints, regularities) from data from databases” (Gregory Piatetsky- Shapiro). While this field is far from new, it is only in recent years that practitioners have faced new challenges related to a significant increase in the volume of data. This increase has in some cases been much faster than the continued growth in the compute and storage capacities of individual servers, with the resulting volumes incompatible with centralized processing. This is generally referred to as “big data”.

But volume isn't the only (relatively) new challenge for data mining. In a 2001 report the META Group (now Gartner) spoke of 3V: volume, variety, velocity. Indeed, big data is no longer simply relational but often comes in a great diversity (variety) of semi-structured (XML, JSON) or unstructured (e.g. text, images, video) formats, which require to the point of suitable excavation (or at least pre-treatment) methods. You can watch the latest surveys on the KDnuggets site (surveys to be taken with care because there is nothing to assess their representativeness). Velocity corresponds to the fact that in many cases new data arrives as a stream and must be processed in real time (or within timelines consistent with the streams), which places new demands on the latency of mining operations. Finally, various players in this field are happy to add other Vs: veracity, value, visibility, etc. We must also mention another characteristic that should not be overlooked, the "low information density", which severely limits the usefulness of work carried out on a small sample size or on a reduced number of variables.

**Text mining**: The textual data contains potentially very useful information for the excavation. These data are present in very diverse forms, ranging from elaborate texts, with good grammatical conformity, to simple "word tags" (tags, often parts of words or words from a group lexicon), including incomplete sentences in SMS language, presenting a particular lexicon, numerous spelling errors and a very simplified syntax. This data is intended to be read and understood by humans, sometimes belonging to restricted groups.


Beyond relatively superficial difficulties, such as lexical or syntactic nonconformity, the main problem in textual data mining is the "semantic gap", i.e. the gap between the interpretation that a computer can obtain. automatically from a text and the meaning of this same text for a human (of the category targeted by the text). Similar difficulties arise in mining other types of data, such as images or videos.

Even though textual data analysis methods are not yet able to bridge this semantic gap, it is nevertheless often possible to automatically extract useful information from textual data. The volume of data sometimes helps this process of extracting information. As textual data cannot be directly exploited by conventional data mining methods, prior processing is necessary depending on the objective.

**We will be interested in this part by (as some simples exemples of text mining from basic to a more realistic one):**

Learning how to examine, with Spark, the content of a fairly large text base, using Latent Semantic Analysis (LSA). The primary goal is to explore the data by determining which "concepts" (or semantic classes) best explain the data. We will also extract representative documents and make queries that find documents in the database that mention certain terms or that are similar to a query document.

LSA aims to better represent a corpus of documents by exploring the relationships between words in documents. The aim is to “distil” from the corpus a set of relevant “concepts”. Each concept captures a direction of variation in the data, which often corresponds to a subject addressed in the corpus. Broadly speaking, each concept is described by three characteristics: the relevance of the concept for each document in the corpus, the affinity with the terms present in the corpus and the usefulness of the concept in describing the variance of the data. By selecting only the most important concepts, LSA can describe the data with a rough representation that employs fewer concepts, eliminates "noise", and merges similar topics.

We will briefly present the fundamentals behind text mining then make a lab about the specific example installing and using standalone spark on Linux and/or Windows 10 with Python 

* [Fundamentals](Fundamentals)
* [Lab spark python](Labs)


