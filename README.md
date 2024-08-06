# Poshem-Mid-year-Business-Analysis
Analyzing Poshem Business Data set and give recommendation

## <center>Poshem Business School</center>
### Mid Season Review July 2024

### Project Overview:

Poshem Business School's CEO, Simon E. Akhamie has tasked the data analytics team with
conducting an <b>Exploratory data analysis (EDA)</b> on the company's sales dataset. 
<br>The objective is to derive meaningful insights and patterns that can inform strategic decisions. The dataset
comprises information on orders, customers, products, and shipping details.

### Exploratory Data Analysis (EDA) Questions:
#### Overview:

What is the timeframe of the dataset? (Start and end date)

● How many rows and columns are there in the dataset?


● Are there missing values? If yes list them and fix them


● What are the data types of each column?


● Are there duplicates in the dataset? If yes list them and fix them


● Give a quick statistical description of numerical contents in the dataset.



#### Understandind the dataset columns

<b>Row ID:</b> This identifies a particular row in the dataset

<b>Order ID:</b> This identifies a particular order in the dataset

<b>Order Date:</b> This identifies the paricular date the order is placed

<b>Ship Date:</b> The Date when the oder is shipped 

<b>Ship Mode:</b> The mode of the ship whether 'Second Class', 'Standard Class', 'First Class' or 'Same Day'

<b>Customer ID:</b> This shows the unique idenity of a particular customer

<b>Customer Name:</b> This idenity the of a particular customer

<b>Segment:</b> This shows the segment or categories in which the order is being placed either 'Consumer', 'Corporate', 'Home Office'

<b>Country:</b> The Country of residence from which the order is placed from

<b>City:</b> The City of residence from which the order is placed from

<b>State:</b> The State of residence from which the order is placed from

<b>Postal Code:</b> The Postal Code of the residence from which the order is placed from

<b>Region:</b> The Region from which the order is placed from 

<b>Product ID:</b> This shows the unique idenity of a particular Product

<b>Category:</b> This shows the Category a particular Product

<b>Sub-Category:</b> This shows the Sub-Category a particular Product

<b>Product Name:</b> This shows the Product Name

<b>Sales:</b> The Sale amount of the product

#### Exploratory Data Analysis (EDA) Questions:
##### Overview:
● What is the timeframe of the dataset? (Start and end date)

● How many rows and columns are there in the dataset?

● Are there missing values? If yes list them and fix them

● What are the data types of each column?

● Are there duplicates in the dataset? If yes list them and fix them

● Give a quick statistical description of numerical contents in the dataset.


##### Order Statistics:
● How many unique orders are there in the dataset?

● What is the distribution of order statuses (e.g., delivered, pending)?

● How many unique customers are there?


##### Geographical Insights:
● Which countries are included in the dataset?

● What is the distribution of orders across different regions?

● Can you identify the top 5 cities with the highest number of orders?


##### Product Categories:
● How many unique product categories are there?

● What are the most popular product categories based on sales?

● Can you identify the top 5 selling products?


##### Customer Segmentation:
● How are customers segmented based on the "Segment" column?

● What is the average order value for each customer segment?


##### Shipping Insights:
● What are the different shipping modes available?

● How does the shipping mode relate to the order date and delivery date?

● Are there any patterns in shipping modes based on regions?


##### Sales Distribution:
● What is the overall distribution of sales values?

● Are there any outliers in the sales data?

● Can you visualize the distribution of sales for each product category?


##### Project Deliverables:
● Summary of key findings.

● Any actionable recommendations based on the analysis.

Display all this information using either Seaborn or Matplotlib

#### Project Deliverables:

● Summary of key findings

From the datase, the following insight were found

1. The time frame of the dataset?  <b>Start date is:</b> 3rd January 2015  -- <b>End date is:</b>    30th December 2018
2. The Dataset has 9800 rows  and 17 columns
3. There was 11 empty rows from the postal code column, it was fixed by comparing the rows with similar city and country
4. We found a duplicaed columns, row Id 3406 and 3407 were duplicate and row id 3407 was removed.
5. Satistical description was done on the dataset and we noticed that from the sales column, we had a minimun sales value of 0.444000 and maximum of 22638.480000.
6. We have about 4922 unique orders in the dataset, which means that some of the order had different products but the same orders.
7. we have about 793 unique customers in the dataset, that is to say that most of the customers placed more than one order.
8. United State is the only country included in the dataset.

9. The distribution of orders across different regions are: Central: 2277, East: 2784, South: 1598, West: 3140
10. The top 5 cities with the highest number of orders are: New York City: 891, Los Angeles: 728, Philadelphia: 532, San Francisco: 500, Seattle: 426.
11. There are 3 unique product categories 'Furniture', 'Office Supplies', 'Technology'.
12. the product categories on sales count are Office Supplies	5909, Furniture	2077, Technology	1813, but the 'Office Supplies' is the most popular product category with the highest sale count.
13. From he dataset, the top 5 selling products? are: Staple envelope	47 sales, Staples	46 sales, Easy-staple paper	44sales,  Avery Non-Stick Binders	20 sales, Staples in misc. colors	18 sales, Staple remover	18 sales.
14. from the dataset, we can noticed that products that are been delivered in the same day has lesser delivery time than products that we delivered using the standard class shipping mode which took an average of 5 days to be delivered, while that of first class and second class shipping mode took an average of 2 and 3 days respectively to be delivered
15. It was also noticed that the standard class shipping mode was used for most of the regions, just few was shipped on the same day and his happened for all the regions.
16. The sales data has ouliers. 

    It was observed tha most sales values is between 0.44400 which is less than 1 to 1200 sales amount, While not much sales are made above 1200.

    We can say the sales was mostly distributed between 0 USD to 1200 USD
    
17. The average sales amount distrubuion for the caegories are Technology	456.401474, Furniture	350.687147, Office Supplies	119.381001


#### Actionable recommendations based on the analysis
1. For customer satisfaction, we recommend that products should be delivered on the first day or using either the first or the second class shipping more which took 2 to 3 days instead of using the standard class shipping mode which too 5 days to be delivered, and it was used for all the regions which can lead to customer dissatisfaction. This will encourage the customer to order more products where the delivery time is optimal.

2. For product production, products of the office supplies category are most popular and mostly ordered, that we noticed by checking for the top 5 selling products as that of the office supplies products were the highest, so considerations might be given on producing more of office Supplies, even though the sales amount is largely distributed among the Technology products maybe because the Technology products are more expensive.

    So the price of the products should also be considered inorder to have much sales count for the different products.
