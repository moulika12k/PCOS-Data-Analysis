# 🩺 PCOS Data Analysis using Excel, Power Query, and DAX

## 📊 Overview
This project analyzes real-world health data related to Polycystic Ovary Syndrome (PCOS), a common but underdiagnosed hormonal disorder in women. By examining clinical and biological factors using Excel, this project aims to uncover trends and patterns that could support early diagnosis and raise awareness.

---

## 🎯 Objectives
- Analyze patterns and correlations in PCOS-related health data.
- Understand how clinical variables (like BMI, age, hormone levels) relate to PCOS diagnosis.
- Build a clean, interactive dashboard summarizing key insights.
- Practice the complete data analysis process using **Excel**, **Power Query**, and **DAX**.

---

## 🛠 Tools & Techniques Used
- **Excel**
  - Pivot Tables
  - Conditional Formatting
  - Data Visualization
- **Power Query**
  - ETL (Extract, Transform, Load)
  - Data Cleaning (removing nulls, renaming, formatting)
- **DAX (Data Analysis Expressions)**
  - Custom Measures for calculations and deeper insights
- **Star Schema**
  - Basic data modeling using one-to-many relationships

---

## 🗂️ Project Structure

| File/Folder | Description |
|-------------|-------------|
| `PCOS_PRESENTATION.pdf` | Full walkthrough of the project, including objectives, methods, and insights |
| `README.md` | You’re reading it! Project summary and explanation |
| `Cleaned_Dataset.xlsx` | Cleaned and transformed dataset used for analysis |


**BEFORE AFTER RAW DATA COMPARISON**
Before (Raw Data): The dataset contains missing values, inconsistencies, and irrelevant information that may hinder analysis.
After (Clean Data): The data is processed to remove errors, handle missing values, and standardize formats, making it ready for analysis.

![Image](https://github.com/user-attachments/assets/a2c06372-22fb-4ba8-87d0-39d9ab87bfba)

---
**DATA MODELING**
Data Modeling: Data modeling involves designing the structure of data to represent relationships and ensure efficient data storage and retrieval for analysis.
Star Schema: In the star schema, data is organized into fact tables and dimension tables, simplifying queries and enhancing reporting; I implemented this by creating a central fact table and linking it to dimension tables for easy data access and analysis.

![Image](https://github.com/user-attachments/assets/79cfcaf5-0185-40a8-a9c4-ab3477bfdf25)

---

**PIVOT TABLES**
Used pivot tables to analyze PCOS diagnosis across BMI, age groups, and blood groups. Additional pivots compared hormone levels (LH, FSH, PRL, TSH) between diagnosed and non-diagnosed individuals.

![Image](https://github.com/user-attachments/assets/91afd584-5cf5-47ab-a119-af2c48fd40d1)

---

**DASHBOARD**
Designed a dashboard to visualize PCOS diagnosis trends. Included charts for BMI distribution, hormone levels, age groups, and blood group comparison to highlight key patterns.

![Image](https://github.com/user-attachments/assets/ebdd6019-ebcd-4dbb-9946-4d0dd66d3c88)

---

## 📌 Key Insights

- Women with **higher BMI** are more likely to be diagnosed with PCOS.
- The **20–34 age group** shows the highest number of diagnoses.
- **B+ and O+ blood groups** have a slightly higher occurrence of PCOS.
- PCOS-diagnosed women tend to have **LH and PRL hormone levels higher than non-diagnosed women**.

---

## 🔗 Dataset Source
The dataset was obtained from Kaggle:
[PCOS Data without Infertility](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos)

---
## 💬 Feedback & Suggestions
If you have suggestions, feedback, or ideas to improve this project, feel free to open an issue or drop a message!
