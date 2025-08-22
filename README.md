# 🧾 Automatic Ticket Classification (NLP + Topic Modeling)

## Context: A financial institution wants to categorize customer complaints by product/service type.

## Objective: Use unsupervised and supervised learning to classify support tickets into five categories.

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