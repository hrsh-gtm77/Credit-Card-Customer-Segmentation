# Credit-Card-Customer-Segmentation
## Credit Card Customer Segmentation using K-Means Clustering

This project performs customer segmentation on the **CC GENERAL dataset** using **K-Means clustering** to group credit card customers based on spending and usage behaviour

----

## PROJECT OVERVIEW
- Dataset: "CC GENERAL.csv"

- Dataset size: 8,950 customers
- Method: **K-Means Clustering**
- Preprocessing: missing value handling + feature standardization (StandardScaler)
- Optimal clusters (k): selected using Elbow Method
- Features Used:
  - Purchases
  - Purchases_frequency
  - Cash_Advance
  - Credit_limit
  - Payments
 
    ----

## RESULTS

Using the Elbow Method, customers were segmented into 3 clusters:

Low-usage users: 6,204 customers, avg purchases ≈ ₹432

Regular users: 2,580 customers, avg purchases ≈ ₹1,906

High-value users: 166 customers, avg purchases ≈ ₹8,647

Cluster-wise mean analysis showed that high-value users had the highest:

Average purchases: ≈ 8,647

Credit limit: ≈ 11,762

Payments: ≈ 16,706

This identifies a small but premium customer segment.

## Tools Used

Python, Pandas, NumPy, Scikit-learn (StandardScaler, KMeans), Matplotlib
    
