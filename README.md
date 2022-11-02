# Information-Retrieval-using-word2vec-based-Vector-Space-Model
Performed information retrieval using Word2Vec based vector space model with 367k queries and 3.2M documents and performed pre-processing steps like converting text into lower case, expanding contractions, removing stop words, lemmatizing texts. 

![information-retrieval-2-632c7ba46ffa3-sej-1520x800](https://user-images.githubusercontent.com/68578215/199520987-ac9f9f27-7d60-4572-8e1f-e91c376285c8.png)

## Information Retrival
Information Retrieval is the process of finding desired documents from a collection of documents.


<img width="624" alt="Screen Shot 2022-10-27 at 9 19 38 PM" src="https://user-images.githubusercontent.com/68578215/198501795-6a9c1df2-e6e4-4674-9d90-b9f7c7dd5d58.png">




The way this works is that the user inputs his need in the form of text(query) in the information retrieval system. The system then processes this query and finds the relevant documents from the existing collection of documents(corpus). These relevant documents are then sent to the user in the decreasing order of relevance. In this whole process, the rank of documents returned determines how good or bad our results are.

For example, you go to an e-commerce website and search for an iPhone, and the website shows you the iPhone charger and back cover first and then shows you the smartphone. Now, tell me one thing, are charger and back cover related to the query?-Yes they’re somewhat. But, Are they most relevant to the query? No, the smartphone is most relevant to the input query, so it should be shown to the user first.

You see, in information retrieval problems, just returning relevant documents is not the task. Instead, you have to return the most relevant ones first, followed by less relevant documents. This is known as document ranking. There are multiple ways of ranking documents for a query, but in this article, we’ll only use the vector space model, which is an unsupervised method.

<img width="867" alt="Screen Shot 2022-10-27 at 9 20 35 PM" src="https://user-images.githubusercontent.com/68578215/198501792-823c726e-294a-48b4-86cd-433624d0db44.png">

### Data Description

The Deep Learning Track is a new track for TREC 2019, with the goal of studying ad hoc ranking
in a large data regime. It is the first track with large human-labeled training sets, introducing two
sets corresponding to two tasks, each with rigorous TREC-style blind evaluation and reusable test
sets. The document retrieval task has a corpus of 3.2 million documents with 367,000
queries, for which we generate a reusable test set of 43 queries.
