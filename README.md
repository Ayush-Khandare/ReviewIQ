# ReviewIQ 🍽️

**Restaurant Review Sentiment Analysis using NLP & Deep Learning**

## 📌 Overview

ReviewIQ is a Natural Language Processing project that analyzes restaurant customer reviews and classifies them into **Positive** or **Negative** sentiment.

The project uses text preprocessing, **TF-IDF vectorization**, and a **Deep Learning Neural Network** built with TensorFlow/Keras.

## 🎯 Objective

* Analyze customer restaurant reviews automatically.
* Classify reviews as Positive or Negative.
* Convert text data into numerical features using TF-IDF.
* Build and evaluate a Deep Learning classification model.

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Jupyter Notebook

## 🔄 Workflow

```text
Restaurant Reviews
       ↓
Data Preprocessing
       ↓
Text Cleaning
       ↓
Tokenization
       ↓
Stopword Removal
       ↓
TF-IDF Vectorization
       ↓
Train/Test Split
       ↓
Neural Network
       ↓
Model Evaluation
       ↓
Sentiment Prediction
```

## 🧹 Text Preprocessing

The reviews are processed using:

* Lowercase conversion
* Removal of unwanted characters
* Tokenization
* Stopword removal
* Text cleaning

## 🤖 Model

The project uses a fully connected Neural Network with:

* Dense layers
* Dropout layers
* ReLU activation
* Sigmoid output
* Adam optimizer
* Binary Crossentropy loss
* Accuracy as evaluation metric
* Early stopping to reduce overfitting

## 📊 Evaluation

The model is evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

## 🔮 Prediction

ReviewIQ can classify new restaurant reviews.

**Example:**

```text
Input:
"The food was amazing and the service was excellent."

Prediction:
Positive
```

```text
Input:
"The food was terrible and the service was very bad."

Prediction:
Negative
```

## 📁 Project Structure

```text
ReviewIQ/
│
├── Restaurant_Reviews.csv
├── sentiment_analysis.ipynb
├── sentimentModel.keras
├── README.md
└── requirements.txt
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ReviewIQ.git
```

### 2. Install dependencies

```bash
pip install pandas numpy nltk scikit-learn tensorflow matplotlib
```

### 3. Open the notebook

```bash
jupyter notebook sentiment_analysis.ipynb
```

### 4. Run the notebook cells

Run the cells sequentially to preprocess the data, train the model, evaluate performance, and perform sentiment predictions.

## 💼 Business Applications

ReviewIQ can help restaurants:

* Monitor customer satisfaction
* Analyze customer feedback
* Identify negative experiences
* Understand customer opinions
* Automate review analysis

## 📈 Skills Demonstrated

* Natural Language Processing
* Text preprocessing
* Feature engineering
* TF-IDF
* Deep Learning
* Binary classification
* Model evaluation
* Sentiment analysis
* Python data analysis


