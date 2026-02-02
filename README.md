# AI-Assisted Business-Driven EDA on Superstore Data

## Overview
This project performs a **business-focused exploratory data analysis (EDA)** on the Superstore sales dataset to identify profitability drivers, loss patterns, and operational inefficiencies.

The analysis uses **Python for all computations and visualizations**, with **AI assistance (ChatGPT)** used to frame analytical questions, validate assumptions, and summarize insights — aligning with the *ChatGPT Advanced Data Analysis* certification.

---

## Business Objectives
The analysis answers the following key business questions:

1. Which product categories generate sustainable profit?
2. Which customer segments are most margin-efficient?
3. How does regional performance differ?
4. What is the impact of discounting on profitability?
5. Where are losses concentrated, and why?
6. Does shipping delay affect profit margins?

---

## Dataset
- **Name:** Superstore Sales Dataset  
- **Format:** CSV  
- **Type:** Structured retail transaction data  
- **Records:** ~10,000 rows  

The dataset includes order details, customer segments, regions, sales, profit, discounts, and shipping information.

---

## Tools & Technologies
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- Jupyter Notebook  
- ChatGPT (AI-assisted analysis support)

---

## Analytical Approach

### Data Preparation
- Validated data quality and missing values
- Parsed and cleaned date fields
- Removed duplicates and logically invalid records
- Engineered business-relevant features such as:
  - Profit Margin
  - Shipping Delay
  - Time-based attributes

### Outlier Treatment
- Applied IQR-based outlier handling for:
  - Shipping Delay
  - Profit Margin
- Preserved raw data while using filtered data for trend analysis to avoid distorted conclusions

---

## Key Insights
- Profitability depends more on **margin** than sales volume
- Technology is the strongest profit-generating category
- Furniture shows margin erosion despite high revenue
- Discounts have a clear negative impact on profit margins
- Corporate customers deliver more stable profitability than Consumer segments
- Regional performance varies significantly, requiring localized strategies
- Longer shipping delays increase profit volatility

---

## Business Recommendations
- Re-evaluate discount strategies for low-margin categories
- Focus growth initiatives on high-margin product segments
- Introduce region-specific pricing and logistics optimization
- Improve shipping efficiency for high-profit products

---

## How AI Was Used
ChatGPT was used to:
- Frame structured analytical questions
- Validate reasoning during EDA
- Improve clarity of insight summaries

All data processing, calculations, and decisions were performed using Python.

---

## Author
Krishna Kumar  
Aspiring Data Analyst | Python | Business Analytics | AI-Assisted Data Analysis
