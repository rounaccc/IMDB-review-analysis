# IMDb review analysis

## Introduction
Review analysis is the process of transforming unstructured review data into structured data that can be used to guide decision-making.
A few of the primary uses include:
- Product feature ideas: scanning product reviews for the sentiment on desired features
- Roadmap prioritization: determining what the dev team should focus on first
- Bug tracking: scanning new reviews in real-time
-	Customer care ratings: determining what customer service departments are delivering good service

## Overview
- The dataset used for this project was an inbuilt tensorflow dataset
- The dataset had total of `50,000` samples of IMDb comments and labeled data
- The comments are distributed into `Positive` and `Negative` comments
- Data was split into train and test set in **80:20 ratio**

## Methodology
1. Used `Google Colab` to make the model
2. Data preprocessing
   - Lemmatization
   - Stop-words Removal
   - Tokenization
3. Embedding words into vectors using `FastText`
4. Trained Model using Dense Layer
5. Model Evaluation 
With FastText:
   - Train Data - **93.56%** Test Data - **91.32%**
Without FastText:
   - Train Data - **98.50%** Test Data - **88.23%**


## Visualization



## Key Takeaways
- Learnt how to pre-process string data using various techniques
- Hyperparameter tuning was quite a bit of an headache but learned alot throughout the process
- The model is currently over-fitting, which we are working on to enhance the efficiency by tring out multiple hyperparamenters and layers
- FastText Word Embedding works better since the accuracy of train and test set was increasing parallelly, to a certain degree 
