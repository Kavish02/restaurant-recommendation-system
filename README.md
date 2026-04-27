# 🍽️ Restaurant Recommendation System

## 📌 Overview

This project implements a **content-based restaurant recommendation system** that suggests restaurants based on user preferences such as **cuisine, location, and price range**.

The system uses **Natural Language Processing (NLP)** techniques like **TF-IDF vectorization** and **cosine similarity** to find similar restaurants.

---

## 🎯 Objective

* Build a recommendation system using content-based filtering
* Provide personalized restaurant suggestions
* Improve user decision-making experience

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📂 Dataset

The dataset contains restaurant details such as:

* Restaurant Name
* Cuisines
* City
* Price Range
* Aggregate Rating

> 📌 Note: Dataset used is similar to Zomato restaurant data.

---

## 🔧 Data Preprocessing

* Removed missing values using `dropna()`
* Selected relevant columns
* Converted categorical data into string format
* Combined features into a single column for analysis

---

## 🧠 Methodology

### 1. Feature Engineering

Combined important attributes:

```
Cuisines + City + Price Range
```

### 2. Text Vectorization

Used **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical vectors.

### 3. Similarity Calculation

Used **Cosine Similarity** to measure similarity between restaurants.

---

## 🔍 How It Works

1. User provides input like:

```
"Italian Delhi 2"
```

2. Input is converted into vector form
3. Compared with dataset using cosine similarity
4. Top 5 similar restaurants are recommended

---

## 💻 Example Output

```
Input: Italian Delhi 2

Recommended Restaurants:
1. Cafe Roma
2. Pizza Hub
3. La Italia
4. Urban Pasta
5. Foodies Kitchen
```

---

## 🚀 Features

* Content-based recommendation
* Fast and efficient similarity search
* Easy to extend with more filters
* Works on real-world dataset

---

## 📊 Testing

Tested with multiple inputs:

* Italian Delhi 2
* Chinese Mumbai 1
* North Indian Pune 3

Results showed relevant recommendations based on:

* Cuisine match
* Location match
* Price similarity

---

## 🔮 Future Improvements

* Add **Streamlit Web App UI**
* Integrate **location-based filtering (GPS)**
* Use **hybrid recommendation system**
* Add **user history & personalization**

---

## 📸 Screenshots

(Add your Colab output screenshots here)

---

## 📁 Project Structure

```
restaurant-recommendation-system/
│
├── notebook.ipynb
├── Dataset.csv
├── README.md
└── screenshots/
```

---

## 🧠 Key Learning

* Learned how recommendation systems work
* Applied NLP techniques in real-world data
* Understood cosine similarity for matching

---

## 💼 Resume Highlight

Developed a content-based Restaurant Recommendation System using TF-IDF and cosine similarity on real-world dataset to provide personalized suggestions based on cuisine, location, and pricing.

---

## 🔗 Author

**Kavish Vijan**
B.Tech CSE Student

---
