# Predicting customer value using clumpiness: From RFM to RFMC.  
**RFM + C (Clumpiness) for Customer Relationship Management (CRM)**

Companies have been experimenting with various CRM methods to understand the level of loyalty of their own customers. 
RFM analysis has been widely used for the purpose of customer segmentation which R is Recency, F is Frequency and M is Monetary.

![image](https://github.com/chantaporn-tubtimdee/RFMC/assets/37092034/0302ae83-18ff-47e7-89f4-70dbdd7c1e25)
										**Figure 1: RFM on the same period**

However, if you look at Figure 1, although the RFM indicators are the same, the patterns are clearly different.  "User A" regularly purchases but "User B" does not. Therefore, the purchasing patterns cannot be identified by RFM solely.

With the aim of capturing such purchasing patterns, Zhang, Bradlow & Small (2015) of The Wharton School of the University of Pennsylvania proposed RFMC analysis that added clumpiness index (C) to RFM.

**1. What is Clumpiness?**
According to Zhang et al. (2013), Clumpiness is defined as the degree of nonconformity to equal spacing and demonstrates an essential component in a better understanding of recognizing a profitable customer. 
**2. Calculation of clumpiness index (C)**
Hp = Heterogeneity of consumer purchase.

If a purchase is made 𝑛 times out of 𝑁 purchase opportunities, let 𝑡𝑖 be the timing of the 𝑖th purchase. Furthermore, when 𝑥𝑖 standardized to 𝑡𝑖 and defined as equations below.

Hp will be:
![image](https://github.com/chantaporn-tubtimdee/RFMC/assets/37092034/ead6a912-203f-4ac0-a2e4-c8ec1c6a5898)


Next, run a random purchasing simulation (Monte Carlo method) under the conditions of purchase opportunities 𝑁 times and number of purchases 𝑛.
Repeat 𝑀 times and set the 𝛼%.

![image](https://github.com/chantaporn-tubtimdee/RFMC/assets/37092034/77b11261-5ea5-4847-a94d-75ca81f81741)







