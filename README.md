# Python_Diwali_Sales_Analysis
OBJECTIVES:
-IMPROVE CUSTOMER EXPERIENCE BY ANALZING SALES DATA.
-INCREASE SALES REVENUE OR SALES AMOUNT.

DATA ANALYST PROJECT :
- Performed data cleaning and manipulation.
- Performed exploratory data analysis (EDA) using **pandas**, **matplotlib**, and **seaborn** libraries.
- Improved customer experience by identifying potential customers across different states, occupations, genders, and age groups.
- Improved sales by identifying most selling product categories and products, helping to plan inventory and meet demand.

# 🪔 Diwali Sales Data Analysis

## 📊 Project Overview
This project analyzes Diwali sales data to understand customer purchasing behavior and identify factors that impact sales performance.  
The goal is to derive actionable business insights that can help improve customer targeting, marketing strategies, and inventory planning during festive seasons.

---

## 🎯 Objectives
- Clean and preprocess raw Diwali sales data.
- Perform exploratory data analysis (EDA) to uncover patterns in customer demographics and purchasing behavior.
- Visualize relationships between key attributes like gender, age, state, occupation, and total purchase amount.
- Provide insights to improve business decisions during festive campaigns.

---

## 🧩 Dataset Information
- **Dataset Name:** `Diwali Sales Data.csv`  
- **Size:** ~11,000 records (after cleaning)
- **Features:**  
  - Customer details: `Gender`, `Age Group`, `Marital Status`, `State`, `Occupation`  
  - Purchase details: `Orders`, `Amount`, `Product Category`  

---

## 🧹 Data Cleaning Steps
- Dropped unrelated and blank columns (`Status`, `unnamed1`).
- Removed missing values using `dropna()`.
- Converted `Amount` column to integer type.
- Renamed columns for better readability.
- Verified data consistency using `info()` and `describe()` methods.

---

## 📊 Exploratory Data Analysis (EDA)
### 1. Gender
- Majority of buyers are **female**.
- Females have a **higher total purchase amount** compared to males.

### 2. Age Group
- Most active buyers belong to the **26–35 years** age group.
- Within this group, females contribute the most to total revenue.

### 3. State
- Top 3 states by sales and order volume:  
  🥇 **Uttar Pradesh**  
  🥈 **Maharashtra**  
  🥉 **Karnataka**

### 4. Marital Status
- **Married women** are the dominant customers with higher average spending.

### 5. Occupation
- Customers from **IT, Healthcare, and Aviation** sectors spend the most.

### 6. Product Category
- Top-selling categories: **Food, Clothing, and Electronics**.

---

## 💡 Key Insights
- Focus marketing efforts on **females aged 26–35**, especially in **UP, Maharashtra, and Karnataka**.
- Promote **family-oriented offers** targeting **married women**.
- Prioritize **electronics and clothing** categories for festive discounts.
- Strengthen inventory and ad campaigns in top-performing states.

---

## ⚙️ Technologies & Tools Used
| Category | Tools |
|-----------|--------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 🧮 Project Workflow
1. **Data Import & Inspection**  
   - Load CSV using pandas and inspect structure.
2. **Data Cleaning**  
   - Handle nulls, drop redundant columns, and correct data types.
3. **Exploratory Data Analysis (EDA)**  
   - Perform groupby and aggregation.
   - Create countplots, barplots, and distribution charts.
4. **Visualization & Insights**  
   - Draw business conclusions from data trends.

---

## 📈 Sample Visualizations
| Visualization | Insight |
|----------------|----------|
| ![Gender vs Amount](https://via.placeholder.com/300x150?text=Gender+vs+Amount) | Females spend more than males. |
| ![Age Group vs Orders](https://via.placeholder.com/300x150?text=Age+Group+vs+Orders) | Highest orders from 26–35 age group. |
| ![State-wise Sales](https://via.placeholder.com/300x150?text=Top+10+States) | UP, Maharashtra, Karnataka lead sales. |

*(Replace placeholders with your actual plot screenshots if uploading visuals)*

---

## 🚀 Future Enhancements
- Add predictive analysis (forecast next Diwali sales using regression).
- Apply customer segmentation using clustering.
- Create an interactive dashboard (Power BI / Tableau).

---

## 👨‍💻 Author
**Shreyansh Jain**  
Data Analyst | Python Enthusiast | Visualization & Insights  

---

## 📂 Repository Structure
