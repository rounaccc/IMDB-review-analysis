# IMDB review analysis

## Introduction
Review analysis is the process of transforming unstructured review data into structured data that can be used to guide decision-making.
A few of the primary uses include:
- Product feature ideas: scanning product reviews for the sentiment on desired features
- Roadmap prioritization: determining what the dev team should focus on first
- Bug tracking: scanning new reviews in real-time
-	Customer care ratings: determining what customer service departments are delivering good service

## Exploratory Data Analysis
- The dataset is taken from kaggle 
- The dataset had total of `50,000` samples of IMDb comments and labeled data.
- The comments are distributed into `Positive` and `Negative` comments

## Methodology
1. Used `Google Colab` to make the model
1. Data Analysis
2. Data preprocessing
   - Text Normalisation
   - Lemmatization
   - Stop-words Removal
   - Tokenization
3. Embedding words into vectors using `FastText`
4. Trained Model using Dense Layer
5. Model Evaluation 
   - Acurracy : Train Data - **100%** Test Data - **83.28%**

## Visualization


## Key Takeaways
- Learnt how to pre-process straing data using various techniques
- Hyperparameter tuning was quite a bit of an headache but learned alot throughout the process
- The model is curruntly over-fitting, which we are working on to enhance the effeciency by tring out multiple hyperparamenters and layers
