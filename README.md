# Superstore-Evaluation
---

# Table of Content

[Project Overview](#project-overview)

[Data Source](#data-source)

[Tools Used](#tools-used)

[Data Preparation](#data-preparation)

[Data Overview](#data-overview) 

[Tabular Overview](#tabular-overview) 

[Analysis Visualisation](#analysis-visualisation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Key Findings](#key-findings)

[Recommendations](#recommendations)

[Limitations](#limitations)


---

## Project Overview

An assessment of superstore historical sales data of the United State of America aimed to extract actionable data-driven insights to increase performance, profitability, and customer satisfaction.  Leveraging Excel and Power BI, raw data is transformed into interactive dashboards that support analysis to understand key factors impacting sales and profit in the USA across multiple dimensions including product categories, regions, segments, ship modes, and time trends. 

## Data Source

A primary *Excel data file* that contains information on superstore transactions.

## Tools Used

1. Excel

- Data cleaning and structuring. 
  - [Highlighted Here](https://ibb.co/YTNDsCMm)
- Exploring and performance across categories in Superstores. 
- Data Visualization
  - [Click here](https://ibb.co/ns5vps1M)


2. Power BI
- Data Importing: Getting data as an excel file in PowerBI
 - Data Transformation and Manipulation: Use of powerquery for Table quality and distribution. Dax function for a calculated column of the Year. [Clik Here](https://ibb.co/4ntwcfVb)
- Data visualization of pre-processed data. [View here](https://ibb.co/23Z5rKdw)


## Data Preparation
  1.	Data loading and Preparation
     
  2.	Handling errors
     
  3.	Data formatting – Column Type 

## Data Overview

The datasets includes the following columns:

  - Row ID: this are the serial number down the cells
  - Order ID: An identifier number assigned to each customer order
  -Order Date: The Period in which product line was Ordered
  - Ship Date: The date it was shipped into the country 
  - Ship Mode: The category Class to which it was move into the Country 
  - Customer ID: The identification number assigned to every customer per purchase(s) 
  - Customer Name: The name of customer
  - Segment: The type of customer placing the order 
  - Country: The Country the sales are made
  - City: The City sales are made
  - State: The State of the country that sales are transacted 
  - Postal code: The code that tells the delivery location
  - Regin: A broader geographic area grouping multiple states
  -  Product ID: An identifier number for every product sold.
  - Category: The Grouped products
  - Sub-Category: A more specific grouping within each category
  - Product Name: The kind of Product  
  - Sales: The total revenue generated
  - Profit: The net income (gains) of sales after deducting costs. 
  - Quantity: The numbers of unit bought/sold
  - Discount: The percentage reduction applied to the product’s original price

## Tabular Overview 

A brief overview of the tabular datasets to be evaluated. the first 5 records are displayed below.

|Row ID|	Order ID|	Order Date|	Ship Date|	Ship Mode|	Customer ID|	Customer Name|	Segment|	Country|	City|	State|	Postal Code|	Region|	Product ID|	Category|	Sub-Category|	Product Name|	Sales|	Quantity|	Discount|	Profit|
|-----|-----|-----|-----|-----|-----|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|
|1	|CA-2013-152156|	09/11/13|	12/11/2013|	Second Class|	CG-12520|	Claire Gute|	Consumer|	United States|	Henderson|	Kentucky|	42420|	South|	FUR-BO-10001798|	Furniture|	Bookcases|	Bush Somerset Collection Bookcase|	261.96|	2|	0|	41.9136|
|2	|CA-2013-152156|	09/11/13|	12/11/2013|	Second Class|	CG-12520|	Claire Gute|	Consumer|	United States|	Henderson|	Kentucky|	42420|	South|	FUR-CH-10000454|	Furniture|	Chairs|	Hon Deluxe Fabric Upholstered Stacking Chairs, Rounded Back|	731.94|	3|	0|	219.582|
|3	|CA-2013-138688|	13/06/2013|	17-06-2013|	Second Class|	DV-13045|	Darrin Van Huff|	Corporate|	United States|	Los Angeles|	California|	90036|	West	|OFF-LA-10000240|	Office| Supplies|	Labels	Self-Adhesive Address Labels for Typewriters by Universal	|14.62	|2	|0	|6.8714|
|4	|US-2012-108966|	11/10/12|	18-10-2012|	Standard Class|	SO-20335|	Sean O'Donnell|	Consumer|	United States|	Fort Lauderdale|	Florida|	33311|	South|	FUR-TA-10000577|	Furniture|	Tables|	Bretford CR4500 Series Slim Rectangular Table|	957.5775|	5|	0.45|	-383.031|
|5	|US-2012-108966|	11/10/12|	18-10-2012|	Standard Class|	SO-20335|	Sean O'Donnell|	Consumer|	United States|	Fort Lauderdale|	Florida|	33311|	South|	OFF-ST-10000760|	Office Supplies|	Storage|	Eldon Fold 'N Roll Cart System|	22.368|	2|	0.2|	2.5164|



## Analysis Visualisation
Chart Visualisation of the transformed data

![Screenshot (41)](https://github.com/user-attachments/assets/d2c0ab22-2cc6-4b4c-ac48-e3ad0150aac9)


![Screenshot (42)](https://github.com/user-attachments/assets/5711c7fa-da53-4d65-868f-0c145681d5de)


## Exploratory Data Analysis

Data is explored to answer Key question such as;

i. What are the top and underperforming markets based on geographical locations.

ii.	Which product Category and Sub-category are driving the most revenue or loss.

iii.	Which Products names are top 10 sellers 

iv.	 What shipping mode is most popular and efficient per Regional location

v.	What is the impact of discounts on profitability 

vi.	What is the Yearly Sales Trend . 

vii.	What customer groups has high and low revenues (sales) in specific regions.

viii.	What are the Sales Performance across Segment and Categories .


## Key Findings
The outcome of the analysis are outlined as folloes:

1.	The high performing regions are West and East with a Revenue of 725K and 679K respectively and low performing regions are Central and South with revenue of 501K and 392K.

2.	Standard class is the dominant shipping mode across all regions, with minimal use of First Class and Same day options.

3.	The consumer segment generates the highest sales, Corporate segment next in- line and the Home office segments lagging behind across all regions.

4.	Discounts between 0-0.2 yields positive profits indicating gain-making transactions. Discounts higher than 0.2 yield negative profit, indicating loss-making transactions.  

5.	The Revenue by segment and category indicate that Consumer outperforms both Corporate and Home Office Segment in all Categories of Technology, Office Supplies and Furniture. Technology products has the largest sales and furniture contributing lower sales across all segments.  

6.	 The Top 10 Product lines with best sales are aligned Descending in this order of Canon imageCLASS 2200 Advanced Copier < Fellowes PB500 Electric Punch Plastic Comb Binding Machine with Manual Bind < Cisco TelePresence System EX90 Videoconferencing Unit< HON 5400 Series Task Chairs for Big and Tall< GBC DocuBind TL300 Electric Binding System< GBC Ibimaster 500 Manual ProClick Binding System< Hewlett Packard LaserJet 3310 Copier< GBC DocuBind P400 Electric Binding System< HP Designjet T520 Inkjet Large Format Printer - 24" Color< High Speed Automatic Electric Letter Opener.

7.	Technology absorbs discounts pressure much better than Office supplies and Furniture. Furniture reveals the highest decline in profit with increased discounts. 

8.	There is an upward trend in both sales and profits form 2011(0.48M) to 2014(0.73M).

9.  A show of geographic map sales spread 

## Recommendations

### Region
- Sales and marketing efforts should be improved in the South and Central regions to improve overall revenue distribution.

### Region and Ship mode
- Incentivize faster shipping mode options in lagging regions. 
- Explore why alternatives shipping modes are underutilized.

### Region and Segment
- The use of corporate platforms and tailored platforms to promote office solutions to Home Office and Corporate users.

### Profit and Discount
- Optimize discount offering between 0.1-0.25
- Discounts can be replaced with complementary value bundle (Printer + Paper)

### Product Name
- Upsells and promotions should be made for this ten product line
 - Customer feedbacks should be assessed on underperformed product lines on their choice reason.

### Segment and Category
- Implement the use of Cross selling, suggesting technology tools to corporate clients and office essentials to consumer.


## Limitations

During the development of this Power BI report, the complete dataset could not be fully loaded due to memory and platform performance limits when handling large datasets. 
As a result, a cleaned and representative subset of the data was used to ensure smooth interactivity and accurate analysis without compromising performance.




💻 📉 📈







