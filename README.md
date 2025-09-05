# Olist E-Commerce Analytics Dashboard (2016–2018)

This project analyzes **99K+ e-commerce orders from Olist (Brazil, 2016–2018)**.  
The goal is to uncover why Olist had **strong revenue growth but 0% repeat customers**, and what actions could be taken to improve retention and satisfaction.

👉 [Explore the Interactive Dashboard here](https://app.powerbi.com/view?r=eyJrIjoiY2Y5MGUwZTEtYzA0Mi00NzYzLWI5YzktZjdlYmU4YWZiZjMzIiwidCI6ImFmMWYzNzUzLTM5MjUtNGU2Zi05NDliLTk3YzAwNzMyMDgwMyIsImMiOjEwfQ%3D%3D)

---

## 🔹 Why This Analysis?

At first glance, Olist looks successful:  
- **Revenue up quarter by quarter**  
- **97% delivery success rate**  

But one KPI stood out:  
⚠️ **Repeat Customer Rate = 0.00%**

This contradiction led to the key business question:  
👉 *“If orders are growing and deliveries succeed, why don’t customers come back?”*

---

## 🔹 Data Storytelling Across 5 Pages

### 1. Sales Performance (Overview)
- Revenue and orders grew steadily until early 2018.  
- Top sellers and cities (São Paulo = 2.2M revenue) drove growth.  
- However, the repeat rate remained **0%**.  

**Insight:** Growth was fueled by *new customers only*. There was **no loyalty loop**.

<img width="1244" height="787" alt="image" src="https://github.com/user-attachments/assets/a6e769e8-519f-4b60-9cfa-2a9dcf1a2532" />


---

### 2. Customer Analysis (RFM Segmentation)
- **Loyal** segment: highest revenue (6.2M).  
- **Promising** segment: highest order count (51K).  
- Both had **similar recency**, meaning they bought recently but never returned.  
- Customers are concentrated in **São Paulo & coastal regions**.

**Insight:** The most valuable groups (Loyal + Promising) were not retained. This points to a retention gap, not acquisition.  

<img width="1242" height="783" alt="image" src="https://github.com/user-attachments/assets/2e0539ef-a9e7-4cf9-86d6-da8e5e507df8" />


---

### 3. Customer Experience (Review & Delivery)
- Loyal customers paradoxically gave the **lowest review scores (3.9–4.0)** despite being most valuable.  
- Analysis shows **>80% of their orders took 8–14 days** to arrive.  
- Promising customers had better scores, even with similar delivery times → expectations may differ.

**Insight:** Dissatisfaction wasn’t just about late delivery — it was about **expectations not being managed**.  
Even “successful” deliveries took too long, eroding trust.

<img width="1239" height="784" alt="image" src="https://github.com/user-attachments/assets/305da856-82cf-474b-aeac-75b7cc5e2c82" />


---

### 4. Product Analysis (Revenue by Category)
- Top 3 categories: **Health & Beauty, Watches & Gifts, Bed Bath Table**.  
- Loyal customers heavily purchased **Watches & Gifts** and **Beauty products**.  
- These are **time-sensitive products**: gifts must arrive before an occasion, beauty products often needed urgently.  

**Insight:** When these products were delayed, review scores dropped significantly.  
For gifts, *a delay = a lost purpose*.  

<img width="1239" height="787" alt="image" src="https://github.com/user-attachments/assets/24fec06a-ae82-4e0b-ba0e-16ef1ff3009d" />


---

### 5. Report Detail (Drill-Down)
- Drill-down confirmed: Watches & Gifts orders from Loyal customers had **lowest review scores when late**.  
- Health & Beauty also showed sensitivity to lead time.  

**Insight:** The retention blind spot was clear → **high-value customers buying time-sensitive products suffered the most delays.**

<img width="1234" height="785" alt="image" src="https://github.com/user-attachments/assets/20524019-1b92-4678-95b6-27e062b12544" />


---

## 🔹 Recommended Actions

1. **Logistics Optimization**  
   - Reduce lead time from 8–14 days → **<7 days**.  
   - Focus on São Paulo & coastal regions where Loyal customers cluster.  

2. **Proactive Communication**  
   - Notify customers early if a shipment is delayed.  
   - Offer vouchers or discounts to mitigate dissatisfaction.  

3. **Segment-Specific Strategies**  
   - Prioritize **Loyal & Promising customers** with faster shipping options.  
   - Special handling for **time-sensitive categories** (Watches & Gifts, Beauty).  

---

## 🔹 Potential Impact (What-if Scenario)

If Loyal customers’ review scores improved from ~3.9 → 4.3 (the average for on-time deliveries):  
- Retention could realistically move from **0% → 10–15%** in the next cycle.  
- With Loyal segment revenue = 6.2M, even **10% repeat rate** would add **~620K revenue** annually.  
- Better reviews → higher seller reputation → stronger growth flywheel.

---

## 🔧 Tools & Techniques
- **Power BI**: DAX measures, data modeling, dashboard design  
- **SQL**: Data cleaning & exploration  
- **Storytelling with Data**: turning metrics into actionable business insights  

---

## 📌 About This Project
This is part of my **Data Analytics Portfolio**, showcasing skills in:  
- Business & customer analytics  
- RFM segmentation  
- Customer experience analysis  
- Data visualization & storytelling  

👉 [View Interactive Dashboard] (https://app.powerbi.com/view?r=eyJrIjoiY2Y5MGUwZTEtYzA0Mi00NzYzLWI5YzktZjdlYmU4YWZiZjMzIiwidCI6ImFmMWYzNzUzLTM5MjUtNGU2Zi05NDliLTk3YzAwNzMyMDgwMyIsImMiOjEwfQ%3D%3D)
