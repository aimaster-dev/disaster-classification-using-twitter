# Twitter Disaster Classification Using LSTM, Attention and Transformers

[![made-with-kaggle](https://img.shields.io/badge/Made%20with-Kaggle-lightblue.svg)](https://www.kaggle.com/)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![Generic badge](https://img.shields.io/badge/STATUS-IN PROGRESS-<COLOR>.svg)](https://shields.io/)
[![GitHub license](https://img.shields.io/github/license/teyang-lau/Dog_Breeds_Classification_CNN.svg)](https://github.com/teyang-lau/Melanoma_Detection/blob/master/LICENSE)

Author: TeYang, Lau <br>
Last Updated: 22 December 2020

<img src = "./Pictures/tweet_wc.png">

<br><br>

### **Please refer to this [notebook](https://www.kaggle.com/teyang/melanoma-detection-using-effnet-and-meta-data) on Kaggle for a more detailed description, analysis and insights of the project.** 



## **Project Motivation** 

For this project, I applied **sequence models** to sequential data in a NLP problem of classifying twitter data into whether they are about disaster events or not. This is easy for a human, but a computer will find it difficult as languages contain multiple complexities. A model will thus will have to take into account the sequential nature of the tweet, the meaning and representation of each word in numbers, as well as the importance and contribution of other words in the same sequence, since two words can have completely different meanings in two different contexts. Here, I will be using **Long-Short Term Memory (LSTM)**, **Attention** and **Transformers **models, which have provided state-of-the-art results for many NLP tasks.

This project also used to be a competition on **Kaggle**, but I didn't have the time nor the knowledge to complete the challenge the first time I joined. After finishing a deep learning specialization course and doing more readings on sequential models, I am back to tackle this problem again!



## **Project Goals** 

1. *Explore* using different sequence models **(LSTM, Attention, Transformers)** for NLP sentence classification problem
2. *Preprocess/Clean* tweets data into appropriate format for inputting into neural network models 
3. *Understand* **word embeddings** and how they are used to represent words as inputs into NLP models
4. *Engineer* new features from tweets data that can help to improve model classification



## **Project Overview** 

* Preprocess and clean tweets data
* Exploratory data analysis of the texts to understand the text structure
* **Engineer meta-features** from the text for training additional model for **ensemble**
* Wrangling text into appropriate format as inputs into models (**tokenization**, **padding**)
* Using **GloVe embeddings** for **word representation**
* Training **LSTM**, **Bidirectional LSTM with Attention**, and **BERT** models
* **Error Analysis** to look at mistakes made by models



## **About this Dataset** 

The dataset contains 10,000 tweets that were classified as disaster or non-disaster. It was created by the company figure-eight and originally shared on their [‘Data For Everyone’ website](https://www.figure-eight.com/data-for-everyone/).



## Exploratory Data Analysis

#### Most Common Bigrams

<img src='/Pictures/bigrams.png' width=1100>



#### Most Common Trigrams

<img src='/Pictures/trigrams.png' width=1100>

<br><br>

## Text Preprocessing/Cleaning

- Expand Contractions

- Remove Emojis

- Remove URLs

- Remove Punctuations except '!?' as they convey intensity and tonality of tweet

- Replace 'amp' with 'and'

- Word Segmentaion - segment words such as 'iwould' into 'i' and 'would'

- Lemmatization - reduces inflected words into their root form; verb part-of-speech tag is used here)

  

#### Most Common Words After Cleaning

<img src='/Pictures/wordcloud.png' width=1100>

<br><br>

## LSTM





## Bidirectional LSTM with Attention





## BERT





## Error Analysis



## Conclusion