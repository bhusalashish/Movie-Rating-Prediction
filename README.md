# 🎬 Movie Rating Prediction – Supervised Learning Lab

This project implements a machine learning pipeline to predict movie ratings using the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/). The project demonstrates real-world application of supervised learning, data preprocessing, feature engineering, model comparison, and evaluation.


---

## Objectives

- Ingest and clean movie rating data
- Perform rich exploratory data analysis (EDA) with visualizations
- Engineer meaningful features from metadata
- Train and evaluate multiple supervised learning models
- Visualize and compare model performance
- Save and export the best performing model

---

## 📊 Features Used

- **User behavior**: average rating, count of ratings
- **Movie popularity**: average rating, rating count
- **Genres**: one-hot encoded movie genres
- **Demographics**: user age, gender, occupation
- **Temporal patterns**: rating year, month, weekday

---

## 📦 Models Trained

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor (🏆 Best)

Each model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 📈 Visualizations Included

- Correlation heatmap of features
- Distribution of ratings by genre, age group, gender
- Actual vs Predicted ratings scatter plot
- Residuals (error distribution) histogram
- Model performance comparison (MAE, MSE, R²)

---

## 🛠 Requirements

- Python 3.8+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Getting Started

1. Clone this repository
2. Download the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/) and place it in the `ml-100k/` directory
3. Run the notebook: `movie_rating_prediction.ipynb`
4. View evaluation results and export the best model

---

## 📌 Author Notes

- The pipeline avoids data leakage by splitting the dataset **based on users**, ensuring realistic evaluation.
- Feature selection includes both user and movie metadata for more personalized predictions.
- The notebook is well-annotated for educational and academic review.