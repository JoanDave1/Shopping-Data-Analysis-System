# Shopping-Data-Analysis-System

## Automated Monthly Shopping Data Analysis System | Advanced Excel & Power Query

This is an automated Excel-based data processing and analysis system designed to consolidate monthly shopping transactions, perform data transformation, and generate useful customer and transaction insights.

### Project Overview

This project simulates a real-world business scenario where shopping transaction data is received monthly in separate files. Instead of manually copying and consolidating each month's transactions, I built a reusable workflow using Power Query that automatically incorporates new monthly data when the source folder is updated and the query is refreshed. 
This project uses advanced Excel functions including XLOOKUP and INDEX-MATCH to create useful analysis and reporting outputs.

### Business Problem

Monthly transaction data often arrives as separate files, creating repetitive manual work for:

* Consolidating monthly transactions
* Cleaning and transforming data
* Retrieving customer/product information
* Updating analysis when a new month's transaction is added
* Preparing monthly summaries

Performing these steps manually creates unnecessary repetitive work and increases the risk of inconsistent processing.

### Problem Statement

How do we set up monthly shopping reports to update automatically when we add new data?

### Solution

The system separates the workflow into three major stages:

* **Data Ingestion:** Monthly transaction files are stored in a designated folder.
* **Data Transformation:** Power Query imports, cleans, transforms, and consolidates the files.
* **Analysis & Reporting:** Advanced Excel formulas and reporting tables are used to calculate, organize, and summarize insights from the consolidated dataset.

### Excel Techniques 

1. Power Query: Power Query was used to handle the monthly files.

* Bring the monthly files into Excel
* Clean the data
* Put the monthly data together into one dataset
* Make it possible to update the dataset when a new month is added

2. XLOOKUP: Used to find information from another table.
3. INDEX-MATCH: Used to find information from another table using a matching value.

### Business Value

The project was built to make monthly reporting easier, faster and less repetitive.

#### What the project improved
* Less copying and pasting: Power Query handles the process of bringing the monthly files together.
* Less repeated work: I don't have to rebuild the analysis every time a new month is added.
* Fewer chances of making mistakes: The same steps are used to process the monthly data instead of doing them manually each time.
* Easier monthly updates: When a new month's data is available, I can add it and refresh the process.

