# 🛍️ Amazon Fashion Review Insights Dashboard

## 📊 Project Overview

This project presents an **interactive Power BI dashboard** built to analyze customer reviews from the Amazon Fashion dataset. The dashboard transforms raw review data into meaningful insights that help understand **customer satisfaction, product performance, sentiment trends, and reviewer behavior**.

The goal of this project is to demonstrate how **data visualization and analytics can support data-driven business decisions in e-commerce**, especially in understanding customer feedback and improving product strategies.

---

## 📂 Dataset Description

The dataset contains **Amazon Fashion product reviews** with multiple attributes related to customer feedback and product details.

### Key Columns Used

* **product_id (ASIN)** – Unique identifier for each product
* **reviewer_id** – Unique identifier for reviewers
* **reviewer_name** – Name of the reviewer
* **overall** – Customer rating (1–5 stars)
* **review_text** – Full text of the review
* **summary** – Short summary of the review
* **review_date** – Date when the review was posted
* **verified_purchase** – Indicates whether the purchase was verified
* **vote** – Number of helpful votes received
* **style_color / style_size** – Product variation details
* **sentiment** – Derived column based on rating analysis

---

## 🧹 Data Preparation

Data cleaning and transformation were performed using **Power Query in Power BI**.

Main preprocessing steps included:

* Cleaning and formatting **date columns**
* Handling **missing values**
* Converting columns to correct **data types**
* Removing inconsistencies in text fields
* Creating derived columns such as:

  * **Sentiment classification** (Positive / Neutral / Negative)
  * **Review length metrics**
  * **Product categories**

---

## 📑 Dashboard Pages

### 🏠 Home

Landing page introducing the dashboard and providing navigation to all analysis sections.

### 📈 Overview

High-level KPIs summarizing the dataset:

* Total Reviews
* Average Rating
* Verified Purchases
* Unique Products
* Sentiment Distribution

### 👕 Product Insights

Focuses on product performance:

* Top products by number of reviews
* Rating distribution across products
* Category comparison

### 💬 Text & Sentiment Analysis

Analyzes customer feedback through:

* Sentiment classification
* Review length analysis
* Text-based insights from review summaries

### 👤 Reviewer Insights

Explores reviewer behavior:

* Distribution of review activity
* Verified vs non-verified purchases
* Helpful vote patterns

### 🔎 Review Details

A **drill-through page** for detailed exploration of individual reviews including:

* Product ID
* Reviewer name
* Rating
* Review text
* Sentiment
* Helpful votes

---

## 📊 Key Insights

The dashboard helps identify:

* Products receiving the **highest number of reviews**
* Distribution of **positive, neutral, and negative sentiment**
* Differences between **verified and non-verified purchases**
* Reviewer engagement through **helpful votes**
* Customer opinions extracted from **review summaries**

These insights can help businesses improve **product quality, marketing strategies, and customer experience**.

---

## 🛠 Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX (Data Analysis Expressions)**
* **Microsoft Excel**

---

## ⭐ Key Features

* Interactive **filters and slicers**
* **Drill-through functionality** for detailed review analysis
* Multi-page dashboard for structured insights
* Sentiment classification based on ratings
* Clean and business-oriented dashboard design

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. Navigate through the dashboard pages.
4. Use filters and slicers to explore insights interactively.

---


## 🎯 Project Objective

This project demonstrates skills in:

* Data cleaning and transformation
* Exploratory data analysis
* Interactive dashboard design
* Business insight generation
* Power BI visualization

---

## 🔮 Future Improvements

Possible enhancements include:

* Advanced **Natural Language Processing (NLP)** for sentiment analysis
* **Topic modeling** for deeper review insights
* Integration with **live review data**
* Predictive analysis for **rating trends**

---

## 📌 Author

**Prachi Dhiman**
BTech Computer Science Engineering Student

* GitHub: https://github.com/PrachiDhiman5
* LinkedIn: https://linkedin.com/in/prachi-dhiman05/
