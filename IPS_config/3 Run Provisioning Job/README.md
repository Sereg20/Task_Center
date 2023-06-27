## Details

With this step you will run Provisioning job to provision Users data from IAS to SAP S4HANA On-Premise system


### Step 1: Run Provisioning job

1. Access your IAS tenant admin console
2. On the Home Page, go to Source Systems tile

![Source Systems tile](./Images/1.2.1.png "Source Systems tile")

3. Choose the Source system you created 
4. Go to Jobs tab

![Jobs tab](./Images/1.4.1.png "Jobs tab")

5. Run Read Job

![Jobs tab](./Images/1.5.1.png "Jobs tab")

As a result, the Provisioning job has been successfully triggered


### Step 2: Check the job's result

1. Go to Job Logs

![Job logs](./Images/2.1.1.png "Job logs")

2. Check the job status (should be **Finished Successfully**). In case the status is **Finished with Error** check the job logs and fix an issue 

![Result](./Images/2.2.1.png "Result")
