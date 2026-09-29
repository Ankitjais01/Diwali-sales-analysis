# Diwali-sales-analysis
Diwali Sales EDA using Python — analyzing customer behavior, purchasing power, regional trends, and product category performance.
# Diwali Sales Data Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of Diwali sales data to understand customer purchasing behaviour, identify high-performing customer segments, and discover product and regional sales trends during the festive season.

Using Python and its data analysis and visualization libraries, the project explores how customer demographics, marital status, occupation, geographical location, and product categories relate to sales performance.

## Objectives

- Clean and preprocess the sales dataset.
- Identify and handle missing values and duplicate records.
- Analyze customer purchasing patterns by gender, age group, marital status, and occupation.
- Compare sales orders and spending across states.
- Examine product category performance.
- Derive actionable insights to support business and marketing decisions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
eda-diwali-sales/
├── README.md
├── eda_diwali_sales.ipynb
├── requirements.txt
└── data/
    └── diwali_sales.csv
```

*Note: Update the file and folder names to match your actual repository. Add the dataset only if you have permission to share it.*

## Analysis Workflow

### 1. Data Cleaning and Preprocessing

- Inspected the dataset structure and data types.
- Checked for missing or null values.
- Identified duplicate records.
- Prepared the data for exploratory analysis.

### 2. Exploratory Data Analysis

Analyzed sales data across the following dimensions:

- Gender
- Age group
- Marital status
- State or region
- Occupation
- Product category

Used data visualizations to compare customer counts, order volumes, and spending patterns.

## Key Findings

### Gender
Female customers accounted for more purchases and higher overall purchasing power than male customers in the analyzed dataset.

### Age Group
Customers aged 26–35, particularly female customers, represented a prominent segment in purchasing activity and spending.

### Regional Performance
Uttar Pradesh, Maharashtra, and Karnataka recorded relatively high order volumes and spending in the analyzed data.

### Marital Status
Married female customers showed substantial purchasing activity during the Diwali season.

### Occupation
Customers associated with the IT sector contributed the highest spending and order volume among the occupational groups analyzed.

### Product Categories
Clothing recorded a higher number of orders, while Food generated greater overall spending in the analyzed dataset.

## Business Recommendations

- Develop targeted festive campaigns for high-engagement customer segments.
- Evaluate regional marketing opportunities in Uttar Pradesh, Maharashtra, and Karnataka.
- Explore customer preferences across age groups and marital status.
- Investigate the spending patterns of IT-sector customers.
- Consider category-specific promotions based on order volume and total sales value.

These recommendations should be validated against margins, customer acquisition costs, and additional business data before implementation.

## Installation

### Prerequisites

Install Python 3 and Jupyter Notebook.

### Step 1: Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/eda-diwali-sales.git
cd eda-diwali-sales
```

Replace YOUR_USERNAME with your GitHub username and update the repository URL if necessary.

### Step 2: Install dependencies

```bash
pip install -r requirements.txt
```

Alternatively, install the libraries directly:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `eda_diwali_sales.ipynb` and run the cells from top to bottom.

## Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

## Limitations

- Findings describe the dataset analyzed and may not represent all Diwali shoppers.
- Sales totals and order counts depend on the dataset's definitions and preprocessing.
- The analysis identifies patterns and associations; it does not establish causal relationships.

## Future Improvements

- Add interactive sales dashboards using Power BI or Tableau.
- Perform statistical analysis of customer segments.
- Analyze product-level revenue and profitability if those fields are available.
- Build customer segmentation models using machine learning.
- Develop a sales forecasting model using suitable historical data.

## Author

**Ankit Kumar Jaiswal**

Data Analysis | Python | Exploratory Data Analysis

## License

Add a suitable open-source license if you intend to distribute this project publicly. Ensure you have permission to share the dataset and comply with its terms of use.
