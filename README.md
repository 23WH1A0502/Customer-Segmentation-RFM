## Customer Segmentation Using RFM Analysis

### 📌 Project Overview

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis on an e-commerce dataset.
The goal is to understand customer behavior and categorize customers into segments such as Best Customers, Loyal Customers, At-Risk Customers, etc.

This kind of analysis is widely used in retail, e-commerce, and online services like Amazon, Flipkart, and Swiggy to improve marketing and retention strategies.

---

### 🗂 Dataset

* Dataset: E-commerce transactions (local CSV file: `"C:\Users\lasya\Downloads\online_retail.csv"`)
* Contains **transaction-level data** of an e-commerce store
* Columns include:

  * `InvoiceNo` – Invoice number
  * `StockCode` – Product code
  * `Description` – Product name
  * `Quantity` – Number of items purchased
  * `InvoiceDate` – Date of purchase
  * `UnitPrice` – Price per item
  * `CustomerID` – Customer identifier
  * `Country` – Customer country
* Note: Original source of the dataset is unknown

---

### 🛠 Tools & Libraries

* **Python**
* **Pandas** – Data cleaning, feature engineering, grouping
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Visualizations

---

### 🔧 Project Steps

1. **Data Cleaning**

   * Handled missing values
   * Converted `InvoiceDate` to datetime format

2. **Feature Engineering**

   * Created `Revenue = Quantity * UnitPrice`
   * Extracted Month from `InvoiceDate`
   * Calculated Recency for each customer

3. **Aggregation**

   * Total orders and total revenue per customer

4. **RFM Analysis**

   * Computed Recency, Frequency, Monetary scores
   * Segmented customers into categories using RFM score

5. **Visualization**

   * Customer distribution per segment
   * Revenue contribution by segment

---

### 📊 Key Insights

* **Best Customers**: Contribute the highest revenue even though they are fewer in number
* **Loyal Customers**: Frequently purchase and can be targeted for retention campaigns
* **At-Risk Customers**: Have high past spending but low recent activity, need engagement offers

---

### 📈 Visualizations

#### Customer Segments Distribution

![Segment Chart](images/segment_chart.png)

#### Revenue Contribution by Segment

![Revenue Chart](images/revenue_chart.png)

---

### 💼 Outcome

This project demonstrates:

* Real-world data analysis workflow
* Ability to segment customers for actionable business insights
* Skills in Python, Pandas, and data visualization


