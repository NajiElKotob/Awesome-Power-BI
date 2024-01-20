# DP-500: Designing and Implementing Enterprise-Scale Analytics Solutions Using Microsoft Azure and Microsoft Power BI [⤴](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-500)
`
As a candidate for this exam, you should have advanced Power BI skills, including managing data repositories and data processing in the cloud and on-premises, along with using Power Query and Data Analysis Expressions (DAX). You should also be proficient in consuming data from Azure Synapse Analytics and should have experience querying relational databases, analyzing data by using Transact-SQL (T-SQL), and visualizing data.
`

## Data Analytics Environment Implementation and Management (25–30%)

### Govern and Administer a Data Analytics Environment
- Manage Power BI assets by using Microsoft Purview.
- Identify data sources in Azure by using Microsoft Purview.
- Recommend settings in the Power BI admin portal.
- Recommend a monitoring and auditing solution for a data analytics environment, including Power BI REST API and PowerShell cmdlets.

### Integrate an Analytics Platform into Existing IT Infrastructure
- Identify requirements for a solution, including features, performance, and licensing strategy.
- Configure and manage Power BI capacity.
  - [Large semantic models in Power BI Premium](https://learn.microsoft.com/en-us/power-bi/enterprise/service-premium-large-models) 
- Recommend and configure an on-premises gateway type for Power BI.
- Recommend and configure a Power BI tenant or workspace to integrate with Azure Data Lake Storage Gen2.
- Integrate an existing Power BI workspace into Azure Synapse Analytics.

### Manage the Analytics Development Lifecycle
- Commit Azure Synapse Analytics code and artifacts to a source control repository.
- Recommend a deployment strategy for Power BI assets.
- Recommend a source control strategy for Power BI assets.
- Implement and manage deployment pipelines in Power BI.
- Perform impact analysis of downstream dependencies from dataflows and datasets.
- Recommend automation solutions for the analytics development lifecycle, including Power BI REST API and PowerShell cmdlets.
- Deploy and manage datasets by using the XMLA endpoint.
  - [Power BI XMLA Endpoint: Why you should care](https://www.youtube.com/watch?v=YEIKzeNCqGg) - Guy in a Cube
- Create reusable assets, including Power BI template (.pbit) files, Power BI data source (.pbids) files, and shared datasets.

## Query and Transform Data (20–25%)

### Query Data using Azure Synapse Analytics
- Identify an appropriate Azure Synapse pool when analyzing data.
- Recommend appropriate file types for querying serverless SQL pools.
- Query relational data sources in dedicated or serverless SQL pools, including querying partitioned data sources.
- Use a machine learning PREDICT function in a query.

### Ingest and Transform Data using Power BI
- Identify data loading performance bottlenecks in Power Query or data sources.
- Implement performance improvements in Power Query and data sources.
- Create and manage scalable Power BI dataflows.
- Identify and manage privacy settings on data sources.
- Create queries, functions, and parameters using the Power Query Advanced Editor.
- Query advanced data sources, including JSON, Parquet, APIs, and Azure Machine Learning models.

## Implement and Manage Data Models (25–30%)

### Design and Build Tabular Models
- [Choose when to use DirectQuery for Power BI datasets.](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-use-directquery)
- Choose when to use external tools, including [DAX Studio](https://daxstudio.org/docs/intro/) and [Tabular Editor 2](https://www.sqlbi.com/tools/tabular-editor/).
- [Create calculation groups.](https://learn.microsoft.com/en-us/analysis-services/tabular-models/calculation-groups?view=asallproducts-allversions)
- Write calculations using DAX variables and functions.
  - [Use variables to improve your DAX formulas](https://learn.microsoft.com/en-us/dax/best-practices/dax-variables) 
- Design and build a large format dataset.
- Design and build composite models, including aggregations.
- Design and implement enterprise-scale row-level security and object-level security.

### Optimize Enterprise-Scale Data Models
- Identify and implement performance improvements in queries and report visuals.
- Troubleshoot DAX performance using DAX Studio.
- Optimize a data model using Tabular Editor 2.
- Analyze data model efficiency using VertiPaq Analyzer.
- Optimize query performance using DAX Studio.
- Implement incremental refresh (including the use of query folding).
- Optimize a data model using denormalization.

## Explore and Visualize Data (20–25%)

### Explore Data using Azure Synapse Analytics
- Explore data using native visuals in Spark notebooks.
- Explore and visualize data using the Azure Synapse SQL results pane.

### Visualize Data using Power BI
- [Create and import a custom report theme.](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes)
- Create R or Python visuals in Power BI.
  - [Create Power BI visuals with Python](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-python-visuals)
  - [Create Power BI visuals using R](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-r-visuals)
- Connect to and query datasets using the XMLA endpoint.
- Design and configure Power BI reports for accessibility.
- Enable personalized visuals in a report.
  - [Let users personalize visuals in a report](https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-personalize-visuals?tabs=powerbi-desktop)
  - [Personalize visuals in a report](https://learn.microsoft.com/en-us/power-bi/consumer/end-user-personalize-visuals)
- [Configure automatic page refresh.](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-automatic-page-refresh)
- Create and distribute paginated reports in Power BI Report Builder.
  - [What are paginated reports in Power BI?](https://learn.microsoft.com/en-us/power-bi/paginated-reports/paginated-reports-report-builder-power-bi) 

## Extra Knowledge
* [Introduction to datamarts](https://learn.microsoft.com/en-us/power-bi/transform-model/datamarts/datamarts-overview)

## Microsoft Learn
* [Designing and Implementing Enterprise-Scale Analytics Solutions Using Microsoft Azure and Microsoft Power BI](https://learn.microsoft.com/en-us/training/courses/dp-500t00)
