# Chicago Data Insights: 
> Exploring Socioeconomic Indicators, Schools, and Crime

<center>
    <img src="https://clipground.com/images/sql-logo-clipart-2.jpg" width="1000" alt="cognitiveclass.ai logo" />
</center>

> View Notebook @ [https://github.com/zooviee/Chicago-Data-Insights/blob/main/notebook.ipynb](https://github.com/zooviee/Chicago_Data_Insights/blob/main/Chicago%20Crime%20Insights.ipynb)

## Project Overview

This project involves analyzing three datasets related to Chicago: Socioeconomic Indicators in Chicago, Chicago Public Schools, and Chicago Crime Data. The project begins by establishing a connection to the database using the `ibm_db_sa` module. Once the connection is established, SQL queries are executed to solve a series of problems.

## Repository Contents

The repository contains the following files:

1. `README.md`: This file provides an overview of the project, instructions for setup, and details about the datasets and analysis.
2. `notebook.ipynb`: This Jupyter Notebook file contains the code and analysis for the project. It includes SQL queries to load the datasets into an IBM DB2 database and perform various data analysis tasks.

## Datasets

The datasets used in this project are available on the city of Chicago's Data Portal. They can be downloaded as CSV files from the following links:

1. [Chicago Census Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv)
2. [Chicago Public Schools](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)
3. [Chicago Crime Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv)

## Setup Instructions

To replicate the analysis and run SQL queries on the datasets, follow these steps:

1. Ensure you have access to an IBM DB2 database.
2. Download the three datasets mentioned above.
3. Import the datasets into the DB2 database as separate tables using the provided CSV files.
4. Open the `notebook.ipynb` file in a Jupyter Notebook environment.
5. Connect to the DB2 database using the appropriate credentials.
6. Execute the SQL queries provided in the notebook to perform the desired analysis.

## Analysis

The `notebook.ipynb` file contains the code and SQL queries necessary to perform the analysis on the datasets. It provides a step-by-step guide for loading the datasets into the DB2 database and conducting various data analysis tasks. Here's a brief summary of each problem and its solution:

- Problem 1: How many Elementary Schools are in the dataset.
- Problem 2: What is the highest Safety Score.
- Problem 3: Which schools have highest Safety Score.
- Problem 4: What are the top 10 schools with the highest Average Student Attendance.
- Problem 5: The list of 5 Schools with the lowest Average Student Attendance.
- Problem 6: Which Schools have Average Student Attendance lower than 70%.
- Problem 7: The total College Enrollment for each Community Area.
- Problem 8: The 5 Community Areas with the least total College Enrollment.
- Problem 9: List 5 schools with lowest safety score.
- Problem 10: The name of the community area with highest hardship index.
- Problem 11: List all case numbers for crimes involving minors.
- Problem 12: List all kidnapping crimes involving a child
- Problem 13: What kinds of crimes were recorded at schools.
- Problem 14: Which community area is most crime prone.
- Problem 15: Determine the Community Area Name with most number of crimes.


## Dependencies
The following dependencies are required to run the project:

- Python 3
- Jupyter Notebook
- ibm_db_sa
- pandas
- sqlalchemy

Please refer to the `requirements.txt` file for the complete list of dependencies.

## Getting Started
To get started with the project, follow these steps:

1. Clone the repository
2. Install the dependencies
3. Set up the database connection details in the Jupyter Notebook.
4. Open `notebook.ipynb` and run the cells to execute the SQL queries and explore the data.

## Conclusion

By analyzing the Socioeconomic Indicators, Chicago Public Schools, and Chicago Crime Data, this project aim to provide insights into various aspects of Chicago's communities, education system, and crime rates. The use of SQL queries on an IBM DB2 database allows for efficient analysis and data-driven decision-making.

Please refer to the provided datasets, set up the DB2 database accordingly, and execute the SQL queries in the `notebook.ipynb` file to explore and analyze the data.
