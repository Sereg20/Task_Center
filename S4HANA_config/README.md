## Prerequisites

- You have access to SAP S4HANA On-Premise system
- You have service user in the SAP S4HANA On-Premise system
- The service user is assigned to SAP_ALL profile
- You have a business user in the SAP S4HANA On-Premise system you are going to use in SAP Task Center to process incoming tasks
- You have configured SAP Cloud Connector which is required for secure tunnel between Cloud and On-Premise system [SAP Cloud Connector Configuration](https://github.com/Sereg20/Task_Center/blob/master/SCC_config/README.md)

## Details

With these steps you will configure SAP S4HANA On-Premise system to allow tasks propagating to SAP Task Center

Configuration flow requires
- setting up trust configuration to enable principal propagation
- setting up SAP Task Center Integration
- managing user roles

Start with [1 Trust Config](https://)