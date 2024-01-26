# NLP Classification Chatbot
## Introduction

This Jupyter Notebook serves as the implementation and documentation for an NLP Classification Chatbot project. The goal of this project is to create an intelligent conversational agent capable of categorizing user input into predefined categories using Natural Language Processing (NLP) techniques.

## Project Outline

1. **Importing Necessary Libraries:**
   - Utilize libraries such as `nltk`, `pandas`, and `scikit-learn` for NLP, data manipulation, and machine learning.

2. **Download NLTK Resources:**
   - Ensure access to NLTK resources by downloading necessary datasets.

3. **Load and Preprocess Data:**
   - Load the dataset Leaves.txt but before we apply on some Examples.
   - Preprocess text data by applying tokenization, stemming, Lemmitize and other relevant techniques.

4. **Train-Test Split:**
   - Split the dataset into training and testing sets with spliting ratio 80:20.

5. **Train a Classification Model:**
   - The code demonstrates training the model using both Decision Tree and Naive Bayes classifiers.
   - The trained model can be saved and reused for chatbot interactions.

6. **Model Evaluation:**
   - Evaluate the performance of the trained model using accuracy metrics.

7. **Chatbot Integration**
   - The `reply` function can be integrated into any chatbot UI framework.
   - The chatbot takes user input, classifies it using the trained model, and generates a relevant response

## **Conclusion**
   - This project provides a foundation for building a conversational chatbot with a focus on understanding and classifying user input using NLP techniques.
