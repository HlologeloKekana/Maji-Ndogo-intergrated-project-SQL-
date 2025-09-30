# Maji-Ndogo-intergrated-project-SQL-
A 4-part project showcasing my skills in database design, querying, and analysis using MySQL Workbench. This project demonstrates my ability to work with databases, perform complex queries, and extract insights from data.
The project relies on several database tables to store and manage data. These tables include:

- Location Table: stores location-specific information, such as address, province, town, and urban status.
- Visits Table: captures details about employee visits, including source and location, time of record, visit count, and queue time.
- Water Quality Table: contains subjective quality scores and visit counts for water sources.
- Water Source Table: logs information about each water source, including location, source type, and population served.
- Well Pollution Table: provides data on well pollution, including type, source ID, date recorded, pollutant concentration, and biological contamination.
- Auditor Report Table: stores auditor's reports, including location ID, water source type, true water source score, and statements.
- Project Progress Table: which tracks improvement projects, including project ID, source ID, address, town, province, source type, improvement action, source status, and completion date.

Data Analysis and Queries
The project involves various queries to explore and analyze the data, including:

- Water Source Analysis: investigates unique water sources by source type.
- Visit Analysis: identifies visits with estimated water collection times of approximately 8 hours.
- Water Quality Assessment: evaluates water source quality based on visit count and subjective quality scores.
- Data Inconsistency Handling: addresses inconsistencies in the well pollution table's description column.

Data Transformation and Enrichment
Queries are used to update and refine the data for better accuracy and clarity, such as:

- Employee Information Enrichment: updates employee data with email addresses and removes trailing whitespaces from phone numbers.

Performance Metrics and Employee Recognition
Queries assess performance metrics and recognize top-performing employees, including:

- Top Employees by Visit Count: identifies the top 3 employees based on visit count.

Location Analysis and Water Source Prioritization
Queries provide insights into record distribution across locations and prioritize water sources, including:

- Water Source Ranking: ranks water sources based on population served and other criteria.

Data Visualization and Reporting
The project includes queries for creating views and generating reports, such as:

- Town and Province Reports: generates reports for provinces and towns, breaking down data by source type.

Project Progress and Improvement Actions
Queries track improvement projects and populate the project progress table with data based on water source conditions.

Datasets and Database Information
The project uses two datasets:

- md_water_services.sql: an SQL file containing eight tables with comprehensive information about water sources, visits, water quality, and related data.
- Auditor_report.csv: a CSV file containing auditor reports with water source scores and related statements.
