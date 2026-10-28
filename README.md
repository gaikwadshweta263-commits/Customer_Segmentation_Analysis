# Customer Segmentation Analysis

**End-to-End Data Analytics Project using Python**

# Project Overview

- This project focuses on analyzing customer and transaction data to understand customer demographics, spending patterns, purchasing behaviour, and product performance.
- It demonstrates an end-to-end Data Analytics workflow, including data cleaning, missing value treatment, exploratory data analysis (EDA), data visualization, and business insight generation using Python.
- The project uses two CSV datasets: `customers.csv` and `transactions.csv` to explore customer characteristics and transaction trends.

# Project Objectives

- Clean and preprocess raw customer and transaction datasets.
- Handle missing values using appropriate methods.
- Remove duplicate records and validate data types.
- Perform Exploratory Data Analysis (EDA).
- Visualize data using Matplotlib and Seaborn.
- Analyze customer spending and purchasing frequency.
- Identify high-value customers and popular products.
- Generate actionable business insights.

# Skills & Tools Used (ATS Optimized)

- Python
- NumPy
- Pandas
- Data Cleaning & Preprocessing
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Customer Analytics
- Transaction Analysis
- Business Analytics

# Dataset Information

**Dataset Files:**
1. `customers.csv`
2. `transactions.csv`

### 1. Customers Dataset

**Key Columns:**
- `Customer_ID` – Customer identification number.
- `Customer_Name` – Customer name.
- `Gender` – Gender of the customer.
- `Age` – Customer age.
- `Age_Group` – Customer age category.
- `Date_of_Birth` – Customer date of birth.
- `Email` – Customer email address.
- `Phone` – Customer contact number.
- `City` – Customer city.
- `State` – Customer state.

### 2. Transactions Dataset

**Key Columns:**
- `TransactionID` – Unique transaction identifier.
- `CustomerID` – Customer identifier recorded in the transaction.
- `ProductID` – Product identifier.
- `TransactionDate` – Date of the transaction.
- `Quantity` – Quantity purchased.
- `TotalValue` – Total transaction value.
- `Price` – Product price.

# Project Workflow

## Data Loading & Understanding

- Loaded both CSV datasets using Pandas.
- Checked dataset shape, column names, and data types.
- Displayed sample records using `head()`.
- Examined summary statistics using `describe()`.
- Identified missing values and duplicate records.

## Data Cleaning & Preprocessing

- Removed unnecessary index columns, such as `Unnamed: 0`, if present.
- Standardized text values in columns such as Gender, City, and State.
- Converted numerical columns to appropriate data types.
- Converted date columns into datetime format.
- Removed duplicate records where applicable.

## Missing Value Treatment

**Missing values were checked in both datasets.**

**Methods Used:**
- Missing values in `Quantity` were handled using median imputation.
- Missing customer identifiers were not guessed or replaced with fabricated values.
- Remaining missing values were reviewed before analysis.

## Exploratory Data Analysis (EDA)

**EDA was performed using:**
1. Histograms
2. Count plots
3. Bar charts
4. Scatter plots
5. Correlation heatmaps
6. Line charts

**Key Analysis Areas:**
- Customer age distribution.
- Gender distribution.
- Customer distribution by city and state.
- Transaction value distribution.
- Relationship between quantity, price, and transaction value.
- Product performance based on transaction value.
- Monthly transaction trends.
- Highest-spending customers.
- Customers with the highest transaction frequency.

## Customer Spending Analysis

- Calculated total spending for each transaction customer identifier.
- Identified customers with the highest recorded spending.
- Analyzed transaction frequency to understand purchasing activity.
- Compared customer spending patterns to identify potentially valuable customer groups.

## Product & Transaction Analysis

- Identified products with the highest total transaction value.
- Analyzed the relationship between quantity, price, and total value.
- Examined transaction trends over time.
- Used visualizations to understand purchasing patterns.

## Data Visualization

- Created visualizations using Matplotlib and Seaborn.
- Used charts to present customer demographics and transaction patterns.
- Compared customer spending, product performance, and monthly trends.
- Presented analytical findings in a clear and understandable format.

# Key Business Insights

1. Customer age and gender distributions help describe the customer base.
2. Spending analysis identifies customer identifiers associated with high transaction values.
3. Transaction frequency helps identify frequent purchasers.
4. Product transaction values help highlight products contributing the most recorded sales value.
5. Monthly transaction trends reveal changes in transaction activity over time.
6. City and state analysis identifies locations with larger customer populations.
7. Quantity and price analysis helps explain transaction value patterns.

# Business Recommendations

1. Develop targeted marketing campaigns for different customer groups.
2. Create loyalty programs for frequent and high-spending customers.
3. Use product performance analysis to support promotional and sales strategies.
4. Study monthly transaction trends to plan campaigns and inventory.
5. Use regional customer distribution to guide location-specific marketing.
6. Continue collecting accurate customer identifiers to improve customer-level analysis.

# Limitations & Assumptions

**Limitations:**

- Missing values may affect some analyses.
- Results depend on the accuracy and completeness of the supplied datasets.
- Customer-level findings are based on the identifiers available in the transaction dataset.
- Customer identifiers in the two files use different formats; their mapping must be validated before combining the datasets.
- The analysis is descriptive and does not include predictive machine learning.

**Assumptions:**

- The supplied datasets represent the customer and transaction records available for analysis.
- `TotalValue` represents the recorded transaction value.
- Transaction dates are interpreted after conversion to datetime format.
- Findings describe the available data and should not automatically be treated as proof of future customer behaviour.

# Final Conclusion

This project successfully transformed raw customer and transaction datasets into clean, structured, and meaningful data using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

By performing data cleaning, missing value treatment, duplicate removal, exploratory data analysis, and visualization, useful insights were obtained about customer demographics, spending patterns, transaction frequency, product performance, and purchasing trends.

These insights can help businesses understand customer behaviour, identify valuable customer groups, improve marketing strategies, and make informed business decisions.

# Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook
- **Data Format:** CSV

# Project Type

**Python Data Analytics | Exploratory Data Analysis | Customer & Transaction Analysis**
