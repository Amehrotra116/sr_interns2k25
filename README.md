# Automated Data Pipeline: AWS S3 to Snowflake

## Project Overview

This project implements an automated data pipeline that efficiently loads and transforms daily transaction data from AWS S3 into Snowflake for analysis. The system handles both daily and monthly file uploads, applying necessary transformations as per business requirements.

## Challenges Addressed

1. **Daily File Uploads**: Automatically load files into a Snowflake table as soon as they are uploaded to the AWS S3 bucket.
2. **Monthly File Uploads**: Efficiently load files from new monthly folders in the AWS S3 bucket (e.g., 012025, 022025, 032025) into the Snowflake table.

## Tools and Technologies

- Snowflake
- AWS (Amazon Web Services)
- SQL
- Snowpark
- Python

## Key Features

- Automated data ingestion from AWS S3 to Snowflake
- Real-time processing of daily uploads
- Efficient handling of monthly batch uploads
- Basic data transformations as per business logic
- Scalable and maintainable data pipeline

## Setup and Installation

1. AWS Account Creation
   - Collaborate with team members to create a shared AWS account
   - Ensure all team members have appropriate access

2. Snowflake Configuration
   - Set up Snowflake account and warehouse
   - Configure stages, Snowpipe, and tasks

3. AWS S3 Configuration
   - Create necessary S3 buckets
   - Set up IAM roles and policies for Snowflake integration

4. Pipeline Implementation
   - Develop SQL scripts for data transformations
   - Implement Snowpipe for continuous data loading
   - Create Snowflake tasks for scheduled operations

## Usage

Refer this doc for aws account setup
[1_AWS_Account_creation 2.docx](https://github.com/user-attachments/files/18701238/1_AWS_Account_creation.2.docx)


## Contributing

This project is developed collaboratively. Each team member should work on a separate branch for version control. Please follow these steps for contributing:

1. Create a new branch for your feature
2. Commit your changes
3. Push to your branch
4. Create a Pull Request

## Team

- Ashish (Reviewer)
- Anand (Reviewer)
- Apoorv (Maintainer)

## Support

For any questions or assistance, please contact the project mentors or team leads.
