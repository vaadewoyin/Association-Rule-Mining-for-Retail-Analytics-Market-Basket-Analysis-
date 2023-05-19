# Association Rule Mining for Retail Analytics: Market Basket Analysis of the online retail dataset

## Market Basket Analysis
![Photo by Tara Clark from Pexels](https://github.com/vaadewoyin/Association-Rule-Mining-for-Retail-Analytics-Market-Basket-Analysis-/blob/main/image.jpg)

*Image credit: [Photo by Tara Clark from Pexels](https://www.pexels.com/photo/a-person-holding-a-basket-9070106/)*


Market Basket Analysis is a data mining technique used to uncover associations and patterns within a set of transactions or customer purchases. It helps identify which items are frequently bought together or sequentially by customers. The analysis aims to understand the relationships between different products and uncover insights that can be used for various purposes, such as optimizing product placement, cross-selling, and targeted marketing.
By applying market basket analysis, we aim to uncover hidden patterns, associations, and co-occurrence of items within the transaction data. This will enable us to generate meaningful and actionable insights to support decision-making processes and enhance business strategies

### Dataset Description
The Online Retail Data Set contains a wealth of information about customer transactions. It includes details such as the invoice date and invoice no. of the transaction, the items purchased, the quantity, and the customer's ID. The dataset allows us to explore the purchasing patterns of customers and identify the relationships between different products.All the necessary data cleaning and transformations are done to prepare the data for market basket analysis using the apriori algorithm.

### Some insights from exploratory data analysis
1. The "Regency Cakestand 3 Tier" is the top-selling item in the dataset, based on purchase frequency
2. The day with highest items purchased is 2011-11-14, while Novemeber, 2011 is the month with highest number of items purchased from the store
3. Most of the purchase came from customers in the United Kingdom, followed by Germany and the rest.
4. The countries with customers with the lowest purchase are Saudi Arabia, Bahrain,Czech Republic, Brazil, Lithuania , with Saudi Arabia been the lowest. it could mean that we have few customers in those regions.
5. The Most expensive item in the dataset is the VINTAGE RED KITCHEN CABINET with unit price of 295
6. The customer with customerId-14646 is the customer with most spending.

### Apriori Algorithm and Association rule:
The Apriori algorithm is a popular association rule mining algorithm that efficiently finds frequent itemsets that can be used to generate meaningful association rules. Association rule mining identifies associations between items based on their co-occurrence in transactions. Association rules consist of an antecedent (premise) and a consequent (outcome) with corresponding measures like support, confidence, and lift.

In this analysis, a total of 646 association rules were generated. To filter the frequent itemsets and focus on meaningful associations, a minimum lift threshold of 1.01 was applied during the pruning stage of the Apriori algorithm. This choice was made because lift values greater than 1 indicate significant positive associations, aligning with our objective of uncovering meaningful relationships among items.

### Result
Based on the outcomes of the analysis, the generated association rules hold valuable insights for various business applications. These rules can be utilized to identify patterns, optimize store layout, and select items for cross-selling purposes. 

For example:
we can gain valuable insights into the products frequently purchased together, enabling us to enhance our marketing strategies, optimize store layout, and effectively implement cross-selling initiatives as illustrated below:

![result_1_picture](https://github.com/vaadewoyin/Association-Rule-Mining-for-Retail-Analytics-Market-Basket-Analysis-/blob/main/result_1.png)

Also, a market basket analysis based recommendation can be created based on item's stockcode:
![result_2_picture](https://github.com/vaadewoyin/Association-Rule-Mining-for-Retail-Analytics-Market-Basket-Analysis-/blob/main/result_2.png)



