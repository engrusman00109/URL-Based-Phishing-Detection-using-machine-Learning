# URL-Based Phishing Detection using Machine Learning

## Overview
Phishing is a type of online fraud where attackers impersonate legitimate websites or services to steal sensitive information such as usernames, passwords, or account IDs. This project uses **Machine Learning** to detect phishing websites based on URL characteristics.

The goal is to build an automated system that can classify websites as phishing or legitimate with high accuracy and speed.

## Dataset
- Source: [Kaggle - Phishing Website Detector](https://www.kaggle.com/eswarchandt/phishing-website-detector)
- Instances: 5849 after removing duplicates
- Features: 30 independent features extracted from URLs, 1 dependent feature (`class`)

## Features
Some of the key features include:
- UsingIP
- LongURL, ShortURL
- Symbol@
- Redirecting//
- PrefixSuffix-
- SubDomains
- HTTPS
- DomainRegLen
- PageRank, WebsiteTraffic
- And others (total 31 features)

## Methodology
1. **Data Preprocessing**
   - Removed duplicate entries
   - Checked for null values (none found)
   - Feature selection based on importance

2. **Exploratory Data Analysis (EDA)**
   - Analyzed class distribution
   - Visualized key features
   - Found dataset imbalance, applied appropriate handling

3. **Machine Learning Models**
   - **Naive Bayes** (Accuracy: 66%)
   - **Decision Tree** (Accuracy: 91%)
   - **Random Forest** (Accuracy: 93.8%)
   - **Gradient Boosting Classifier** (Accuracy: 94.5%) ✅ *Best Model*
   - **Multi-Layer Perceptron (MLP)** (Accuracy: 93.9%)
   - **Support Vector Machine (SVM)** (Accuracy: 93.8%)
   - **Logistic Regression** (Accuracy: 92.2%)
   - **K-Nearest Neighbors (KNN)** (Accuracy: 92.2%)

4. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-Score

## Results
The **Gradient Boosting Classifier** achieved the highest accuracy of **94.5%**. This model is effective in detecting phishing websites with high precision and recall.

## How to Use
1. Clone the repository:
   ```bash
   git clone https:........


## Muhammad Usman Akram
### musman00109@gmail.com 
