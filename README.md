# Customer Segmentation using RFM Analysis
A comprehensive customer analytics project that applies RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment eCommerce customers based on purchasing behavior. This project transforms large-scale transactional data into actionable business insights and marketing strategies using Python-based data analysis, machine learning, and visualizations.

## Project Overview
This project focuses on identifying meaningful customer segments from an eCommerce transaction dataset to support targeted marketing, customer retention, and revenue optimization. By combining classical RFM scoring with unsupervised machine learning, the system uncovers high-value customers, at-risk segments, and growth opportunities.
The analysis demonstrates real-world data preprocessing, behavioral modeling, clustering optimization, and business-oriented interpretation of results, making it highly relevant for analytics, data science, and marketing intelligence roles.

## Key Features
### Data Preprocessing & Cleaning
- Removal of missing customer IDs, cancellations, invalid prices, and returns
- Feature engineering (TotalPrice, datetime conversions)
- Retention of high-quality transactional records for analysis

### RFM Metric Calculation
- Recency: Days since last purchase
- Frequency: Total number of orders per customer
- Monetary: Total spend per customer

### RFM Scoring & Segmentation
- Quartile-based scoring (1–4) for each RFM metric
- Combined RFM score generation for behavioral comparison

### Customer Segmentation with Machine Learning
- K-Means clustering on RFM scores
- Optimal cluster selection using Elbow Method and Silhouette Score
- Identification of actionable customer groups

### Segment Profiling
- Champions
- At Risk
- Promising
- Potential Loyalists
- Lost Customers

### Business Insights & Marketing Strategy
- Revenue concentration analysis (Pareto principle)
- Churn risk identification
- Segment-specific marketing recommendations
- Budget allocation strategy based on customer value

## Technologies Used
- Programming Language: Python 3.x
- Data Analysis: pandas, numpy
- Machine Learning: scikit-learn (K-Means, Silhouette Score)
- Data Visualization: matplotlib, seaborn
- Clustering Techniques:
1.  K-Means
2. Elbow Method
3. Silhouette Analysis

## Visualizations
The project generates a rich set of analytical visualizations, including:
### Customer & RFM Analysis
- Top 5 customers by order volume
- RFM score distributions with density curves
- Correlation heatmap between R, F, and M scores

### Clustering Analysis
- Elbow curve for optimal cluster selection
- Silhouette score comparison
- 2D and 3D customer segmentation plots (R × F × M)

### Time-Based Analysis
- Orders by day of the week
- Orders by hour of the day
- Monthly and seasonal order trends

### Geographical & Product Insights
- Top countries by order volume
- Average Order Value (AOV) by country
- Return rate by product category
- Top products by profit margin

## Key Insights
- Strong revenue concentration, where ~30% of customers generate over 70% of total revenue
- Identification of a small VIP elite segment contributing disproportionately high value
- Large one-time buyer population, highlighting conversion challenges
- Clear churn risk signals in At Risk and Lost segments
- Frequency identified as the strongest driver of customer lifetime value
- High geographic dependency on the UK, indicating diversification opportunities

## Marketing Recommendations
- Champions: VIP loyalty programs, personalized offers, referral incentives
- At Risk: Win-back campaigns, personalized recommendations, feedback surveys
- Promising: Automated onboarding journeys and second-purchase incentives
- Potential Loyalists: Milestone-based rewards and seasonal reactivation
- Lost: Low-cost reactivation and list hygiene strategies
A data-driven budget allocation framework is proposed to maximize ROI across segments.

## Future Enhancements
- Predictive churn modeling using supervised ML
- Integration with CRM and marketing automation platforms
- Real-time customer segmentation dashboards
- Customer Lifetime Value (CLV) forecasting
- Web-based interactive analytics interface
