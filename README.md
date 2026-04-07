from reading the 01_load.sql file I discovered: 

Dataset is wide format
Each year (1990–2023) is a separate column
All year columns are stored as VARCHAR (strings)

The dataset was initially explored using SQL queries to understand its structure and contents.

<img width="494" height="573" alt="DESCRIBE" src="https://github.com/user-attachments/assets/e9900108-62c8-40cc-a9b9-d5b86cd903f5" />

Key Observations
The dataset is stored in a wide format, with each year represented as a seperate column (1990 - 2023)
Emission values are stored as strings (VARCHAR) rather than numeric types.
Missing values are represented using '-', requiring cleaning before analysis.
Each row represents emissions for a specific:
  - Gas type
  - Sector (Source)
  - Activity (e.g fuel type)
    
