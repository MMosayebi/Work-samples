# 🛒 Customer Purchase History Analysis

A Python-based data analysis project focused on understanding **sales performance, customer behavior, product performance, and purchasing patterns**.

The goal of this project is to turn raw customer transaction data into **clear and actionable business insights**.

---

## 📌 About the Project

This project analyzes **1,800 customer purchase records** across different products, categories, prices, payment methods, and customer ratings.

The analysis answers several real-world business questions, such as:

* Which products and categories generate the most revenue?
* Who are the highest-value customers?
* How does revenue change over time?
* Which customers should be prioritized for retention?
* Does purchase frequency affect customer value?
* Which products have the highest customer ratings?
* Is there a relationship between product price and customer satisfaction?
* Which payment methods are most commonly used?

---

## 🔍 What I Analyzed

### 💰 Sales & Revenue

I analyzed:

* Revenue by product
* Revenue by category
* Monthly and yearly revenue
* Revenue vs. sales volume
* Average Selling Price (ASP)

This helps identify the products and categories that have the biggest impact on overall sales.

---

### 👥 Customer Behavior

I analyzed customer purchasing patterns to identify:

* High-value customers
* Purchase frequency
* Total customer spending
* Revenue contribution of top customers

One of the key findings was that the **top 10% of customers generated approximately 27.41% of total revenue**.

---

### 🎯 RFM Customer Segmentation

I used **RFM analysis** to segment customers based on:

* **Recency** — How recently they purchased
* **Frequency** — How often they purchased
* **Monetary** — How much they spent

Customers were then grouped into segments such as:

* 🏆 Champions
* 💙 Loyal Customers
* 🌱 Potential Customers
* ⚠️ At Risk / Lost Customers

This makes the analysis more useful for **customer retention and marketing strategies**.

---

### ⭐ Customer Satisfaction

I analyzed customer ratings across products and categories to understand differences in customer satisfaction.

The analysis also compares the average rating of different product categories and individual products.

---

### 💵 Pricing Analysis

I investigated the relationship between:

**Product Price ↔ Customer Rating**

The correlation was approximately **-0.02**, indicating almost no linear relationship between product price and customer rating in this dataset.

---

### 💳 Payment Methods

I also analyzed payment methods based on:

* Number of transactions
* Total revenue
* Average transaction value

This provides a better understanding of customer payment behavior.

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📈 Seaborn
* 📗 OpenPyXL
* 📓 Jupyter Notebook
* 📑 Microsoft Excel

---

## 📂 Project Structure

```text
Customer-Purchase-History/
│
├── dataset/
│   └── Customer-Purchase-History.xlsx
│
├── export-data/
│   ├── Sales Performance & Revenue/
│   ├── Customer Behavior & Value/
│   ├── Pricing & Product Economics/
│   └── Operational & Transaction Efficiency/
│
├── Customer-Purchase-History.ipynb
│
└── requirements.txt
```

The exported Excel files contain the results of the different analyses and are organized by business question.

---

## 💡 Key Takeaways

This project demonstrates how Python can be used to move from **raw transaction data to business insights**.

The main areas covered are:

**Sales → Customers → Products → Pricing → Satisfaction → Transactions**

It also demonstrates practical use of **RFM segmentation** to identify different types of customers and support data-driven retention strategies.

---

## 👨‍💻 Author

**Mohammad Mosayebi**

**Sales & Marketing Data Analyst | Python | Excel | Power BI | SQL Server**

GitHub: [MMosayebi](https://github.com/MMosayebi)

---

⭐ If you find this project useful, feel free to star the repository.
