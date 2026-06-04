# 🏠 Airbnb NYC Case Study | Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)

---

# 📌 Project Overview

This project explores Airbnb listings across **New York City** to uncover valuable business insights related to hosts, neighborhoods, pricing patterns, room types, and customer preferences.

Using **Exploratory Data Analysis (EDA)** techniques, the study identifies market trends, busiest locations, popular room types, and factors affecting Airbnb listings.

---

# 🎯 Business Problem

Airbnb hosts and travelers often face challenges in understanding:

- 🏘️ Which neighborhoods attract the most visitors?
- 💰 How are Airbnb prices distributed across NYC?
- 👤 Who are the most active hosts?
- 🏠 Which room types are most preferred?
- 📈 Can listing popularity be predicted using available data?

The goal is to analyze Airbnb listing data and generate actionable insights that support data-driven decision-making.

---

# 📂 Dataset Information

The dataset contains Airbnb listings from **New York City**, including:

| Feature | Description |
|----------|------------|
| property_id | Unique property identifier |
| property_name | Listing name |
| host_id | Unique host identifier |
| host_name | Host name |
| neighbourhood_group | Larger geographical area |
| neighbourhood | Specific neighborhood |
| latitude | Property latitude |
| longitude | Property longitude |
| room_type | Type of accommodation |
| price | Price per night |
| minimum_nights | Minimum stay requirement |
| total_reviews | Total customer reviews |
| reviews_per_month | Monthly review count |
| host_listing_count | Number of listings owned by host |
| availability_365 | Availability in a year |

---

# 🛠️ Tools & Technologies

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook

---

# 🧹 Data Cleaning Process

The following preprocessing steps were performed:

✅ Renamed confusing column names

✅ Handled missing values

✅ Replaced null host/property names with "Unknown"

✅ Removed unnecessary columns

✅ Converted missing review values to 0

✅ Checked for duplicate records

✅ Removed price outliers using IQR Method

---

# 🔍 Exploratory Data Analysis

### 📍 Host & Neighborhood Analysis

- Identified total unique hosts
- Analyzed neighborhood distribution
- Evaluated neighborhood group popularity

### 💰 Pricing Analysis

- Studied Airbnb pricing distribution
- Detected skewness and pricing concentration
- Removed extreme outliers

### 🏠 Room Type Analysis

- Compared popularity of different room types
- Determined the most preferred accommodation type

### 📈 Correlation Analysis

- Generated correlation heatmap
- Explored relationships between numerical variables

---

# 📊 Key Findings

### 🏙️ Neighborhood Insights

- NYC contains **5 major neighborhood groups**
- More than **220 unique neighborhoods**
- Brooklyn and Manhattan are the busiest areas

### 👤 Host Insights

- Over **37,000 hosts** operate listings
- Many hosts own multiple properties

### 💰 Pricing Insights

- Average Airbnb price is approximately **$152 per night**
- Most listings fall between **$50 – $200**
- Price distribution is heavily right-skewed

### 🏠 Room Type Insights

- Entire Home/Apartment is the most popular room type
- Private rooms are the second most preferred option

### ⭐ Popularity Insights

- Manhattan receives the highest overall attention
- Williamsburg is among the most popular neighborhoods

---

# 📈 Visualizations Included

✔️ Price Distribution Histogram

✔️ Neighborhood Group Count Plot

✔️ Room Type Distribution

✔️ Correlation Heatmap

✔️ Outlier Detection Boxplots

---

# 💡 Business Recommendations

### 🏠 For Hosts

- Focus on high-demand areas such as Manhattan and Brooklyn
- Optimize pricing within the $50–$200 range
- Increase availability during peak demand periods

### 📊 For Airbnb

- Promote underutilized neighborhoods
- Encourage hosts to improve guest experience
- Use review-based recommendation systems

### 👥 For Travelers

- Consider neighborhoods outside Manhattan for better value
- Entire apartments provide the most popular accommodation experience

---

# 📁 Project Structure

```bash
Airbnb-NYC-Case-Study/
│
├── Airbnb_data.csv
├── AirBnb_Case_Study.ipynb
├── README.md
│
└── Visualizations/
    ├── Price_Distribution.png
    ├── Room_Type_Count.png
    ├── Neighbourhood_Group_Count.png
    └── Correlation_Heatmap.png
```

---

# 🚀 Future Improvements

- 🤖 Build price prediction models
- 📈 Forecast listing demand
- 🗺️ Create interactive geospatial dashboards
- 🎯 Predict listing popularity using Machine Learning
- 📊 Deploy insights through Power BI/Tableau dashboards

---

# 📚 Skills Demonstrated

- Data Cleaning 🧹
- Exploratory Data Analysis 📊
- Data Visualization 📈
- Business Insight Generation 💡
- Statistical Analysis 📉
- Outlier Treatment 🔍
- Python Programming 🐍

---

# 👨‍💻 Author

**Kunal Tomar**

🎓 B.E. Information Technology | NIT Karnataka

📊 Aspiring Data Analyst

💻 Python | SQL | Power BI | Excel | Machine Learning

🔗 GitHub: *(Add your GitHub Profile Link Here)*

---

## ⭐ If you found this project useful, don't forget to Star the repository!
