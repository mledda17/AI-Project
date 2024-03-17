# E-mail spam detection system based on Machine Learning techniques

## Overview
This project explores the application of machine learning techniques to detect email spam, a challenge that has persisted as email remains a crucial communication medium. Utilizing decision trees and artificial neural networks, our goal was to develop an efficient and accurate spam detection system that outperforms traditional rule-based filters. Through comparative analysis, we sought to uncover the most effective model for distinguishing spam from legitimate emails.

## Project Structure
1. **Data Exploration**: Initial analysis of the dataset to understand its structure, identify potential issues, and prepare for preprocessing.
2. **Preprocessing**: Implementation of data cleaning and transformation techniques, including URL, punctuation, and stop-word removal, as well as stemming to reduce words to their base forms.
3. **Feature Selection**: Utilization of the Scikit-Learn library's CountVectorizer for text conversion and mutual_info_classif for information gain calculation, aiding in the selection of the most influential words.
4- **Model Training and Evaluation**: Deployment of k-fold cross-validation for model training and testing, with experiments conducted to determine the optimal number of features for model performance.
5. **Comparison and Analysis**: Evaluation of the decision tree and artificial neural network models based on misclassification rates and ROC curve analysis to assess their spam detection capabilities.

## Experimental Setup
* The dataset comprised 5456 emails labeled as spam or ham, with preprocessing steps applied to ensure data quality.
* Models tested include the Scikit-Learn's Decision Tree and MLP Classifier, with specific attention to hyperparameters like split criterion and max depth for the decision tree, and the architecture of the neural network.
* Evaluation metrics focused on misclassification rates and ROC curve analysis to compare model performances.

## Results
Our findings indicate that the neural network model achieves superior accuracy and precision in spam detection compared to the decision tree model, with a notable improvement as the number of features increases. This suggests the potential of deep learning techniques in enhancing email security and filtering processes.

## Limitations and Future Work
The project acknowledges limitations such as the sample size and feature selection, which could impact model accuracy. Future directions include increasing the dataset size, refining feature extraction methods, and exploring more complex neural network architectures for improved spam detection.
