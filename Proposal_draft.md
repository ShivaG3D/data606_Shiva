# Capstone Project: Customer Lifetime Value (CLV) Prediction 
**Name: Shiva S (Fall 2022-Data 606)**

## Introduction

Analyzing customer lifetime value is critical to improving marketing decision-making, campaign ROI and customer retention. Weirdly, everyone in marketing understands its importance, but few can define it sufficiently to measure it correctly. The exact same thing applies to customer retention, which is also commonly misunderstood by most marketers. **Customer Lifetime Value is the discounted value of future profits a customer yields to the company.** Customer lifetime value can help you see which customers are worth your focus and investment and allow you to better plan your marketing budget.

## Data Source and Description

### Online Retail Data Set
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

### Attribute Information:
-   InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
-   StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
-   Description: Product (item) name. Nominal.
-   Quantity: The quantities of each product (item) per transaction. Numeric.
-   InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
-   UnitPrice: Unit price. Numeric, Product price per unit in sterling.
-   CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
-   Country: Country name. Nominal, the name of the country where each customer resides. 

### Online Shoppers Purchasing Intention Dataset
This dataset contains Online Shoppers Of the 12,330 sessions in the dataset, 84.5% (10,422) were negative class samples that did not end with shopping, and the rest (1908) were positive class samples ending with shopping.

### Global Superstore Dataset information
The Global Super Store dataset is a customer-centric dataset, which has all the orders placed through different vendors and markets. The attributes and dataset information for Global Superstore dataset are described in TABLE III.

Below data elements represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.
-	Administrative
-	Administrative_Duration
-	Informational
-	Informational_Duration
-	ProductRelated
-	ProductRelated_Duration

-	BounceRates: Feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session
-	ExitRates: The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session
-	PageValues: The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction
-	SpecialDay: The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. 	The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 
-	Month - Calender Month

    _The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year._

-	OperatingSystems
-	Browser
-	Region
-	TrafficType
-	VisitorType
-	Weekend
-   Revenue : The 'Revenue' attribute can be used as the **class label**.


## Approach / Methodologies
-  Analyze and visualize data in Python using pandas and Matplotlib
-  Study clustering techniques, such as hierarchical and k-means clustering
-  Create customer segments based on manipulated data
-  Predict customer lifetime value using linear regression, DNN
-  Use classification algorithms to understand customer choice
-  Optimize classification algorithms to extract maximal information



## Reference
*   https://marketinglabs.co.uk/why-you-need-to-be-measuring-customer-lifetime-value/
*   https://www.shopify.com/au/blog/customer-lifetime-value
*   https://wsp.wharton.upenn.edu/blog_post/customer-lifetime-value-centricity-peter-fader-ted-x-penn-talk/
*   https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf


