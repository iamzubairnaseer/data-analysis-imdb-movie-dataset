# 🎬 IMDb Movie Data Analysis & Rating Prediction

## 📌 Project Overview
This project analyzes an IMDb movie dataset to uncover insights and build a model that predicts movie ratings based on various features such as genre, director, actors, and revenue.

The project combines:
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- 🤖 Machine Learning (Regression Model)

---

## 🎯 Objective
To predict how a movie might be rated using its attributes and extract meaningful insights from the dataset.

---

## 📂 Dataset Description

The dataset contains the following features:

| Column | Description |
|------|-------------|
| Rank | Movie ranking |
| Title | Movie name |
| Genre | Movie genre |
| Description | Short summary |
| Director | Director name |
| Actors | Cast |
| Year | Release year |
| Runtime (Minutes) | Duration |
| Rating | IMDb rating (Target Variable) |
| Votes | Number of votes |
| Revenue (Millions) | Revenue generated |
| Metascore | Critic score |

---

## 🧹 Data Preprocessing

- Handled missing values
- Converted categorical variables into numerical format
- Cleaned text-based columns
- Removed irrelevant features

---

## 📊 Exploratory Data Analysis (EDA)

Key insights:
- 📈 Relationship between **Votes and Rating**
- 🎭 Genre-wise performance comparison
- 🎬 Top directors based on ratings
- 💰 Revenue vs Rating trends

---

## ⚙️ Feature Engineering

- Encoded categorical variables (Genre, Director)
- Selected important numerical features:
  - Votes
  - Revenue
  - Metascore
  - Runtime

---

## 🤖 Model Building

### Model Used:
- Random Forest Regressor

### Why?
- Handles non-linearity well
- Works with mixed feature types
- Provides feature importance

---

## 🧪 Model Evaluation

Metrics used:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

```python
RMSE = √MSE