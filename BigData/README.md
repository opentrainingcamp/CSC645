# BigData, Machine Learning and text mining by example Using PySpark (Spark+Python).

1. General introduction
2. DataMining and Text mining
1. Why Spark for BigData, ML and text mining
2. Basic knowledge for Text Mining:
    * LSA,
    * DSA,
    * TF-IDF,
    * Word2Vec. 
3. installing pyspark on Windows or Linux and first basic exemples
4. More realistic use case

1,2,3 Will be available online (asynchronously) followed by an online gathering for caching and complementary needs.

4. Synchronous online session for lab

## Data Mining
**Data mining** can be defined as the “non-trivial process of extracting implicit, previously unknown and potentially useful information (in the form of rules, constraints, regularities) from data from databases” (Gregory Piatetsky- Shapiro). While this field is far from new, it is only in recent years that practitioners have faced new challenges related to a significant increase in the volume of data. This increase has in some cases been much faster than the continued growth in the compute and storage capacities of individual servers, with the resulting volumes incompatible with centralized processing. This is generally referred to as “big data”.

But volume isn't the only (relatively) new challenge for data mining. In a 2001 report the META Group (now Gartner) spoke of 3V: volume, variety, velocity. Indeed, big data is no longer simply relational but often comes in a great diversity (variety) of semi-structured (XML, JSON) or unstructured (e.g. text, images, video) formats, which require to the point of suitable excavation (or at least pre-treatment) methods. You can watch the latest surveys on the KDnuggets site (surveys to be taken with care because there is nothing to assess their representativeness). Velocity corresponds to the fact that in many cases new data arrives as a stream and must be processed in real time (or within timelines consistent with the streams), which places new demands on the latency of mining operations. Finally, various players in this field are happy to add other Vs: veracity, value, visibility, etc. We must also mention another characteristic that should not be overlooked, the "low information density", which severely limits the usefulness of work carried out on a small sample size or on a reduced number of variables.

## Text mining
**Text mining**: The textual data contains potentially very useful information for the excavation. These data are present in very diverse forms, ranging from elaborate texts, with good grammatical conformity, to simple "word tags" (tags, often parts of words or words from a group lexicon), including incomplete sentences in SMS language, presenting a particular lexicon, numerous spelling errors and a very simplified syntax. This data is intended to be read and understood by humans, sometimes belonging to restricted groups.


Beyond relatively superficial difficulties, such as lexical or syntactic nonconformity, the main problem in textual data mining is the "semantic gap", i.e. the gap between the interpretation that a computer can obtain. automatically from a text and the meaning of this same text for a human (of the category targeted by the text). Similar difficulties arise in mining other types of data, such as images or videos.

Even though textual data analysis methods are not yet able to bridge this semantic gap, it is nevertheless often possible to automatically extract useful information from textual data. The volume of data sometimes helps this process of extracting information. As textual data cannot be directly exploited by conventional data mining methods, prior processing is necessary depending on the objective.



We will briefly present the fundamentals behind text mining then make a lab about the specific example installing and using standalone spark on Linux and/or Windows 10 with Python 

* [Why Spark, basic concept](/Spark/)
* [From Functions to BigData MapReduce paradigm](/relatedConcepts/mapReduce.md)
* [Fundamentals for Text Mining](Fundamentals)
* [Lab spark python](Labs)
