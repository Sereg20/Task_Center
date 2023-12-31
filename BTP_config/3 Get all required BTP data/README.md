## Details

With this step you will grab all required data from BTP Subaccount including Destination trust file and SAP Task Center service key info  
You will need this data in the following Configuration steps:

- [Configure SAP SuccessFactors system](https://github.com/Sereg20/Task_Center/blob/master/SF_config/README.md)
- [Configure SAP S4HANA Cloud system](https://github.com/Sereg20/Task_Center/blob/master/S4HANA_Cloud_config/README.md)


### Step 1: Download Destination Trust

1. Access your BTP Subaccount
2. Go to Destinations Tab
3. Download Trust to your local computer via clicking on **Download Trust** button

![Download trust](./Images/1.3.1.png "Download trust")


As a result, the Trust has been successfully saved on your local computer


### Step 2: Save SAP Task Center service key info 

1. Access your BTP Subaccount
2. Go to Instances and Subscriptions Tab
3. Access the SAP Task Center service instance
4. On the service instance, choose service key

![Service Key](./Images/2.4.1.png "Service Key")

5. Copy the following parameters:

- inbox_rest_url
- uaa –> clientid
- uaa –> client secret
- uaa –> url

As a result, all required SAP Task Center Service key parameters have been copied

Proceed to the next part: [IAS Configuration steps](https://github.com/Sereg20/Task_Center/blob/master/IAS_config/README.md)
