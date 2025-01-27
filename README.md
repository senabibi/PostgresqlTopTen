# Retail Sales Data Analysis

<div align="center">
  <a href="https://github.com/senabibi/PostgresqlTopTen">
    <img src="https://files.oaiusercontent.com/file-GqSgx5HjCtzGcoYL7R9BVQ?se=2025-01-27T11%3A57%3A31Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D099351d8-a03b-4ba4-8a47-4d2529dac3d7.webp&sig=9BL2kAjLroUgApEZ29abUaC9hVJofIqBl7t8ed0Gc3Y%3D" alt="Logo" width="500" height="400">
  </a>
  <h3 align="center">Retail Sales Data Analysis</h3>
  <p align="center">
    A comprehensive SQL project designed to analyze retail sales data and derive actionable business insights. The project includes database creation, data cleaning, exploratory data analysis (EDA), and the development of business-critical SQL queries.
    <br />
    <a href="https://github.com/senabibi/PostgresqlTopTen"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/senabibi/PostgresqlTopTen">View Demo</a>
    ·
    <a href="https://github.com/senabibi/PostgresqlTopTen/issues">Report Bug</a>
    ·
    <a href="https://github.com/senabibi/PostgresqlTopTen/issues">Request Feature</a>
  </p>
</div>

---

## Table of Contents

1. [About The Project](#about-the-project)
   - [Built With](#built-with)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [Usage](#usage)
4. [Roadmap](#roadmap)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)
8. [Acknowledgments](#acknowledgments)

---

## About The Project

The **Retail Sales Data Analysis** project highlights the practical application of SQL in analyzing and deriving actionable insights from retail sales data. Designed for professionals and aspiring data analysts, this project offers hands-on experience in working with structured datasets, performing exploratory data analysis (EDA), and answering business-critical questions. 

The dataset is inspired by real-world retail environments, featuring detailed transaction-level data. Key fields include transaction details, customer demographics, sales categories, and financial metrics, making it an ideal simulation platform for business intelligence tasks. 

---

## Key Features

This project demonstrates how to effectively utilize SQL in analyzing retail sales data and solving business challenges. The key components of the project include:

1. **Database Creation and Setup**: 
   - Design and populate a robust retail sales database, including transactional and demographic data, to enable detailed analysis.
   
2. **Data Cleaning and Preparation**: 
   - Identify and handle missing, null, or inconsistent values to ensure data quality and reliability.

3. **Exploratory Data Analysis (EDA)**: 
   - Discover patterns and trends in sales data, such as customer behavior, category performance, and revenue distribution.

4. **Business Insights Generation**:
   - Use SQL queries to answer critical business questions, including:
     - Which product categories drive the most revenue?
     - How do customer age groups influence purchasing behavior?
     - What are the peak sales times and days?

---

## Built With
This project employs industry-standard tools and technologies to deliver efficient and professional results. SQL serves as the core querying language for data manipulation and analysis, while PostgreSQL is used as the relational database management system (RDBMS) to handle large-scale transactional data. Markdown is utilized for detailed documentation, ensuring that the project is presented in a clear and organized manner.

By integrating these features and tools, this project simulates the challenges and requirements of real-world retail data analysis tasks, highlighting the critical role of SQL in data-driven decision-making and business intelligence.
- **SQL**: The core language for database manipulation and analysis.
- **PostgreSQL**: A reliable and powerful relational database management system (RDBMS) for handling large-scale datasets.
- **Markdown**: Used for project documentation and presentation to ensure clarity and organization.

---

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

# Priority Queue and Retail Sales Analysis

This project involves implementing a Priority Queue for analyzing retail sales data stored in a PostgreSQL database. Below are the steps to set up and use the project.

## Installation


### 1. PostgreSQL Installation
Download and install PostgreSQL from the [official PostgreSQL website](https://www.postgresql.org/download/).

Once installed, configure the PostgreSQL database to integrate with the project files.

### 2. Database Setup

Create the required databases using the following commands in your PostgreSQL environment:

```sql
CREATE DATABASE sql_project_p2;
CREATE DATABASE p1_retail_db;

```

Set up the retail_sales table by running the following SQL commands:
```
DROP TABLE IF EXISTS retail_sales;

CREATE TABLE retail_sales (
    transactions_id INT PRIMARY KEY,
    sale_date DATE,  
    sale_time TIME,
    customer_id INT,  
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,  
    cogs FLOAT,
    total_sale FLOAT
);

```

## Usage

<div align="center">
    <img src="https://github.com/senabibi/PostgresqlTopTen/blob/main/POST.png" alt="Post ERD">
</div>

To use the Priority Graph project and set up your work routine, follow these steps:

### 1. **PostgreSQL Installation:**
   - Ensure that PostgreSQL is installed on your system. If it's not already installed, you can download it from the [official PostgreSQL website](https://www.postgresql.org/download/).

### 2. **Creating the Database:**
   - Run the provided SQL script to set up the `p1_retail_db` database. The database will include the necessary tables and data for the retail sales analysis.

### 3. **Menu-Driven Interface:**
   - Once the database is set up, a menu-driven interface will allow you to perform various queries related to retail sales data analysis.

### 4. **Exploratory Data Analysis (EDA):**
   - Perform EDA to understand the dataset, checking for null values, missing data, and analyzing different columns using SQL queries.

### 5. **Running Business Queries:**
   - Use the provided SQL queries to analyze specific business questions, such as:
     - Retrieve sales made on a specific date.
     - Find transactions for a specific category in a given month.
     - Calculate total sales by category, average age of customers, and more.

### 6. **Exiting the Interface:**
   - After completing the analysis, you can exit the interface to end the session.

Feel free to explore and interact with the Retail Sales Analysis project, answering business questions through SQL queries and analyzing the data.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Roadmap

- [ ] **PostgreSQL Setup:** Ensure that you have PostgreSQL installed and configured on your system for project development.
- [ ] **Familiarize with SQL Logic:** Get acquainted with SQL concepts like SELECT, JOIN, GROUP BY, and aggregate functions used in this project.
- [ ] **Database Setup:** Run the provided SQL scripts to set up the `p1_retail_db` and `retail_sales` table.
- [ ] **Exploratory Data Analysis (EDA):** Perform EDA queries to explore the data, check for null values, and assess the dataset's structure.
- [ ] **Answer Business Queries:** Use SQL to answer specific business-related questions about the dataset.
- [ ] **Test and Debug:** Ensure that each query works as expected and that any issues are addressed during testing.
- [ ] **Documentation:** Document the project, providing an explanation of the queries used and insights derived from the analysis.

This roadmap outlines the key steps to understand, interact with, and test the Retail Sales Analysis project. Follow these steps to explore the capabilities of the database and gain insights into the sales data.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this project better, please fork the repository and create a pull request. You can also simply open an issue with the "enhancement" tag. Don't forget to give the project a star! Thanks again!

### Steps to Contribute:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Contact

Nursena Bitirgen - [LinkedIn](https://www.linkedin.com/in/nursena-bitirgen-5743341b9/)

Project Link: [https://github.com/senabibi/PriorityQueue](https://github.com/senabibi/PriorityQueue)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Acknowledgments

The development of the Retail Sales Analysis project was made possible thanks to various resources and skills:

* **PostgreSQL Knowledge:** Special gratitude to PostgreSQL for providing a robust and scalable database management system.
* **SQL Proficiency:** Acknowledgment for the ability to craft efficient SQL queries to analyze large datasets and answer business questions.
* **Data Cleaning and Analysis:** Appreciation for the data cleaning methods, including handling null values and performing exploratory data analysis.
* **Business Insights:** Recognition for deriving actionable business insights based on the sales data, such as identifying high-value customers and sales trends.
* **Testing and Debugging:** Recognition for testing SQL queries to ensure accuracy and performance.
* **Documentation:** Gratitude for creating comprehensive documentation that helps users understand and utilize the features of the project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## How to Use

1. **Clone the Repository:** Clone this project repository from GitHub.
2. **Set Up the Database:** Run the SQL scripts provided in the `database_setup.sql` file to create and populate the database.
3. **Run the Queries:** Use the SQL queries provided in the `analysis_queries.sql` file to perform your analysis.

### Example Queries
1. Retrieve sales for a specific date:

```sql
SELECT *
FROM retail_sales
WHERE sale_date = '2022-11-05';
```

2.Find transactions for the 'Clothing' category and quantity sold > 4 in Nov-2022:

```
SELECT * 
FROM retail_sales
WHERE category = 'Clothing'
  AND TO_CHAR(sale_date, 'YYYY-MM') = '2022-11'
  AND quantity >= 4;

```
3.Calculate the total sales by category:
```
SELECT category,
       SUM(total_sale) as net_sale,
       COUNT(*) as total_orders
FROM retail_sales
GROUP BY category;

```



