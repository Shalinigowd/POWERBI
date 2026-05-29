Data Warehousing Concepts – Questions & Answers

1. What is a Data Warehouse?

Answer:
A Data Warehouse is a centralized system used to store large volumes of structured data collected from multiple sources for reporting and analysis.

It is optimized for querying and analytics, not transactions.

Example:
A retail company stores sales data from POS, website, and mobile app into a single warehouse for reporting.

2. What are the characteristics of a Data Warehouse?

Answer:
A Data Warehouse has 4 key characteristics:

Subject-Oriented → Focused on business areas (Sales, Finance)
Integrated → Combines data from multiple sources
Time-Variant → Stores historical data
Non-Volatile → Data is not frequently updated or deleted

3. Difference between Data Warehouse and Database?
Database (OLTP)	      Data Warehouse (OLAP)
Used for transactions	Used for analysis
Real-time operations	Historical data
Normalized structure	Denormalized structure
Fast inserts/updates	Fast querying

4. What is OLTP?

Answer:
OLTP (Online Transaction Processing) systems are used to manage day-to-day transactions.

Example:
Banking systems, booking systems, e-commerce checkout systems.

5. What is OLAP?

Answer:
OLAP (Online Analytical Processing) is used for analyzing large datasets and business intelligence reporting.

Example:
Sales trends, customer behavior analysis, financial reporting.

6. Difference between OLTP and OLAP?
OLTP	                 OLAP
Transactional	         Analytical
Small data operations	 Large data processing
Real-time updates	     Historical analysis
High concurrency	     Complex queries

7. What is ETL in Data Warehousing?

Answer:
ETL stands for:

Extract → Get data from sources
Transform → Clean and process data
Load → Store data in Data Warehouse

Tool Example:
Power BI Power Query, Informatica, SSIS

8. What is Data Mart?
Answer:
A Data Mart is a subset of a Data Warehouse focused on a specific business area.

Example:
Sales Data Mart
HR Data Mart
Finance Data Mart
9. Difference between Data Warehouse and Data Mart?
Data Warehouse	Data Mart
Enterprise-wide data	Department-specific data
Large volume	Smaller subset
Complex	Simple

10. What is Fact Table?

Answer:
A Fact Table contains measurable, quantitative data.

Examples:
Sales Amount
Quantity Sold
Profit

11. What is Dimension Table?
Answer:
A Dimension Table contains descriptive attributes used for filtering and grouping.

Examples:

Product Name
Customer Details
Region
Date

12. Difference between Fact and Dimension Table?
Fact Table                 Dimension Table
Numeric data	             Descriptive data
Contains metrics	         Contains attributes
Foreign keys	             Primary keys

13. What is Star Schema?
Answer:
A Star Schema is a data model where a central Fact Table is connected to multiple Dimension Tables.

Example:
Sales Fact → Product, Customer, Date, Region

Advantage:
Fast performance and simple design.

14. What is Snowflake Schema?
Answer:
A Snowflake Schema is an extension of Star Schema where dimension tables are normalized into multiple related tables.
Example:
Product → Category → Subcategory
Disadvantage:
More complex queries and slower performance.

15. Star Schema vs Snowflake Schema?
Star Schema       	Snowflake Schema
Denormalized	      Normalized
Simple design	      Complex design
Faster queries	    Slower queries
Easy maintenance	  Hard maintenance
16. What is Schema  Design Importance?

Answer:
Schema design improves:

Query performance
Data organization
Reporting efficiency
Scalability

17. What is Grain in Data Warehouse?

Answer:
Grain defines the level of detail in a fact table.

Example:

Daily sales per product per store = fine grain
Monthly sales per region = coarse grain

18. What is Slowly Changing Dimension (SCD)?
Answer:
SCD manages changes in dimension data over time.
Types:
Type 1: Overwrite old data
Type 2: Keep history with new row
Type 3: Store limited history in new column
Example:
Customer address change tracking.

19. What is Data Modeling in Data Warehousing?
Answer:
Data modeling is designing how data is structured, related, and stored in a warehouse for efficient reporting.

20. What is Aggregation in Data Warehouse?
Answer:
Aggregation is summarizing data to improve performance.

Example:
Daily sales → Monthly sales → Yearly sales

21. What is a Surrogate Key?

Answer:
A Surrogate Key is a unique system-generated key used instead of natural business keys.
Example:
CustomerID = 101 (instead of phone number or email)

22. What is a Natural Key?
Answer:
A Natural Key is a real-world attribute used to identify records.
Example:
Email ID, PAN number, Aadhaar number

23. Why do we use Surrogate Keys?

Answer:
Avoid business logic dependency
Improve performance
Handle SCD changes
Ensure uniqueness

24. What is Data Cleansing?
Answer:
Process of fixing or removing incorrect, duplicate, or incomplete data.

Examples:
Removing duplicates
Fixing null values
Standardizing formats

25. What is a Bus Matrix?
Answer:
A Bus Matrix maps business processes to facts and dimensions in a data warehouse.
Example:
Sales, Inventory, Finance → shared dimensions like Date, Product, Customer

26. What is Conformed Dimension?
Answer:
A dimension shared across multiple fact tables.
Example:
Date Dimension used in Sales, Inventory, Finance tables

27. What is Data Warehouse Architecture?
Answer:
Layers:

Data Source Layer
Staging Layer
ETL Layer
Data Warehouse Layer
Presentation Layer (Power BI)

28. What is Staging Area?
Answer:
A temporary storage area where raw data is cleaned and transformed before loading into the warehouse.

29. What is Metadata?
Answer:
Metadata is data about data.

Example:

Column name
Data type
Source system
Refresh time

30. What are the benefits of Data Warehousing?

Answer:
Faster reporting
Historical analysis
Better decision making
Centralized data
Improved data quality
