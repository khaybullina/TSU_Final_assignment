# 🛒 Customer Behavior Analysis & Recommendation System

## 📌 Overview

This project is a final assignment focused on analyzing retail customer behavior using Python and Pandas.

It includes data cleaning, exploratory data analysis (EDA), hypothesis testing, customer segmentation (clustering), and building a simple recommendation system based on transaction data.

---

## 🎯 Project Objectives

* Analyze customer purchasing behavior
* Identify top-performing products
* Explore the relationship between customer attributes and buying activity
* Segment customers into meaningful groups
* Build a basic recommendation system

---

## 📂 Dataset

The project uses three datasets:

* **customers.csv** — customer information (e.g., age, club membership, fashion news frequency)
* **product.csv** — product information
* **transactions.csv** — purchase history linking customers and products

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Matplotlib / Seaborn
* Scikit-learn

---

## 🔄 Workflow

### 1. Data Preparation

* Imported required libraries
* Loaded datasets from CSV files
* Cleaned and preprocessed the data

---

### 2. Exploratory Data Analysis (EDA)

Performed analysis and built visualizations:

* Number of products sold by month (density plot)
* Top 10 products by revenue (bar chart)
* Top 10 most popular products (bar chart)
* Share of products sold only once (pie chart)
* Analysis of purchases by age groups (10-year bins)
* Impact of following fashion news on purchasing behavior

---

### 3. Feature Relationship Analysis

* Formulated and tested a hypothesis:
  **Does club membership affect the number of purchased products?**
* Performed statistical testing
* Calculated p-value and interpreted the result

---

### 4. Customer Segmentation (Clustering)

* Created a dataset with features:

  * customer ID
  * number of purchases
  * age
  * total spending
  * club membership
  * fashion news frequency

* Determined the optimal number of clusters

* Built a clustering model

* Visualized clusters using scatter plots

---

### 5. Recommendation System

* Built a dataset: customer–product interactions
* Applied collaborative filtering based on customer similarity
* Generated product recommendations
* Example: recommendations for customer **ID = 6510**

---

## 💡 Key Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Data visualization
* Hypothesis testing
* Customer segmentation (clustering)
* Recommendation systems (collaborative filtering)

---

## 📎 Project Structure

```
TSU_Final_assignment/
│
├── Final_assignment_TSU.ipynb
├── customers.csv
├── product.csv
├── transactions.csv
└── README.md
```

---

## ✅ Conclusion

This project demonstrates a full analytical workflow:
from raw data processing to advanced techniques such as clustering and recommendation systems.


---

## 👩‍💻 Author

Albina Khaybullina

