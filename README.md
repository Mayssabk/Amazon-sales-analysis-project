# Amazon Sales Analysis Project 📊📈📉

## 📋 Objectives of This Project
* **Analyze Consumer Preferences:** Delve into product categories, prices, ratings, and sales patterns to identify characteristics that resonate with consumers and propel them to purchase.
* **Translate Insights into Actionable Recommendations:** Optimize product development, inform marketing strategies, and boost your competitive edge.
* **Empower Businesses:** Equip stakeholders with the knowledge to create products that cater to evolving consumer needs and desires.
* **Craft Communication Strategies:** Resonate with specific demographics and maximize engagement.
* **Optimize Marketplace Matching:** Facilitate an ecosystem where products find their ideal match in the hearts of consumers.

---

## 📂 Dataset Overview
This dataset contains data on over 1,000 Amazon products, including ratings and reviews as listed on the official Amazon website.

### Features
* `product_id`: Product ID
* `product_name`: Name of the Product[cite: 2]
* `category`: Category of the Product[cite: 2]
* `discounted_price`: Discounted Price of the Product[cite: 2]
* `actual_price`: Actual Price of the Product[cite: 2]
* `discount_percentage`: Percentage of Discount for the Product[cite: 2]
* `rating`: Rating of the Product[cite: 2]
* `rating_count`: Number of people who voted for the Amazon rating[cite: 2]
* `about_product`: Description about the Product[cite: 2]
* `user_id`: ID of the user who wrote a review for the Product[cite: 2]
* `user_name`: Name of the user who wrote a review for the Product[cite: 2]
* `review_id`: ID of the user review[cite: 2]
* `review_title`: Short review title[cite: 2]
* `review_content`: Detailed review content[cite: 2]
* `img_link`: Image Link of the Product[cite: 2]
* `product_link`: Official Website Link of the Product[cite: 2]

---

## 🛠️ Methodology & Task Workflow
In this project, the following Exploratory Data Analysis (EDA) pipeline was executed:

1. **Data Cleaning & Preparation:** Ensured data accuracy and consistency by handling missing values, standardizing formats, and correcting data types (e.g., parsing prices, percentages, and handling anomalies in ratings)[cite: 2].
2. **Descriptive Statistics:** Summarized the data using statistical measures such as central tendency and spread[cite: 2].
3. **Data Visualization:** Built charts and graphs using `matplotlib` and `seaborn` to uncover underlying patterns, trends, and correlations[cite: 2].
4. **Outlier & Assumption Testing:** Detected unusual data points and tested underlying assumptions about the dataset[cite: 2].
5. **Segmentation & Findings:** Grouped data for deeper understanding and summarized key actionable takeaways[cite: 2].

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the following libraries:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import scipy as sp
