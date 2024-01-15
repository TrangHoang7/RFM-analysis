# RFM-analysis
## Context
The SuperStore company, a global retail giant with a vast customer base, plans to run Christmas and New Year marketing campaigns to appreciate loyal customers and target potential ones. The Marketing department seeks help from the Data Analysis team to overcome challenges in manually segmenting this year's customers due to the large dataset. They propose using a Python-based RFM model to efficiently categorize customers and deploy tailored marketing programs for each group, as the traditional Excel method is no longer viable given the company's growth and data volume.
## Data description
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
  - InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
  - StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
  - Description: Product (item) name. Nominal.
  - Quantity: The quantities of each product (item) per transaction. Numeric.
  - InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
