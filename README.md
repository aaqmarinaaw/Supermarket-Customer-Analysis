# **Capstone Modul 2 : Supermarket ABC Customer Analysis**
*Created by : Azelia Aqmarina*



## **Background**
Supermarket ABC, established as the first retail supermarket in the city and has been a pioneer in offering wide variety of products, including meat, fruits, wines, fish, and sweet golds. Over time, the supermarket became a go-to destination for the community, setting a benchmark for quality and variety.

However, as years passed, the retail landscape in the city became increasingly competitive with the emergence of new supermarkets. The growing number of competitors has challenged Supermarket ABC's market position, leading to a noticeable decline in their sales performance.

In response to this challenge, the Management has launched numerous marketing campaigns aimed to boost sales and customer engagement. Despite these efforts, the campaigns have not delivered the expected results, prompting the need for a more data-driven approach.

To address this, the Management has hired a data analyst to examine their customer data, collected from 2012 to 2014. This data includes comprehensive details on customer demographics, purchase histories, product offerings, and the various campaigns conducted during this period. The goal is to uncover insights and develop strategies that will enhance Supermarket ABC's competitiveness and drive sales growth in the increasingly crowded market.


## **Data explanation**
The dataset used in this capstone project is provided by Purwadhika team which composed of 2,240 rows and 29 columns, offering a detailed and comprehensive view of customer behavior and business operations at Supermarket ABC from 2012 to 2014. 

It includes a wide range of information, such as customer demographics, which provide insight into the characteristics and profiles of the customers; purchase histories, which detail the products purchased and frequency of visits; and product offerings, which highlight the variety of items sold by the supermarket. 

Additionally, the dataset captures the various marketing campaigns conducted by Supermarket ABC during this period, enabling an in-depth analysis of their effectiveness and impact on customer behavior. 

This rich dataset serves as the foundation for uncovering actionable insights to drive strategic decision-making and boost sales performance.

**Key attributes (along with the data types):** 

#### ***People***
|No.|Column name| Description|
| --- | --- | :--- |
| 1 | ID | Customer's unique identifier | 
| 2 | Year_Birth | Customer's birth year| 
| 3 | Education | Customer's education level |
| 4 | Marital_status | Customer's marital status | 
| 5 | Income | Customer's yearly household income | 
| 6 | Kidhome | Number of children in cusstomer's household | 
| 7 | Teenhome | Number of teenagers in customer's household | 
| 8 | Dt_Customer | Date of customer's enrollment with the company |
| 9 | Recency | Number of days since customer's last purchase |
| 10 | Complain | 1 if the customer complained in the last 2 years, 0 otherwise |


#### ***Products***
|No.|Column name| Description|
| --- | :--- | :--- |
| 1 | MntWines | Amount spent on wine in last 2 years |
| 2 | MntFruits | Amount spent on fruits in last 2 years|
| 3 | MntMeatProducts | Amount spent on meat in last 2 years |
| 4 | MntFishProducts | Amount spent on fish in last 2 years |
| 5 | MntSweetProducts | Amount spent on sweets in last 2 years |
| 6 | MntGoldProds | Amount spent on gold in last 2 years |


#### ***Promotion***
|No.|Column name| Description|
| --- | :--- | :--- |
| 1 | NumDealsPurchases | Number of purchases made with a discount |
| 2 | AcceptedCmp1 | 1 if the customer accepted the offer in the 1st campaign, 0 otherwise| 
| 3 | AcceptedCmp2 | 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise |
| 4 | AcceptedCmp3 | 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise |
| 5 | AcceptedCmp4 | 1 if the customer accepted the offer in the 4th campaign, 0 otherwise |
| 6 | AcceptedCmp5 | 1 if the customer accepted the offer in the 5th campaign, 0 otherwise |
| 7 | Response | 1 if the customer accepted the offer in the last campaign, 0 otherwise |


#### ***Place***
|No.|Column name| Description|
| --- | :--- | :--- |
| 1 | NumWebPurchases | Number of purchases made through the company’s website |
| 2 | NumCatalogPurchases | Number of purchases made using a catalog |
| 3 | NumStorePurchases | Number of purchases made directly in stores |
| 4 | NumWebVisitsMonth | Number of visits to the company’s website in the last month |


## **Problem Statement** 
The management is seeking a deeper understanding of their customer base and the effectiveness of their past marketing efforts. Their primary goals are to evaluate previous campaigns, understand customer segmentation, and identify potential areas for growth and development. 

To address these objectives, the following key questions need to be explored:

* How the distribution of age, income and marital status affects customer purchasing patterns?
* What products are often purchased together by customers and how can this be used to increase sales?
* What products have the highest and lowest sales rate?
* How effective each campaign bacth to each product category revenue?

By answering these questions, the data analyst will provide Supermarket ABC's management with actionable insights to enhance their strategic decisions, ultimately aiming to increase sales and customer satisfaction in a competitive market environment.


