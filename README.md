User Journey Analysis Project

Overview

This project focuses on extracting and analyzing user journey data using SQL. The aim is to gain insights into user behavior, understand purchase trends, and evaluate website interactions for better decision-making. The data provided is structured across three primary tables:

front_interactions: Logs visitor activity on the front pages.

front_visitors: Links visitor sessions to user accounts.

student_purchases: Contains payment information related to user purchases.

We use CTEs (Common Table Expressions), window functions, and joins to perform exploratory data analysis and derive actionable insights regarding user behavior and purchasing trends.

Project Files

user_journey_analysis.sql: SQL script containing all the advanced queries used for analysis.

user_journey_database.sql: SQL file to generate the schema and load the required data into MySQL.

user_journey_analysis.ipynb: Jupyter notebook that uses Python to connect to MySQL and execute SQL queries using Pandas.

README.md: This documentation file.

Requirements

To successfully run this project, you will need the following tools and libraries:

Python 3.7+

MySQL 8.0+

Pandas: For managing SQL query outputs in a DataFrame.

MySQL Connector: Python library for connecting to a MySQL database.

Jupyter Notebook (Optional): To interactively execute and visualize results.

VS Code or any preferred IDE for editing scripts.

Setup Instructions

Clone the Repository

Clone the project repository to your local machine:

git clone [https://github.com/nikhilchoudhary28/USER-JOURNEY-ON-WEBSITE-SQL-](https://github.com/nikhilchoudhary28/USER-JOURNEY-ON-WEBSITE-SQL-)

Set Up MySQL Database

Open MySQL Workbench or another MySQL client and run the provided user_journey_database.sql file to set up the database:

SOURCE path/to/user_journey_database.sql;

This will create the schema and load all necessary tables.

Configure Python Environment

Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # For Linux/MacOS
venv\Scripts\activate  # For Windows

Install dependencies:

pip install pandas mysql-connector-python jupyter

Run Analysis

You can run the analysis using the Jupyter notebook user_journey_analysis.ipynb:

jupyter notebook user_journey_analysis.ipynb

This notebook contains step-by-step SQL queries to perform EDA (Exploratory Data Analysis), along with explanations for each result.

Advanced SQL Queries in the Project

The project uses a variety of advanced SQL features, including:

CTEs (Common Table Expressions): To create temporary result sets for easy reuse.

Window Functions: For ranking users by total purchase amount, calculating conversion rates, and analyzing user retention.

JOINS: To bring together data from different tables, linking users, visitors, and their interaction paths.

Some of the main queries include:

Identifying Top Spenders: Ranking users based on their total spending.

Conversion Rate Analysis: Evaluating how many visitors converted to paying users for each page URL.

Tracking Visitor Journeys: Following the sequence of pages visited by users.

Key Insights Derived

Total Revenue Generated: Calculated the total revenue by excluding test users.

User Behavior Analysis: Analyzed user interactions with the website, identifying high-traffic and high-conversion pages.

Retention Insights: Identified returning users and provided metrics on user loyalty.

How to Contribute

Contributions are welcome! Please feel free to create issues or submit pull requests for improvements or new features.

Steps to Contribute

Fork the repository and clone it locally.

Create a new branch for your modifications:

git checkout -b feature-branch-name

Commit your changes and push to your forked repository.

Create a Pull Request to have your changes reviewed and merged.

Contact

If you have any questions or need help, feel free to reach out:

Email: nikhil28choudhary1999@gmail.com

LinkedIn: https://www.linkedin.com/in/nikhil-choudhary-0b7879198/

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Thank you for exploring the User Journey Analysis Project! Your insights are invaluable, and we hope this project helps you understand user behaviors effectively.

