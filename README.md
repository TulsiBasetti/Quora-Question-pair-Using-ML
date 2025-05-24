# Quora Question Pair Duplicate Detection Using Machine Learning

This project focuses on detecting duplicate question pairs from the Quora dataset using various machine learning techniques. The goal is to predict whether two questions are semantically similar (duplicates) or not, which is a common natural language processing (NLP) problem.

## Project Overview

Quora’s question pairs dataset contains pairs of questions along with labels indicating whether the questions are duplicates. This project explores different approaches to feature extraction and modeling to improve duplicate detection performance.

## Repository Structure

- **train.csv**  
  The dataset containing question pairs and their duplicate labels.

- **initial_EDA.ipynb**  
  Exploratory Data Analysis (EDA) to understand dataset characteristics such as distribution of duplicates and question lengths.

- **applying-only-BOW.ipynb**  
  Implements a Bag of Words (BoW) approach to convert text into features, followed by training a classifier.

- **applying-BOW-With-basic-features.ipynb**  
  Enhances BoW features by adding basic text features like common word count and question length, improving model performance.

- **applying-Word2Vec.ipynb**  
  Uses Word2Vec embeddings to represent questions as dense vectors and applies machine learning models for classification.

## Key Features

- Comprehensive analysis of the Quora question pairs dataset.  
- Multiple feature extraction techniques: BoW and Word2Vec embeddings.  
- Incorporation of additional textual features to boost model accuracy.  
- Step-by-step Jupyter notebooks showcasing model building and evaluation.

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/TulsiBasetti/Quora-Question-pair-Using-ML.git
2. Install the required Python packages (use a virtual environment recommended)  
   ```bash
   pip install -r requirements.txt
## How to Use

3. Open and run the Jupyter notebooks in the order:  
   - `initial_EDA.ipynb`  
   - `applying-only-BOW.ipynb`  
   - `applying-BOW-With-basic-features.ipynb`  
   - `applying-Word2Vec.ipynb`  

## Dependencies

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- nltk  
- gensim  
- matplotlib  
- seaborn  
- jupyter  
- xgboost

## Dataset

The Quora Question Pairs dataset used in this project can be found on Kaggle or included as `train.csv` in the repository.

   
