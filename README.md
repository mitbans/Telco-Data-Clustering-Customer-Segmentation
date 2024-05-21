# Profiling customer groups for a large telecommunications company
## Features used:

- Demographics: Age, Gender, Married, Number of Dependents
- Payment behavior: Paperless Billing, Payment Method, Contract
- Customer Status: Churn Value
- Service Usage and Financials: Type of services, tenure, charges & refunds

## Encoding Categorical Features:

- Binary Encoding: for all the columns having 2 values 'Yes' and 'No', converted to 1 and 0
- One Hot Encoding: for 'Contract', 'Payment Method', 'Gender'

## Explained Variances using Scikit-learn PCA
<img width="709" alt="image" src="https://github.com/mitbans/telco-data-clustering-customer-segmentation/assets/166747739/cb6280bc-f2df-43e4-9172-497a46f36aee">

- Conclusion: 99.9% variance is explained by first 3 components.

## k-means clustering 3D plot
<img width="593" alt="image" src="https://github.com/mitbans/telco-data-clustering-customer-segmentation/assets/166747739/d1e29597-a52b-438f-9ba8-aa40706d4247">

## Customer Segmentation Final Summary

### Cluster 0: 
Long-tenured customers with comprehensive service subscriptions, high usage, and high charges. They are middle-aged, married, and have no dependents. They are loyal customers who have not churned. They have a two-year contract and pay via bank withdrawal.
### Cluster 1: 
Mid-tenured customers with moderate service subscriptions and usage. They have a mix of streaming services and are also loyal. They are slightly older and married with no dependents. They have a month-to-month contract and pay via bank withdrawal.
### Cluster 2: 
Short-tenured customers with minimal service subscriptions and usage. They have lower charges and no dependents. They are younger or middle-aged and not married, and they have not churned. They have a month-to-month contract and pay via bank withdrawal.

### Repository Structure
- <code>data/</code>: Contains dataset used in the analysis.
- <code>notebooks/telco-data-clustering.jpynb</code>: Jupyter notebook with code for data analysis.
- <code>README.md</code>: Summary of findings and link to notebook

## Notebook
The detailed analysis and code can be found in the Jupyter notebook <a href="https://github.com/mitbans/telco-data-clustering-customer-segmentation/blob/main/notebooks/telco-data-clustering.ipynb">here</a>.

