# Diwali Sales Insights: Customer & Retail Analytics Using Python

An Exploratory Data Analysis (EDA) project focused on understanding customer purchasing behaviour, sales patterns, and product performance during the Diwali season using Python.

## Project Overview

The **Diwali Sales Insights** project focuses on analyzing retail sales data to understand customer behaviour and identify meaningful purchasing patterns during the Diwali season.

In this project, I explored customer demographics, product categories, occupations, geographical locations, and order information to understand different aspects of sales performance.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, I performed data cleaning, data manipulation, exploratory data analysis (EDA), and data visualization to extract useful business insights.

## Project Notebook

The complete project, including Python code, data cleaning steps, exploratory analysis, and visualizations, is available on Google Colab.

**[🚀 Open Project in Google Colab](https://colab.research.google.com/drive/1uhP18puKdwS956XwhXkY9fOWeCYkCXf8?usp=sharing)**

## Project Objectives

- Analyze customer purchasing behaviour during the Diwali season.
- Understand purchasing patterns across different age groups and genders.
- Identify states contributing significantly to overall sales.
- Explore customer distribution across different occupations.
- Analyze product category performance.
- Identify popular products based on order frequency.
- Extract meaningful insights through data visualization.

## Dataset Description

The dataset contains customer details, product information, order quantities, and purchase amounts.

**Dataset Statistics**

| Description            | Details |
| ---------------------- | ------- |
| Original Records       | 11,251  |
| Original Columns       | 15      |
| Records After Cleaning | 11,239  |
| Columns After Cleaning | 13      |

**Important Dataset Columns**

| Column           | Description                    |
| ---------------- | ------------------------------ |
| User_ID          | Customer identification number |
| Cust_name        | Customer name                  |
| Product_ID       | Product identification number  |
| Gender           | Customer gender                |
| Age Group        | Customer age category          |
| Age              | Customer age                   |
| Marital_Status   | Marital status indicator       |
| State            | Customer's state               |
| Zone             | Geographical zone              |
| Occupation       | Customer occupation            |
| Product_Category | Product category               |
| Orders           | Number of orders               |
| Amount           | Purchase amount                |

## Technologies & Libraries Used

| Technology   | Purpose                            |
| ------------ | ---------------------------------- |
| Python       | Programming and data analysis      |
| Google Colab | Notebook development and execution |
| NumPy        | Numerical operations               |
| Pandas       | Data cleaning and manipulation     |
| Matplotlib   | Data visualization                 |
| Seaborn      | Statistical visualization          |

## Project Workflow

### 1. Data Loading

- Imported the required Python libraries.
- Loaded the CSV dataset using Pandas.
- Displayed initial records to understand the dataset.

### 2. Data Inspection

Used different Pandas functions to understand the dataset:

- `head()` – View initial records.
- `info()` – Check column names and data types.
- `describe()` – Generate statistical summaries.
- `isnull().sum()` – Identify missing values.

### 3. Data Cleaning & Preprocessing

Performed the following operations:

- Removed unnecessary columns such as `Status` and `unnamed1`.
- Identified missing values.
- Removed 12 records containing missing values in the Amount column.
- Converted the Amount column from float to integer.
- Prepared the cleaned dataset for further analysis.

### 4. Exploratory Data Analysis (EDA)

Performed analysis across multiple customer and product dimensions.

**Gender Analysis**

- Compared male and female customer records.
- Analyzed total purchase amounts by gender.

**Age Group Analysis**

- Examined customer distribution across age groups.
- Compared purchase amounts across different age categories.

**State Analysis**

- Identified the top 10 states based on order counts.
- Analyzed the top 10 states based on total purchase amount.

**Marital Status Analysis**

- Explored customer distribution based on marital status.
- Compared purchase amounts across gender and marital status.

**Occupation Analysis**

- Analyzed customer distribution across occupations.
- Identified occupations contributing significantly to sales.

**Product Category Analysis**

- Compared different product categories.
- Identified the top 10 categories based on total purchase amount.

**Product Analysis**

- Identified the top 10 products based on order frequency.
- Used grouping and sorting techniques to explore product performance.

## Key Insights & Findings

Based on the exploratory data analysis, the following observations were identified:

1. **Gender:** Female customers represent a larger share of customer records and contribute more to the total purchase amount.

2. **Age Group:** Customers belonging to the 26–35 age group contribute the highest purchase amount.

3. **State:** Uttar Pradesh, Maharashtra, and Karnataka are among the leading states in terms of total purchase amount.

4. **Occupation:** IT, Healthcare, and Aviation are among the occupations contributing significantly to overall purchases.

5. **Product Categories:** Food records the highest total purchase amount, followed by other major categories such as Clothing & Apparel and Electronics & Gadgets.

6. **Product Performance:** Product-level analysis helps identify frequently ordered products and understand purchasing preferences.

## Conclusion

This project provided practical experience in using Python for real-world sales data analysis.

By performing data cleaning, exploratory data analysis, and visualization, I explored customer purchasing behaviour and identified important patterns across different customer segments, geographical locations, occupations, and product categories.

The analysis helped me understand how data can be used to identify customer preferences, explore sales trends, and generate useful business insights.

Overall, this project strengthened my understanding of Python, Pandas, NumPy, data manipulation, grouping, aggregation, and data visualization techniques.

## How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/your-username/Diwali-Sales-Insights-Python.git
```

**2. Navigate to the project directory**

```bash
cd Diwali-Sales-Insights-Python
```

**3. Install the required libraries**

```bash
pip install numpy pandas matplotlib seaborn
```

**4. Open the notebook**

Open the `.ipynb` file using Google Colab or Jupyter Notebook.

**5. Load the dataset**

Make sure the CSV dataset is available in your working environment.

**6. Run the notebook**

Execute the notebook cells to perform data cleaning, exploratory analysis, and visualization.

## Author

**Ishan Vardan**

Computer Science and Data Analytics Student

Interested in Python, Data Analytics, Exploratory Data Analysis, and Data Visualization.

---

*This project represents my hands-on learning and practical implementation of Python-based data analysis techniques.*
