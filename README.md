# 📊 Zomato Market Expansion & Pricing Analysis

## 📌 Project Overview
This project analyzes Zomato’s restaurant ecosystem across cities, states, and zones in India to uncover patterns in **market penetration, cuisine diversity, and pricing behavior**.

The objective is to translate raw operational data into **actionable business insights** that can inform **market expansion, localization, and pricing strategies**.

The analysis is designed as a real-world **Data Analyst case study**, emphasizing data cleaning, exploratory analysis, and business-driven recommendations.

---

## 🧠 Business Questions Addressed
- How is Zomato’s restaurant presence distributed across zones, states, and cities?
- Are Tier-1 or Tier-2 cities driving platform adoption?
- Which cuisines dominate nationally, and where does regional specialization occur?
- How do average prices vary across zones?
- What strategic actions can be derived from these patterns?

---

## 📂 Dataset
- **Source:** Zomato restaurant dataset
- **Records:** ~44,000 restaurants
- **Key fields:**
  - Location, State, Zone
  - Cuisine categories (up to 5 per restaurant)
  - Average price (text → numeric)
  - Average delivery time (text → numeric)
  - Ratings

> **Note:** Pricing and delivery time fields were originally text-based  
> (e.g., “₹50 for one”, “36 min”) and were cleaned and standardized as part of this analysis.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook (Google Colab compatible)

---

## 🔍 Analytical Approach
1. Data Loading & Overview  
2. Data Quality Checks (missing values, duplicates, data types)  
3. Data Cleaning & Validation  
   - Text standardization  
   - Numeric extraction from pricing and delivery time fields  
4. Exploratory Analysis  
   - Market presence by zone, state, and city  
   - Tier-1 vs Tier-2 city comparison  
   - Cuisine diversity and regional specialization  
   - Pricing patterns across zones  
5. Synthesis  
   - Key insights  
   - Business recommendations  
   - Limitations and next steps  

---

## 📈 Key Insights
- Restaurant presence is uneven across regions, with **North and Central zones** showing the highest penetration.
- **Tier-2 cities account for the majority of restaurant listings**, highlighting strong adoption beyond major metros.
- Cuisine demand is highly concentrated, with **North Indian, Fast Food, and Chinese** dominating nationally.
- Clear regional cuisine specialization exists (e.g., South Indian cuisine in southern zones).
- Pricing varies moderately by zone, with **North, South-1, and East zones** exhibiting higher average prices than Central and South-2 zones.

---

## 🎯 Business Recommendations
- Prioritize expansion and merchant onboarding in high-performing **Tier-2 cities**, which account for the majority of restaurant listings.
- Focus on differentiation strategies in highly saturated zones (North and Central), such as premium listings and improved discovery.
- Leverage dominant cuisines for platform-wide campaigns while using region-specific cuisine preferences for localized marketing.
- Implement **zone-level pricing and promotional strategies based on observed average price differences across zones** to align with regional spending behavior and maximize conversion.
- Explore cross-selling opportunities by bundling popular cuisines with high-demand add-ons such as beverages and desserts.

---

## ⚠️ Limitations & Future Work
- The dataset does not include order volume or revenue metrics, limiting demand intensity analysis.
- City tier classification is simplified and may not capture all urban nuances.
- Future analysis could integrate order-level data, time-based trends, customer behavior, and logistics performance.

---

## ▶️ How to Run This Project
1. Clone the repository  
2. Open the notebook:

