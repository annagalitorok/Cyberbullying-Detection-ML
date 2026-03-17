# Cyberbullying Detection ML
Machine learning project for cyberbullying detection using NLP techniques and scikit-learn. Includes text preprocessing, TF-IDF feature extraction, Logistic Regression model, and evaluation with classification metrics.

## Overview

This project presents a machine learning approach for detecting cyberbullying in textual data using classical Natural Language Processing (NLP) techniques and scikit-learn.

The goal of the project is to classify online text into different categories of harmful or non-harmful content, providing a simple yet effective baseline solution for cyberbullying detection.

## What the Project Does

The model processes textual input and predicts whether it belongs to one of the following categories:

* ethnicity/race
* gender/sexual
* religion
* not_cyberbullying

The pipeline includes:

* data loading and exploration
* text preprocessing and cleaning
* feature extraction using TF-IDF
* model training using Logistic Regression
* evaluation with classification metrics

## Why This Project is Useful

Cyberbullying is a significant issue in online communication. Detecting harmful content automatically can support:

* safer online platforms
* content moderation systems
* AI-based monitoring tools

This project demonstrates how even simple machine learning models can achieve strong performance on text classification tasks.

## Dataset

The dataset used in this project contains labeled text samples for different types of cyberbullying.

**Note:**
The dataset is not included in this repository.
To run the project, place the dataset file (e.g. `cb_multi_labeled_balanced.csv`) in the project directory.

## Methodology

### 1. Data Exploration

* checking dataset structure
* analyzing label distribution
* inspecting text lengths

### 2. Text Preprocessing

* lowercasing
* removing URLs, mentions, hashtags
* removing punctuation and numbers

### 3. Feature Extraction

* TF-IDF vectorization (max 5000 features)

### 4. Model Training

* Logistic Regression classifier

### 5. Evaluation

* accuracy
* precision, recall, F1-score
* confusion matrix

## Results

The model achieves approximately:

**Accuracy: ~98.8%**

This suggests that the model performs very well on the dataset, although further validation would be required to ensure generalization.
This indicates strong performance for a baseline NLP model.

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/annagalitorok/Cyberbullying-Detection-ML.git
cd Cyberbullying-Detection-ML
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run:

* `ML_Cyberbully_Detection.ipynb`

## Technologies Used

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

## Important Note

This project contains potentially offensive language, as detecting cyberbullying requires working with real examples of harmful text.

The content is used strictly for educational and machine learning purposes.

## Future Improvements

* compare with Naive Bayes or SVM models
* preserve emojis, hashtags, and mentions for better context
* hyperparameter tuning
* cross-validation
* build a simple web interface (e.g. Streamlit)

## Author

Created as a machine learning project for cyberbullying detection using NLP techniques.
