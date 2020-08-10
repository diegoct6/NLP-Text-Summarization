# Building a Text Summarizer Web Application: Read Smarter, Learn Faster
Based on a survey we conducted on 20 former IE MBA studetnts, we found out that on average, they were assigned 120 cases to read. Out of those, they read only around 58%. And 80% stated that the reason of not reading them was that they were too long or time consuming.

In this group project, we developped a Text Summarizer designed to assist IE MBA students facing this issue. We believe that this Application can be used as an assistant to students, allowing them to summarize online sources and business cases, efficiently saving time in the research and studying stages. 

In order to accomplish this goal, we have analyzed and looked into a set of text summarizers: 

- Four Extractive Summarizers: based on Word Frequency, TF-IDF, Cosine Similarity, and TextRank Algorithm.
- One Abstractive Summarizer: Google's T5 pre-trained Abstractive Summarizer

We used and were inspired by the codes and ideas of [Himanshu Sharma](https://www.presentslide.in/2019/08/text-summarization-python-spacy-library.html), [Jesus Saves](https://jcharistech.wordpress.com/2018/12/31/text-summarization-using-spacy-and-python/), [Akash Panchal](https://towardsdatascience.com/text-summarization-using-tf-idf-e64a0644ace3), [Ashish Singhal](https://medium.com/datapy-ai/nlp-building-text-summarizer-part-1-902fec337b81), [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2018/11/introduction-text-summarization-textrank-python/), [Ramsri Goutham](https://towardsdatascience.com/simple-abstractive-text-summarization-with-pretrained-t5-text-to-text-transfer-transformer-10f6d602c426). For the development of the Web Application, we followed the steps greatly described by [JCharisTech & J-Secur1ty](https://www.youtube.com/watch?v=xvLQdP549NA&t=228s).

This work was done with my study group, comprising namely: Mohamed Khanafer, Guillermo Chacon, Esteban Delgado, Aayush Kerjiwal, Mariana Naváez, and Valentina Premoli. I here share the Report of our study, the notebook in which we develop the code, the final presentation, and the files that we used to build the Web Application using Flask.

The welcome page allows the user to input the text or the URL containing the article/case/report to summarize. And the other page allows to see the output of various summarizers as seen here:
![WebApp interface](/FlaskApp.png)
