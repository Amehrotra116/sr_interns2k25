Use Case Overview: 
A company receives daily transaction data from multiple sources in CSV format, which is stored in an AWS S3 bucket. Our objective is to efficiently query and analyze this data in Snowflake, applying basic transformations as per business requirements, without the need for manual file loading.
Before we begin, please note that each of you will be working on a separate branch for version control. Additionally, for setting up the AWS account, we request that you three collaborate to create a single AWS account where all of you have access. This shared account will be used to complete all the steps in this project.

[1_AWS_Account_creation 2.docx](https://github.com/user-attachments/files/18701167/1_AWS_Account_creation.2.docx)

We have two main challenges to address:
Problem 1: For daily file uploads, we need to implement a system that automatically loads files into a Snowflake table as soon as they are uploaded to the AWS S3 bucket.
Problem 2: For monthly file uploads, where files are stored in new folders in the AWS S3 bucket (e.g., 012025, 022025, 032025), we need to develop a solution to load these files into the Snowflake table efficiently.
To tackle these challenges, we'll be utilizing the following tools and skills:
Tools:
•	Snowflake
•	AWS (Amazon Web Services)
Skills:
•	Snowflake: Stage, Snowpipe, Tasks
•	SQL Transformations
•	Snowpark and Python
This project will provide you with hands-on experience in cloud data storage, ETL (Extract, Transform, Load) processes, and data analytics. You'll learn how to automate data ingestion, perform transformations, and set up efficient querying mechanisms.
We encourage you to collaborate, share ideas, and support each other throughout this project. If you have any questions or need assistance, please don't hesitate to reach out to your mentors or team leads.
Good luck, and we look forward to seeing your innovative solutions!

