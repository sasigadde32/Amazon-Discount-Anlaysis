# Amazon - Discount Analysis Dashboard 📊

## **Business Overview**
This project analyzes pricing efficiency and sales volume across **$32.9M in total revenue**. The goal was to identify how different "Discount Slabs" (from 0% to 30%) impact the **Average Order Value (AOV)** and unit movement across six major retail categories.

---

## 🚀 **Key Insights**

> ### **1. The AOV vs. Discount Trade-off**
> There is a direct correlation between higher discounts and lower revenue per order. 
> * **Maximum AOV:** **$749** (achieved with 0% discounts).
> * **Minimum AOV:** **$522** (at the 30% discount slab).
> * **Finding:** While discounts drive volume, they reduce the average ticket size by **30.3%** at the highest tier.

> ### **2. Category Performance Leaders**
> * **Highest Volume:** **Beauty** leads the pack with **854K units** sold.
> * **Lowest Volume:** **Home & Kitchen** trails slightly at **824K units**.
> * **Market Trend:** Over **83.57%** of all quantities sold across all categories were purchased under a discount.

> ### **3. Discount Distribution**
> The sales volume is remarkably balanced across all promotional tiers, with each slab (5%, 10%, 15%, 20%, 30%) capturing approximately **16.6%** of the total quantity sold.

---

## 🛠️ **Technical Highlights**
* **Data Modeling:** Transformed raw Amazon sales data into structured "Discount Slabs" for granular analysis.
* **DAX Implementation:** * `AOV = DIVIDE([Total Revenue], [Total Quantity])`
    * `Discounted Qty % = DIVIDE([Qty with Discount], [Total Qty])`
* **Visualization:** Area charts were utilized to visualize the "Quantity vs. Discount" relationship across the product lifecycle.

---

---


## 📂 Project Repository
* 📊 **[Interactive Dashboard](./Amazon%20Sales%20Analysis.pbix)**
* 📽️ **[Management Presentation](./Amazon.pptx)**
* 🖼️ **[Dashboard Screenshot](./Screenshot%202026-03-12%20155855.png)**
