# 🛒 Instacart Python Analysis

**Analyzing Baskets. Predicting Behavior.**

## Objective
<img src="instacart_logo.png" alt="Instacart Logo" width="200">
This project explores customer behavior in an online grocery platform using Python. I focused on data wrangling, feature engineering, and predictive modeling to find key trends like which customer types order most frequently, which products dominate carts, and what drives loyalty.

---

## 🚀 Fast Facts for Busy Reviewers

- **Tool Stack:** Python (Pandas, NumPy), Jupyter Notebooks, Matplotlib, Seaborn  
- **Focus Areas:** Cleaning, feature engineering, data exploration, predictive logic  
- **Dataset:** 3M+ grocery orders across 200K Instacart users  

### 🔑 Key Wins:
- Identified peak shopping hours, most common order sizes, and reordering patterns  
- Mapped family-oriented and loyalty-driven behaviors  
- Built visual dashboards to spotlight shopper segments  
- Cleaned, wrangled, and exported high-volume transaction data efficiently

---

## 🎯 The Challenge

Instacart’s dataset offers a detailed look at customer orders. The data can help us understand customer behavior in order to support smarter decision-making across Instacart’s platform.

The questions we must explore are:
- What day/time do customers prefer to shop?
- What products are bought most often?
- Who are the loyal customers?
- Are there spending patterns based on region or family size?

---

## 🧼 Data Cleaning Highlights

Working with this dataset required thoughtful preprocessing:
- **Reduced to core tables** for manageable memory use  
- **Renamed and merged** data for clarity  
- **Engineered features** like reorder rates and cart positioning  
- **Filtered edge cases** (e.g., nulls, missing departments)  
- **Validated joins** between customer, product, and order tables  

📁 Notebooks in the `Scripts/` and `Analysis/` folders cover:
- Order-level cleaning  
- Feature creation (e.g. days since prior order, reorder rates)  
- Segment profiling and visualization

---

## 📊 Key Visuals & What They Show

- **Orders by Day of the Week:** When do people shop most?
- **Customer Loyalty Chart:** Who keeps coming back?
- **Family-Oriented Shoppers:** Which products are repeated most in large households?
- **Regional Patterns:** Spending variations by region or location clues  
- **Product Popularity:** What’s in everyone's cart?

---

## 🧠 Main Insights (Recap)

- **🧺 Big Baskets = Frequent Shoppers**  
  A small segment of customers drove the majority of reorders. Targeting high-volume users could have an outsized impact.

- **📍 Regional Shopping Patterns**  
  Customers in the Midwest and South ordered more produce and family essentials. Shoppers in the Northeast leaned toward smaller, specialty carts.

- **👨‍👩‍👧 Family-Oriented Shoppers**  
  Larger households (4+ members) had higher average basket sizes and reordered the same products often — signaling loyalty potential.

---

## 💼 From Data to Decisions
Based on this analysis, here’s how Instacart could take smarter action:

1. **Pinpoint Peak Days**  
  Weekends and Mondays were high-traffic reorder days. Promotions or reminders could boost engagement.

2. **Reach Loyalty Clusters**  
  Families and loyal reordering users are prime targets for subscription incentives and bundled offers.

3. **Prioritize Regional Needs**  
  Stock more family essentials in Midwest/Southern areas; test specialty offerings in coastal regions.

4. **Enhance Personalization**  
  Use behavior-based clusters to refine targeting for recommendations, promos, and seasonal items.

---

## 🛠️ Tools Used

- **Python** (Pandas, NumPy) — for data wrangling, analysis, and feature engineering  
- **Matplotlib & Seaborn** — for data visualization  
- **Jupyter Notebooks** — to write and run all scripts interactively 

---

## 📁 Repository Structure

```bash
Instacart-Python-Analysis
│
├── Analysis/                    # Final data checks and QA on grouped results
│
├── Scripts/                    # Python notebooks for wrangling, EDA, visuals
│
├── Sent to Client/            # Final report files prepared for delivery
│
├── instacart_logo.png         # Custom header image for visual polish
└── README.md                  # Project overview, insights, and repo guide
```
