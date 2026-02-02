# 📊 Zomato Bangalore Restaurant Data Analysis

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Zomato Bangalore restaurant dataset to extract **data-driven business insights**.  
The analysis focuses on understanding restaurant performance based on **ratings, pricing, cuisines, locations, and service availability**, helping stakeholders make informed decisions.

## 🏢 About Zomato
Zomato is one of India’s leading restaurant discovery and food delivery platforms. It helps users explore restaurants, view ratings and menus, and place online orders.  
Zomato partners with thousands of restaurants and plays a key role in shaping customer dining preferences.

## ❓ Business Problem
The objective of this project is to analyze restaurant data from Bangalore to:

- Identify high-performing restaurant types and cuisines  
- Compare **Delivery vs Dine-out** restaurants  
- Understand how **pricing, ratings, and services** impact customer behavior  
- Identify the best locations to open new restaurants  

The goal is to help **Zomato and restaurant owners** improve business performance using data-backed insights.

## 📂 Dataset Information
**Dataset Name:** Zomato Bangalore Dataset  

The dataset contains restaurant listings with the following attributes:

| Column Name | Description |
| name | Name of the restaurant |
| online_order | Online ordering availability |
| book_table | Table booking availability |
| rate | Restaurant rating |
| votes | Number of user votes |
| location | Restaurant location |
| rest_type | Type of restaurant |
| cuisines | Cuisines served |
| approx_cost(for two people) | Cost for two people |
| listed_in(type) | Delivery / Dine-out |

⚠️ The dataset is **messy** and contains missing values, inconsistent formats, and text-based numerical columns.

## 🧹 Data Pre-Processing
The following steps were performed before analysis:
- Cleaned rating column (`4.2/5 → 4.2`)
- Converted cost column to numeric
- Handled missing values
- Removed duplicate records
- Split and exploded multi-valued columns:
  - Cuisines
  - Restaurant types
  - Locations

## 📊 Exploratory Data Analysis
### 🔹 Non-Graphical Analysis
- Distribution of online ordering and table booking
- Count of restaurant types and locations
- Number of unique cuisines

### 🔹 Visual Analysis
**Univariate Analysis**
- Rating distribution  
- Cost for two distribution  
- Votes distribution  

**Bivariate Analysis**
- Rating vs Online Order  
- Rating vs Table Booking  
- Rating vs Restaurant Type  
- Rating vs Top Locations  

## 🔍 Key Insights
- Restaurants offering **online ordering** tend to receive higher ratings  
- **Mid-range priced restaurants** perform better than very expensive ones  
- Certain cuisines dominate among top-rated restaurants  
- Some locations show higher customer engagement and competition  
- Zomato has a stronger focus on **delivery-based restaurants**

## 💡 Business Recommendations
- Promote online ordering among partner restaurants  
- Encourage mid-range pricing strategies  
- Focus on high-demand cuisines  
- Expand restaurant partnerships in high-performing locations  
- Use ratings and votes to prioritize restaurant promotions  

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook
  
## 📁 Project Structure
Zomato-Restaurant-Data-Analysis/ │ ├── Dataset/ ├── Notebook/ ├── Output_PDF/ └── README.md

## ✅ Conclusion
This project demonstrates a **business-focused EDA approach**, converting raw restaurant data into **clear insights and actionable recommendations** that support strategic decision-making.
