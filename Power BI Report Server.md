# Power BI Report Server

## Table of contents

* [Power BI Report Server :star2:](#Power-BI-Report-Server)
* [Installation and Configuration](#Installation-and-Configuration)
* [Settings and Troubleshooting](#Settings-and-Troubleshooting)
* [ReportServer Database](#ReportServer-Database)
* [Security](#Security)
* [Web Portal](#Web-Portal)
* [Tools](#Tools)
* [KPI](#KPI)
* [APIs](#APIs)

-----
## Power BI Report Server
* [Power BI Report Server](https://powerbi.microsoft.com/en-us/report-server/) - Power BI Report Server is the on-premises solution for reporting, with the flexibility to move to the cloud. 
* [Power BI RS vs Power BI Service](https://docs.microsoft.com/en-us/power-bi/report-server/compare-report-server-service)
* [What's new in Power BI Report Server](https://docs.microsoft.com/en-us/power-bi/report-server/whats-new)

-----
## Installation and Configuration
* [Install Power BI Report Server](https://docs.microsoft.com/en-us/power-bi/report-server/install-report-server)
* [Install Power BI Report Server (RADACAD)](https://radacad.com/power-bi-report-server-power-bi-in-on-premises-world)

-----
# Settings and Troubleshooting
* [Error Logs and Troubleshooting](https://docs.microsoft.com/en-us/power-bi/report-server/scheduled-refresh-troubleshoot#tools-for-troubleshooting)
* [Querying ReportServer Database](https://www.mssqltips.com/sqlservertip/6001/ssrs-reportserver-database-overview-and-queries/)
* [Connect to Power BI Report Server with SSMS](https://sqlkover.com/connecting-to-power-bi-report-server-with-ssms/)
* The service is not available (Error)
   * [The Report Server Web Portal Urls And Web Service Urls Don’t Match](http://www.midnightdba.com/Jen/2018/03/report-server-web-portal-urls-web-service-urls-dont-match/)
   * [The Service is Not Available (LuCELL)](http://lucell.co.uk/the-service-is-not-available)
   * Go to Report Server Configuration Manager, Backup the Encryption Keys and change the Service Account to "Network Service"

-----
### ReportServer Database
* [Dynamic row level security with Analysis services tabular model](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-row-level-security-onprem-ssas-tabular)
* [SSRS ReportServer Database Overview and Queries](https://www.colabug.com/5946636.html)

-----
## Security
* [Configure Windows Authentication on the Report Server](https://docs.microsoft.com/en-us/sql/reporting-services/security/configure-windows-authentication-on-the-report-server)
* [Configure Kerberos to use Power BI reports (Video)](https://docs.microsoft.com/en-us/power-bi/report-server/configure-kerberos-powerbi-reports)
* [Configure Custom or Forms Authentication on the Report Server](https://docs.microsoft.com/en-us/sql/reporting-services/security/configure-custom-or-forms-authentication-on-the-report-server)

-----
## Web Portal
* [Branding the web portal](https://docs.microsoft.com/en-us/sql/reporting-services/branding-the-web-portal)
* [Manage content in the web portal](https://docs.microsoft.com/en-us/power-bi/report-server/getting-around)
* [Work with shared datasets](https://docs.microsoft.com/en-us/sql/reporting-services/work-with-shared-datasets-web-portal)
    * [Connect to OData feeds in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/desktop-connect-odata)
* [Create shared data sources and datasets for your reports (Video)](https://channel9.msdn.com/Events/DataDriven/SQLServer2016/shared-data-sources-and-datasets-for-your-reports)

-----
## Tools
### Power BI Desktop for PBI RS
* [Power BI Desktop optimized for Power BI Report Server](https://docs.microsoft.com/en-us/power-bi/report-server/install-powerbi-desktop)
* [Filter a report using query string parameters in the URL](https://docs.microsoft.com/en-us/power-bi/service-url-filters)
* [Embed a Power BI Report Server report](https://docs.microsoft.com/en-us/power-bi/report-server/quickstart-embed)

### Power BI Report Builder (Paginated reports)
   * [Working with paginated reports](https://docs.microsoft.com/en-us/sql/reporting-services/working-with-paginated-reports-web-portal)
* [Working with subscriptions](https://docs.microsoft.com/en-us/sql/reporting-services/working-with-subscriptions-web-portal)
* [Working with snapshots](https://docs.microsoft.com/en-us/sql/reporting-services/working-with-snapshots-web-portal)

### Report Designer - SQL Server Data Tools (SSDT) for VS
   * [Download and install SQL Server Data Tools (SSDT) for Visual Studio](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt)
       
### Mobile Report Publisher
* [Create mobile reports with SQL Server Mobile Report Publisher](https://docs.microsoft.com/en-us/sql/reporting-services/mobile-reports/create-mobile-reports-with-sql-server-mobile-report-publisher)
* [Mobile Report Publisher – Dashboards Everywhere](https://www.red-gate.com/simple-talk/sql/bi/mobile-report-publisher-dashboards-everywhere/) - Robert Cain
    
-----    
## KPI
* [Working with KPIs in Reporting Services](https://docs.microsoft.com/en-us/sql/reporting-services/working-with-kpis-in-reporting-services)
    
-----
## APIs
* [Power BI Report using Shared Dataset](http://dataap.org/blog/2018/03/20/power-bi-report-using-shared-dataset-detailed-step-by-step/)
   * [Power BI Report Server REST API](https://app.swaggerhub.com/apis/microsoft-rs/pbirs/)

