# MY-LITA-DATA-ANALYSIS-TRAINING

## Table of content

- Project overview
- Foundation of data
- Data cleaning and presentation
- Tools used and understanding of each tools
- HR data and presentation.
  
  
### PROJECT OVERVIEW
This project aims at documenting all i have learnt so far on the basis of Data Analyisis. The understanding of Data, Data sources, Entry and the different types of tools used in DAta Analysis.


### FOUNDATION OF DATA
1. Data Literacy: Understanding the fundamentals of data, its types, sources, and applications. Data literacy encompasses:

- Data interpretation
- Data visualization
- Data communication

2. Data Generation: Sources and methods of data creation:

- Transactions (e.g., sales, payments)
- Social media
- Surveys


3. Data Structure: Organizing data for efficient storage and retrieval:

- Relational databases (tables, rows, columns)
- NoSQL databases (key-value, document-oriented)
- Data warehousing
- Data modeling

4. Data Storage: Storing data securely and efficiently:

- Relational databases (RDBMS)
- NoSQL databases
- Cloud storage (e.g., AWS S3)
- Data warehousing

5. Data Analysis: Examining data to extract insights:

- Descriptive analytics (summary stats)
- Diagnostic analytics (cause-and-effect)
- Predictive analytics (forecasting)
- Prescriptive analytics (recommendations)

6. Statistics: Mathematical techniques for data analysis:

- Descriptive statistics (mean, median, mode)
- Inferential statistics (hypothesis testing)
- Regression analysis
- Time series analysis

7. Data-Driven Decision Making: Using data to inform business decisions:

- Identifying key performance indicators (KPIs)
- Setting data-driven goals
- Monitoring progress
- Adjusting strategies based on data insights


### Data cleaning and presentation

Data cleaning is the process of ensuring accuracy, consistency, and reliability of data.

Key aspects:

1. Handling missing values
2. Data normalization
3. Data transformation
4. Removing duplicates
5. Data validation
Data Presentation:

Data presentation enables Effective data presentation communicates insights and findings.

Key aspects:

1. Data visualization (charts, graphs, tables)
2. Dashboard design
3. Storytelling with data
4. Interactive visualizations
5. Reporting and documentation

### Tools used

Microsoft Excel

SQL-Structured Query language

Github for portfolio building

PowerBi


#### EXCEL AND EXCEL FUNCTIONS 

WHAT IS EXCEL

Microsoft Excel is a versatile spreadsheet software developed by Microsoft, used globally for organizing data and performing financial analysis. Its key features include data entry, management, financial modeling, and charting. Excel is extensively used in finance and accounting for budgeting, forecasting, and analysis due to its robustness and flexibility. It supports various functions, formulas, and shortcuts to enhance productivity and efficiency. Excel is a vital tool for professionals in finance, accounting, and other fields requiring data organization and analysis.

The main uses of Excel include:

- Data entry
- Data management
- Accounting
- Financial analysis
- Charting and graphing
- Programming

Data Entry

Data entry involves manually or automatically inputting data into a computer system or database. Best practices:

1. Accuracy: Ensure data is entered correctly.
2. Consistency: Use standardized formats.
3. Efficiency: Minimize errors and duplication.

 Data Formatting

Data formatting involves organizing and presenting data in a clear, readable manner.

Types of formatting:

1. Text formatting (uppercase, lowercase, title case)
2. Date formatting (MM/DD/YYYY, DD/MM/YYYY)
3. Numeric formatting (currency, percentages)
4. Data normalization (standardizing data values)

Benefits:

1. Improved readability
2. Enhanced data analysis
3. Better data integration

Data Validation

Data validation ensures data accuracy and consistency by checking for errors or inconsistencies.

Types of validation:

1. Syntax validation (format checks)
2. Range validation (numeric or date ranges)
3. Logical validation (cross-field checks)
4. Data type validation (text, number, date)


Benefits:

1. Reduced errors
2. Improved data quality
3. Enhanced data security
4. Streamlined data processing

for example, we're ensuring all columns takes only numbers greater than zero;
- highlight all cells
- go to data tab,click on data tools then click on data validation
- a page pops up, choose allow whole numbers option and click on greater than 0
- then okay

Pictorial representation of what Excel worksheet looks like whereby the upperpart is called the INTERFACE and also comprises of the quick access tool bar

![Screenshot (4)](https://github.com/user-attachments/assets/94782e92-be3c-4615-ad79-87a7bd739d58)



DATA CLEANING ON EXCEL

When it comes to data cleaning on excel, the main functions are Upper,Lower, Trim and Proper function.

To eliminate excesses spaces in excel

 =TRIM(TEXT)

TO USE UPPER FUNCTION

 =UPPER(TEXT)

 TO ACHIEVE THE TRIMMED AND PROPER FUNCTION
   =PROPER(TRIM(TEST))
   
![Screenshot (7)](https://github.com/user-attachments/assets/c13cd30b-67c2-4986-97bd-cbf654e8fc3c)


TEXT EXTRACTION IN EXCEL

Text extraction in Excel refers to the process of retrieving specific text or data from a cell or range of cells, often using formulas, functions, or other tools.

![Screenshot (8)](https://github.com/user-attachments/assets/b1ca5687-e134-4d09-8fd3-13d38bc7381f)

On the table above, a record was lost but from the codes generated in the prevoius analysis, the records are easily retraceable using the Left, Mid and Right  Functions.


#### STRUCTURED QUERY LANGUAGE- SQL

Structured Query language is used for storing and managing data in Relational Daatabase Management system(RDBMS). IT enables a userto relate to databases and tables.

Various types of SQl commands are;

- DDL- Data Definition Language (create, insert,Alter, Truncate)
- DML- data Manipulation Language (insert, update, delete)
- DCL- Data control language (Grant,revoke)
- DQL- Data query Language(select)

##### PROBLEM STATEMENT
 Creating a database called Woman of substance store with different branches in different lagos. 
 
 ![Screenshot (9)](https://github.com/user-attachments/assets/7b9834c7-2052-4007-a00d-5d59f0d4607f)

 The table aboves shows the query of my database creation for stores in Lagos. 
 
![Screenshot (11)](https://github.com/user-attachments/assets/d805f809-2405-4c2c-ae59-e1bafda21a37)

on this table, i use the Count query to count the address of each customer per location in Lagos and i was able to get
 that.


#### GITHUB

What is GitHub?

GitHub is a web-based platform for version control and collaboration on software development projects.

Key Features:

1. Repository creation and management
2. Version control (Git)
3. Collaborative coding
4. Issue tracking
5. Project management
6. Open-source community

Benefits:

1. Streamlines development workflow
2. Enhances collaboration
3. Tracks changes and updates
4. Secure and scalable
5. Large community support

Basic GitHub Concepts:

1. Repositories (repos)
2. Branches
3. Commits
4. Pull requests
5. Merge

Getting Started:

1. Create a GitHub account
2. Explore repositories
3. Learn Git basics
4. Join open-source projects
5. Start collaborating!

GitHub is an essential tool for developers, providing a platform for seamless collaboration and version control.




#### - POWERBI

Powerbi is a tool that enables users to transform raw data into meaningful insights through interactive visuals and reports.

##### Dax Function: Data Analysis Expressions

Dax function is a formula language and is a collection of functions,operators and constants that can be usedin a formula or expressions to calculate and return one or more.
Below is a project i worked on;



### HR DATA ANALYSIS AND VISUALIZATION

#### PROJECT OVERVIEW

This repository contains exploratory data analysis and visualization of HR data, focusing on employee attrition and demographic factors. The dataset includes 1470 rows and 44 columns, covering various aspects of employee information.

Dataset Description

The HR dataset comprises the following features:

1. Attrition (yes/no)
2. Business Travel (frequency)
3. Age Band (categorical)
4. Department (categorical)
5. Educational Field (categorical)
6. Employee Number (unique identifier)
7. Gender (categorical)
8. Job Role (categorical)
9. Marital Status (categorical)
10. Overtime (yes/no)
11. No of training in a year
12. age
13. current employees, etc.

Analysis and Findings

Attrition Analysis

1. Attrition Rate: The overall attrition rate is 16% out of 1470 employees which indicating a moderate level of employee turnover.

2. Department-wise Attrition: The R&D department has the highest attrition rate (56.12%), followed by sales with(38.82%) while HR has the lowest(5.06%). 

3. Age Band and Attrition: Employees in the 25-34 age band have the highest attrition count (112), while those in the 55 and below age band have the lowest count (11).

4. Job Role and Attrition count based on thier satisfation: Manager and research director has the lowest attrition count with (5 and 2, respectively) compared to laboratory technician (62) and sales executive (57) which indicates how satisfied they are with thier job.

5. Gender and Attrition count: The male gender has the highest total sum of attrition of 150(63.29%) while the female gender has 87 sum of attrion count with (36,71%).

Demographic Insights

1. Gender Distribution: The workforce is predominantly male (63.2%), with females comprising 36.71%.

2. Marital Status: single employees constitute 50.6% of the workforce, married employees make up 35.44% while divorced has 13.92%.

3. Educational Field: The majority of employees hold a high school leaving certificate (23.95%), followed by Bachelor's degree(22.73%), then Associaate degree(20.49%).

Key Takeaways

1. R&D and Sales departments require targeted retention strategies.

2. Business travel frequency impacts attrition; consider flexible work arrangements.

3. Employees in the 25-34 age band require engagement and development opportunities.

4. Laboratory technician and sales department needs support and training.

5. Department-specific strategies can improve overall retention.


Visualizations
- ![Screenshot (24)](https://github.com/user-attachments/assets/93b89514-a2fa-48b6-912a-1825f91966cf)

- ![Screenshot (29)](https://github.com/user-attachments/assets/5d469688-1783-412d-8b27-7b9d7b2a72ce)


Code and Tools

- Power Bi Dax function

Conclusion

This project demonstrates my ability to:

1. Clean and preprocess HR data
2. Conduct exploratory data analysis
3. Visualize key insights using powerbi
4. Identify potential factors influencing employee attrition





