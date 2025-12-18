# Healthcare SQL Analysis

## 🎯 Objective

Analyze healthcare patient data using SQL to understand disease patterns, patient demographics, hospital performance, and financial trends. The goal is to support data-driven decision-making for healthcare planning, preventive care, and resource allocation.

## 🧩 Process

### 🧹 Data Cleaning

* Identified and corrected invalid negative billing amounts
* Applied transaction control (BEGIN TRANSACTION / COMMIT)

### 🧩 Data Preprocessing

* Created **Age Group** categories from raw age values
* Derived a **Season** column from admission dates (Winter, Spring, Summer, Fall)

### 📊 Data Analysis

* Analyzed disease frequency and patient demographics
* Evaluated hospital intake and doctor specialization patterns
* Performed financial analysis by disease, hospital, and insurance provider
* Calculated monthly, yearly, and year-over-year (YoY) trends

## 🛠 Tools & Features

| Tool                    | Purpose                                       |
| ----------------------- | --------------------------------------------- |
| SQL                     | Data cleaning, preprocessing, and analysis    |
| CTEs & Window Functions | ROW_NUMBER, LAG                               |
| Joins & Aggregations    | Multi-table analysis and summarization        |
| Date Functions          | Monthly, yearly, and YoY trend analysis       |

## 📈 Key Insights

### 🦠 Disease Burden

* Cancer and Diabetes are the most prevalent medical conditions, indicating a high disease burden
* Hospitals should prioritize early detection, and community awareness focused on healthlife risks

### 👥 Age & Gender Impact

* Most affected age groups: 36–55 and 56–75, requiring targeted clinical protocols
* Improve care accessibility for elderly patients
* Females represent 56.75% of cases; design gender-specific health programs and campaigns

### 🏥 Hospital Performance

* Smith Group Hospital has the highest patient intake; replicate efficiency across other hospitals

### 💰 Financial & Insurance Insights

* Cancer treatments has the highest costs
* United Healthcare covers the largest number of patients

## 🏁 Conclusion
This project demonstrates how **SQL** can be used to deliver a **full healthcare data analysis workflow** — from **data cleaning and feature engineering** to **insightful analytics** — providing findings that support **Better Healthcare Planning**.



