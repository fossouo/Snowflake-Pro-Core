1. Which of the following objects can be cloned ? 
    A. Tables
    B. Named File Formats 
    C. Schemas
    E. Databases 
    
2. Which object allows you to limit the number of credits consumed within a Snowflake account 
    B. Resource Monitor 
    
3. Snowflake is designed for which type of workloads ? 
    A. OLAP (Analytics) workload 
    C. Concurrent workloads 
    
4. What are the three layers that make up Snowflake's architecture ? 
    A. Compute 
    C. Storage 
    D. Cloud Service
    
5. Why would a customer size a Virtual Warehouse from an X-Small to a Medium ? 
    C. To accommodate more complex workload 
    
6. Reader Accounts incur no additional Compute costs to the Data Provider since they are simply reading the shared data without making changes 
    B. False 
    
7. Which of the following connectors allow Multi-factor Authentication (MFA) authorization when connecting ? 
    A. JDBC 
    B. SnowSQL
    C. Snowflake Web UI
    D. ODBC 
    E. Python 
    
8. True or False, Snowflake charges a premium for storing semi-structured data 
    B. False
    
9. Which of the following statements describes a benefit of Snowflake's separation of compute and storage ? 
    B. Storage expands without the requirement to add more compute 
    C. Compute can be scale up or down without the requirement to add more storage 
    D. Multiple compute clusters can access stored data without contention 

10. True or False : it is possible to unload structured data to semi-structured formats such as JSON and Parquet. 
    A. True 
    
11. In which layer of its architecture does Snowflake store its metadata statistics ? 
    D. Cloud Services Layer 
    
12. True or False : Data in fail-sage can be deleted by a user or the Snowflake team before it expires 
    B. False 
    
13. True or False : Snowflake's data warehouse was built from the ground up for the cloud in lieu of using an existing database or a platform, like Hadoop, as a base. 
    A. True 

14. Which of the following statements are true of Virtual Warehouses ? 
    A. Customers can change the size of the warehouse after creation 
    B. A warehouse can be resized while running 
    C. A warehouse can be configured to suspend after a period of inactivity 
    D. A warehouse can be configured to suspend when new queries are submitted 
    
15. The PUT command : 
    C. Automatically compresses files using Gzip
    D. Automatically encrypts files 
    
16. Which type of table corresponds to a single Snowflake session 
    A. Temporary Table

17. Which interfaces can be used to create and / or manage Virtual Warehouses ? 
    A. The Snowflake Web Inteface (UI) 
    B. SQL Commands
    C. Data Integration tools 
    D. All of the above 
    
18. When a pipe is recreated using the CREATE OR REPLACE PIPE command : 
    A. The pipe load history is reset to empty 
    B. The refresh parameter is set to TRUE 
    C. Previously loaded files will be ignored 
    D. All of the above - X
    
19. When a Pipe is recreated using the CREATE OR REPLACE PIPE command : 
    A. The pipe load history is reset to empty

20. What is the minimum Snowflake edition that customers planning on storing protected information in Snowflake should consider for regulatory compliance ?
    D. Business Critical Edition 

21. Select the three types of tables that exist within Snowflake 
    A. Temporary 
    B. Transient 
    D. Permanent 
    
22. True or False, Snowpipe via REST API can only reference External Stages as source 
    B. False 
    
23. True or False: A Third-party tool that supports standards JDBC or ODBC but has no Snowflake-specific driver will be unable to connect to Snowflake 
    B. False 

24. True or False : it's possible to load data into Snowflake without creating a named File Format Object : 
    A. True 

25. True or False : A table in Snowflake can only be queried using the Virtual Warehouse that was used to load the data 
    B. False 
    
26. Which of the following statements are true of Snowflake data loading ? 
    D. It is recommended to use staging tables to manage MERGE statements 
    C. It is recommended to validate the data before loading into the Snowflake target table 
    A. Variant null values are not the same as SQL NULL values 
    
27. Which statements are true of micro-partitions ? 
    A. They are approximately 16 MB in size 
    C. They are immutable 
    
28. True or False : Query ID's are unique across all Snowflake deployments and can be used in communication with Snowflake Support to help troubleshoot issues 
    A. True 
    
29. A deterministic query is run at 8 am, takes 5 minutes, and the results are cached. Which of the following statements are true ? 
    B. The same exact query will return the precomputed results if the underlying data hasn't changed and the results were last accessed within previous 24 hour period
    D. The 24 hour timer on the precomputed results gets renewed every time the exact query is executed 
    
30. Snowflake provides a mechanism for its customers to override its natural clustering algorithms. This method is : 
    B. Clustering keys 

31. True or False : A single database can exist in more than one Snowflake account. 
    B. False 

32. Which of the following are valid Snowflake Virtual Warehouse Scaling Policies ? 
    B. Economy 
    D. Standard 
    
33. Which of the following roles is recommended to be used to create and manage users and roles ? 
    B. SECURITYADMIN 
    
34. True or False : Bulk unloading of data from Snowflake supports the use of a SELECT statement 
    A. True 
    
35. Select the different types of Internal Stages : 
    A. Named Stage 
    B. User Stage 
    C. Table Stage 
 
 36. True or False: A customer using SnowSQL / native connectors will be unable to also use the Snowflake Web Interface (UI) unless access to the UI is explicitly granted by support. 
    B. False 
 
 37. Account-level storage usage can be monitored via: 
    A. The Snowflake Web Interface (UI) in the Account -> Billing & Usage section 
    
 38. Credit Consumption by the Compute Layer (Virtual Warehouses) is based on : (choose two) 
    B. Warehouse size 
    D. # of clusters for the Warehouse 
    
 39. Which statement best describes `clustering` ? 
 
    A. Clustering represents the way data is grouped together and stored within Snowflake's micro-partitions 

 40. True or False: The Copy command must specify a File Format in order to execute
    B. False 
    
 41. Which of the following commands sets the Virtual Warehouse for a session ? 
    C. USE WAREHOUSE = << warehouse name >> 
    
 44. Which of the following objects can be cloned ? 
    A. Tables 
    B. Named File Formats 
    C. Schema 
    E. Databases 
