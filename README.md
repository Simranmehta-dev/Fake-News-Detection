# Fake-News-Detection
## Overview
This repository contains a fake news detection program implemented using Natural Language Processing (NLP) techniques and various machine learning algorithms. The goal of this project is to classify news as either real or fake based on their content.

## Data
The program utilizes a dataset consisting of labeled news , where each article is labeled as either real or fake. The dataset is split into training and testing sets to train and evaluate the machine learning models.

## Features
- *Text Preprocessing:* Before feeding the data into the machine learning algorithms, the text is preprocessed, including tokenization, stop-word removal, and stemming or lemmatization.
- *Feature Extraction:* Various feature extraction techniques, such as Bag-of-Words, TF-IDF, and word embeddings, are employed to represent the textual data numerically for model training.
- *Machine Learning Algorithms:* The program implements several machine learning algorithms, including but not limited to:
  - Random forest
  - Decision tree
  - SVM
  - Gaussian Naive bayes
  - Bernoulli Naive bayes
- *Model Evaluation:* The performance of each model is evaluated using metrics such as accuracy, precision and score. Additionally, confusion matrices are generated to visualize the performance of the models.

## Usage
1. *Clone the Repository:*
    
    git clone https://github.com/yourusername/fake-news-detection.git
    
2. *Install Dependencies:*
    
    pip install -r requirements.txt
    
3. *Run the Program:*
    
    python fake_news_detection.py
    

## Results
After training and evaluating the machine learning models, the program generates a report detailing the performance of each algorithm. This report includes metrics such as accuracy, precision along with visualizations like confusion matrices to aid in interpreting the results.At the end there is a comparasion chart to compare all 4 models with each other. You can see the most accurate model with the visual representation of the models.

## Conclusion
Through this project, we aimed to demonstrate the effectiveness of using NLP techniques and various machine learning algorithms in detecting fake news. By comparing the performance of different models, we can gain insights into which approach works best for this task and potentially improve the accuracy of fake news detection systems in the future.

