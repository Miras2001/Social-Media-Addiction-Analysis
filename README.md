# Social-Media-Addiction-Analysis

Here's a refined and well-structured version of your project documentation tailored for a `README.md` file. It follows a clear Markdown format, includes headers, bullet points, and emphasizes clarity for readers browsing the project on platforms like GitHub:

---

# 📊 Social Media Addiction and Relationships – Data Analysis Project

## 🧠 Introduction

This project investigates the relationship between **social media addiction** and **relationship status**, using a dataset from [Kaggle](https://www.kaggle.com/). The analysis process included:

* **Data cleaning in Excel**
* **Data exploration using SQL in DataGrip**
* **Visualization with Power BI**

The goal was to uncover trends and insights around usage patterns, demographics, and emotional/social contexts.

---

## 🧹 Data Preparation (Excel)

The dataset was cleaned and prepared using Microsoft Excel through the following steps:

* **Removing Duplicates**: Ensured uniqueness by eliminating repeated rows.
* **Adjusting Data Types**: Proper formatting for numerical and categorical variables (e.g., addiction scores, usage time, academic level, relationship status).
* **Handling Null Values**: Rows with missing data were removed to maintain analysis accuracy.

---

## 🗃️ Data Exploration (SQL in DataGrip)

Data exploration was performed with SQL queries in **DataGrip**. Four CSV files were generated based on specific research questions:

1. **`QUESTION_1__Whats_than_males_on_average.csv`**
   *Average Social Media Usage by Gender*
   → Found similar usage times for males and females.

2. **`Q2_Top10_countries.csv`**
   *Top 10 Countries by Average Addiction Score*
   → Identified countries with the highest addiction levels (e.g., Liechtenstein, Lebanon, Armenia).

3. **`Q3_academic_addiction.csv`**
   *Addiction and Sleep Patterns by Academic Level*
   → Compared sleep hours and addiction scores across high school, undergraduate, and graduate students.

4. **`QUESTION_5__Does_rela_usage_or_addiction.csv`**
   *Social Media Usage by Relationship Status*
   → Explored how being single, in a relationship, or "it's complicated" correlates with addiction levels.

---

## 📈 Data Visualization (Power BI)

The four CSVs were imported into **Power BI** to create meaningful visualizations. These are detailed in the file `dataviz_1.pdf`.

### Key Visuals:

* **📊 Bar Chart: Social Media Usage by Gender**

  * Females: \~5h 49m
  * Males: \~5h 50m
  * Slightly higher usage for males.

* **🌍 Filled Map: Top 10 Countries by Addiction Score**

  * Highlights high-addiction regions geographically.

* **📊 Bar Chart: Sleep and Addiction by Academic Level**

  * High school students: \~8h sleep, lower addiction.
  * Graduate students: \~6h sleep, higher addiction (\~7/10).

* **🥧 Pie Chart: Relationship Status Distribution**

  * 33.81% In a Relationship
  * 33.81% Single
  * 32.37% It’s Complicated

---

## ✅ Conclusion

This project demonstrates a structured data analysis workflow:

* **Excel** for data cleaning
* **SQL in DataGrip** for exploration
* **Power BI** for visualization

### 🔍 Key Insights:

* **Gender**: Nearly equal average usage times.
* **Geography**: Some smaller nations report higher addiction levels.
* **Academia**: Addiction increases with academic level while sleep decreases.
* **Relationships**: Relationship status appears to influence addiction and usage behavior.




