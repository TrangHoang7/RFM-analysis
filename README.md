# RFM-analysis
code: https://colab.research.google.com/drive/1AWNUFVQ2z2HV-WOF7QEGZGHlUv8wnLV-
## Context
The SuperStore company, a global retail giant with a vast customer base, plans to run Christmas and New Year marketing campaigns to appreciate loyal customers and target potential ones. The Marketing department seeks help from the Data Analysis team to overcome challenges in manually segmenting this year's customers due to the large dataset. They propose using a Python-based RFM model to efficiently categorize customers and deploy tailored marketing programs for each group, as the traditional Excel method is no longer viable given the company's growth and data volume.
## Data description: 2 tables

Ecommerce retail: This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
  - InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
  - StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
  - Description: Product (item) name. Nominal.
  - Quantity: The quantities of each product (item) per transaction. Numeric.
  - InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
  - UnitPrice: Unit price. Numeric, Product price per unit in sterling.
  - CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
  - Country: Country name. Nominal, the name of the country where each customer resides.

Segmentation: 2 columns (Segment; RFM score)

## Insights
  - The company has a significant number of Champions, Loyal, and Potential Loyalist customers. This indicates that the company is doing well in retaining current customers and attracting new ones.
  - Additionally, there is a noteworthy number of At Risk and Can't Lose Them customers. These customers have previously spent a substantial amount and made frequent purchases but have not made any purchases from the company for a considerable period. These high-value customers require reactivation strategies.
  - The company also has a segment of Hibernating customers. These customers have a long history of purchasing from the company but spend less and make infrequent purchases.

## Business question: Suggestions for the Superstore Marketing and Sales teams regarding the company's retail model should focus on which of the three indices R, F, M?
  - The Marketing and Sales teams should also pay attention to the Recency and Monetary indices. However, the Frequency index is the most crucial factor that the company should concentrate on.
  - The Frequency index indicates the number of times a customer makes a purchase within a specific period. For a retail model, purchasing frequency is a critical factor that determines the company's revenue and profitability.
  - According to the chart, approximately 60% of customers make frequent purchases. These are high-value customers, and the company should prioritize retaining them.
  - The company also has about 30% of customers who make a purchase only once. This indicates the company should focus on encouraging these customers to make more purchases.
## Recommendations
  - Retention Strategy:
    Send promotional emails to customers about products they have viewed or purchased in the past or items in their cart.
    Implement a customer loyalty program offering free delivery, points for gift redemption, and exclusive benefits for the customer group.

  - Stimulation and Development Strategy:
    Provide special discounts for customer groups making higher-value purchases or shopping frequently within a specific timeframe.
    Encourage customers to accumulate points and receive more benefits through regular shopping.
    Promote participation to enhance loyalty and reduce shipping costs.
    Based on shopping history and personal preferences, offer personalized product suggestions and information about special promotional programs.
    Notify customers about upcoming products, services, or events that may interest them.
    Product Reviews and Ratings: Send reminder emails to encourage customers to review and rate previously purchased products to foster interaction and increase engagement.
