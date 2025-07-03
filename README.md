# DSA_PROJECT_ 📊 Amazon Product Review Analysis

**Tools Used:** Google sheets and WPS (mobile), Pivot Tables, Calculated Columns  
**Dataset:** Amazon Product Listings and Reviews (1,465 rows, 16 columns)  
**Submission:** Capstone Project – DSA Data Analysis Course  

---

## 🔍 Project Overview

This project involves exploratory data analysis (EDA) on an Amazon product review dataset. The dataset contains product information such as names, categories, prices, discounts, ratings, and review counts. The goal is to extract meaningful insights for business decisions using Excel.

---

## ✅ Analysis Questions and Answers

### 1. **Average Discount Percentage by Product Category**
| Category | Avg. Discount |
|----------|----------------|
| Electronics | 50.83% |
| Computers & Accessories | 53.92% |
| Home & Kitchen | 40.17% |
| Office Products | 12.35% |
| Others... | See dashboard |

### 2. **How Many Products Are Listed per Category?**
Total of 1,462 products distributed across categories like Electronics (526), Home & Kitchen (447), Computers & Accessories (451), (see dashboard) 

### 3. **Total Number of Reviews per Category**
Displayed as a **clustered column chart** in the dashboard. Electronics has the highest review count.

### 4. **Top 5 Products with Highest Average Ratings**
- Amazon Basics Wireless Mouse - 5.0
- Syncwire LTG to USB Cable - 5.0
- Instant Pot Air Fryer - 4.8
- Oratech Coffee Frother - 4.8
- Swiffer Instant Water Heater - 4.8

### 5. **Average Actual vs Discounted Price per Category**
| Category | Actual Price | Discounted Price |
|----------|--------------|------------------|
| Electronics | $10,127.31 | $5,965.88 |
| Home & Kitchen | $4,165.79 | $2,331.13 |
| Others... | ... | ... |

### 6. **Top 5 Products with Highest Review Count**
- AmazonBasics HDMI Cable (3-Foot) — 3,757,358 rating score  
- Others listed in dashboard with rating × review counts.

### 7. **Number of Products with ≥ 50% Discount**
**749** products.

### 8. **Distribution of Product Ratings**
Most products are rated between 3.8 and 4.4. Full breakdown in bar chart (dashboard).

### 9. **Total Potential Revenue by Category**
Potential revenue = `Actual Price × Rating Count`.  
Electronics leads with over **$98 billion**.

### 10. **Number of Unique Products per Price Range**
| Bucket | Count |
|--------|-------|
| Low (< $500) | 220 |
| Mid ($501 – $5,000) | 921 |
| High ($5,001 – $20,000) | 224 |
| Luxury (> $20,000) | 97 |

### 11. **Relationship Between Rating and Discount**
| Rating Group | Avg. Discount |
|--------------|----------------|
| Low (< 3.0) | 64.00% |
| Medium (< 4.0) | 52.50% |
| High (≥ 4.0) | 46.07% |

### 12. **Products with Fewer than 1,000 Reviews**
**325** products.

### 13. **Categories with the Highest Discounts**
- Home Improvement (57.5%)
- Computers & Accessories (53.9%)
- Health & Personal Care (53%)

### 14. **Top 5 Products Based on Rating × Reviews Combined**
- AmazonBasics HDMI Cable – **3.75M**
- Amazon Basics High-Speed HDMI (2-pack) – **1.88M**
- Amazon Basics High-Speed HDMI Cable,Black - **1.88M**
- JBL Wired Earphones – **1.57M**
- boAt Bassheads – **1.49M**

---

## 📈 Dashboard Summary

The Excel dashboard (separate sheet) includes:
- KPI Cards: Total Products, Total Revenue, Avg. Discount
- Clustered Column Chart: Actual vs Discounted Price per Category
- Bar Chart: Price Range Distribution, Top 5 Products by Rating and Reviews, Average Discount Percentage by Category, Product Count by Category. 
- Pie Chart: Product Count by Price Range Bucket 

---

## 🧠 Key Insights

- Products with lower ratings tend to have deeper discounts.
- Electronics dominate both in sales volume and potential revenue. 
- High rating does not always equate to highest review count.
- Most products are mid-priced and heavily discounted, especially those with low ratings.
- Some product names are repeated but vary by minor attributes (color, pack, etc.), influencing the average ratings and review counts.

---

## 📌 Author Info

**Name:** Obiekezie Precious Chinaza  
**Email:** alexprecious100@gmail.com  
**Location:** Kaduna State, Nigeria  

---
