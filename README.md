# 🎬 Movie Success Prediction and Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project focuses on predicting the commercial success of movies using machine learning techniques and analyzing audience sentiment using Natural Language Processing (NLP). By combining financial attributes such as budget and IMDb score with sentiment extracted from movie descriptions, the project demonstrates how data-driven approaches can provide valuable insights into movie performance.

The study integrates **data analysis, sentiment modeling, and predictive machine learning** to understand factors influencing box office revenue.

---

## 🎯 Objectives

* Perform sentiment analysis on movie descriptions using NLP (VADER).
* Build a machine learning model to predict movie revenue.
* Analyze genre-wise sentiment and performance trends.
* Generate business insights from the results.

---

## 📂 Dataset

The dataset contains movie-related information including:

* Movie Name
* Genre
* IMDb Score
* Overview (text description)
* Budget
* Revenue

Dataset Source: IMDb / Kaggle movie dataset

---

## 🛠️ Technologies Used

### Programming & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK (VADER Sentiment Analyzer)

### Tools

* Jupyter Notebook
* Excel (optional visualization/dashboard)

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection & Cleaning

* Loaded movie dataset
* Handled missing values
* Converted budget and revenue into numeric format

### 2️⃣ Sentiment Analysis

* Used VADER sentiment analyzer from NLTK
* Generated sentiment scores from movie overview text
* Classified sentiment into Positive, Negative, and Neutral

### 3️⃣ Exploratory Data Analysis

* Sentiment distribution visualization
* Genre vs sentiment comparison
* Correlation heatmap of numerical features

### 4️⃣ Machine Learning Model

* Model Used: Linear Regression
* Features:

  * Budget
  * IMDb Score
  * Sentiment Score
* Target:

  * Movie Revenue

### 5️⃣ Model Evaluation

* Mean Absolute Error (MAE)
* R² Score (Coefficient of Determination)
* Actual vs Predicted visualization

---

## 📊 Key Insights

* Movies with higher budgets generally generate higher revenue.
* Positive sentiment is associated with better movie performance.
* IMDb score moderately correlates with financial success.
* Certain genres consistently outperform others in revenue generation.
* Sentiment analysis can enhance prediction accuracy beyond financial metrics alone.

---

## 📈 Results

The regression model successfully learned relationships between movie attributes and revenue, demonstrating the usefulness of combining financial and textual data for predictive analytics.

---

## 🚀 Future Improvements

* Implement advanced models (Random Forest, XGBoost)
* Add classification model (Hit vs Flop prediction)
* Perform sentiment analysis on real user reviews instead of descriptions
* Deploy the model as a web application

---

## 📁 Project Structure

```
Movie-Success-Prediction/
│
├── imdb_movies.csv
├── Movie_Success_Prediction.ipynb
├── movie_analysis.xlsx
├── README.md
└── images/
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/yourusername/movie-success-prediction.git
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

3. Run Jupyter Notebook:

```
jupyter notebook
```

4. Execute the notebook cells step-by-step.

---

## 💼 Real-World Applications

* Film industry revenue prediction
* Audience perception analysis
* Marketing strategy optimization
* Entertainment analytics

---

## 🏆 Resume Value

This project demonstrates skills in:

* Machine Learning
* Natural Language Processing
* Data Analysis
* Predictive Modeling
* Business Insight Generation

---

## 👨‍💻 Author

**Samarth Joshi**

---

## ⭐ Acknowledgements

* IMDb / Kaggle datasets
* Scikit-learn documentation
* NLTK VADER sentiment analysis tool

---

## 📜 License

This project is for educational and research purposes.
