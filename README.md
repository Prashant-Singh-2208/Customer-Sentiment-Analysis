## Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on customer sentiment data collected from an e-commerce platform. The goal is to uncover patterns in customer ratings, sentiment distribution, regional behavior, and complaint resolution — insights that can directly guide business decisions around customer experience and product improvement.


## Business Questions Answered


* Which product categories receive the best and worst customer ratings?
* How does sentiment (positive/negative/neutral) vary across regions and gender?
* What is the regional distribution of customers and their feedback?
* How does response time affect customer satisfaction and issue resolution?
* What % of complaints are resolved vs unresolved?
* Which platform/purchase channel generates the most feedback?



## Dataset — Sentiment.csv

| Column | Description|
| :-- |:--|
|'customer_id'| Unique customer identifier|
|'gender'| Customer gender |
|'age_group' | Age group of the customer |
|'region' | Geographic region of the customer |
|'product_category' | Category of product purchased |
|'purchase_channel' | Online / Offline / App |
|'platform' | Platform used for purchase/review |
|'customer_rating' | Rating given by customer (1–5) |
|'review_text' | Raw text of the customer review |
|'sentiment' | Positive / Negative / Neutral |
|'response_time_hours' | Time taken to respond to customer |
|'issue_resolved' | Whether the issue was resolved (Yes/No) |
|'complaint_registered' | Whether a complaint was filed (Yes/No) |


## Tools & Libraries Used
| Tool | Purpose|
| :--- | :--- |
| **Python 3.x** |Core programming language |
| **Pandas** |Data loading, cleaning, and analysis |
| **Matplotlib** |Data visualization |
| **Seaborn** |Statistical charts |
| **Jupyter Notebook** |Interactive analysis environment |


## Visualizations

1. **Category-Wise Average Rating**
<img width="1617" height="621" alt="category_wise" src="https://github.com/user-attachments/assets/e1b7e0e0-2433-46ac-842a-dc3a624d2d50" />

2. **Regional Distribution of Customers**
<img width="429" height="425" alt="regional_distribution" src="https://github.com/user-attachments/assets/a1275cc7-cb62-4026-bc11-eb631b7e04b7" />

3. **Average Rating by Region and Gender**
<img width="1601" height="559" alt="Average_rating_of_region_by_gender" src="https://github.com/user-attachments/assets/158e4dbc-b033-4cc8-a0eb-c3e547ef49a3" />


## Key Insights


* Sentiment varies by region — **East  and West**  regions show consistently higher negative sentiment, indicating localized service issues.
* Product category impacts ratings — **Fashion and Books** receive significantly lower ratings, pointing to quality or delivery issues.
* Gender-based rating patterns differ across regions — **In Central Region Females rated 3.077 while Males rated East region 3.03** useful for targeted marketing strategies.
* Response time correlation — **On average, issues resolved successfully had a response time of about 24 hours while for unresolved issues dragged on about 60 hours** longer response times are associated with lower customer ratings and unresolved complaints.
* Complaint resolution rate directly impacts repeat sentiment — **Surprising trend** as 66.4% of issues resolved yet both resolved and unresolved complaints gets same average ratings ~3.0 out of 5.



## Project Structure
```text
Customer-Sentiment-Analysis/
│
├── data/
│   └── Sentiment.csv                         
│
├── notebooks/
│   └── customer_sentiment.ipynb             
│
├── visualizations/
│   ├── category_wise.png                    
│   ├── regional_distribution.png            
│   └── Average_rating_of_region_by_gender.png  
│
└── README.md                                
```

## How to Run This Project


Clone the repository


```bash

git clone [https://github.com/Prashant-Singh-2208/Customer-Sentiment-Analysis.git](https://github.com/Prashant-Singh-2208/Customer-Sentiment-Analysis.git)
cd Customer-Sentiment-Analysis
```


Install required libraries



```bash
pip install pandas matplotlib seaborn jupyter
```

Open Jupyter Notebook



```bash
jupyter notebook customer_sentiment.ipynb
```

Run all cells to reproduce the full analysis



## Methodology

* Data loading and inspection
* Data cleaning (handling nulls, type conversion)
* Exploratory Data Analysis (EDA)
* Group-by aggregations and filtering
* Multi-variable visualization
* Business insight extraction from raw data



## Author

Prashant Singh
M.Sc. Physics | Aspiring Data Analyst
Varanasi, India
GitHub Profile
