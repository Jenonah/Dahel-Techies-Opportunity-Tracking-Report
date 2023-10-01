# Dahel Techies OpportunityTracking Report

![Web capture_1-10-2023_182845_app powerbi com](https://github.com/Jenonah/Dahel-Techies-Opportunity-Tracking-Report/assets/138598218/14297e65-0418-4148-bf41-8448c30e3cd8)
![Web capture_1-10-2023_183131_app powerbi com](https://github.com/Jenonah/Dahel-Techies-Opportunity-Tracking-Report/assets/138598218/91b1cf64-7a75-4a1d-8d95-294153530c11)
![Web capture_1-10-2023_183242_app powerbi com](https://github.com/Jenonah/Dahel-Techies-Opportunity-Tracking-Report/assets/138598218/bc94cfa8-8edc-4f6d-a0c5-a058c7f2b7c2)
![Web capture_1-10-2023_18343_app powerbi com](https://github.com/Jenonah/Dahel-Techies-Opportunity-Tracking-Report/assets/138598218/47113d09-6c42-4f49-852c-a38573987c84)

# Objectives
- To gain insights into a software company's sales channels
- To provide actionable information to sales managers, enabling them to optimize sales strategies, resource allocation, and revenue generation.

# Data Source
Data was gotten from https://drive.google.com/drive/folders/1fpvtYsk3SAAbx-4GOmY9XmsrHy05udjk

# Data Cleaning and Transformation

Power Query was used for the data cleaning and power Bi was used for visualization.
- Changed the Create Date column in epoch form to date format.
- Renamed the create date  column to start date.
- Renamed the opportunity days column to Sales duration (days).
- Renamed the product code column to Product name.
- Renamed the partner column to Channel.
- Created a Channel status column using conditional column.
- Replaced content in sales stage column to include the stage name and level.
- Created a date table, marked it as a date table.
- Created a relationship between the date table and the Start date column in the fact table.
- Calculated a measure for total revenue for start date.
- Used USERELATIONSHIP function to calculate total revenue for end date  so as to activate the second relationship between the date table and the End date column in the fact Table
*Note;* Columns were renamed for a clearer understanding of the data based on the description of each column as stated  in the data dictionary contained in the data link above.

Visualization
- Created 
