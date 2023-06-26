**MIAMI Superstore Transactions Analysis**
***
![](images.jpg)
***
**Introduction**
- This project focuses on using Microsoft PowerBI to conduct sale analysis for a fictional store named " MIAMI Superstore". The primary goal is to analyze  the data and extract valuable insights in order to address essential questions that will enable the store to make informed decisions that's data-driven 
- Disclaimer: Please note that the dataset used and report generated in this context are purely fictional and do not represent any specific company ,country or institution.  They have been solely created for the purpose of demonstrating the capabilities of PowerBI .
- MIAMI store is a fictional store that sells three(3) categories of products:Technology, Furniture and office supplies.
  **Problem Statement**
  ***
1. To identify the Profit margin over the past 5 years(2014-2017)
2.To identify how sales and profit trended on monthly and yearly basis
3.The products sub-category that's most profitable and least profitable
4.To examine the Top 5 and Bottom 5 product performance 
5. Total Sales revenue and Profit generated
6. The total cost incurred for goods / Products availability without the operating expenses
7. The Profit by segment ,category and Region.
**Skills Demonstrated**
***
       1. Data preparation, transformation using Microsoft excel and Power Query Editor (PowerBI)
       2. Data modelling
       3 DAX
       4. Quick measures 
       5 connecting Slicers with the report
       6. Ribbon chart 
       7. Hyperlinks 
       8. Tooltips
       9.Filters
       10. creating a Calendar Table.
       
 **Data sourcing**
 ***
The sample Suoerstore dataset was gotten from Data.World
**Data Transformation**
***
1.The dataset( Transaction Table) was transformed using Power Query Editor (PowerBI) 
2.Three(3) Dimension Tables(Customer, Location ,Product) were formed from the Transaction Table and all the categorized tables were grouped according to related data concept
2. Fact able ( Transaction Table ) was renamed SALESFact
3. Duplicates were removed from the Dimension Tables 

![](1a.png)
![](1.png)
![](8.png)
![](9.png)

Data modelling

Please note that all the necessary relationship couldn't  be formed  successfully I.e the Product ID could not form a one (1) to many(*)  Relationship because PowerBI needed assurance that the many(*) to many(*) Relationship is valid( can serve its intended purpose) before interpreting it the way it ought to be.

Technique Applied to Solve Barrier Encountered 
I examined the dataset( Transaction Table ) from the  secondary source (where I imported the file from I.e Microsoft excel) in order to verify if any many(*) to many (*) Relationship was formed in any of the data category I.e the dimension tables . I realized the Product ID and Product Name fields/columns
contained duplicated values respectively and since the Product ID and Product Name are under the same data category,  i merged both of them to form a unique identifier (Primary key;Product key ) for the product category then merged the two columns(Product ID and Product Name) accordingly to form the same Primary key;
Product key for the Fact Table(SALESFact) .
I removed both the Product ID and Product Name columns from the Fact Table after merging to form Product Key

Put the necessary images that's is related here


Data modelling image here 
 The structure of the data follows a star schema design consisting of three(3) Dimension Tables (Customer, Location and Product) and one Fact Table (SALESFact). The dimension tables are connected  to the Fact Table through a one(1) to many(*)
Relationship. 

Visualization image here 

![](VISUALIZATION.png)

**Variance( Difference in Sales & Profit) Analysis**
***
This report should help the Superstore management team have a mind blueprint to evaluate and get answers to the following questions:
Which products have impressive  profitable Performance ?
How will the trends suit planning and budget allocation?
Are the the Pricing and Promotion really effective?
How can the Performance Benchmarking be determined?
Which  areas are showing inefficiencies?
What are the factors influencing the sales and Profit Variance?
The images below represent the variance according to periods( Month over Month ,Year over Year I.e monthly and yearly basis respectively for Sales and Profit. 

![](V1.png)
![](V2.png)
![](V3.png)
![](V4.png)
![](V6.png)
![](V10.png)
![](V11.png)
![](V13.png)
![](V14.png)
![](V15.png)

Top Performance chart ( sales and profit)
talk about the items 
Technology  device( Phone) is the most Profitable product ,it generates close to 45% of the 
Total profit 
The Paper(23.79%) and Binders(21.12%) implies the office equipment generate an impressive quota of the profits likewise the storage equipment(14.87%) and Furnishing equipment (9.12%)
![](V21.png)
![](V22.png)
![](V23.png)
![](V24.png)
![](V25.png)
Bottom Performance chart
![](V26.png)
![](V27.png)




Conclusion



Recommendations





Link to PowerBI service here
one drive Google drive for the Pbix file link here
