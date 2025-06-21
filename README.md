# 🛒 Amazon Sales Recommendation System

A machine learning project that analyzes Amazon sales data and builds a recommendation system to suggest relevant products to users based on their past purchase behavior. This helps improve user experience and increase sales conversion.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Project Pipeline](#project-pipeline)
- [EDA & Preprocessing](#eda--preprocessing)
- [Recommendation Approach](#recommendation-approach)
- [Evaluation](#evaluation)
- [Results & Insights](#results--insights)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [License](#license)

---

## 📖 Overview

The goal of this project is to recommend products to Amazon customers based on their transaction history. By analyzing user-item interactions, the system provides personalized suggestions to enhance customer satisfaction and drive repeat purchases.

---

## 📍 Problem Statement

With millions of products available on e-commerce platforms like Amazon, customers often face decision fatigue. This project aims to reduce this issue by developing a recommendation engine that suggests items based on past user behavior, product popularity, or similar users.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib (EDA)
- Scikit-learn
- Surprise / LightFM (for collaborative filtering)
- Jupyter Notebook
- Streamlit (optional - for UI)
- Git & GitHub

---

## 📊 Data Description

The dataset contains anonymized transaction records. Key columns include:

| Column Name     | Description                                      |
|------------------|--------------------------------------------------|
| User_ID          | Unique ID for each customer                     |
| Product_ID       | Unique ID for each product                      |
| Product_Category | Category of the product                         |
| Purchase_Date    | Date of the transaction                         |
| Rating           | Product rating given by the user (if available) |
| Quantity         | Number of units purchased                       |
| Price            | Unit price of the product                       |

---

## 🔄 Project Pipeline

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Building Recommendation Models**
5. **Evaluation & Comparison**
6. **Saving and Serving Recommendations**

---

## 📈 EDA & Preprocessing

- Identified top-selling categories and users
- Visualized sales trends over time
- Treated missing values and handled duplicates
- Converted timestamps, normalized ratings, encoded IDs

---

## 🧠 Recommendation Approach

This project supports multiple recommendation techniques:

### 1. 📌 Popularity-Based Recommender
- Recommends most frequently purchased products overall

### 2. 👥 Collaborative Filtering
- **User-User** and **Item-Item** similarity
- Based on cosine similarity or Pearson correlation
