# data-analysis-with-sql
A growing SQL portfolio built with MySQL, covering data cleaning techniques and exploratory analysis on global layoff trends and employee datasets.
SQL Data Analysis Portfolio
A hands-on collection of SQL projects built to demonstrate real-world skills in data cleaning, database querying, and exploratory analysis all powered by MySQL.

What's Inside

1. Global Layoffs: Data Cleaning & Exploratory Analysis
About This Project
This project takes a raw, messy dataset of global company layoffs and transforms it into something clean and meaningful. The goal was to dig into the data, fix what's broken, and pull out insights that actually tell a story about how the job market shifted over recent years.
Skills Used

Data Cleaning & Standardization
Removing Duplicates
Handling Null & Missing Values
Data Transformation
Window Functions
CTEs (Common Table Expressions)
Exploratory Data Analysis (EDA)
Deriving Business Insights

What the Data Revealed

Total layoffs recorded: 386,379
Biggest companies involved: Amazon, Google, Meta, Salesforce
Most affected industry: Consumer
Most affected country: United States
Worst year for layoffs: 2022

Project Files

layoffs.csv
layoffs_adeen.sql


2. Parks & Recreation: Employee Database Analysis
About This Project
Using a fictional Parks & Recreation employee database, this project covers everything from basic SELECT queries to stored procedures and triggers. It's a full walkthrough of SQL from the ground up — great for showing both foundational and advanced skills in one place.
Skills Used

SELECT, WHERE, ORDER BY, GROUP BY
Aggregate Functions (SUM, AVG, COUNT)
JOINS (Inner, Left, Right)
CASE Statements
Subqueries
CTEs
Temporary Tables
Stored Procedures
Triggers
Window Functions & Ranking

Analysis Done

Broke down employee demographics by age and gender
Analyzed salary ranges across departments
Ranked employees by compensation
Summarized workforce structure at the department level
Calculated average pay and headcount per team

Database Tables
employee_demographics

employee_id
first_name
last_name
gender
birth_date
age

employee_salary

employee_id
occupation
salary
dept_id

parks_departments

department_id
department_name

What I Learned
Working through this project sharpened my understanding of how relational databases are structured, how tables connect to each other, and how to write clean, efficient queries that scale. It also gave me hands-on practice with advanced SQL features that are commonly used in real analyst roles.

Tools & Technologies

MySQL
MySQL Workbench
SQL
CSV Data Sources


SQL Topics Covered

Data Cleaning & Transformation
Joins & Relationships
CTEs & Subqueries
Window & Ranking Functions
Aggregate Functions
Stored Procedures & Triggers
Temporary Tables & Views

Folder Structure

Folder Structure
SQL-Projects/
│
├── Global-Layoffs-Project/
│   ├── layoffs.csv
│   ├── layoffs_adeen.sql
│   └── README.md
│
├── Parks-and-Recreation-Project/
│   ├── parks_and_recreation.sql
│   ├── parks_and_recreation_adeen.sql
│   └── README.md
│
└── README.md

Author
Adeen
Aspiring Data Analyst with a strong interest in SQL, Tableau, Power BI, and turning raw data into clear, visual stories.
