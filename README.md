# Customer Purchase Data Analysis

## Overview

This project analyzes customer purchase data to derive insights about customer behavior, identify high-value customers, and predict churn. The analysis includes aspects such as customer lifetime value, churn prediction, and the impact of discounts and payment methods.

## Dataset

```python
# Columns in the dataset
columns = [
    'Customer ID', 'Age', 'Gender', 'Item Purchased', 'Category',
    'Purchase Amount (USD)', 'Location', 'Size', 'Color', 'Season',
    'Review Rating', 'Subscription Status', 'Payment Method',
    'Shipping Type', 'Discount Applied', 'Promo Code Used',
    'Previous Purchases', 'Preferred Payment Method',
    'Frequency of Purchases', 'purchase_diff'
]

1. **Customer Behavior:**
   - **Gender Trends:** Males generally show higher 'purchase_diff' across various segments, indicating they contribute significantly to overall revenue.
   - **Location Impact:** Locations with high purchase_diff often include states with a larger customer base or higher spending patterns. 

2. **Churn Analysis:**
   - **High-Risk Groups:** Customers with significant differences in purchase behavior are more likely to churn. The analysis identifies these high-risk segments.
   - **Category Impact:** Certain product categories and items are linked with higher churn rates, providing insights for targeted retention strategies.

3. **Geographic Trends:**
   - **Top Locations:** States like West Virginia and Idaho show high purchase_diff, indicating these locations are crucial for revenue and might need focused marketing strategies.
   - **Female vs Male:** While females dominate in some locations, males have a significant impact on total purchase_diff due to higher spending in specific segments.
"""
