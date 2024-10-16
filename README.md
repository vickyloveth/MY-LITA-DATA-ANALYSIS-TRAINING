# MY-LITA-DATA-ANALYSIS-TRAINING

## Table of content

- Project overview
- Foundation of data
- Data cleaning and presentation
- Tools used and understanding of each tools
  
  
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

Best practices:

1. Validate data at entry point.
2. Use automated validation tools 
3. Provide clear error messages
4. Continuously monitor data quality
   
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
 

