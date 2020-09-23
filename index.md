# Welcome to GCSC645

## Two parts Neural Network for Machine Learning and Text mining as part of Data mining

### Part 1 : Neural Network for Machine Learning. 

It is meant to be a hands-on course without sacrificing the conceptual background. As such the first few code examples are developed (using numpy or cupy) from basic principles without using any ML framework. After that we use Tensorflow v2 for almost all examples.

### Part 2: Data mining 
can be defined as the “non-trivial process of extracting implicit, previously unknown and potentially useful information (in the form of rules, constraints, regularities) from data from databases” (Gregory Piatetsky- Shapiro). While this field is far from new, it is only in recent years that practitioners have faced new challenges related to a significant increase in the volume of data. This increase has in some cases been much faster than the continued growth in the compute and storage capacities of individual servers, with the resulting volumes incompatible with centralized processing. This is generally referred to as “big data”.

But volume isn't the only (relatively) new challenge for data mining. In a 2001 report the META Group (now Gartner) spoke of 3V: volume, variety, velocity. Indeed, big data is no longer simply relational but often comes in a great diversity (variety) of semi-structured (XML, JSON) or unstructured (e.g. text, images, video) formats, which require to the point of suitable excavation (or at least pre-treatment) methods. You can watch the latest surveys on the KDnuggets site (surveys to be taken with care because there is nothing to assess their representativeness). Velocity corresponds to the fact that in many cases new data arrives as a stream and must be processed in real time (or within timelines consistent with the streams), which places new demands on the latency of mining operations. Finally, various players in this field are happy to add other Vs: veracity, value, visibility, etc. We must also mention another characteristic that should not be overlooked, the "low information density", which severely limits the usefulness of work carried out on a small sample size or on a reduced number of variables.

**We will be interested in this part by (as a simple exemple of text mining):**

Learning how to examine, with Spark, the content of a fairly large text base, using Latent Semantic Analysis (LSA). The primary goal is to explore the data by determining which "concepts" (or semantic classes) best explain the data. We will also extract representative documents and make queries that find documents in the database that mention certain terms or that are similar to a query document.

LSA aims to better represent a corpus of documents by exploring the relationships between words in documents. The aim is to “distil” from the corpus a set of relevant “concepts”. Each concept captures a direction of variation in the data, which often corresponds to a subject addressed in the corpus. Broadly speaking, each concept is described by three characteristics: the relevance of the concept for each document in the corpus, the affinity with the terms present in the corpus and the usefulness of the concept in describing the variance of the data. By selecting only the most important concepts, LSA can describe the data with a rough representation that employs fewer concepts, eliminates "noise", and merges similar topics.

We will briefly present the fundamentals behind text mining then make a lab about the specific example using spark with Python 

* [Fundamentals](Fundamentals)
* [Lab spark python](Labs)


