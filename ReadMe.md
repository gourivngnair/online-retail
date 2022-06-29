# RFM Analysis on Online Retail dataset

The online retail dataset is downloaded from the [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/online+retail). It is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Attribute Information:

- **InvoiceNo**: Invoice number. Nominal- is a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- **StockCode**: Product (item) code. Nominal- is a 5-digit integral number uniquely assigned to each distinct product.
- **Description**: Product (item) name. Nominal.
- **Quantity**: The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
- **CustomerID**: Customer number. Nominal- is a 5-digit integral number uniquely assigned to each customer.
- **Country**: Country name. Nominal, the name of the country where each customer resides.

RFM-based clustering is the clustering of customers based on their buying behaviour to ensure customer retention. It takes into account three attributes, mainly
- Recency: How long ago was the customer's last purchase
- Frequency: How many times has a customer made purchases from the store?
- Monetary: How much revenue does the customer generate?

Here, we are clustering the online retail dataset using **K-Means clustering** algorithm. 