# 🧾 Automatic Ticket Classification (NLP + Topic Modeling)

## Context: 
A financial institution wants to categorize customer complaints by product/service type.

## Objective: 
Use unsupervised and supervised learning to classify support tickets into five categories.

## Approach:

### 🧹 Text Preprocessing:

Clean text (remove punctuation, stopwords, lemmatize)

POS tagging for nouns

### 🔍 Topic Modeling:

Apply Non-negative Matrix Factorization (NMF)

Assign topics: Credit Card, Bank Account, Dispute, Mortgage, Others

### 🤖 Supervised Classification:

Train models: Logistic Regression, Naive Bayes, Random Forest

Evaluate using classification metrics

## Outcome: 

Logistic Regression performs best and is used for real-time ticket classification.

## Sumary 

Developed an unsupervised learning solution to automatically classify unlabeled customer support tickets into 5 product categories (Credit Card, Bank Account Services, Theft/Dispute, Mortgages/Loans, Others) for a financial institution.

Technical Approach:
Data Preprocessing: Cleaned and prepared unstructured text data through removal of null values, special characters, and stopwords; applied lemmatization and POS tagging for noun extraction

Exploratory Analysis: Generated word clouds and analyzed top unigram, bigram, and trigram patterns to understand complaint characteristics

Feature Engineering: Implemented TF-IDF vectorization to transform text into numerical features

Unsupervised Learning: Applied Non-negative Matrix Factorization (NMF) for topic modeling to discover latent patterns and automatically cluster complaints into 5 distinct categories

Supervised Classification: Built and evaluated multiple classification models (Logistic Regression, Multinomial Naive Bayes, Random Forest) using NMF-generated labels as ground truth

Results: Identified Logistic Regression with hyperparameter tuning as the best-performing model for production deployment, enabling automated routing of new customer complaints to appropriate departments.

Technical Stack: Python, NLP, Scikit-learn, TF-IDF, NMF, Logistic Regression, Random Forest, Naive Bayes