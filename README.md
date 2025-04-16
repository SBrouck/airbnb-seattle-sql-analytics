# airbnb-seattle-sql-analytics
Airbnb Seattle – Full SQL project: schema design, data modeling, and analytical queries on real marketplace data.
# 🏙️ Airbnb Seattle – Data Analytics Project (SQL + Python)

This project explores real Airbnb data from Seattle using SQL and Python to extract actionable insights on pricing dynamics, occupancy behavior, and listing performance across neighborhoods and room types.

As someone currently relocating to Seattle for my Master's in Business Analytics at the University of Washington, this analysis started as a personal deep-dive into the housing market — but quickly evolved into a full analytics case study. It also connects back to the professional real estate data I explored during my 2024 internship at Engel & Völkers (family office, Paris), where I conducted office acquisition studies and asset performance reviews.

> 🧠 The project is fully SQL-driven and runs inside Google Colab using SQLite. The visualizations are generated using `matplotlib` and `seaborn`.

---

## 📊 What This Project Covers

Each table or graph is the result of a real business question. Here's how it breaks down:

### 1. 🧩 Dataset Exploration (EDA)
We begin by exploring the listings, calendar, and reviews datasets, focusing on:
- Total number of listings and event types
- Price and review activity distribution
- Room types and category breakdowns

> This helps frame the scope of the market and spot any early outliers or data issues.

---

### 2. 🧠 High-Performance Listings
Using SQL, we identified listings that overperform in **price**, **occupancy**, and **reviews/month**. These are the "rockstars" of the platform — and ideal to learn from.

> This kind of segmentation is valuable for product managers or host consultants optimizing platform supply.

---

### 3. 🏘️ Room Type Comparison
We compared Entire Homes, Private Rooms, Shared Rooms, and Hotel Rooms across:
- Number of listings
- Price per night
- Average occupancy
- Review activity

> This provides a clear view of product strategy: which types perform best, and how users interact with each one.

---

### 4. 📆 Temporal Analysis
We looked at:
- 📈 Average price by **month** (seasonality)
- 📉 Average price by **weekday** (short-term dynamics)
- 📊 Occupancy by **weekday** (demand patterns)

> This insight is critical for yield management, revenue optimization, and travel behavior analysis.

---

## 🏗️ Technical Stack

- **Python (pandas, seaborn, matplotlib)**
- **SQLite (via ipython-sql magic in Google Colab)**
- **GitHub for version control**
- **Google Colab for cloud-based execution**

---

## 📁 Repo Structure


---

## 📌 Notes

- The dataset comes from publicly available Airbnb data through InsideAirbnb.com.
- This analysis is partial and based on 1 year of snapshot data. True insights would require longer temporal windows and contextual cross-data (e.g. events, weather).
- For privacy and performance, only lightweight data extracts are included.

---

## ✨ Final Thoughts

This project helped me grow not only as a data analyst — but also as a renter 😄  
Through this work, I better understood housing dynamics in Seattle, while also connecting it to my previous work on office markets in Europe.

As I prepare to start my MSBA at UW, this project is part of a larger portfolio of **analytics-focused storytelling** and **business-relevant data work**.

Feel free to reach out!

— Sacha Brouck  
[@sacha-brouck](https://www.linkedin.com/in/sacha-brouck)
