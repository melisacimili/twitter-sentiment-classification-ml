# Comparative Evaluation of Classical Machine Learning Models for Binary Sentiment Classification on Twitter Data

## Overview

This project presents a comparative evaluation of classical machine learning models for binary sentiment classification using the Sentiment140 dataset.

Text data were transformed into high-dimensional sparse representations via TF-IDF vectorization. Multiple classifiers were evaluated and compared in terms of accuracy, precision, recall, and F1-score.

Model performance was assessed using both a held-out test set and 5-fold stratified cross-validation to ensure robust and stable performance estimation.

The objective of this study is to examine how well classical linear models perform on large-scale sparse text data.

## Dataset

- **Name:** Sentiment140  
- **Size:** 1.6 million labeled tweets  
- **Task:** Binary sentiment classification (positive vs. negative)  
- **Sampling:** Balanced subset used for training and evaluation  

Dataset source: https://www.kaggle.com/datasets/kazanova/sentiment140

## Evaluated Models

- Logistic Regression  
- Multinomial Naive Bayes  
- Linear Support Vector Machine  
- Random Forest  
- Hard Voting Ensemble  

## Results Summary

- Best Model: **Logistic Regression**
- Accuracy: ~79%
- Test F1-score: 0.7937  
- 5-Fold CV Mean F1-score: 0.7866 (σ ≈ 0.0010)  
- Balanced precision and recall across classes

## Key Steps

1. Data loading and preprocessing  
2. Balanced sampling  
3. Text cleaning  
4. TF-IDF feature extraction  
5. Model training and evaluation  
6. Ensemble evaluation  
7. Error analysis  
8. Final model selection  

## Future Work

Future improvements may include transformer-based architectures (e.g., BERT) and systematic hyperparameter optimization.

## Author
Melisa Ceren Cimili