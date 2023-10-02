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
- Created a four page report consisting of front page, Summary page, Channel page and Sales/Revenue page.
- Some visuals had the report tool tip, drill down and drill through  functions.
- A segment for advanced analysis was created.


# Findings

In the analysis of the software company's sales data for the period of 2014-2015, several key insights have been generated, which can be summarized as follows:

**Summary:**

1. Total Revenue: The software company generated a total revenue of $2.11 billion from 487 sales during the specified period.
2.  During this sales period, the company had 25 products, utilized 101 different sales channels, classified into two types (partner and non-partner), employed 5 sales stages (Lead, Solution, Qualify, Proposal, and Finalize), managed 357 accounts, and categorized opportunity sizes into Medium, Small, and Large.
3. The sales activities were spread across three regions: East, Central, and West.
4. The product "Talus" generated the highest revenue, while "Omins" had the lowest revenue among all products.
5. "Direct" was the top-performing channels in terms of revenue, while "Zonrap" was the Revenue Channel with the lowest performance.
6. Partner-driven channels had higher revenue in the "Large" opportunity size category, while non-partner channels performed better in both "Medium" and "Small" opportunity sizes.
7. The East region had the highest revenue, followed by the Central and West regions.
8. All three regions had the same number of products, but the Central region had the highest number of channels, followed by the East and West regions.

**In-depth Insight:**

1. Sales Stage Participation: Almost half (47.9%) of channels were in the initial "Lead" stage, but there was a significant drop in participation as sales progressed, with only 4.41% reaching the "Finalize" stage.
2. Partner-driven channels excelled in the "Large" opportunity size, while non-partner channels performed well in both "Medium" and "Small" opportunity sizes, highlighting potential areas for improvement.
3. Both channel types showed weaker performance in the West region. Partner-driven channels had the highest revenue in the Central region, while non-partner channels excelled in the East region.
4. Channels that went through all 5 sales stages tended to deal with more products compared to those with fewer sales stages.
5. Although partner-driven channels had the highest total revenue, non-partner channels were responsible for the product with the highest revenue.
6. Products with a higher number of channels also had a higher number of sales, and vice versa. The number of sales stages did not significantly affect the sales outcome.
7. Total revenue for the start year exhibited a downward trend from January to December, while revenue for the end year showed fluctuations, with December being the highest and October the lowest.
8. Weekly revenue at the start year remained relatively stable, with the highest point on Fridays and the lowest on Mondays. Conversely, weekly revenue at the end year exhibited significant fluctuations, peaking on Thursdays and dropping on Sundays.

# Recommendations

Based on the insights derived from the analysis of the software company's sales data for 2014-2015, here are some key recommendations for sales managers to optimize sales strategies, resource allocation, and revenue generation:
   - Allocate more resources and attention to advancing channels from the "Lead" stage to later stages in the sales funnel.
   - Tailor strategies to cater to the "Large," "Medium," and "Small" opportunity sizes differently. For partner-driven channels, emphasize targeting larger opportunities, while for non-partner channels, develop strategies for both medium and small opportunities.
   - Address the underperformance in the West region by  investigating the specific challenges faced in this region and devise region-specific strategies for improvement.
   - Encourage channels to engage in more sales stages to handle a wider variety of products. Cross-train channels to be proficient in multiple products, allowing for greater product diversity in the sales portfolio.
    - Recognize the weekly revenue patterns and schedule sales activities and marketing campaigns accordingly. Allocate more resources and marketing efforts during the mid-week peaks and consider strategies to boost revenue on low-performance days.
   - Allocate resources, marketing efforts, and incentives in alignment with regional revenue potential. Focus on driving growth in regions that have shown strong performance, such as the East and Central regions.
  



