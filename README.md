# UCW Policies - Exploratory Analysis and Data Wrangling

## Project Title
Exploratory Analysis and Data Wrangling for UCW Policies

## Project Description

This project involves conducting an exploratory analysis and data wrangling of the UCW Survey Procedure Policy. The primary goal is to understand the structure, content, and quality of the survey data, and to clean, transform, and consolidate the data for further analysis and reporting.

## Objective

The main objective of this project is to provide a clear and structured process for analyzing and wrangling data related to the UCW Survey Procedure Policy. This involves cleaning, transforming, and analyzing the dataset to uncover insights related to survey procedures and compliance within UCW.

## Background

UCW requires a structured survey process to ensure that all surveys conducted within the university adhere to high standards of quality and relevance. The Survey Management Committee is tasked with overseeing this process to align survey activities with institutional goals and ethical standards.

## Exploratory Analysis

### Dataset

The dataset used in this project includes the following fields:
- **Policy Title**: The title of the policy.
- **Section**: The specific section of the policy.
- **Description**: A detailed description of the policy section.
- **Date Implemented**: The date the policy was implemented.
- **Last Reviewed**: The date the policy was last reviewed.
- **Responsible Party**: The department or individual responsible for the policy.
- **Status**: The current status of the policy (e.g., Active, Inactive).

### Methodology

#### Data Collection

- Collect data from internal UCW policy documents and databases.
- Verify data accuracy and completeness to ensure reliable analysis.

#### Data Assessment

- Perform a thorough evaluation of data quality to identify issues such as missing values, duplicates, errors, and inconsistencies.
- Review and document data types, formats, and structures used within the dataset.
- Identify and flag potential data integrity issues and assess the need for data cleaning or transformation.

### Visual ETL DataPipeline

![Ucw policies ETL](https://github.com/user-attachments/assets/cf083b26-0be3-4e5b-b8fd-8c81c198dc1d)


### Results and Insights

- Summary statistics of the policy dataset.
- Identification of any patterns or trends in policy implementation and review dates.
- Visualization of policy status and responsible parties.

## Data Wrangling

### Dataset

The data wrangling process will involve the following datasets:
- **Policy Data**: Detailed records of each policy, including implementation and review dates, responsible parties, and status.
- 
### Visual ETL DataPipeline

![UCW POLOCIES QPC ETL](https://github.com/user-attachments/assets/2927fe4b-c5c3-4430-98c9-cce33e644a01)

### Methodology

#### Data Cleaning

- Resolve missing values using suitable techniques, such as imputation or exclusion.
- Eliminate duplicate entries and rectify inconsistencies in data formats (e.g., standardizing date formats and naming conventions).
- Standardize categorical variables to ensure uniformity across datasets.

![ucw polocies clean](https://github.com/user-attachments/assets/a22ea91c-9431-48a4-88e7-5faf88d576a3)


#### Data Transformation

- Perform data type conversions to ensure that all fields are in suitable formats for analysis (e.g., converting strings to datetime objects).
- Derive new features that may aid in analysis, such as the time since last review or the duration of policy activity.
- Aggregate data as necessary to ensure alignment with intended analysis (e.g., summarizing policy statuses by department).

![UCW POLICIES Obs](https://github.com/user-attachments/assets/97fcafe5-faef-491b-afcf-0550107ff446)


#### Data Consolidation

- Merge datasets into a unified policy database, ensuring all relevant information is accurately linked through unique identifiers (e.g., Policy ID).
- Create a comprehensive view of each policy by combining data from various sources.

### Deliverables

- A cleaned and transformed policy dataset ready for analysis, available in a suitable format (e.g., CSV, Excel).
- A comprehensive report documenting the data wrangling process, including challenges encountered, methods employed, and final dataset characteristics.
- Visualizations illustrating key data insights and confirming data quality checks conducted during the process.

## Timeline

- Expected completion of the project: 6 weeks, including phases for assessment, cleaning, transformation, and documentation.

This project aims to establish a high-quality dataset that enables UCW to conduct effective policy analysis, ultimately enhancing policy management and compliance within the university.
