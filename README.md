# Data-Analysis-and-Tag-Extraction-from-Operational-Logs

## Overview

This repository presents a complete pipeline for exploratory data analysis (EDA), data cleaning, visualization, and automated tag extraction from operational log data. The project is designed to provide insights into operational issues such as failures, component errors, and delays by transforming raw textual and tabular data into structured and meaningful information.

The work was carried out using Python in a Jupyter Notebook environment, leveraging libraries such as Pandas, Matplotlib, and Seaborn for analysis and visualization.

---

## 📂 Files Included

- `TASK-2.xlsx` – Original dataset containing raw operational data.
- `TASK-2-Cleaned.xlsx` – Cleaned version of the dataset post-processing.
- `Analysis.ipynb` – Jupyter notebook detailing the full analysis pipeline.
- `Data Analysis Report.pdf` – A comprehensive summary of the methods and findings.

---

## 📊 Data Description

The dataset primarily consists of both numerical and categorical fields. A significant portion of the data includes free-text descriptions of operational issues.

### Column-Level Analysis Included:

- **Data Types**: Differentiated between categorical and numerical types.
- **Unique Values**: Counted to identify variability and cardinality.
- **Distributions**: Descriptive statistics for numerical columns and frequency counts for categorical columns.

---

## 🧹 Data Cleaning

The cleaning process ensured consistency and completeness across the dataset:

- **Missing Values**:
  - Numerical columns filled with median values.
  - Categorical columns filled with mode values.
- **Text Standardization**:
  - All text converted to lowercase.
  - Removal of leading/trailing whitespace.
- **Outliers**:
  - Detected using the IQR method but retained for analysis.

---

## 📈 Visualizations

Three key types of plots were generated to interpret the data:

- **Distribution Plots**: To assess spread and skewness of numerical data.
- **Count Plots**: To evaluate dominance in categorical features.
- **Boxplots**: For visual detection of outliers.

---

## 🏷️ Tag Generation

Free-text descriptions were processed to extract thematic tags:

- **Tags Identified**: `failure`, `error`, `component issue`, `delay`, `warning`, `general`.
- **Method**: Keyword matching and filtering based on semantic relevance.

These tags provide critical insights into frequent problem categories, guiding targeted corrective actions.

---

## 📌 Key Takeaways

- Tags such as `failure` and `component issue` were most prevalent, indicating priority areas.
- The dataset, post-cleaning, is now suitable for further modeling or decision-making tasks.
- Visual and statistical summaries reveal potential areas for operational improvement.

---
