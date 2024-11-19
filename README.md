

![EDA](https://github.com/user-attachments/assets/deca5cfa-c13b-482f-80fb-55cbdb80a5f9)

# Diwali Sales Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset containing sales data for Diwali. The goal is to extract valuable insights into customer behavior, product performance, and overall sales trends.

## Dataset Overview

The dataset used in this project contains information about sales during the Diwali festival. It includes customer demographic details, product categories, order details, and sales amounts.

Key dataset details:
- **Size:** Includes information about thousands of transactions.
- **Attributes:** Customer demographics, product categories, sales amounts, states, and other key variables.

---

## Steps Performed

1. **Data Loading and Cleaning**
   - Loaded the dataset using `pandas`.
   - Inspected the dataset's structure using `.info()` and `.head()`.
   - Removed irrelevant columns like `Status` and `Unnamed1`.
   - Handled missing values by dropping rows with null data.
   - Converted columns like `Amount` to the appropriate data type.

2. **Data Exploration**
   - Renamed columns for better readability.
   - Generated descriptive statistics using `.describe()`.

3. **Data Visualization**
   - **Gender Analysis:**
     - Visualized purchase behavior across genders using bar plots.
     - Calculated total sales for each gender.
   - **Age Group Analysis:**
     - Analyzed sales and orders across different age groups.
     - Highlighted gender distribution in each age group.
   - **State-Wise Sales:**
     - Identified top-performing states based on orders and sales amounts.
   - **Marital Status Analysis:**
     - Analyzed sales trends for marital status, further divided by gender.
   - **Occupation Analysis:**
     - Explored sales distribution across occupations.
   - **Product Category Analysis:**
     - Investigated the sales performance of various product categories.
   - **Top Products:**
     - Identified top-selling products based on the number of orders.

---

## Insights

1. **Gender Trends:**
   - Male customers contributed more to the total sales amount compared to females.
   - Significant sales differences observed in product preferences between genders.

2. **Age Group Trends:**
   - The age group with the highest sales contribution was identified.
   - Younger customers showed higher purchasing trends during Diwali.

3. **State Performance:**
   - The top-performing states in terms of orders and revenue were visualized.
   - Regional sales trends were analyzed for business opportunities.

4. **Product Insights:**
   - Certain product categories and specific products showed the highest demand.
   - Insights into customer preferences helped understand market trends.

5. **Occupation Trends:**
   - The most significant contributions came from specific occupational groups.
   - Targeted marketing strategies can be inferred from these insights.

---

## Libraries Used

- **Pandas:** For data manipulation and cleaning.
- **NumPy:** For numerical computations.
- **Matplotlib:** For creating static visualizations.
- **Seaborn:** For creating detailed and aesthetic statistical visualizations.

---

## Visualizations

The project includes various visualizations to better understand the data:
- **Bar Plots:** For categorical data analysis.
- **Count Plots:** To visualize frequency distributions.
- **Grouped Bar Charts:** For comparing sales trends across multiple dimensions.

---

## Usage

To run this project:
1. Clone the repository.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn



Future Work
Implement advanced statistical analyses or machine learning models to predict sales trends.
Explore deeper segmentation of customer demographics.
Automate the generation of dashboards for real-time insights.
