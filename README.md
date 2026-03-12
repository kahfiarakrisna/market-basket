# 🛒 Market Basket Analysis Dashboard

## 📌 Project Overview

This project analyzes customer purchasing behavior using **Market Basket Analysis** to identify product relationships and cross-selling opportunities.

The dataset contains **37,369 grocery transactions with 160 unique products** collected between **2014 and 2015**. By applying association rule mining techniques such as **Support, Confidence, and Lift**, this project uncovers purchasing patterns and product combinations frequently bought together.

The results are presented through an **interactive Tableau dashboard**, allowing users to explore seasonal trends, product popularity, and cross-selling opportunities that can support retail decision-making.

---

# 📊 Dataset Overview

The dataset consists of grocery store transaction records where each row represents a purchased item within a transaction.

### Dataset Summary

| Metric              | Value       |
| ------------------- | ----------- |
| Total Transactions  | 37,369      |
| Unique Products     | 160         |
| Average Basket Size | 2.98 items  |
| Time Period         | 2014 – 2015 |

### Key Variables

| Column           | Description                               |
| ---------------- | ----------------------------------------- |
| Transaction ID   | Unique identifier for each purchase       |
| Date             | Transaction date                          |
| Member Number    | Unique identifier for each customer       |
| Item Description | Name of the purchased product             |
| Category         | Product category grouping                 |
| Basket Size      | Number of items purchased per transaction |

This dataset is suitable for **association rule mining and consumer behavior analysis**.

---

# 📈 Dashboard Structure

## 1️⃣ Overview Page

The overview page provides a **high-level summary of transaction patterns and product distribution**.

### Key Components

* **KPI Cards**

  * Total Transactions
  * Average Basket Size
  * Total Unique Products
  * Average Confidence
  * Average Lift

* **Seasonal Pattern of Transactions**

  * Displays monthly transaction trends between 2014 and 2015.

* **Most Frequent Items (Support Value)**

  * Highlights products most frequently purchased by customers.

* **Product Category Overview**

  * Shows distribution of products across categories.

### Purpose

To give a **quick understanding of store performance, product popularity, and purchasing trends**.

---

## 2️⃣ Deep Dive Page

The deep dive page focuses on **association rules and cross-selling opportunities**.

### Key Components

* **Top Cross-Selling Opportunities (Confidence-Based)**

  * Displays product combinations most likely to be purchased together.

* **Top Cross-Selling Opportunities by Lift**

  * Shows strong product associations using lift values.

* **Detail Transaction Table**

  * Displays transaction-level data with basket size and product categories.

* **Interactive Filters**

  * Confidence threshold
  * Lift threshold
  * Product filters

### Purpose

To identify **product combinations that can be used for bundling, promotions, or recommendation systems**.

---

# 🔍 Key Insights

### 1️⃣ Whole Milk is the Most Purchased Product

Whole milk has the highest **support value (~15.7%)**, indicating that it is the most frequently purchased product and acts as a **core item in many customer baskets**.

---

### 2️⃣ Bakery and Dairy Products Drive Cross-Selling

Several high-confidence combinations include:

* **Sausage + Yogurt → Whole Milk**
* **Rolls/Buns + Sausage → Whole Milk**
* **Rolls/Buns + Yogurt → Whole Milk**

These patterns suggest that **bakery and dairy products often appear together in customer purchases**.

---

### 3️⃣ Anchor Products Trigger Additional Purchases

Products such as:

* Whole Milk
* Rolls/Buns
* Yogurt
* Other Vegetables

frequently appear across multiple association rules, indicating that these items function as **anchor products that drive additional purchases**.

---

### 4️⃣ Stable Seasonal Transaction Trends

Transaction volumes remain relatively consistent throughout the year with slight increases during **mid-year months**, suggesting stable customer purchasing behavior.

---

### 5️⃣ Balanced Product Category Distribution

The store offers a well-balanced assortment of products with dominant categories including:

* Pantry & Cooking
* Beverages
* Household
* Dairy

This indicates diversified inventory that supports multiple shopping needs.

---

# 💡 Business Recommendations

* Place **high-support products such as milk near complementary items** to encourage additional purchases.
* Develop **bundle promotions** combining bakery and dairy products.
* Use **high-confidence association rules** to design targeted marketing campaigns.
* Optimize **store layout and product placement** based on association patterns.

---

# 📚 Lessons Learned

### Data Analysis

* Applied **Market Basket Analysis using the Apriori algorithm**.
* Learned how to interpret **support, confidence, and lift metrics**.
* Identified meaningful patterns within transaction data.

### Data Visualization

* Built interactive dashboards using **Tableau**.
* Translated complex association rules into **clear visual insights**.

### Business Insights

* Converted analytical results into **practical retail strategies**.
* Identified **key products that influence customer purchasing behavior**.

---

# 🛠 Tools & Technologies

| Tool    | Purpose                                           |
| ------- | ------------------------------------------------- |
| Python  | Data preprocessing and association rule mining    |
| Pandas  | Data manipulation and transformation              |
| MLxtend | Apriori algorithm and association rule generation |
| Tableau | Interactive dashboard visualization               |
| GitHub  | Project documentation and portfolio showcase      |

---

# 📊 Key Metrics Explained

| Metric     | Definition                                                                                     |
| ---------- | ---------------------------------------------------------------------------------------------- |
| Support    | Frequency of a product or product combination in all transactions                              |
| Confidence | Probability that product B is purchased when product A is purchased                            |
| Lift       | Strength of association between products (values greater than 1 indicate strong relationships) |

---

# 🎯 Project Outcome

This project demonstrates how **transaction data can be transformed into actionable retail insights**. By identifying frequently purchased items and strong product relationships, businesses can optimize **cross-selling strategies, product placement, and promotional campaigns** to improve overall sales performance.

---
