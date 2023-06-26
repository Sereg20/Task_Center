## Prerequisites

- You have BTP Enterprise Account
- You have Identity Authentication Service (IAS) Tenant
- You have admin rights in the IAS Tenant

## Details

With this step you will set up trust configuration between BTP Subaccount and IAS tenant

### Step 1: Create a new app in IAS

1. Access you IAS admin console via link: https://\<your IAS tenant\>.accounts.ondemand.com/admin

2. Create a new app

- Go to the Applications tile

<!-- image -->

- Click **Create** button
- In Create Application popup Fill in the Display Name field and click **Save** button

<!-- image -->

As a result the newly created app is displayed in Charged Applications list

<!-- image -->

### Step 2: Download SAML Metadata from tenant settings

1. Go to Tenant Settings tab

<!-- image -->

2. Go to SAML 2.0 Configuration under Single Sign-On tab

3. Download SAML Metadata to your local computer via clicking **Download Metadata File** button

<!-- image -->

As a result the SAML Metadata of your tenant is downloaded to your local computer

### Step 3: Create a new Trust Configuration in BTP

1. Access your BTP Subaccount

<!-- image -->

2. Create a new Trust Configuration using the SAML Metadata from the previous step

- Go to Trust Configuration tab
- Click **New Trust Configuration** button

<!-- image -->

- Upload the SAML Metadata file from your local computer via clicking **Upload** button in New Trust Configuration popup
- Fill in the Name field with an appropriate name and click **Save** button

<!-- image -->

As a result new Trust Configuration is established and displayed in Trust Configuration list in your BTP Subaccount

### Step 4: Download SAML Metadata from BTP Subaccount

1. Go to Trust Configuration tab
2. Download SAML Metadata to your local computer via clicking **SAML Metadata** button

<!-- image -->

As a result the SAML Metadata of your BTP Subaccount is downloaded to your local computer

### Step 5: Establish Trust Configuration in IAS tenant

1. Access you IAS admin console
2. Establish Trust Configuration via uploading the BTP Subaccount SAML Metadata file to the newly created app in IAS

- Go to Applications tab and choose the newly created app

<!-- image -->

- Go to SAML 2.0 Configuration under Trust tab

<!-- image -->

- Upload the BTP Subaccount SAML Metadata file from your local computer to the IAS tenant via clicking **Browse...** button
- Click **Save** button

<!-- image -->

As a result the trust configuration between your BTP subaccount and IAS tenant is established. In IAS admin console you can see your app in Bundled Applications list