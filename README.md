# E-commerce
E-commerce Data Cleaning and Analysis project focusing on data validation, cleaning, and insightful reporting using MySQL and Power BI. The project includes database migration to Microsoft Azure for cloud hosting and secure access.
# 📊 E-commerce Project: Data Cleaning and Validation

## 🗓 Date
May 23, 2025

## 🧾 Executive Summary

This project focuses on the **data cleaning**, **validation**, and **analysis** processes for migrating an E-commerce database to **Microsoft Azure Cloud**. The goal is to enhance data quality and improve **reporting accuracy** and **business intelligence** using tools like **Power BI** and **TPOT** for customer segmentation.

---

## 📁 Project Objectives

- Ensure scalable and secure data storage using **Azure**.
- Enable advanced reporting and dashboards via **Power BI**.
- Perform customer segmentation using **machine learning (TPOT)**.
- Clean and validate existing data for reliability.

---

## 🧹 1. Data Cleaning

### 1.1 Initial Inspection

- **Missing values**:
  - Categories table: 5 `NULL`s in `parent_id`.
- **Discounts table issues**:
  - Missing foreign keys (`product_id`, `category_id`, `order_id`).
  
### 1.2 Action Taken

- Excluded discounts from analysis due to poor data integrity.
- Marked affected rows for future remediation.

---

## 📈 2. Key Insights

### 2.1 Customer Segmentation (via TPOT)

Three primary customer personas identified:

- **Seekers**: Browse a lot, use wishlists, but do not purchase.
- **Quick Buyers**: Visit and purchase with minimal delay.
- **Hesitant**: Long session durations without conversion.

### 2.2 Returns Analysis

- Some **returned products received positive reviews**, suggesting issues like:
  - Poor fit or unmet expectations.
- **Fake reviews** identified from users with no purchase history.

---

## 💡 3. Recommendations

1. **Enforce foreign key constraints** in the discounts table to ensure data integrity.
2. **Collect demographic data** (e.g., age, gender) to improve segmentation.
3. **Target customers who return positively-reviewed products** for potential retention.
4. **Implement detection for fake reviews**, possibly via machine learning classifiers.
5. **Add `delivery_date` and `stock_in_date` fields** to enhance logistics and sales forecasting.

---

## 🔧 Tech Stack

- **Azure Cloud**: Data hosting and management.
- **Power BI**: Dashboards and visualization.
- **Python (TPOT)**: Machine learning for segmentation.
- **SQL**: Data cleaning and transformation.

---

## 👥 Team Members

Team **Team 24** who contributed to this project:

- Shimaa Mohamed — [LinkedIn](https://www.linkedin.com)  
- Marim Mohamed — [LinkedIn](www.linkedin.com/in/mariam-mohamed𓂆-33a3a0245)  
- Ibrahim — [LinkedIn](https://www.linkedin.com/in/ibrahim)  
- Ahmed Sultan — [LinkedIn](https://www.linkedin.com/in/ahmed-sultan)  
- Ahmed Ali — [LinkedIn](https://www.linkedin.com/in/ahmed-ali)  
- Mohamed — [LinkedIn](https://www.linkedin.com/in/mohamed)  
--Ahmed
---

## 🎓 Organizers and Trainers

- Engineer Ahmed Ali  
- Engineer Ahmed Hafez  
- Eng. Islam  

Training Program: **Bootcamp EYouth**
