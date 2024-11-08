# 📊 Market Analysis Project with Power BI

## 📝 Project Overview
Welcome to the Market Analysis Project! This project, developed in collaboration with **MarketMindz**, focuses on analyzing customer data and campaign performance for a retail vendor in the food and beverage industry. The goal is to extract valuable insights that inform our client about customer preferences, product popularity, and campaign success factors.

## 🎯 Objectives
- **📈 Campaign Performance Analysis**: Evaluate the effectiveness of six recent marketing campaigns.
- **🍷 Product Performance**: Identify which products are driving revenue and customer interest.
- **👥 Customer Profiling**: Understand demographic factors such as education level, marital status, and family structure.
- **🔍 Influence Drivers**: Determine key factors influencing campaign performance and purchase decisions.

## 🔄 Data Model
Originally, all data resided in a single table called **"Marketing Data"**, which combined information on campaigns, customers, products, and channels. After data transformations, we structured the data into separate tables for a more organized and in-depth analysis:

1. **📢 Canal**: Details the distribution channels (e.g., web, store, catalog, deals) used across campaigns.
2. **🛒 Products**: Lists products involved in campaigns, enabling product-specific analysis.
3. **📅 Campaign**: Contains unique attributes of each campaign, including performance metrics and customer engagement data.

This transformed data model allows for a focused and efficient analysis of the campaign metrics, customer segmentation, and product performance.

## 📊 Key Performance Indicators (KPIs) and Insights

1. **💥 Top Campaign by Purchases**: **Campaign 6** had the highest number of purchases attributed to it.
2. **🏆 Best-Selling Products**: Wine consistently emerged as the top-selling product, followed by meat and baked goods.
3. **💰 Sales Revenue by Campaign**: Campaigns 6 and 5 led in revenue, with Campaign 6 generating the highest total.
4. **🧑‍🎓 Customer Demographics**:
   - **Education**: The majority of customers have a university-level education.
   - **Marital Status**: A large portion of customers are married.
   - **Family Structure**: 58% of customers do not have children at home, and 52% do not have teenagers.
5. **💳 Spending & Platform Preferences**:
   - **Top-Spending Product**: Wine generated the highest revenue, followed by meat.
   - **Preferred Purchase Platforms**: Most purchases occurred via stores and online platforms.
6. **💡 Customer Segmentation by Income**: Customers with an income above $60,585 were more likely to engage with **Campaign 1**.

## 🌟 Key Influencers
The Key Influencers visualization helped identify important factors that impact campaign acceptance and overall sales. Key drivers include:

- **💵 Income**: Higher-income customers showed greater engagement with certain campaigns.
- **🌐 Web Visits**: Customers with frequent web visits tended to participate more in campaigns.
- **👨‍👩‍👧 Family Composition**: Households without children or teenagers showed higher spending patterns.

## 🚀 Installation and Usage
To explore this project on Power BI Desktop, follow these steps:

1. **Clone the Project Repository**:
   ```bash
   git clone <repository-url>
