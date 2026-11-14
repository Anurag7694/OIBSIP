# Task 3: Data Cleaning – Titanic Dataset

## 📌 Project Overview
This project focuses on cleaning and preprocessing the Titanic dataset as part of the Oasis Infobyte Data Analytics Internship.

The main objective is to identify and handle missing values, check duplicate records, standardize text data, and detect outliers to prepare a clean dataset for further analysis.

## 🎯 Objectives
- Identify missing values in the dataset.
- Handle missing values using suitable techniques.
- Check and remove duplicate records.
- Standardize categorical and text columns.
- Detect outliers using the IQR method.
- Export the cleaned dataset.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset Information
- Dataset: Titanic Train Dataset (`train.csv`)
- Original Rows: 891
- Original Columns: 12

### Missing Values Identified

| Column | Missing Values |
|---|---:|
| Age | 177 |
| Cabin | 687 |
| Embarked | 2 |

## 🔧 Data Cleaning Process

1. **Data Inspection:** Examined dataset structure, data types, and missing values.
2. **Missing Value Treatment:**
   - Age: Filled using median.
   - Cabin: Filled with "Unknown".
   - Embarked: Filled using mode.
3. **Duplicate Handling:** Checked and removed duplicate records.
4. **Text Standardization:** Standardized values in Sex and Embarked columns and removed unnecessary whitespace.
5. **Outlier Detection:** Used the Interquartile Range (IQR) method to identify outliers in numerical columns. Identified outliers were retained because they may represent genuine observations.
6. **Export:** Saved the cleaned dataset as a CSV file.

## 📊 Final Results

- Original Records: 891
- Final Records: 891
- Final Columns: 12
- Missing Values After Cleaning: 0
- Duplicate Rows After Cleaning: 0

## 📁 Project Structure

```text
DataAnalytics-L1-Task3-DataCleaning/
│
├── Data_Cleaning.ipynb
├── train.csv
├── titanic_cleaned.csv
└── README.md
```

## ▶️ How to Run

1. Clone this repository.
2. Open the project folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the notebook:

```bash
jupyter notebook Data_Cleaning.ipynb
```

5. Run all notebook cells.

## ✅ Conclusion
The Titanic dataset was successfully cleaned by handling missing values, checking duplicates, standardizing text data, and detecting outliers. The final dataset contains 891 records and 12 columns with no missing values or duplicate rows.

## 👨‍💻 Internship
**Organization:** Oasis Infobyte  
**Domain:** Data Analytics  
**Task:** Level 1 – Task 3: Data Cleaning

