# 📱 iPhone Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing iPhone product data from Flipkart to uncover insights related to pricing, ratings, reviews, and discounts. The dataset includes multiple iPhone models along with their specifications and customer feedback.

The goal of this analysis is to understand:

* Which iPhones are most popular
* Pricing trends
* Relationship between ratings, reviews, and discounts
* Identification of most and least expensive models

---

## 📂 Dataset Information

The dataset contains **62 rows and 11 columns** with the following features:

* Product Name
* Product URL
* Brand
* Sale Price
* MRP
* Discount Percentage
* Number of Ratings
* Number of Reviews
* UPC
* Star Rating
* RAM

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Plotly (Express & Graph Objects)

---

## 🧹 Data Preprocessing

* Loaded dataset using Pandas
* Checked for missing values → ✅ No missing values found
* Performed statistical summary using `describe()`

---

## 📊 Exploratory Data Analysis

### ⭐ Top Rated iPhones

* Highest rating observed: **4.7**
* Top models include:

  * iPhone 11 Pro Max variants
  * iPhone 12 series
  * iPhone 8 Plus

---

### 👍 Most Rated iPhones

* Highest number of ratings: **95,909**
* Most popular models:

  * iPhone SE (multiple variants)
  * iPhone XR variants

---

### 📝 Most Reviewed iPhones

* Highest number of reviews: **8,161**
* Top reviewed:

  * iPhone SE series
  * iPhone XR series

---

## 📈 Visualizations

### 1. Ratings vs Sale Price

* Scatter plot with trendline
* Insight:

  * No strong correlation between price and number of ratings
  * Lower-priced models tend to have more ratings

---

### 2. Ratings vs Discount Percentage

* Insight:

  * Products with higher discounts often receive more ratings
  * Budget-friendly phones attract more engagement

---

### 3. Bar Charts

* Top-rated iPhones vs number of ratings
* Top-rated iPhones vs number of reviews

---

## 💰 Pricing Analysis

### 🔴 Most Expensive iPhone

* **iPhone 12 Pro (512 GB)**
* Price: ₹140,900
* Ratings: 542
* Reviews: 42

---

### 🟢 Least Expensive iPhone

* **iPhone SE (64 GB)**
* Price: ₹29,999
* Ratings: 95,807
* Reviews: 8,154

---

## 🔍 Key Insights

* Budget iPhones (like SE, XR) have **higher engagement** (ratings & reviews)
* Premium models have **higher prices but lower engagement**
* Ratings are consistently high (4.5–4.7), showing strong customer satisfaction
* Discounts play a role in increasing product popularity

---

## 🚀 Conclusion

This analysis highlights how pricing and discounts influence customer behavior. Affordable iPhones dominate in terms of popularity, while premium models maintain high ratings but lower interaction.

---

## 📌 Future Improvements

* Include more brands for comparison
* Perform time-series analysis
* Add sentiment analysis on reviews
* Build a recommendation system

---

## 📎 How to Run

```bash
pip install pandas numpy plotly
```

```python
python your_script.py
```

---

## 👨‍💻 Author

Your Name

---

## 📜 License

This project is open-source and free to use.
