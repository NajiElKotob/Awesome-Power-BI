# Exam DP-600: Implementing Analytics Solutions Using Microsoft Fabric [⤴](https://learn.microsoft.com/en-us/credentials/certifications/exams/dp-600/)

{Awesome Works in Progress}

## Study Guides
* [Awesome Microsoft Fabric: A Comprehensive Guide to Microsoft Fabric References](https://github.com/NajiElKotob/Awesome-Microsoft-Fabric)
* [Study guide for Exam DP-600: Implementing Analytics Solutions Using Microsoft Fabric](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-600)
* [Microsoft Fabric Learn Together 📺](https://www.youtube.com/playlist?list=PL1N57mwBHtN0-AJVURyfqbdmX65JMXSVv) 🌟 - Microsoft Power BI
* [New Fabric certification and Fabric Career Hub](https://powerbi.microsoft.com/en-us/blog/new-fabric-certification-and-fabric-career-hub/)
  - [Get Your DP-600 the Smart Way: Microsoft Fabric Career Hub 📺](https://www.youtube.com/watch?v=U3aqC7VQTSw) - Guy in a Cube
* [Exam DP-600: Implementing Analytics Solutions Using Microsoft Fabric](https://learn.microsoft.com/en-us/credentials/certifications/exams/dp-600/)
* [Practice Assessment for Exam DP-600](https://aka.ms/DP600-Practice) - aka.ms/DP600-Practice
* [Kevin Chant](https://www.kevinrchant.com/?s=dp-600) 🌟 - A blog about Microsoft Data Platform offerings

  
## DP-600: Implementing Analytics Solutions Using Microsoft Fabric
### Plan, implement, and manage a solution for data analytics (10–15%)
#### Plan a data analytics environment
##### Identify requirements for a solution, including components, features, performance, and capacity stock-keeping units (SKUs)
* [Microsoft Fabric Capacity Licenses: Your Guide for Growth and Success](https://www.ais.com/microsoft-fabric-capacity-licenses-your-guide-for-growth-and-success/) - ais.com
* [Microsoft Fabric concepts and licenses](https://learn.microsoft.com/en-us/fabric/enterprise/licenses) - learn.microsoft.com

##### Recommend settings in the Fabric admin portal
* [What is the admin portal?](https://learn.microsoft.com/en-us/fabric/admin/admin-center)
* [How to Enable Fabric in Your Organization 📺 20min](https://www.youtube.com/watch?v=W5vrFHsGsIA) - Pragmatic Works

##### Choose a data gateway type
* [The Power BI Gateway; All You Need to Know](https://radacad.com/the-power-bi-gateway-all-you-need-to-know) - radacad.com
* [Use a personal gateway in Power BI](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-personal-mode)
* [What is an on-premises data gateway?](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-onprem)

##### Create a custom Power BI report theme
* [Use report themes in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes)

#### Implement and manage a data analytics environment
##### Implement workspace and item-level access controls for Fabric items
* [Control ACCESS to your Microsoft Fabric Lakehouse or Warehouse 📺](https://www.youtube.com/watch?v=MdmPjZAV9I8) - Guy in a Cube
* [Microsoft Fabric: Workspace access, Item level access, SQL policy and object level security](https://shabnamwatson.com/2023/11/14/microsoft-fabric-workspace-access-item-level-access-sql-policy-and-object-level-security/) - Shabnam Watson's Blog
  
##### Implement data sharing for workspaces, warehouses, and lakehouses

##### Manage sensitivity labels in semantic models and lakehouses

##### Configure Fabric-enabled workspace settings

##### Manage Fabric capacity

#### Manage the analytics development lifecycle

##### Implement version control for a workspace

##### Create and manage a Power BI Desktop project (.pbip)

##### Plan and implement deployment solutions

##### Perform impact analysis of downstream dependencies from lakehouses, data warehouses, dataflows, and semantic models

##### Deploy and manage semantic models by using the XMLA endpoint

##### Create and update reusable assets, including Power BI template (.pbit) files, Power BI data source (.pbids) files, and shared semantic models

-----

### Prepare and serve data (40–45%)


#### Create objects in a lakehouse or warehouse
##### Ingest data by using a data pipeline, dataflow, or notebook

##### Create and manage shortcuts

##### Implement file partitioning for analytics workloads in a lakehouse

##### Create views, functions, and stored procedures

##### Enrich data by adding new columns or tables

#### Copy data
##### Choose an appropriate method for copying data from a Fabric data source to a lakehouse or warehouse
* [How to copy data using copy activity](https://learn.microsoft.com/en-us/fabric/data-factory/copy-data-activity)
* [Ingest data into the Warehouse](https://learn.microsoft.com/en-us/fabric/data-warehouse/ingest-data)

##### Copy data by using a data pipeline, dataflow, or notebook

##### Add stored procedures, notebooks, and dataflows to a data pipeline
* [Preprocess data with a stored procedure before loading into Lakehouse](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-preprocess-data-with-stored-procedure-load-into-lakehouse)

##### Schedule data pipelines
* [Concept: Data pipeline Runs](https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-runs)
* [Run and schedule the data pipeline](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-dataflows-gen2-pipeline-activity#run-and-schedule-the-data-pipeline)

##### Schedule dataflows and notebooks


#### Transform data
##### Implement a data cleansing process

##### Implement a star schema for a lakehouse or warehouse, including Type 1 and Type 2 slowly changing dimensions

##### Implement bridge tables for a lakehouse or a warehouse

##### Denormalize data

##### Aggregate or de-aggregate data

##### Merge or join data

##### Identify and resolve duplicate data, missing data, or null values

##### Convert data types by using SQL or PySpark

##### Filter data

#### Optimize performance
##### Identify and resolve data loading performance bottlenecks in dataflows, notebooks, and SQL queries

##### Implement performance improvements in dataflows, notebooks, and SQL queries

##### Identify and resolve issues with Delta table file sizes

----


### Implement and manage semantic models (20–25%)
#### Design and build semantic models
##### Choose a storage mode, including Direct Lake
* [Semantic model modes in the Power BI service](https://learn.microsoft.com/en-us/power-bi/connect-data/service-dataset-modes-understand)
* [Direct Lake vs. Import mode in Power BI](https://www.sqlbi.com/blog/marco/2024/04/06/direct-lake-vs-import-mode-in-power-bi/) - sqlbi.com

##### Identify use cases for DAX Studio and Tabular Editor 2
* [External tools in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-external-tools)

##### Implement a star schema for a semantic model

##### Implement relationships, such as bridge tables and many-to-many relationships

##### Write calculations that use DAX variables and functions, such as iterators, table filtering, windowing, and information functions

##### Implement calculation groups, dynamic strings, and field parameters

##### Design and build a large format dataset

##### Design and build composite models that include aggregations

##### Implement dynamic row-level security and object-level security

##### Validate row-level security and object-level security

#### Optimize enterprise-scale semantic models
##### Implement performance improvements in queries and report visuals

##### Improve DAX performance by using DAX Studio

##### Optimize a semantic model by using Tabular Editor 2

##### Implement incremental refresh

-----


### Explore and analyze data (20–25%)
#### Perform exploratory analytics
##### Implement descriptive and diagnostic analytics

##### Integrate prescriptive and predictive analytics into a visual or report

##### Profile data

#### Query data by using SQL
##### Query a lakehouse in Fabric by using SQL queries or the visual query editor

##### Query a warehouse in Fabric by using SQL queries or the visual query editor
* [Query using the visual query editor](https://learn.microsoft.com/en-us/fabric/data-warehouse/visual-query-editor)
* [Query using the SQL query editor](https://learn.microsoft.com/en-us/fabric/data-warehouse/sql-query-editor)
* [View data in the Data preview in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/data-preview)
* [Delta Lake logs in Warehouse in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/query-delta-lake-logs)
  
##### Connect to and query datasets by using the XMLA endpoint




