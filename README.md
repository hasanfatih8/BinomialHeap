# BinomialHeapIn WWW, when you enter a “keyword” search engines try to rank the documents
In WWW, when you enter a “keyword” search engines try to rank the documents according to the similarities between your keyword and the documents lying on
WWW. The most famous search engines are Google, Bing, Yahoo... Various
machine learning and deep learning algorithms run behind these search engines. On
the other hand, the common logic behind them is to rank the documents according to
relevance.  
In text classification studies, textual materials are represented with the frequencies of
the words. Consider the following three documents:  
#### Doc1:  
“Text mining studies have gained importance in recent years because of the
increasing number of electronic documents like news, social networks, research
papers and digital libraries. There is no doubt that this enormous data continues to
increase day by day with the contribution of lots of people.”
#### Doc2: 
“Automatically processing, organizing and handling this text materials are a
central problem. The key aim of text mining is to allow users to get information from
text materials. Text mining mainly deals with several important applications like
information retrieval (IR), classification (i.e., supervised, unsupervised and semi
supervised classification), document filtering, summarization, sentiment or opinion
classification.”
#### Doc3: 
“Natural Language Processing (NLP), Machine Learning (ML) and Data
Mining methods work together to detect patterns from the different types of the
documents and classify them in an automatic manner.”
When we want to rank documents according to some keyword there are some
different methods in the literature. One of the simplest ways of achieving this task is
to find a similarity score between the search keyword and the document by using
common terms. For example, let’s calculate the similarity score between the search
keyword (i.e., text) and three documents.  
* Similarity score between search keyword: “text” and Doc1: 1 since “text” occurs
1 times in Doc1.  
* Similarity score between search keyword: “text” and Doc2: 4 since “text” occurs
4 times in Doc2.  
* Similarity score between search keyword: “text” and Doc3: 0 since “text” occurs
0 times in Doc3.  
***The most relevant document with the given keyword is the one having the highest
similarity score. Consequently, the ranking of the documents according to the
relevance to the keyword is Doc2, Doc1, Doc3.
