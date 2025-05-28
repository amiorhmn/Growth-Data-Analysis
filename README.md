# Growth-Data-Analysis

The notebook contains various analysis on users' interaction and purchase data of a certain product on an e-commerce platform and insights to help improve user retention and overall growth.

## Dataset
The dataset contains 20,000 users’ interactions with a certain product of an e-commerce website. The columns in the dataset are as follows:
- *user_id*: Unique identifier for each user
- *install_date*: Date when the user installed the product
- *last_active_date*: Last recorded activity date of the user
- *subscription_type*: The type of subscription the user has ("Free" or "Pro")
- *country*: User’s country
- *total_sessions*: Total number of times the user engaged with the product
- *page_views*: Total number of pages viewed by the user
- *download_clicks*: Indicates if the user clicked "Download Pro" (1 = Yes, 0 = No)
- *activation_status*: Whether the product was activated (1 = Yes, 0 = No)
- *days_active*: Total number of days the user was active
- *pro_upgrade_date*: If upgraded, the date the user subscribed to Pro
- *plan_type*: Type of subscription plan ("Basic", "Standard", or "Enterprise")
- *monthly_revenue*: Average monthly revenue accumulated from the user
- *churned*: Indicates if the user has churned (1 = User has churned, 0 = Still active)

## Data Analysis
The notebook contains following analysis

### Data Exploration & Cleaning
1. Data Loading and Exploration
2. Missing Value Handling
3. Summary of the dataset
4. Distribution of Free vs. Pro users

### User Engagement Analysis
1. Identification the average number of sessions for Free vs. Pro users
2. Top 5 most active users based on total sessions
3. Top 5 countries with the highest engagement

### Churn Analysis
1. Calculation of the overall churn rate for Free vs. Pro users
2. Top 3 factors contributing to churn using regression analysis
3. Comparison of churn trends between Free and Pro users

### Revenue & Upgrade Trends
1. Percentage of users upgraded from Free to Pro
2. Total monthly revenue from Pro users
3. Which Pro plan (Basic, Standard, or Enterprise) contributes to the most revenue
4. How long it takes for Free users to upgrade based on country and engagement level

### Actionable Growth Recommendations
1. Three strategies to reduce churn
2. Two ways to increase Free-to-Pro conversions
3. Potential market expansion opportunities based on country trends

### Conversion Rate Optimization (CRO)
1. Estimated impact on Pro upgrades
2. A simple A/B test simulation to evaluate conversion optimization
3. Three A/B test ideas that could help improve the conversion rate

### Growth Strategy & KPI Recommendations
1. Three key performance indicators (KPIs)
2. Two actionable growth strategies

### Data Storytelling & Visualization
1. Dashboard creation with three insightful charts and graphs