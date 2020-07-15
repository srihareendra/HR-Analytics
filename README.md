## Introduction

**Departmental Analytics (with EBS Integration)**

Lines of business typically don't have timely or efficient access to data and information. Analysts gather the data manually, work with it on an individual basis, and then share copies of files through email or file servers. With Oracle Autonomous Data Warehouse and Oracle Analytics Cloud, you can load and optimize data from Oracle E-Business Suite and other sources into a centralized data warehouse location for analysis so departments can gain actionable insights.

This solution uses Oracle Data Integrator to load and optimize data from multiple sources into a centralized Oracle Autonomous Data Warehouse and then uses Oracle Analytics Cloud to analyze the data to provide actionable insights.

These hands-on lab guides provide step-by-step directions to set up departmental EBS analytics in Oracle Analytics Cloud.

## Goals for this workshop
1. Provision the infrastructure artifacts required for departmental analytics.
2. Configure and run integration.
3. Analyze data using OAC.


## Prerequisites


## Labs
[Lab 100 - Installing ODI via OCI Marketplace](ProvisionOCVS.md).

- Provision ODI from the marketplace 
- Connection to ODI via VNC Viewer

[Lab 200 - Provision and Configure AWD Target](ExportWorkload.md).

- Provision your ADW instance.
- Connect ADW as your target database in ODI 

[Lab 300 - Configure EBS Source and run integration](MigratingOnPremtoOCI.md). 

- Connect to EBS tables and views.
- Configure mapping between source and target.
- Run integration to move data from EBS to ADW

[Lab 400 - Run Analytics - Create Dashboards](ExtendApptoOCI.md).

- Provision Analytics instance and connect to ADW
- Run analytics
- [Optional] - Uploading DVA files

**You are all set. Let us begin!**