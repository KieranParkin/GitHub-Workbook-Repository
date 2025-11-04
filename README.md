# GitHub-Workbook-Repository
Projects from Data Bootcamp
Weekly Summaries
Week 1

Weekly Learning and Activities Summary

This document outlines the learning activities and skills I developed during my Data Technician course this week.

Day 1: Understanding Data Regulations

On Day 1, I researched and explored key data protection laws including the Data Protection Act, GDPR, Freedom of Information Act, and the Computer Misuse Act.

I learned about their purposes, why they are important, and how they apply to real-world data handling.

I also looked into the potential consequences of breaching these laws and reflected on how they impact the way I handle and protect data.

Day 2: Working with Excel Data

During Day 2, I focused on developing my Excel skills.

I created tables, sorted data using filters, and used the SUM and AVERAGE functions to calculate commission values.

I also experimented with different datasets to strengthen my ability to clean and organize data efficiently.

Day 3: Data Analysis and Visualisation

On Day 3, I worked with datasets such as the Bike Sales dataset to create Pivot Tables and analyze sales trends.

I identified market trends by country, age group, and gender.

I used formulas like SWITCH to categorize sales volumes.

I also practiced creating data visualisations to help communicate insights more clearly and effectively.

Day 4: Presenting Data Insights

Day 4 was focused on communication and presentation.

I prepared for how I would present my analysis findings to a board of directors, focusing on customer retention and churn at the 12-month mark.

I researched effective presentation tools, public speaking techniques, and visualization methods that would support a professional and engaging delivery.

Reflection

Throughout the week, I improved my understanding of data regulations, analytical methods, and presentation skills.

I gained confidence in using Excel for data analysis.

I explored visualization techniques.

I developed a better understanding of how to communicate insights clearly to different audiences.
Week 2

Day 1: Tableau Exploration and Dashboard Creation

Task 1: Researched Tableau Versions

I researched and compared the different versions of Tableau.

I explained the limited functionality of Tableau Public, noting that it only allows access to local copies like spreadsheets, text files, or Tableau Data Extracts. Other versions allow direct connections to dozens of data sources, such as Salesforce, Microsoft SQL, and AWS.

Task 2: Created a Tableau Dashboard

I used the EMSI_JobChange_UK dataset to create my own dashboard.

The dashboard included a bar chart showing percentage change and a UK-based map illustrating the key city locations impacted.

Day 2: Data Analysis and Trend Finding

Task 1: Analyzed the Spotify Dataset

I conducted an analysis on the Spotify data set to find trends and key information.

Key Findings:

I found that the most popular artist is Drake (31,703), who is significantly ahead of the second-place artist.

I also found that the energy in a song does not correlate to popularity.

I noted that Tempo seems to have only a small input in popularity.

Task 2: Analyzed the Health Dataset and Reflected

I conducted an analysis on the Health data set to find trends and key information.

I reflected on how this data could support decision-making for the NHS, knowing that data can be lifesaving and is being used more within the NHS.

Week 4

During Week 4, I successfully completed all required research, practical Azure labs, and the final consultancy report preparation, demonstrating a strong understanding of Cloud Computing Concepts and UK Data Laws and Regulations.

My key achievements for this week include:

Cloud Computing and Architecture

Core Concepts: Researched and articulated the benefits of cloud computing for businesses (e.g., faster time to market, scalability) and explored alternative distributed architectures like Fog, Edge, and Mesh Computing.

Service Models: Defined, compared, and provided real-world use cases for the three main cloud service models: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).

Deployment Models: Explained the four primary cloud deployment models (Public, Private, Hybrid, and Community Cloud) and identified appropriate use cases for each, such as using Private Cloud for highly regulated industries.

Data Laws and Compliance

Computer Misuse Act 1990: Defined and provided examples for the three major offences, including Unauthorised Access (Section 1) and Unauthorised Acts with Intent to Impair Operation (Section 3).

Legal Updates: Described the three extra powers introduced by the Police and Justice Act 2006, notably the explicit criminalisation of Denial-of-Service (DoS) attacks and the offence of creating/supplying 'hacker tools'.

Data Protection: Identified the rules governing employer data storage, specifying which items (e.g., Name, National Insurance Number) can be stored without permission and which sensitive categories (e.g., Racial Origin, Health Data) require explicit employee consent, referencing UK government guidelines.

Intellectual Property: Distinguished between Copyright Infringement and Plagiarism with practical examples, and documented the severe consequences of software piracy, including criminal penalties, civil liability, and security risks from malware.

Regulatory Mapping: Successfully matched various legal clauses to the correct UK legislation, including the Data Protection Act 2018 (DPA) and the Consumer Rights Act 2015.

Consultancy Proposal: Prepared a comprehensive Azure consultancy proposal for "Paws & Whiskers," which involved:

Recommending specific Azure services for storage (Azure SQL Database, Azure Blob Storage), analysis (Azure Synapse Analytics), and integration (Azure Data Factory).

Outlining a data modelling approach for key data categories.

Mandating compliance with GDPR and the DPA 2018.

Incorporating essential technical considerations such as data storage formats (Parquet for analytics), data security (encryption and access controls), and a strategy for Backup and Disaster Recovery.
Week 5

Statement of Achievement: Data Technician Workbook - Week 5

During Week 5, I focused entirely on developing my programming and data manipulation skills, successfully completing foundational tasks in Python and numerous practical exercises using the Pandas library for data analysis.

My key achievements for this week include:

Python Programming Fundamentals

Logical Programming (FizzBuzz): I successfully developed and tested a core Python program to solve the classic FizzBuzz problem. This task demonstrated my understanding of:

Iterating through a range (1 to 100) using a for loop.

Implementing complex conditional logic (if, elif, else).

Using the modulo operator (%) for checking divisibility by 3 and 5.

Data Analysis with Pandas I completed an extensive set of group and individual exercises using the Pandas library, demonstrating mastery of the data workflow from ingestion to exportation.

Data Loading and Exploration (Exercise 1): I learned to ingest data by reading a CSV file into a Pandas DataFrame and immediately performed crucial exploratory steps, including viewing the first 5 rows, checking the DataFrame's overall information and data types, and calculating basic summary statistics.

Indexing and Slicing (Exercise 2): I gained proficiency in selecting data, specifically writing code to select single and multiple columns (e.g., 'name' and 'mark') and using conditional filtering to select rows based on values (e.g., all rows where 'class' is 'Four').

Data Manipulation and Transformation (Exercise 3 & 5): I transformed and cleaned the data by:

Adding a new column ('passed') based on a logical condition (mark >= 60).

Renaming a column (from 'mark' to 'score') and dropping columns.

Creating a new categorical column ('grade') by applying complex criteria (e.g., marks >= 85 are 'A', 70-84 are 'B', etc.).

Aggregation and Reporting (Exercise 4 & 5): I performed key analytical tasks:

Used groupby() to calculate the mean mark for each class and the average mark for each gender.

Counted the number of students in each class.

Created an advanced pivot table using 'class' as rows and 'gender' as columns.

Sorted the final DataFrame by 'mark' in descending order.

Real-World Data Handling

Individual Practice (Day 4): I independently applied my core Pandas skills on the ‘GDP (nominal) per Capita’ dataset. This practice included reading the file into a DataFrame, inspecting the first 10 and last 5 rows, and selecting specific columns ('Country/Territory' and 'UN_Region').

Export and Collaboration: I completed the data pipeline by writing code to save the final transformed DataFrame (with the new 'grade' column) to a new CSV file. I also participated in group activities to further embed my Python skills by working through a dedicated notebook and exploring additional datasets.
