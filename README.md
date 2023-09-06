# Crowdfunding_ETL

This is Collaborative work of Aina Teng and Levan Getia. 

Crowdfunding Data Processing Project
The Crowdfunding Data Processing Project aims to streamline and structure crowdfunding data for analysis and insights. This project involves two main steps: cleaning and transforming crowdfunding information, as well as organizing contact details. The processed data is then stored in a format suitable for further analysis.

Project Details
Crowdfunding Data Processing
Data Cleaning: The project begins by loading crowdfunding data from the provided Excel file (crowdfunding.xlsx). The data is examined and cleaned to ensure consistency and accuracy.

Categorization: The data is split into categories and subcategories to facilitate better organization and analysis.

Date Formatting: Launch and end dates are formatted into a standardized datetime format for easy analysis and visualization.

Data Merging: The cleaned data is merged with category and subcategory information for enhanced context and insights.

Data Export: The processed crowdfunding data is saved as a CSV file (campaign.csv) for further use and analysis.

#Contact Information Organization
###Data Loading: Contact information is loaded from the provided Excel file (contacts.xlsx). The data is prepared for organization.

Data Transformation: The contact details are transformed into a structured format, including extracting first and last names from the full name and creating separate columns.

Data Export: The organized contact information is saved as a CSV file (contacts.csv) for further use and integration.

How to Use
Ensure that the Excel files (crowdfunding.xlsx and contacts.xlsx) are placed in the 'Resources' folder of the project directory.

Run the Python script data_processing.py using a Python interpreter. The script will automatically process the data and generate the necessary CSV files.

The processed data can be used for analysis, reporting, or integration with other tools.


