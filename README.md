# 📈 Website Traffic & User Behavior Overview– SQL + Power BI Project

## Business Problem:
A digital business operating across 7 countries lacked a consolidated view of website engagement — making it hard to understand device preferences, high-traffic pages, returning user behavior, and which UI elements were driving conversions.

 **Domain:** Web Analytics | User Behavior Insights | Marketing Analytics  
 
 **Tools Used:** SQL (MySQL) • Power BI

## 🗃️ Dataset & Schema

I designed a **relational database schema** to represent website interaction data. The database consists of 6 interrelated tables:

| Table Name       | Description                                      |
|------------------|--------------------------------------------------|
| `visitors`       | Basic info about site visitors                   |
| `sessions`       | Start/end time, session duration per visitor     |
| `page_views`     | Pages visited within each session                |
| `events`         | Actions like clicks, scrolls, signups            |
| `devices`        | Device type, OS, browser used                    |
| `traffic_sources`| Source (Google, Email, Social, etc.), campaign   |

---

## 🔍 SQL Exploration

I wrote 20+ queries to extract insights such as:

- Total visitors by country & city  
- New vs Returning visitors  
- Sessions by device type, browser, OS  
- Top marketing campaigns & traffic mediums  
- Most viewed pages and avg. time spent  
- Top event types (clicks, signups, scrolls)  
- Visitor activity rankings using `RANK()` (Window Function)  
- Average session duration by source using a `CTE`  
- Sessions longer than average using a `Subquery`  

---

## 📊 Power BI Dashboard

I built an **interactive dashboard** in Power BI to showcase key insights:

### 🔹 Page 1: Website Overview
- Total sessions  
- Average session duration  
- Device breakdown (desktop/tablet/mobile)  
- Session trend line  

### 🔹 Page 2: Traffic Sources
- Top traffic sources & marketing campaigns  
- Organic vs Paid vs Referral vs Email  
- Average session duration by source  

### 🔹 Page 3: User Behavior
- Most viewed pages  
- Avg. time spent per page  
- Most clicked elements  
- Sessions with signup events  
 ## What I Did:

Connected and modeled website session data across Australia, Brazil, France, Germany, India, UK, and USA
Built KPI cards for Total Visitors (18), Sessions (59), Avg Session Duration (15 min), Avg Time/Page (3 min), and % Returning Users (56%)
Designed a sessions-over-time line chart (June 2–30) showing weekly traffic spikes
Created a donut chart for device type split — Mobile 49%, Desktop 34%, Tablet 17%
Built a top pages by views table listing Homepage, About, Product, Contact, Blog, Pricing pages
Designed a treemap for most-clicked UI elements — Sign Up, Explore Plans, Subscribe Button, Learn More, Book Demo
Added country-level toggle filters for drilling into specific markets

## Key Insights:

56% returning users indicates strong content stickiness and brand loyalty
Mobile accounts for nearly half of all sessions — mobile-first design is critical
"Sign Up" and "Explore Plans" are the most clicked elements — users have high conversion intent
UK was the most active country in the selected filter view
Avg 15-minute session duration signals deep content engagement

## Impact: 

Insights directly guided UX team to prioritize mobile-responsive redesign; conversion funnel analysis of top-clicked elements helped optimize CTA placement; country-level data enabled targeted regional campaigns.
Dashboard Output: Power BI single-page dashboard with KPI cards, sessions timeline, device donut chart, top pages table, UI element treemap, and 7-country filter toggle.



