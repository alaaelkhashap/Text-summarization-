# Text-summarization

![image](https://user-images.githubusercontent.com/60587913/209393893-e922e5bb-5193-4af2-a8b4-132081f971d6.png)



# Introduction 

Text summarization can be defined as the process of extracting important sentences a large document and combining them into a short version of the document.
Text summarization can be split into two types of summaries: extractive and abstractive :
* Abstractive => which ai system tries to write the summary of a given text just like a human would do " first read the input text and try to write a summary".
* Extractive => where we try to learn the system that learns about important sentence in the input text and just extract them "Try to achieve a model that make a text summarization as human ".

![image](https://user-images.githubusercontent.com/60587913/209393690-25261bae-cfdd-4954-87a3-da97b27a366a.png)

Summarizing a text can be both time-efficient and cost-efficient.
Time-efficient => means the human reader can spend less time reading a document by reading a summarized version
Cost-efficient => means summarizing can be used for compressing the amount of textual data being transferred from a device to another device.

# Main Goal
The goal of classification is to classify the dataset before summarizing and test the summarized text on the trained models to see the accuracy increase or dicrease the same aspect for clustering, vlustering before and after and see the number of clusters

# Main topics recovered in methodology
* Dataset
  - Integration 
    * BBC news (business,entertainment,politics,sport,tech)
    * Covid 19 research papers
  - Visualization 
  - Pre-processing 
    * Lemmatization lower
    * remove stop words
    * remove unwanted chars (/n/n)
    * remove punctuation, HTML and URL

* Modeling
  - LSA
  - T5
  - PEGASUS
  - Clustring
  - Classification (Linear SVM, MultiNomialNB, Logistic Regression)
  
* Evaluation

# Conclusion
* Proposed a summarization system that use different techniques to summarize news  + medical articles. 
* Used the summarized articles to do a classification job with different classification algorithms and compared its performance against the original articles. 
* The results shows high performance from the summarized articles with little difference against the original one, which proves that we can rely on them as a source of information. 


