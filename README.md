
# 🌐 Social Media Analytics Using SQL

### **Data-Driven Insights for User Engagement & Marketing Strategy | By Vishal Ratnakar**

<p align="center">
  <img src="https://img.shields.io/badge/Skills-SQL-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tools-PostgreSQL%20%7C%20MySQL-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Social%20Media%20Analytics-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Engagement%20%7C%20Retention%20%7C%20Acquisition-purple?style=for-the-badge" />
</p>

---

## 📌 **Project Overview**

You are hired as a **Data Analyst at Meta**, collaborating with the **Marketing Team** to build targeted strategies using Instagram-style platform data.
The goal:
✔ Increase **user engagement**
✔ Improve **retention**
✔ Boost **user acquisition**

Seven interlinked database tables provide insights into **user activity**, **content trends**, **engagement levels**, **follower networks**, and **behavior patterns**.

This SQL-driven project focuses on extracting actionable insights through relational queries and metric calculations.

---

## 🗂 **Dataset Structure**

The project uses **7 relational tables**:

### **1. Users**

* username
* created_at (join date)
* user_id

### **2. Photos**

* photo_id
* image_url
* user_id
* created_at

### **3. Comments**

* comment_id
* comment_text
* photo_id
* user_id
* created_at

### **4. Likes**

* user_id
* photo_id
* created_at

### **5. Follows**

* follower_id
* followee_id
* created_at

### **6. Tags**

* tag_id
* tag_name

### **7. Photo_Tags**

* photo_id
* tag_id

This relational structure enables multi-dimensional analytics across content, engagement, and user behavior.

---

## 🧠 **Methodology**

### **1️⃣ SQL Data Exploration**

* Identified user activity levels (posts, comments, likes)
* Extracted engagement metrics (total likes + comments received)
* Analyzed follower–followee relationships
* Mapped content categories via tags

### **2️⃣ User Segmentation**

Categories created using SQL conditions:

#### **Activity Segmentation**

* **High Activity** ≥ 250
* **Moderate Activity** 150–249
* **Low Activity** < 150
* **No Activity** = 0

#### **Engagement Segmentation**

* **High Engagement** ≥ 300
* **Moderate Engagement** 200–299
* **Low Engagement** < 200
* **No Engagement** = 0

### **3️⃣ Trend Analysis**

* Yearly user acquisition
* Content upload patterns
* Tag usage distribution
* Photo uploads vs engagement correlation

### **4️⃣ Marketing Insights**

Used SQL outputs to build targeted marketing recommendations for
**Retention, Acquisition, Engagement & Influencer Identification**

---

## 📈 **Key Insights**

### 🔹 **1. User Activity**

* **74 Active Users**, **26 Inactive Users**
* Large inactivity segment → retention challenge
* Only **6 users** posted more than 6 photos
  👉 Very small cluster of highly active users

---

### 🔹 **2. Tag Behavior**

* **21 unique tags**
* **31 users** never used tags
  🔥 Most common tags align with emotional, fun, and aesthetic content
  👉 Tag education can help increase discoverability

---

### 🔹 **3. Activity Distribution**

* **Low Activity (0–9): 23 users**
* **Moderate Activity (130–139): 8 users**
* **High Activity (170–179): Only 1 user**
  👉 User base is majorly passive or mildly active

---

### 🔹 **4. Engagement Patterns**

* **Low Engagement (0–49): 13 users**
* **Moderate (50–99): 18 users**
* **High (300–349): 13 users**
* Very high engagement is extremely rare (1–2 users)
  👉 Strong opportunity to improve engagement across platform

---

### 🔹 **5. Joining Year Insights**

* **2016 Users:** 65
* **2017 Users:** 35
  👉 Acquisition dropped in 2017 → requires marketing intervention
  👉 2017 users show *higher engagement*

---

### 🔹 **6. Uploads & Engagement Correlation**

* Strong positive correlation
* Users with **12 uploads → highest engagement (749)**
* Growth slows after 10–11 uploads
  👉 Quality > Quantity

---

### 🔹 **7. Potential Influencers**

Identified top 5 high-follower + high-engagement users
Ideal for:
✔ Campaign promotion
✔ Organic reach
✔ Ambassador programs

---

## 🎯 **Strategic Recommendations**

### **1️⃣ User Retention**

* Personalized content suggestions
* Time-limited offers to reactivate users
* Short onboarding guides
* Quick surveys for inactive users

### **2️⃣ User Acquisition**

* Referral programs
* Personalized onboarding
* Tag education campaigns
* Influencer partnerships

### **3️⃣ User Engagement**

* "User of the Month" & photo contests
* Community-building forums
* Creator education resources
* Ambassador + influencer-led promotions

---

## 🛠 **Tech Stack**

* **SQL (MySQL / PostgreSQL)**
* Window Functions
* Joins & Subqueries
* Aggregations
* Segmentation Logic
* Data Modeling & Schema Understanding

---

## 📊 **Dashboard / PPT**

This repository also includes:

📌 `VISHAL_Social-Media_PPT.pptx` — Presentation with visuals, insights & charts

---

## 📦 **Repository Structure**

```
├── README.md
├── VISHAL_Social-Media_PPT.pptx
├── SQL Queries/
│   ├── activity_analysis.sql
│   ├── engagement_analysis.sql
│   ├── influencer_queries.sql
│   ├── tag_usage_analysis.sql
│   └── user_segmentation.sql
└── dataset/ (optional)
    └── *.csv
```

---

## 👨‍💻 **Author**

**Vishal Ratnakar**
Data Analyst | SQL Expert | Social Insights | Analytical Storytelling

---

## ⭐ **If you found this project valuable, consider starring the repository!**


