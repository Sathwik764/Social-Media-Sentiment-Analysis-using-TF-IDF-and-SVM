# Social-Media-Sentiment-Analysis-using-TF-IDF-and-SVM
This project performs sentiment analysis on a large Twitter dataset using a Support Vector Machine (SVM) classifier. It includes data preprocessing, visualization, feature extraction using TF-IDF, model training, and evaluation.

## 📝 Project Overview
The goal of this project is to classify tweets into **positive** or **negative** sentiment categories by building a machine learning pipeline:

* Load and preprocess raw Twitter data
* Visualize sentiment distribution and word clouds for positive and negative tweets
* Extract TF-IDF features
* Train a Linear SVM model for classification
* Evaluate model performance with accuracy, classification report, and confusion matrix
* Identify the most important words contributing to positive sentiment
  
## 📂 Dataset

* Dataset: [Sentiment140](http://help.sentiment140.com/for-students/) (Twitter Sentiment Data)
* Format: CSV with 1.6 million tweets, columns include `target`, `ids`, `date`, `flag`, `user`, and `text`
* Target values remapped to binary:

  * `0` → Negative sentiment
  * `4` → Positive sentiment

## 🧰 Technologies Used

* Python 3
* pandas, numpy — Data manipulation
* re — Text preprocessing with regex
* matplotlib, seaborn — Data visualization
* wordcloud — Visualizing common words
* scikit-learn — Machine learning (TF-IDF, LinearSVC, evaluation metrics)

## 📊 Key Features

* **Data Cleaning:** Removal of URLs, mentions, hashtags, punctuation, and case normalization
* **Visualizations:** Sentiment distribution bar chart and word clouds for positive/negative tweets
* **Feature Engineering:** TF-IDF vectorization with stopword removal
* **Modeling:** Linear Support Vector Machine classifier for binary sentiment classification
* **Evaluation:** Accuracy score, classification report, confusion matrix heatmap
* **Interpretability:** Top 10 positive words ranked by model weights

## 🚀 How to Use

1. Load and preprocess the data with the provided cleaning function.
2. Visualize sentiment distribution and word clouds.
3. Extract features using TF-IDF vectorizer.
4. Split the dataset into training and testing sets.
5. Train the LinearSVC model on training data.
6. Evaluate performance on test data and visualize results.
7. Inspect top positive words influencing predictions.

## 📈 Results Summary

* Model Accuracy: \~\[Your Accuracy Here]%
* Confusion matrix shows effective classification between positive and negative tweets.
* Most influential positive words identified through model coefficients.

---


