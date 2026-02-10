# 📊 Customer Behavior Analysis – Data Analytics Project
## 📌 Overview

This project focuses on analyzing customer behavior to uncover insights related to purchasing patterns, revenue distribution, and demographic trends. The workflow covers the complete data analytics lifecycle — from data loading and cleaning in Python, to querying structured data using PostgreSQL, and finally visualizing insights through an interactive Power BI dashboard.

The goal of this project is to demonstrate strong fundamentals in data analysis, SQL, and business-focused visualization.

## 📂 Dataset

The dataset contains customer-level transactional and demographic information.

**Key attributes include**:
  
- Customer details (age group, gender, subscription status)
  
- Product categories
  
- Purchase amounts

- Review ratings

- Shipping types


## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)

- **PostgreSQL** (SQL queries and data analysis)

- **Power BI** (Dashboard & data visualization)

- **Jupyter Notebook**

## 🔄 Project Workflow

1)**Data Loading**

- Imported the dataset into Python using Pandas.

- Initial inspection of rows, columns, and data types.

2)**Exploratory Data Analysis (EDA)**

- Analyzed customer distribution, revenue trends, and category-wise performance.

- Identified missing values, outliers, and data inconsistencies.

- Visualized key patterns using charts and plots.

3)**Data Cleaning & Preprocessing**

- Handled missing values using appropriate statistical techniques.

- Standardized column formats and categorical values.

- Created derived features such as age groups.

4)**SQL Analysis (PostgreSQL)**

- Loaded cleaned data into PostgreSQL.

- Wrote SQL queries to analyze:
  * Revenue by category

  * Sales by age group

  * Subscription vs non-subscription behavior

  * Average purchase value and ratings

5)**Power BI Dashboard**

- Connected PostgreSQL data to Power BI.

- Built interactive visuals with slicers and filters.

- Designed a clean, business-ready dashboard layout.

# 📈 Dashboard Overview

![alt-text](

The Power BI dashboard provides a comprehensive view of customer behavior:

- Total number of customers

- Average purchase amount

- Average review rating

- Subscription vs non-subscription breakdown

- Revenue and sales by product category

- Revenue and sales by age group

- Interactive filters for gender, category, subscription status, and shipping type

**📷 Dashboard Preview:**


# 📊 Key Results & Insights

- Clothing is the top-performing category in both revenue and sales volume.

- Young adults and middle-aged customers contribute the highest revenue.

- A majority of customers are non-subscribers, indicating potential growth opportunities.

- Average customer satisfaction remains positive with a rating of 3.75.

- Subscription status shows a noticeable impact on purchasing behavior.

# ▶️ How to Run This Project

**Clone the repository:**

git clone https://github.com/Ravikumar0311/customer-behavior-analysis.git

**Install required Python libraries:**

     pip install pandas numpy matplotlib seaborn psycopg2 sqlalchemy

**Run the Jupyter Notebook to:**

- Load the dataset

- Perform EDA

- Clean and preprocess data

- Import the cleaned dataset into PostgreSQL and execute SQL queries.

- Open the Power BI (.pbix) file and refresh the data connection to view the dashboard.

# 🚀 Conclusion

This project demonstrates end-to-end data analytics skills, combining Python, SQL, and Power BI to turn raw data into meaningful business insights. It reflects real-world analytics workflows and showcases the ability to communicate data-driven findings effectively.
