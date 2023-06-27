## Prerequisites

- You have Identity Provisioning Service (IPS) within your Identity Authentication Service (IAS) Tenant
- You have configured Identity Authentication Service Tenant (See: [IAS Configuration](https://github.com/Sereg20/Task_Center/blob/master/IAS_config/README.md))
- You have configured SAP S4HANA On-Premise system (See: [SAP S4HANA On-Premise Configuration](https://github.com/Sereg20/Task_Center/blob/master/S4HANA_config/README.md))

## Details

With these steps you will provision SAP Task Center Business Users data from IAS to SAP S4HANA On-Premise system using IPS job
The Provisioning process will update SAP Task Center Business Users in SAP S4HANA On-Premise system with Global User ID field which is automatically generated in IAS and required for Principal Propagation mechanism

Start with [1 Source System Config](https://github.com/Sereg20/Task_Center/blob/master/IPS_config/1%20Source%20System%20Config/README.md)