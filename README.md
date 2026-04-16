Vrinda Store Annual Sales Analysis Dashboard (2022)
📌 Project Overview
The objective of this project is to create an end-to-end annual sales report for Vrinda Store for the year 2022. By analyzing various facets of the sales data, this project aims to understand customer behavior and identify key performance areas to drive sales growth in 2023. An interactive Excel dashboard was developed to visualize critical metrics and insights.

📊 Dataset Description
The source dataset is an Excel file containing over 31,000 rows of transactional data across 21 columns, covering sales operations for the entire year of 2022.

🛠️ Data Cleaning & Processing Steps
Before analysis, the data underwent a comprehensive cleaning and processing phase to ensure accuracy and consistency.

1. Data Cleaning
The following corrections were applied to the raw data:

Gender Field Standardization: Replaced inconsistent entries like "M" with "Man" and "W" with "Woman".

Sales Channels Corrections: Fixed spelling mistakes, such as replacing "AMenazon" with "Amazon", "Meneesho" with "Meesho", and "Menyntra" with "Myntra".

Quantity Field Correction: Converted text entries ("one", "two") to numerical values ("1", "2").

2. Data Processing & Feature Engineering
New calculated columns were created to enhance the depth of analysis:

Age Group Segmentation: Created an 'Age Group' column using a nested IF formula based on the age column (T2):

if(T2>=50, “Senior”, if(T2>=30, “Adult”, “Teenager”))

Month Extraction: Added a 'Month' column to extract the month name from the main date column for monthly trend analysis.

📈 Data Analysis & Visualization
An interactive dashboard was built using Microsoft Excel, featuring the following specific analysis areas:

Sales vs. Orders: Monthly trend analysis to compare total sales amount against the total count of order IDs.

Sales: Men vs. Women: A pie chart illustrating the revenue split by gender.

Sales: Top 5 States: A bar chart showing the five states with the highest sales volume.

Order: Age vs. Gender: A clustered column chart displaying order patterns by both age group and gender.

Order Status: A chart summarizing the breakdown of orders by status (e.g., Delivered, Refunded, Cancelled).

Orders: Channels: A pie chart showing the distribution of orders across different sales channels like Amazon, Flipkart, etc.

Key Dashboard Feature: Multiple Slicers were integrated, allowing users to interactively filter the entire dashboard by:

Month

Sales Channel

Product Category

💡 Final Business Conclusion and Insights (for 2023 Strategy)
Based on the dashboard and analysis, several key insights were generated to improve Vrinda Store's sales in 2023:

Target Audience: The data clearly shows that Women customers (~65%) are the largest buyers.

Prime Demographics: The Adult age group (30–49 years) contributes the maximum to sales (~50%).

Key Regional Markets: Maharashtra, Karnataka, and Uttar Pradesh are the top three performing states.

Channel Strategy: Sales are heavily driven through Amazon, Flipkart, and Myntra.

Conclusion for 2023: Focus marketing efforts on women customers within the 30–49 age group living in the top three performing states. Tailor ads, offers, and coupons specifically for high-volume sales channels like Amazon, Flipkart, and Myntra to maximize ROI.
