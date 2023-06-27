## Details

With this step you will create a System Administrator which is required for Users Provisioning via Identity Provisioning Service (IPS)


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

As a result, a new System Administrator is created


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

As a result, System Administrator secrets are created and stored for future use
