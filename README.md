# 📊 Customer Behavior & Conversion Analytics Project (AI-Assisted)

## 🚀 Project Overview

This project analyzes customer behavior, engagement patterns, and conversion performance using Python and Pandas.
The analysis focuses on understanding how user activities, devices, locations, referral sources, and engagement levels impact purchases and overall revenue.

AI-assisted analytical thinking was used to design structured data exploration, segmentation, funnel analysis, and business insight generation.

---

## 📁 Datasets Used

### 1️⃣ Customers Dataset (`customers_df`)

Contains customer demographic and behavioral summary information:

* customer_id (Primary Key)
* name, age, gender
* location (Metro, Tier 1, Tier 2, Rural)
* salary
* signup_date
* referral_source
* customer_status (New, Active, Inactive)
* preferred_device
* avg_session_time
* app_version
* total_purchases
* total_spend

### 2️⃣ Customer Activity Dataset (`customers_activity_df`)

Contains detailed event-level user interaction data:

* customer_id (Foreign Key)
* event_datetime
* event_name (login, product_view, add_to_cart, wishlist, buy_button_click)
* product_id
* page_name
* event_duration
* is_scroll
* app_version

---

## 🎯 Project Objectives

* Analyze user engagement patterns
* Study conversion funnel performance
* Identify churned or inactive users
* Segment customers based on activity levels
* Evaluate acquisition channel effectiveness
* Compare device and location performance
* Understand the relationship between engagement and revenue

---

## 🔎 Key Analyses Performed

### 📌 Engagement Analysis

* Event distribution by customer status, device, and location
* Activity trends by signup cohorts
* Activity segmentation (Low / Medium / High / Very High users)

### 📌 Conversion Funnel Analysis

* Funnel drop-off from product_view → add_to_cart → buy_button_click
* Conversion rate by referral source, device, and page
* Scroll behavior vs conversion likelihood

### 📌 Revenue & Spending Insights

* Correlation between activity levels and total spend
* Average spend by engagement category
* Identification of high-value user segments

### 📌 Churn & Retention Analysis

* Detection of inactive customers based on last activity
* Cohort activity trend analysis

### 📌 Product & Version Analytics

* Event frequency comparison across app versions
* Feature engagement performance tracking

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib (for trend visualization)
* AI-assisted analytical reasoning

---

## 📈 Key Business Insights Generated

* High engagement users contribute significantly to revenue
* Certain referral channels deliver higher conversion quality
* Device usage patterns influence engagement depth
* Funnel drop-off highlights optimization opportunities
* Regional activity differences help prioritize growth strategy

---

## 💡 Learning Outcomes

* Developed strong customer-level analytical thinking
* Practiced real-world funnel and segmentation analysis
* Improved ability to translate data into business insights
* Applied AI assistance for structured problem solving

---

## 📌 Future Improvements

* Build churn prediction model
* Implement cohort retention heatmaps
* Add revenue forecasting
* Perform A/B test simulations
* Create interactive dashboards

---

## 👤 Author

Sourav Kundu
Aspiring Data Analyst | Python | SQL | Power BI
