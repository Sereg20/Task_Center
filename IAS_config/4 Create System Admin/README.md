## Details

With this step you will create a System Administrator which is required for 
- Configuring Users Provisioning in Identity Provisioning Service (IPS)
- Create Destinations in SAP BTP


### Step 1: Create a System Administrator

1. Go to Administrators tab

![Administrators tab](./Images/1.1.1.png "Administrators tab")

2. Create a System Administrator

- Click **Add** button
- Select **System** option

![System Administrator](./Images/1.2.1.png "System Administrator")

- Fill in Name with value **TASK_CENTER**
- Switch on **Read Users** Authorization

![System Administrator](./Images/1.2.2.png "System Administrator")

- Click **Save** button

As a result, a new System Administrator has been created


### Step 2: Add Secrets to the Administrator

1. Select the newly created System Administrator
2. Add new secrets
- Go to Secrets
- Click **Add** button

![Add user to user group](./Images/2.2.1.png "Add user to user group")

- (Optional) Specify meaningful description
- Click **Save** button

![Create Secrets](./Images/2.2.2.png "Create Secrets")

- Copy Client ID and Client Secret values from the popup. You'll need these values later


As a result, copied System Administrator secrets can be used during next Configuration steps


Proceed to the next part [SAP Cloud Connector Configuration steps](https://github.com/Sereg20/Task_Center/blob/master/SCC_config/README.md) which is a prerequisite for SAP S4HANA On-Premise system Configuration 
