# Customer Segmentation



## What's in the project?
1. Cohort Analysis and visualization
2. RFM segmentation
3. Data pre-processing for k-means
4. Customer Segmentation with k-means
+ Evaluating number of clusters
+ Reviewing and visualizaing segmentation solutions

## [Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

### Attribute Information:  
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.    
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.  
Description: Product (item) name. Nominal.  
Quantity: The quantities of each product (item) per transaction. Numeric.  
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.  
UnitPrice: Unit price. Numeric, Product price per unit in sterling.  
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  
Country: Country name. Nominal, the name of the country where each customer resides. 

## Takeaways
1. What is cohort analysis?
+ Mutually exclusive segments - cohorts
+ Compare metrics across **product** lifecycle
+ Compare metrics across **customer** lifecycle
2. Types of cohort:
+ Time
+ Behavior
+ Size
3. Elements of cohort analysis:
+ Pivot table
+ Assigned cohort in **rows**
+ Cohort index in **columns**
4. Key k-means assumption
+ Symmetric distribution of variables(not skewed)
+ Variables with same average values
+ Variables with same variance
5. Skew removed with logarithmic transformation
6. Dealing with negative values
+ Adding a constant before logarithmic transformation
+ Cube root transformation
7. Centering variable is done by subtracting average value from each observation
8. Scaling variables is done by dividing them by standard deviation
9. Methods to define the number of clusters
+ Visual methods - elbow criterion
+ Mathematical methods - silhouette coefficient
+ Experimentation and interpretation
