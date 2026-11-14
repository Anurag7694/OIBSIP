# Task 1: Exploratory Data Analysis – Retail Sales

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Retail Sales dataset as part of the Oasis Infobyte Data Analytics Internship.

The objective is to analyze retail sales data, identify sales trends, understand customer demographics, compare product categories, and generate meaningful business insights through data visualization.

## 🎯 Objectives
- Understand the structure of the retail sales dataset.
- Perform data cleaning and preprocessing.
- Analyze monthly and quarterly sales trends.
- Study customer demographics and purchasing patterns.
- Compare product category performance.
- Explore relationships between numerical variables.
- Generate business insights and recommendations.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset Information
**Dataset:** `retail_sales_dataset.csv`

- Total Records: 1,000
- Total Columns: 9
- Missing Values: 0
- Duplicate Records: 0

### Dataset Columns
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## 🔍 Analysis Performed

### 1. Data Cleaning and Preprocessing
- Checked missing values and duplicate records.
- Converted Date column into datetime format.
- Created Month, Month_Name, and Quarter columns.
- Prepared data for exploratory analysis.

### 2. Sales Analysis
- Monthly revenue analysis.
- Quarterly revenue comparison.
- Identification of highest and lowest performing months.
- Total revenue and average transaction value calculation.

### 3. Customer Demographic Analysis
- Customer age distribution.
- Age group segmentation.
- Gender-based analysis.

### 4. Product Category Analysis
- Category-wise quantity analysis.
- Comparison of Clothing, Electronics, and Beauty categories.

### 5. Correlation Analysis
- Examined relationships between Age, Quantity, Price per Unit, and Total Amount.
- Created a correlation heatmap.

### 6. Data Visualization
Created charts to understand sales performance, customer behavior, and revenue distribution.

## 📊 Key Findings

| Metric | Result |
|---|---:|
| Total Revenue | 456,000 |
| Total Transactions | 1,000 |
| Unique Customers | 1,000 |
| Average Transaction Value | 456 |
| Total Quantity Sold | 2,514 |

### Important Insights
- May recorded the highest monthly revenue.
- September recorded the lowest monthly revenue.
- Q4 had the highest quarterly revenue.
- Clothing recorded the highest quantity sold with 894 units.
- The 46–55 age group had the largest customer count.
- Price per Unit and Total Amount showed a positive correlation of approximately 0.85.

## 💡 Business Recommendations

1. **Inventory Management:** Maintain sufficient inventory for Clothing because it recorded the highest quantity sold.
2. **Seasonal Marketing:** Introduce promotional campaigns during lower-performing months such as September.
3. **Customer Targeting:** Focus customer retention and marketing strategies on the significant 26–55 age groups.
4. **Sales Strategy:** Monitor monthly and quarterly revenue trends to improve business planning.

## 📁 Project Structure

```text
DataAnalytics-L1-Task1-EDA on Retail Sales Data/
│
├── Retail_Sales_EDA.ipynb
├── retail_sales_dataset.csv
├── README.md
└── output/
    └── charts/
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
jupyter notebook Retail_Sales_EDA.ipynb
```

5. Run all notebook cells to reproduce the analysis.

## ⚠️ Dataset Limitation
The dataset does not contain individual product names. Therefore, individual product-level ranking could not be performed. Product category analysis was used instead.

## ✅ Conclusion
The analysis provides useful insights into retail sales performance, customer demographics, and product category trends. Data visualization and statistical analysis help identify business opportunities and support better decision-making.

## 👨‍💻 Internship
**Organization:** Oasis Infobyte  
**Domain:** Data Analytics  
**Task:** Level 1 – Task 1: Exploratory Data Analysis (EDA)

