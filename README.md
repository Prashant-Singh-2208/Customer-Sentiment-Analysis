📌 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on customer sentiment data collected from an e-commerce platform. The goal is to uncover patterns in customer ratings, sentiment distribution, regional behavior, and complaint resolution — insights that can directly guide business decisions around customer experience and product improvement.


🎯 Business Questions Answered


Which product categories receive the best and worst customer ratings?
How does sentiment (positive/negative/neutral) vary across regions and gender?
What is the regional distribution of customers and their feedback?
How does response time affect customer satisfaction and issue resolution?
What % of complaints are resolved vs unresolved?
Which platform/purchase channel generates the most feedback?



📂 Dataset — Sentiment.csv

ColumnDescriptioncustomer_idUnique customer identifiergenderCustomer genderage_groupAge group of the customerregionGeographic region of the customerproduct_categoryCategory of product purchasedpurchase_channelOnline / Offline / AppplatformPlatform used for purchase/reviewcustomer_ratingRating given by customer (1–5)review_textRaw text of the customer reviewsentimentPositive / Negative / Neutralresponse_time_hoursTime taken to respond to customerissue_resolvedWhether the issue was resolved (Yes/No)complaint_registeredWhether a complaint was filed (Yes/No)


🛠️ Tools & Libraries Used

ToolPurposePython 3.xCore programming languagePandasData loading, cleaning, and analysisMatplotlibData visualizationSeabornStatistical chartsJupyter NotebookInteractive analysis environment


📊 Visualizations

1. Category-Wise Average Rating
<img width="1617" height="621" alt="category_wise" src="https://github.com/user-attachments/assets/e1b7e0e0-2433-46ac-842a-dc3a624d2d50" />

2. Regional Distribution of Customers
<img width="429" height="425" alt="regional_distribution" src="https://github.com/user-attachments/assets/a1275cc7-cb62-4026-bc11-eb631b7e04b7" />

3. Average Rating by Region and Gender
<img width="1601" height="559" alt="Average_rating_of_region_by_gender" src="https://github.com/user-attachments/assets/158e4dbc-b033-4cc8-a0eb-c3e547ef49a3" />


🔍 Key Insights


Sentiment varies by region — certain regions show consistently higher negative sentiment, indicating localized service issues
Product category impacts ratings — some categories receive significantly lower ratings, pointing to quality or delivery issues
Gender-based rating patterns differ across regions — useful for targeted marketing strategies
Response time correlation — longer response times are associated with lower customer ratings and unresolved complaints
Complaint resolution rate directly impacts repeat sentiment — resolved complaints show higher follow-up ratings



📁 Project Structure

Customer-Sentiment-Analysis/
│
├── data/
│   └── Sentiment.csv                        # Raw dataset
│
├── notebooks/
│   └── customer_sentiment.ipynb             # Full EDA notebook
│
├── visualizations/
│   ├── category_wise.png                    # Category-wise rating chart
│   ├── regional_distribution.png            # Regional distribution chart
│   └── Average_rating_of_region_by_gender.png  # Gender x Region rating chart
│
└── README.md                                # Project documentation


🚀 How to Run This Project


Clone the repository


bashgit clone https://github.com/Prashant-Singh-2208/Customer-Sentiment-Analysis.git
cd Customer-Sentiment-Analysis


Install required libraries


bashpip install pandas matplotlib seaborn jupyter


Open Jupyter Notebook


bashjupyter notebook customer_sentiment.ipynb


Run all cells to reproduce the full analysis



💡 Skills Demonstrated


✅ Data loading and inspection
✅ Data cleaning (handling nulls, type conversion)
✅ Exploratory Data Analysis (EDA)
✅ Group-by aggregations and filtering
✅ Multi-variable visualization
✅ Business insight extraction from raw data



👤 Author

Prashant Singh
M.Sc. Physics | Aspiring Data Analyst
📍 Varanasi, India
🔗 GitHub Profile
