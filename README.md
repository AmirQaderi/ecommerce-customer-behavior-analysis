## 🛍️ E-commerce Customer Behavior Dataset (v2)

## Overview

This repository provides an **E-commerce Customer Behavior Dataset (v2)** designed for data analysis, machine learning, and educational purposes. The dataset captures detailed customer demographics, purchasing behavior, order characteristics, device usage, and satisfaction metrics.

Version **v2** extends the earlier release by supporting **multi-order customers**, making it suitable for more realistic behavioral analysis such as customer lifetime value, repeat purchasing patterns, and cohort analysis.

---

 Key Statistics (v2):

* **Total records:** 17,049
* **Total columns:** 18
* **Date range:** 2023-01-01 to 2024-03-25
* **Average Total Amount:** ~1,277.44
* **Median Total Amount:** ~1,250 (approx.)
* **Average Customer Rating:** ~3.9 / 5
* **Returning Customer Rate:** ~88.21%
* **Mobile Transactions:** ~55.97%
* **Missing values:** None detected

> Note: Statistics are computed directly from the provided CSV file and may differ from earlier versions of this dataset.

---

 Dataset Versions:

### v1 (legacy)

* Single-order per customer
* ~5,000 records
* Intended mainly for basic exploratory data analysis (EDA)

### v2 (current)

* **Multi-order per customer** (each customer may place multiple orders)
* 17,049 records
* More realistic transactional behavior
* Suitable for advanced analytics and machine learning tasks

Order identifiers may appear multiple times (e.g., `ORD_1023-1`, `ORD_1023-2`) to represent multiple purchases by the same customer.

---

 Column Description:

| Column Name           | Description                                            |
| --------------------- | ------------------------------------------------------ |
| Order_ID              | Unique identifier for each order                       |
| Customer_ID           | Unique identifier for each customer                    |
| Date                  | Date of the transaction                                |
| Age                   | Customer age                                           |
| Gender                | Customer gender                                        |
| City                  | Customer city                                          |
| Product_Category      | Category of the purchased product                      |
| Quantity              | Number of items purchased                              |
| Unit_Price            | Price per unit                                         |
| Discount_Amount       | Discount applied to the order                          |
| Total_Amount          | Final total amount paid for the order                  |
| Payment_Method        | Payment method used                                    |
| Device_Type           | Device used for purchase (Mobile, Desktop, etc.)       |
| Is_Returning_Customer | Indicates whether the customer is a returning customer |
| Customer_Rating       | Rating given by the customer (1–5)                     |
| Shipping_Method       | Shipping option selected                               |
| Delivery_Time         | Delivery time in days                                  |
| Order_Status          | Final order status                                     |

---

 Intended Use Cases:

* Exploratory Data Analysis (EDA)
* Customer segmentation and profiling
* Predicting repeat purchases
* Recommendation systems
* Customer lifetime value (CLV) estimation
* Educational projects and demonstrations

---

 Data Quality & Assumptions:

* The dataset contains **no missing values**.
* Values are internally consistent and cleaned.
* Monetary values represent the **final transaction amount**, after discounts.
* Customer and order identifiers are anonymized.
* The dataset is either synthetic or anonymized and does not contain personally identifiable information (PII).

---

 Repository Structure (Recommended):

```
├── README.md
├── LICENSE
├── requirements.txt
├── data/
│   ├── ecommerce_customer_behavior_dataset_v2.csv
├── notebooks/
│   ├── ecommerce_customer_eda.ipynb
│   └── ecommerce_customer_eda.html

---

 Installation:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
pip install -r requirements.txt
```

---

 Data Source:

The dataset used in this project was obtained from **Kaggle**:

> *E-Commerce Customer Behavior and Sales Analysis (TR)*
> Author: Umut Tuygur
> Source: [https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr](https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr)

The dataset has been reused for educational and analytical purposes in accordance with Kaggle’s dataset usage policies.

---

 License:

* **Dataset:** CC0 1.0 Universal (Public Domain)
* **Source code:** MIT License (recommended)

You are free to use, modify, and distribute this dataset and code without restriction.

---

 Citation:

If you use this dataset in academic or professional work, please cite it as:

> E-commerce Customer Behavior Dataset (v2), 2024.

---

 Contribution:

Contributions are welcome. Please submit pull requests or open issues for suggestions, improvements, or bug reports.

---

 Disclaimer:

This dataset is provided for research and educational purposes only and does not represent real customer transactions.
