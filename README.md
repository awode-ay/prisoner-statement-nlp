# Prisoner Last Statement NLP Analysis
This project delves into Natural Language Processing (NLP) techniques to analyze the last statements of prisoners. By examining patterns, sentiments, and key topics, we aim to gain insights into the thoughts and feelings expressed by inmates in their final moments.

## Dataset Overview
The dataset used in this project comprises last statements from various prisoners across multiple jurisdictions. Each record includes:

Prisoner_ID: A unique identifier for the prisoner.
Statement: The last words or statement given by the prisoner.
Execution_Date: The date on which the execution took place.
Age: Age of the prisoner at the time of execution.

Other demographic and execution-specific data...

## Preliminary Exploration
A basic word cloud visualization was generated to gauge the most common terms present in the statements.
Histograms were plotted to understand the distribution of statement lengths.

## Text Preprocessing
Tokenization of the statements into individual words.
Removal of stopwords, punctuation, and non-alphanumeric characters.
Lemmatization to reduce words to their base form.

## Feature Engineering
TF-IDF Vectorization: Transformed the statements into numerical data to analyze significance.
Sentiment Analysis: Classified statements based on the sentiment (positive, negative, neutral).

## Model Building & Analysis
Topic Modeling (LDA): Used to identify prevalent topics or themes in the prisoners' statements.
Sentiment Distribution Analysis: Understanding the general sentiment trend in the statements.
Bigram/Trigram Analysis: Detected common two/three-word phrases to understand context.

## Setup & Execution
Clone the repository.
Set up a virtual environment and activate it.
Install necessary libraries and dependencies:
