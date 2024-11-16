# Fake News Detection Project
Fake news on different platforms is spreading widely and is a matter of serious concern, as it causes social wars and permanent breakage of the bonds established among people. A lot of research is already going on focused on the classification of fake news.

Here we will try to solve this issue with the help of machine learning in Python.

Steps to be followed
1.Importing Libraries and Datasets
2.Data Preprocessing
3.Preprocessing and analysis of News column
4.Converting text into Vectors
5.Model training, Evaluation, and Prediction

The project aims to develop a machine-learning model capable of identifying and classifying any news article as fake or not. The distribution of fake news can potentially have highly adverse effects on people and culture. This project involves building and training a model to classify news as fake news or not using a diverse dataset of news articles. We have used four techniques to determine the results of the model.

1. Logistic Regression
2. Decision Tree Classifier
3. Gradient Boost Classifier
4. Random Forest Classifier

Fake news detection using machine learning is essential because it helps combat misinformation quickly and at scale, which is critical in today's fast-paced online environment. It tackles challenges like the large volume of news, evolving tactics used by fake content creators, and multimedia manipulations (e.g., deepfakes). Machine learning automates fact-checking, reduces human biases, and improves the speed and accuracy of identifying false information. This ultimately minimizes harmful societal impacts by controlling the spread of misinformation more effectively.

# Project Overview

Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation.

# Dataset

We have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:
- True: Genuine news articles
- False: Fake or fabricated news articles

# Dependencies

Before running the code, make sure you have the following libraries and packages installed:
- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression

You can install these dependencies using pip:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install sklearn
pip install seaborn 
pip install re 
```

# Results

We evaluated each classifier's performance using metrics such as accuracy, precision, recall, and F1 score. The results are documented in the project files.

# Model Deployment

Once you are satisfied with the performance of a particular classifier, you can deploy it in a real-world application or integrate it into a larger system for automatic fake news detection.
