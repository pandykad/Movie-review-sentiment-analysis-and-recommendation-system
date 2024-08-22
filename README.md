# 🎬 Movie Review Sentiment Analysis & Recommendation System

## 🌟 Overview

This project combines two main components:
1. A sentiment analysis system for movie reviews
2. A proof-of-concept recommendation system based on user similarities

## 🚀 Features

### 😊😐😠 Sentiment Analysis
- Preprocesses and cleanses movie review text data
- Implements multiple machine learning models:
  - Deep Learning (Neural Network)
  - Logistic Regression
  - Multinomial Naive Bayes
  - Linear SVC
  - K-Nearest Neighbors
- Employs an ensemble learning technique (Bagging) to improve accuracy

### 🎯 Recommendation System
- Creates a simulated dataset of user movie ratings
- Calculates user similarities using Euclidean distance
- Generates user rankings based on similarities

## 🛠 Tech Stack

- Python 🐍
- Pandas 🐼
- NumPy 🔢
- Scikit-learn 🧠
- TensorFlow/Keras 📊
- NLTK 📚
- Matplotlib & Seaborn 📈

## 🏗 Setup and Installation

1. Clone the repository
2. Install the required dependencies:
```bash pip install requirements.txt```
3. Run the Jupyter notebook or Python script

## 🎮 Usage

1. Load the IMDB movie review dataset
2. Preprocess the text data
3. Train and evaluate multiple sentiment analysis models
4. Generate the ensemble model predictions
5. Create the simulated user ratings dataset
6. Run the recommendation system algorithm

## 📊 Results

- The ensemble model achieved an accuracy of 83.6% on the test set for sentiment analysis
- The recommendation system successfully identifies similar users based on their movie ratings

## 🔮 Future Improvements

- Incorporate more advanced NLP techniques for text preprocessing
- Experiment with additional machine learning models
- Enhance the recommendation system with collaborative filtering techniques
- Integrate with a real-time movie database for up-to-date recommendations

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
