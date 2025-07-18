# AV Club Datathon Project: Modecraft Ecommerce Analysis
Team:
Amy Oguejiofor (amyo6@uw.edu)

Vy Nguyen (nvy24@uw.edu)

Industry/Business Problem we Will Analyze:
Retail - Accelerating the Sales of the Modecraft Ecommerce Store

Additional Presentation:
🔗 [Slides](https://docs.google.com/presentation/d/1yDQcFMRH7naa-LOqvFEFqCYHMODQoQ8TQbU729rOLCI/edit?usp=sharing)

Data Source:
📊 [Google Sheet Dataset](https://docs.google.com/spreadsheets/d/14JpdZtBkG8mJtfRjrk01R-sQ1WPGgLJXKzZThHx-Zi8/edit?usp=sharing)

🕒 Overview
We participated in a 34-hour data hackathon where we were challenged to help Modecraft — a global ecommerce store — uncover actionable insights to increase their online revenue.

Our Goals were to: 

- Clean and prepare a large transactional dataset  
- Analyze trends across time, geography, and customer behavior  
- Develop interactive data visualizations that tell a clear, compelling story  
- Propose data-backed recommendations for growing Modecraft’s sales

🔧 Tools Used

Data Cleaning:
- Google Sheets / Microsoft Excel
- Python (via Google Colab)

Data Visualization Website:
- HTML, CSS, JavaScript
- Excel
- Power BI

Deployed using Netlify

🧹 Data Cleaning Process
We cleaned the dataset individually using both Python (in Google Colab) and Excel, and then merged our findings to finalize a clean version for analysis. Key steps included:
- Removed rows with null or invalid values
- Added several helpful derived columns:
- Revenue = Quantity × Unit Price
- Day of Week, Time of Day, Weekday/Weekend, Quarter
- Standardized Product Name values
- Ensured date and time fields were formatted properly
  <img width="501" height="265" alt="Screen Shot 2025-07-18 at 10 57 39 AM" src="https://github.com/user-attachments/assets/7bbaffd4-e8e0-4f07-9f01-8f08343cf4b9" />

❓ Key Business Questions We Answered

Seasonality & Time Trends
- Are there seasonal spikes in purchases for specific products?
- What are the peak sales periods throughout the year?
- How does time of day or day of week affect purchasing?

Product-Level Analysis
- Which products increased or decreased in sales over time?
- Which products generate the most vs. least revenue?

Customer & Sales Insights
- Which times/days see the most purchases?

Geographic & Regional Insights
- Which regions/countries have the highest sales?
- Identified strong-performing markets and areas for potential growth
  
Product Reports
- Quantity sold by: month, country, time of day, day of week
- Total quantity sold
- Total revenue generated

📈 Final Deliverable
We built a fully interactive website that allows users to:
- View monthly and product-specific sales reports
- Explore time-based and regional trends
- Gain insights from intuitive visualizations

🔗 [Visit Our Site](https://avclubdatathon.netlify.app/) 
