## Introduction

**Departmental Analytics (with EBS Integration)**

Lines of business typically don't have timely or efficient access to data and information. Analysts gather the data manually, work with it on an individual basis, and then share copies of files through email or file servers. With Oracle Autonomous Data Warehouse and Oracle Analytics Cloud, you can load and optimize data from Oracle E-Business Suite and other sources into a centralized data warehouse location for analysis so departments can gain actionable insights.

This solution uses Oracle Data Integrator to load and optimize data from multiple sources into a centralized Oracle Autonomous Data Warehouse and then uses Oracle Analytics Cloud to analyze the data to provide actionable insights.

These lab guides provide directions on how one can set up departmental EBS analytics in Oracle Analytics Cloud. We will show how to connect EBS to OAC through a data mart (ADW), and show a sample analysis with some refined data.

## Goals for this workshop
1. Provision the infrastructure artifacts required for departmental analytics.
2. Configure EBS and run integration.
3. Analyze data using OAC.


## Prerequisites


## Labs
[Lab 100 - Instantiate pattern](InstantiatePattern.md).

- Go to OCI console and run terraform to instantiate the required resources 
- Connection to ODI via VNC Viewer

[Lab 200 - Configure EBS Source and run integration](ConfigureIntegration.md). 

- Connect to Source EBS tables and views. (note down that target is already preconfigured by the pattern instantiation)
- Configure mapping between source and target.
- Run integration to move data from EBS to ADW

[Lab 300 - Run Analytics - Create Dashboards](runanalytics.md).

- Provision Analytics instance and connect to ADW
- Run analytics
- [Optional] - Uploading DVA files

**You are all set. Let us begin!**