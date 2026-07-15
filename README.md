# 🎥 YouTube Video Popularity Prediction Using Random Forest

## 📌 Project Overview

This project uses **Machine Learning** to predict whether a YouTube video is **Popular** or **Not Popular** based on user engagement features. A **Random Forest Classifier** is trained on a cleaned YouTube Trending Videos dataset to classify videos using likes and comment counts.

---

## 🎯 Objective

The objective of this project is to build and evaluate a supervised machine learning model that predicts the popularity of YouTube videos.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📂 Dataset

The project uses a cleaned YouTube Trending Videos dataset.

### Features Used
- Likes
- Comment Count

### Target Variable

**Popular**

- **1** = Popular Video
- **0** = Not Popular Video

The target variable is created using the median value of the **views** column.

---

# 📊 Project Workflow

```text
                +----------------------+
                |  Load Dataset        |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Data Preprocessing   |
                | - Missing Values     |
                | - Feature Selection  |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Create Target        |
                | Popular / Not Popular|
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Train-Test Split     |
                | (80% / 20%)          |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Random Forest Model  |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Prediction           |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Model Evaluation     |
                | Accuracy             |
                | Confusion Matrix     |
                | ROC Curve            |
                | Classification Report|
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Save Trained Model   |
                +----------------------+
```

---

## 🤖 Machine Learning Algorithm

- Random Forest Classifier

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score
- Feature Importance

---

## 📁 Project Structure

```text
youtube-popularity-prediction/
│
├── youtube_popularity_prediction.ipynb
├── cleaned_youtube_data.csv
├── README.md
├── requirements.txt
├── confusion_matrix.png
├── roc_curve.png
└── youtube_popularity_model.pkl
```

---


## 📊 Expected Output

- Predict whether a video is Popular or Not Popular.
- Evaluate model performance using multiple metrics.
- Visualize performance using Confusion Matrix and ROC Curve.
- Understand feature importance.

---


## 👩‍💻 Author

**Swastika**

