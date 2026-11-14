# House Price Prediction Using Linear Regression

## Project Overview
This project focuses on predicting house sale prices using Machine Learning and Linear Regression. The project uses the Ames Housing dataset, which contains information about residential properties and their selling prices.

The main objective is to understand the relationship between house features and sale prices, perform Exploratory Data Analysis (EDA), and develop a Linear Regression model to predict house prices.

## Objectives
- Perform data cleaning and preprocessing.
- Analyze house price distributions.
- Identify important features affecting house prices.
- Visualize relationships using graphs and heatmaps.
- Build a Linear Regression model.
- Evaluate model performance using regression metrics.

## Dataset Information
- **Dataset:** Ames Housing Dataset
- **Source:** Kaggle – House Prices: Advanced Regression Techniques
- **Training Records:** 1,460
- **Original Columns:** 81
- **Target Variable:** SalePrice

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## Project Workflow

### 1. Data Loading and Understanding
Loaded the dataset using Pandas and examined its structure, columns, data types and statistical summary.

### 2. Data Cleaning
Identified missing values and handled them using appropriate techniques:
- Filled categorical missing values with `None` where missing indicated an absent property feature.
- Used median imputation for selected numerical columns.
- Used mode imputation for the Electrical column.

### 3. Exploratory Data Analysis (EDA)
Performed:
- SalePrice distribution analysis.
- Boxplot analysis to identify potential outliers.
- Correlation analysis.
- Correlation heatmap visualization.

### 4. Feature Selection
Selected the following six features:
- OverallQual
- GrLivArea
- GarageCars
- TotalBsmtSF
- FullBath
- YearBuilt

### 5. Model Building
Implemented Linear Regression using Scikit-learn.

- Training Data: 80%
- Testing Data: 20%
- Random State: 42

### 6. Model Evaluation
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Performance

| Evaluation Metric | Result |
|---|---:|
| MAE | 25,319.86 |
| MSE | 1,576,962,754.88 |
| RMSE | 39,710.99 |
| R² Score | 0.7944 (79.44%) |

The model explains approximately 79.44% of the variation in house sale prices on the test dataset.

## Visualizations
The project includes the following visualizations:
1. SalePrice Distribution Histogram
2. SalePrice Boxplot
3. Correlation Heatmap
4. Actual vs Predicted Prices
5. Residual Plot

## Project Structure

```text
DataAnalytics-L2-Task1-HousePricePrediction/
│
├── House_Price_Prediction.ipynb
├── train.csv
├── README.md
│
└── output/
    └── charts/
        ├── saleprice_distribution.png
        ├── saleprice_boxplot.png
        ├── correlation_heatmap.png
        ├── actual_vs_predicted.png
        └── residual_plot.png
```

## Conclusion
The Linear Regression model successfully predicts house sale prices using six selected numerical features. The model achieved an R² score of 79.44%, indicating that the selected features explain a substantial portion of the variation in house prices.

This project provided practical experience in data cleaning, exploratory data analysis, feature selection, machine learning model development and performance evaluation.

## Future Improvements
- Apply Ridge and Lasso Regression.
- Experiment with Random Forest Regression.
- Perform additional feature engineering.
- Compare multiple machine learning algorithms.
- Improve prediction accuracy through hyperparameter tuning.

## Author
**Anurag Shukla**

Data Analytics Internship Project – Oasis Infobyte