# Identity Provisioning Service (IPS) Configuration

## Overview

The Identity Provisioning service (IPS) automates identity lifecycle processes. It helps you provision identities and their authorizations to various cloud and On-Premise business applications

## Prerequisites

- You have Identity Provisioning Service (IPS) within your Identity Authentication Service (IAS) Tenant
- You have created an RFC mapping to the SAP S4HANA On-Premise on SAP Cloud Connector for Provisioning to the On-Premise system
- You have configured Identity Authentication Service Tenant (See: [IAS Configuration](https://github.com/Sereg20/Task_Center/blob/master/IAS_config/README.md))
- You have configured SAP S4HANA On-Premise system (See: [SAP S4HANA On-Premise Configuration](https://github.com/Sereg20/Task_Center/blob/master/S4HANA_config/README.md))

## Details

With these steps you will provision SAP Task Center Business Users data from IAS to SAP S4HANA On-Premise system using IPS job
The Provisioning process will update SAP Task Center Business Users in SAP S4HANA On-Premise system with Global User ID field which is automatically generated in IAS and required for Principal Propagation mechanism

*Note:* This scenario is applicable for S4HANA On-Premise part only

Start with [1 Create RFC Destination in SAP BTP](https://github.com/Sereg20/Task_Center/blob/master/IPS_config/1%20Create%20RFC%20destination/README.md)