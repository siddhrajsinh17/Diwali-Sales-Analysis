# 🪔 Diwali Sales Analysis

An Exploratory Data Analysis (EDA) project using Python to understand customer purchasing patterns and sales performance during Diwali.

## 📌 Project Overview

This project analyzes a Diwali sales dataset using Python and focuses on data cleaning, exploratory analysis, customer segmentation, and product/sales analysis.

The notebook starts with **11,251 records and 15 columns**. During data cleaning, two blank/unrelated columns (`Status` and `unnamed1`) are removed, 12 missing values in `Amount` are handled, and `Amount` is converted to an integer type. The cleaned dataset contains **11,239 rows and 13 columns**.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### Data Cleaning
- Imported the CSV dataset using Pandas
- Checked dataset shape and information
- Identified missing values
- Removed blank/unrelated columns
- Removed rows with missing values
- Converted `Amount` to integer
- Used descriptive statistics for numerical columns

### Exploratory Data Analysis

The project explores:

- Gender-wise purchasing behavior
- Age-group-wise sales
- State-wise orders and sales
- Marital-status analysis
- Occupation-wise purchasing behavior
- Product-category analysis
- Top-selling products

## 💡 Key Insights

The analysis in the notebook indicates:

- Female customers make up a larger share of buyers and have higher purchasing power than male customers.
- The **26–35 age group** is the major buyer segment, particularly female customers.
- Married women are identified as an important customer segment with high purchasing power.
- Buyers working in **IT, Healthcare, and Aviation** are prominent in the analyzed data.
- Product and product-category analysis is used to identify high-performing products and support sales/inventory decisions.

## 📊 Dataset Columns

The cleaned dataset contains:

`User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`

## 📁 Project Structure

```text
Diwali-Sales-Analysis/
│
├── Diwali_Sales_Analysis.ipynb
├── Diwali Sales Data.csv
├── README.md
└── requirements.txt
```

> **Note:** The notebook expects the dataset file to be named `Diwali Sales Data.csv` and to be in the same directory as the notebook.

## ▶️ How to Run

1. Clone or download this repository.
2. Make sure `Diwali Sales Data.csv` is in the project folder.
3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook Diwali_Sales_Analysis.ipynb
```

5. Run the cells from top to bottom.

## 🎯 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Customer segmentation
- Sales analysis
- Business insight generation
- Python data analysis with Pandas

## 👤 Author

**Siddharajsinh Chavda**

BCA Student | Aspiring Data Analyst

---

⭐ If you find this project useful, consider giving the repository a star.
