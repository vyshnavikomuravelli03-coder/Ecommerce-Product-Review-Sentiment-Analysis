# Women's E-Commerce Clothing Reviews: Business Intelligence & Sentiment Analytics

An end-to-end data analytics, SQL querying, NLP sentiment classification, and interactive dashboard project evaluating 22,000+ customer reviews.

## 🚀 Project Overview
This repository contains a complete data science pipeline built in Python and SQLite to analyze customer satisfaction, uncover root causes of product complaints, and provide actionable business recommendations for e-commerce retail growth.

## 📊 Key Features & Workflow
1. **Data Cleaning & Preparation:** Handled missing values, removed duplicate records, standardized column names (`snake_case`), and validated ratings.
2. **SQL Business Analysis:** Executed robust SQL queries utilizing `GROUP BY`, `ORDER BY`, and `CASE WHEN` to extract department metrics, top-rated products, and customer demographics.
3. **Exploratory Data Analysis (EDA):** Generated publication-ready visualizations uncovering age distribution, department review volumes, and correlation matrices.
4. **NLP Sentiment Analysis:** Deployed NLTK VADER sentiment scoring and TF-IDF keyword extraction to classify customer sentiment and generate word clouds.
5. **Customer Complaint Mining:** Segmented 1- and 2-star reviews into core failure themes (Sizing, Quality, Design Mismatch).
6. **Interactive Dashboard:** Built interactive Plotly charts with KPI summaries and exported a standalone HTML dashboard.

## 🛠️ Tech Stack
* **Languages:** Python, SQL
* **Libraries:** Pandas, NumPy, Scikit-Learn, NLTK (VADER), Matplotlib, Seaborn, Plotly, WordCloud
* **Database:** SQLite (`ecommerce_reviews.db`)
* **Environment:** Google Colab / Jupyter Notebooks

## 📂 Deliverables & Repository Structure
* `notebooks/` - Google Colab Jupyter Notebooks (Steps 1 to 6)
* `database/` - SQLite database and business SQL queries
* `dashboard/` - Standalone interactive HTML dashboard (`ecommerce_review_dashboard.html`)
* `cleaned_reviews.csv` & `sentiment_labelled_reviews.csv` - Processed datasets

## 📈 Executive Summary & Business Impact
* **Overall Satisfaction:** Brand achieves an average rating of **4.18 / 5.0** with **92.4% positive sentiment**.
* **Primary Friction Point:** Over **53.5%** of negative feedback stems from unpredictable sizing and fit discrepancies.
* **Strategic Recommendation:** Implement precise inch-based garment sizing charts and strict pre-shipment quality control audits to significantly reduce return rates.
