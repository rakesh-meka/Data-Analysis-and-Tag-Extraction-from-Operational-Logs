# 📊 Data Analysis and Tag Extraction from Operational Logs

## 📌 Project Overview

This project provides an end-to-end data analysis pipeline for **exploratory data analysis (EDA), data cleaning, visualization, and automated tag extraction** from operational log data.  
The goal is to transform raw operational records—especially free-text issue descriptions—into structured, actionable insights.

The analysis helps identify common operational problems such as **failures, component issues, delays, and warnings**, enabling better monitoring, reporting, and decision-making.

The entire workflow is implemented using **Python** in a **Jupyter Notebook** environment.

---

## 🛠️ Tech Stack & Tools

- **Programming Language**: Python  
- **Environment**: Jupyter Notebook  
- **Libraries Used**:
  - Pandas – Data manipulation and cleaning  
  - NumPy – Numerical operations  
  - Matplotlib – Data visualization  
  - Seaborn – Statistical visualizations  

---

## 📂 Project Structure

Data-Analysis-and-Tag-Extraction-from-Operational-Logs/
│
├── TASK-2.xlsx # Raw operational dataset
├── TASK-2-Cleaned.xlsx # Cleaned and processed dataset
├── Analysis.ipynb # Complete EDA, cleaning, visualization & tagging pipeline
└── README.md # Project documentation


---

## 📊 Dataset Description

The dataset contains a mix of **numerical, categorical, and free-text fields** representing operational events.

### Key Analysis Performed:
- Identification of **data types** (numerical vs categorical)
- **Unique value counts** to understand data variability
- **Statistical summaries** for numerical columns
- **Frequency analysis** for categorical columns
- Inspection of **text-based issue descriptions**

---

## 🧹 Data Cleaning Process

To ensure data quality and consistency, the following steps were applied:

### 1. Handling Missing Values
- Numerical columns filled using **median**
- Categorical columns filled using **mode**

### 2. Text Standardization
- Converted all text to **lowercase**
- Removed leading and trailing whitespaces

### 3. Outlier Treatment
- Outliers detected using the **Interquartile Range (IQR)** method
- Outliers were **retained intentionally** for analytical insights

---

## 📈 Exploratory Data Analysis & Visualizations

The project includes multiple visualization techniques to uncover patterns:

- **Distribution Plots** – Understand spread and skewness of numerical data  
- **Count Plots** – Identify dominant categories and frequent events  
- **Boxplots** – Detect and analyze outliers visually  

These visualizations support better interpretation of operational trends.

---

## 🏷️ Automated Tag Extraction

Free-text operational descriptions were processed to extract meaningful tags.

### Tags Generated:
- `failure`
- `error`
- `component issue`
- `delay`
- `warning`
- `general`

### Methodology:
- Keyword-based matching
- Semantic filtering for relevance

These tags help classify operational problems and highlight recurring issue types.

---

## 📌 Key Insights

- **Failures and component issues** are the most frequent tags, indicating critical focus areas
- Cleaned data is now suitable for **further modeling or advanced analytics**
- Visualization results reveal **patterns and anomalies** useful for operational improvement

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Data-Analysis-and-Tag-Extraction-from-Operational-Logs.git
cd Data-Analysis-and-Tag-Extraction-from-Operational-Logs

### 2. Install Dependencies

### 3. Run the Notebook 