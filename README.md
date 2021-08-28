# Definition of the RFM Analysis
==================================

![Cluserting](images\RFM Customer Analysis.png)

The RFM analysis is a marketing technique for analyzing customers.<br>
RFM is clustering customers based on 3 aspects:

- R for Recency:
When was the customer last purchase? <br>
You take the last order date from the hole data and add one day.<br>
Then you can calculate the Duration since the last purchase for each customer.<br>

- F for Frequency:<br>
How often did the customer make an order during the analysis periode?

- M for Monetary:<br>
How much did the customer spent?<br>

For further Information you can read [this artikel](https://cdn.intechopen.com/pdfs/13162/InTech-Data_mining_using_rfm_analysis.pdf)


# The Data
==================================
The source of the used data is on [kaggle](https://www.kaggle.com/benroshan/ecommerce-data).

The data includes 3 csv files:
1. List of Orders <br>
This dataset contains purchase information. The information includes ID, Date of Purchase and customer details
2. Order Details <br>
This dataset contains order ID, with the order price, quantity,profit, category and subcategory of product
3. Sales target <br>
This dataset contains sales target amount and date for each product category