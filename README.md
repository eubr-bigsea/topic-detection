# topic-detection
Topic detection in online social networks
This descriptive model tries to identify topics being discussed in Twitter OSN. 
Identified topics may be used to infer the cause of events in the context of smart cities. 
For example, a traffic jam may be occurring because people are protesting in a region or because there 
is a flood caused by rain.

Topic identification methods are among the most explored tools to extract information from large amounts of data. They were conceived to find semantically meaningful topics from a document corpus, and they assume that there are hidden variables (topics) that explain the similarities between observable variables (documents). These techniques are usually based on one of the following approaches:

* Probabilistic: These methods assume that the data was generated by a generative model that includes the hidden variables. This generative process defines a joint probability distribution over both the observed and hidden random variables that allow us to infer the existing topics;
* Non-probabilistics: These methods are usually based on matrix factorization techniques, where the matrix terms X documents, which represents the database, is projected into a k-dimensional space where each dimension is a topic.

The main representatives of the aforementioned approaches are Latent Dirichlet Allocation (LDA) [R5] (probabilistic) and Non-negative Matrix Factorization (NMF) [R6] (non-probabilistic).  In summary, these algorithms rely on the words co-occurrence in the document level to infer the topics. 
