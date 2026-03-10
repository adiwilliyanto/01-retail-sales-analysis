# 01-retail-sales-analysis
End-to-end retail sales data analysis project using Python, Pandas, and Matplotlib.  This project performs data cleaning, exploratory data analysis (EDA), and visualization to identify sales trends and generate business insights.

Retail Sales Data Analysis
📌 Project Overview

This project analyzes retail transaction data to uncover sales trends, profit performance, and business insights.
The analysis focuses on identifying patterns in yearly sales performance and understanding how retail sales evolve over time.

The project demonstrates the data analysis workflow, including data cleaning, exploratory data analysis (EDA), and data visualization.

🎯 Project Objectives

The main objectives of this analysis are:

Analyze total sales trends over time

Understand profit performance across years

Identify patterns in retail sales data

Generate business insights that can support decision making

🛠 Tools & Technologies

The tools used in this project include:

Python

Pandas → data manipulation & analysis

Matplotlib → data visualization

Jupyter Notebook → analysis environment

📂 Dataset

The dataset used in this project contains retail transaction data with features such as:

Order ID

Order Date

Customer information

Product category

Sales

Profit

Quantity

This dataset is commonly used for data analysis practice and business insight generation.

🔎 Data Analysis Process
1️⃣ Data Understanding

The first step is exploring the dataset to understand its structure and variables.

Example:

df.info()
df.head()

This step helps identify:

data types

missing values

dataset size

2️⃣ Data Cleaning

Data cleaning ensures the dataset is ready for analysis.

Examples of tasks performed:

converting date columns

checking missing values

validating numeric columns

3️⃣ Exploratory Data Analysis (EDA)

EDA is performed to discover patterns and trends in the data.

Key analysis includes:

Total sales per year

Sales distribution

Profit trends

Example visualization:

plt.figure(figsize=(8,5))
plt.plot(sales_per_year['year'], sales_per_year['sales'], marker='o')
plt.title("Total Sales per Year")
plt.xlabel("Year")
plt.ylabel("Total Sales")
plt.show()
📈 Key Insights

Some insights from the analysis:

Retail sales show a consistent upward trend across the years

Sales growth indicates increasing market demand

Business performance improves as total sales increase

These insights can help businesses evaluate sales growth and strategic planning.

📊 Example Visualization

Example chart produced in this project:

Total Sales per Year

Profit Trends

Sales Distribution

These visualizations help communicate data insights clearly.

🚀 Future Improvements

Possible improvements for this project:

Add interactive visualization using Plotly

Perform customer segmentation

Build sales forecasting model

Create dashboard using Power BI or Tableau

👨‍💻 Author

Adi Williyanto

Aspiring Data Analyst | Data Science Enthusiast

Skills:

Python

Data Analysis

Data Visualization

Exploratory Data Analysis (EDA)
