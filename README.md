## Introduction

**Departmental Analytics (with EBS Integration)** is a fully certified, supported and secure VMware software defined data centre (SDDC) that is hosted on Oracle Cloud Infrastructure (OCI), and uses VMware software and licenses.

The base configuration includes three Oracle Cloud Infrastructure compute bare metal hosts (BM.DenseIO2.52). This configuration can be altered to allow a single Oracle Cloud VMware Solution SDDC to use 64 bare metal hosts. The base configuration also includes an Oracle Cloud Infrastructure virtual cloud network (VCN), 156 OPCUs, 2304 GB of physical memory, and 153 TB of NVMe-based raw storage.

The solution includes VMware software such as vSphere, vSAN, NSX-T, and vCenter Server. The vSAN converged storage technology ensures the availability of data and replicates data across all the bare metal hosts in the SDDC.

These hands-on lab guides provide step-by-step directions to set up and use your VMware Solution SDDC in the Oracle Cloud Infrastructure.

## Goals for this workshop
1. Provision the infrastructure artifacts required for departmental analytics.
2. Configure and run integration.
3. Do sample analytics on OAC.


## Prerequisites


## Labs
[Lab 100 - Installing ODI via OCI Marketplace](ProvisionOCVS.md).

- Provision ODI from the marketplace 
- Connection to ODI via VNC Viewer

[Lab 200 - Provision and Configure AWD Target](ExportWorkload.md).

- Provision your ADW instance.
- Connect ADW as your target database in ODI 

[Lab 300 - Configure EBS Source and run integration](MigratingOnPremtoOCI.md). 

- Connection to EBS tables and views.
- Configure mapping between source and target.
- Run integration to move data from EBS to ADW

[Lab 400 - Run Analytics](ExtendApptoOCI.md).

- Provision Analytics instance and connect to ADW
- Run analytics
- [Optional] - Upload DVA files

**You are all set. Let us begin!**