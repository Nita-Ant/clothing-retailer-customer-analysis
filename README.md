# Clothing Retailer Customer Analysis

## **Business Context**
A clothing business wants to understand how it can increase its sales and frequency of customer purchases. The stakeholders suspect that there are many factors, such as the demographics of their customers, the type of shipping services and payment methods, that influence buying behaviors, however they have no clear insight into how it affects the sales performance and repeat purchase rates.

## **Problem Statement**
The goal of this analysis is to identify the key factors that affect the sales performance and repeat customer purchases for the clothing business. By analyzing customer demographics, product category preferences and transaction behaviors (shipping and payment methods), we aim to provide actionable insight that can help increase the average purchase amount and boost purchase frequency per customer.

### **Key questions to answer**
- What demographics segment and product categories strongly influence repeat purchases?
- How do shipping and payment methods impact average purchase amount value and purchase frequency?
- What strategies can the business implement to increase revenue and strengthen customer retention?

## **Data Preparation**
The dataset gathered from Kaggle shows 3900 rows and 18 columns. The initial inspection using df.head() and df.info() confirmed that there are no missing values in the dataset. 

|index|Customer ID|Age|Gender|Item Purchased|Category|Purchase Amount \(USD\)|Location|Size|Color|Season|Review Rating|Subscription Status|Shipping Type|Discount Applied|Promo Code Used|Previous Purchases|Payment Method|Frequency of Purchases|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|0|1|55|Male|Blouse|Clothing|53|Kentucky|L|Gray|Winter|3\.1|Yes|Express|Yes|Yes|14|Venmo|Fortnightly|
|1|2|19|Male|Sweater|Clothing|64|Maine|L|Maroon|Winter|3\.1|Yes|Express|Yes|Yes|2|Cash|Fortnightly|
|2|3|50|Male|Jeans|Clothing|73|Massachusetts|S|Maroon|Spring|3\.1|Yes|Free Shipping|Yes|Yes|23|Credit Card|Weekly|
|3|4|21|Male|Sandals|Footwear|90|Rhode Island|M|Maroon|Spring|3\.5|Yes|Next Day Air|Yes|Yes|49|PayPal|Weekly|
|4|5|45|Male|Blouse|Clothing|49|Oregon|M|Turquoise|Spring|2\.7|Yes|Free Shipping|Yes|Yes|31|PayPal|Annually|

<img width="577" height="496" alt="image" src="https://github.com/user-attachments/assets/8a2a1d15-5c56-4874-94fc-53fd2dce3eb6" />

Duplication checks were performed to validate the uniqueness of variables relevant to the analysis—Gender, Product Category, Shipping Type, and Payment Method. The checks validated the uniqueness and consistency of the values for each variable. Numerical variables such as Purchase Amount and Frequency of Purchases were reviewed and confirmed to fall within expected ranges with no extreme outliers. Link of the notebook for full data preparation: https://colab.research.google.com/drive/1qVHNV-fCCNL4goii8npFpv3U6big_ZpN?usp=sharing

These validations ensured the dataset was consistent and reliable, providing a solid foundation for analyzing the factors that influence customer purchase frequency and average purchase value.
