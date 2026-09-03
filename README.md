# QuickBite Food Delivery Analytics

Power BI food delivery analytics project analyzing QuickBite's business performance before and during a crisis period.

## 📌 Project Overview

QuickBite is a food delivery business case study focused on understanding how a crisis period affected different areas of the business.

The project combines Python-based data exploration and cleaning with an interactive Power BI dashboard to identify changes in customer activity, orders, delivery performance, ratings, sentiment, restaurants, and menu performance.

## 🎯 Business Objectives

- Understand how customer and order activity changed during the crisis period
- Evaluate delivery performance and SLA compliance
- Analyze customer ratings and sentiment trends
- Identify restaurant and cuisine performance patterns
- Understand popular menu items and dietary-category contribution
- Highlight areas that may represent opportunities for improvement

## 🛠️ Tools & Skills

- **Python** — Pandas, data cleaning and exploration
- **Power BI** — Dashboard development and data visualization
- **Power Query** — Data transformation and preparation
- **DAX** — Measures and business calculations
- **Data Modelling** — Fact and dimension modelling, relationships, and Date table
- **Data Visualization** — KPI cards, trends, comparisons, distributions, and analytical visuals
- **Business Analysis** — Translating analytical findings into business opportunities

## 📊 Dashboard Pages

### 1. Executive Overview

Provides a high-level view of overall business performance, including revenue, orders, customers, customer rating, SLA compliance, cancellation rate, and monthly trends.

### 2. Customer & Order Analysis

Analyzes customer and order decline, acquisition channels, city-level performance, and customer segments.

### 3. Delivery Performance

Examines SLA compliance, average delivery time, delivery delays, delivery partner performance, and delivery patterns.

### 4. Ratings & Sentiment Analysis

Explores rating trends, sentiment distribution, cuisine-level ratings, low-rated restaurants, rating distribution, and customer review keywords.

### 5. Restaurant & Menu Analysis

Analyzes restaurant and cuisine revenue, popular menu items, dietary classification, category contribution, and restaurant/menu performance.

## 🔎 Key Insights

- Customer and order activity declined significantly during the crisis period, with Bengaluru experiencing the largest customer and order decline, as it had the highest pre-crisis activity.
- More than 20K deliveries fell into both the 1–5 minute and 6–10 minute delay categories, highlighting an opportunity to improve delivery operations.
- Positive reviews declined from **95.23% pre-crisis to 58.51% during the crisis**, accompanied by a significant decline in sentiment score.
- 5-star ratings remained the most common rating in both periods, but the crisis period recorded significantly fewer 5-star ratings.
- Non-veg items contributed around **50% of total revenue** while accounting for only **33.89% of quantity sold**, indicating a higher revenue contribution per item.
- North Indian cuisine was the most-sold cuisine, while individual items such as Sweet Lassi, Veg Cutlet, Veg Manchurian, Paneer Tikka, and Masala Chai were among the most-sold menu items.

## 💡 Business Perspective

The analysis goes beyond reporting metrics by considering what the findings could mean for the business. The dashboard highlights potential opportunities around delivery operations, customer experience, sentiment and ratings, and high-value restaurant and menu segments.

## 📷 Dashboard Preview

Dashboard screenshots are available in the [`Screenshots`](Screenshots/) folder.

## 📁 Project Structure

```text
QuickBite-Food-Delivery-Analytics/
├── README.md
├── Data/
│   └── QuickBite_Cleaned_Data/
├── Python/
│   └── QuickBite_EDA.ipynb
├── PowerBI/
│   └── QuickBite_Recovery_Dashboard.pbix
└── Screenshots/
    ├── Overview.png
    ├── Customer_Order_Analysis.png
    ├── Delivery_Performance.png
    ├── Ratings_Sentiment_Analysis.png
    └── Restaurant_Menu_Analysis.png
```

## 📂 Dataset

The original/raw datasets are **not included in this repository**. The project was developed using the QuickBite case-study dataset.

A **cleaned and prepared version of the dataset is included** under the `Data/QuickBite_Cleaned_Data/` folder. This allows the data preparation and analysis workflow to be more reproducible while keeping the original/raw source data excluded from the repository.

## 🔗 Interactive Dashboard

[View the Interactive Power BI Dashboard](https://tinyurl.com/quickbite-bi-dashboard)

## 🙏 Acknowledgement

A big thank you to **Codebasics** for providing the QuickBite case study and the opportunity to work through this business scenario.

---

*Built as a data analytics portfolio project to practice data exploration, transformation, modelling, visualization, and data analysis.*
