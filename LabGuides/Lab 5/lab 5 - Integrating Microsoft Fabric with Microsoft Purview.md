**Lab 05 - Integrating Microsoft Fabric with Microsoft Purview**

**Objectives**

- In this Lab, you redeem an Azure pass and create resource group in the
  Azure portal.

- You create Microsoft Purview account and register Fabric tenant and
  check the authentication

- You create and run the scan

## Task 1 - Redeem Azure Pass

1.  Open a browser and navigate to: **!!www.microsoftazurepass.com!!**

> It is recommended you close all browsers and open a new In-Private
> Browser session. Other log-ins can persist and cause errors during the
> activation step.

2.  Click the **Start** button to get started.

> <img src="./media/image1.jpeg" style="width:6.26806in;height:2.15139in"
> alt="screenshot showing redemption start button" />

3.  Enter your **Office 365 tenant credentials** and select **Sign In**.

> <img src="./media/image2.jpeg" style="width:5.9963in;height:3.89899in"
> alt="screenshot showing login form" />

4.  Click **Confirm Microsoft Account** if the correct email address is
    listed.

> <img src="./media/image3.jpeg" style="width:6.26806in;height:2.73472in"
> alt="screenshot showing confirm microsoft account button" />

5.  Enter your **Azure Pass** promo code in the Enter Promo code box and
    click “**Claim Promo Code**”.

> <img src="./media/image4.jpeg" style="width:6.26806in;height:2.97222in"
> alt="screenshot showing promo code input field" />

6.  It may take up to 5 minutes to process the redemption.

> <img src="./media/image5.jpeg" style="width:6.26806in;height:2.57569in"
> alt="screenshot showing loading screen while promo code is being redeemed" />

#### Activate your subscription

1.  When the redemption process is completed, it will redirect to the
    sign up page.

2.  Enter your account information and click **Next**.

> <img src="./media/image6.jpeg" style="width:5.52525in;height:4.87454in"
> alt="screenshot showing sign up form to enter account information" />

3.  Click the agreement check box and click the Sign-up button.

4.  It may take a few minutes to process the request.

> <img src="./media/image7.jpg" style="width:5.26262in;height:4.34782in"
> alt="screenshot showing agreement checkbox and sign up button" />

5.  Your **Azure subscription** is ready

<img src="./media/image8.jpeg" style="width:5.50505in;height:3.01479in"
alt="screenshot showing azure portal home page" />

## Task 2 – Create a resource Group

1.  Login to Azure portal. Enter resource group in the search area.

<img src="./media/image9.png" style="width:5.42547in;height:2.53355in"
alt="A screenshot of a computer Description automatically generated" />

2.  Select **Create.**

<img src="./media/image10.png" style="width:6.5in;height:1.96667in" />

3.  Enter the below details:

    1.  Subscription - Your Azure subscription

    2.  Resource Group – FabricPurview

    3.  Select **Review + Create**

<img src="./media/image11.png" style="width:6.49167in;height:4.55in" />

4.  On the next page click on Create.

<img src="./media/image12.png" style="width:6.18889in;height:9in" />

4.  The resource group is created.

## Task 3 - Create an active Microsoft Purview account

1.  Open a browser, sign-in to the [Azure
    portal](https://portal.azure.com/) with your Office 365 credentials.

2.  Search for **Microsoft Purview** in the Azure portal.

<img src="./media/image13.png"
style="width:5.46714in;height:3.22528in" />

3.  Select **Create** to create a new Microsoft Purview account.

<img src="./media/image14.png"
style="width:3.80833in;height:1.93333in" />

4.  Enter the below details

    1.  Subscription – Your azure subscription

    2.  Resource Group – **FabricPurview**

    3.  Microsoft Purview account name – **FabricPurviewInt**

    4.  Select **Review+Create**

<img src="./media/image15.png" style="width:6.5in;height:4.9in" />

5.  Click on the **Create** button once the validation passed screen
    appeared.

<img src="./media/image16.png" style="width:6.5in;height:9in" />

6.  Once we click on the **Create** button the Deployment will start,
    and it will take around 5 minutes for the deployment to complete.

<img src="./media/image17.png" style="width:6.5in;height:3.25in" />

<img src="./media/image18.png" style="width:6.5in;height:4.94236in"
alt="A screenshot of a computer Description automatically generated" />

5.  A Purview account is created. Select **Go to resource**

<img src="./media/image19.png" style="width:6.5in;height:3.14028in"
alt="A screenshot of a computer Description automatically generated" />

6.  Scroll down and select **Open Microsoft Purview Governance
    Portal(new)**

<img src="./media/image20.png" style="width:6.5in;height:3.25in"
alt="A screenshot of a computer Description automatically generated" />

7.  On the **Welcome to the new Microsoft Purview portal!** Window,
    agree to the terms of data flow and click on **Get started.**

<img src="./media/image21.png" style="width:5.93105in;height:6.75452in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image22.png" style="width:6.5in;height:2.56458in"
alt="A screenshot of a computer Description automatically generated" />

## Task 4 - Register Fabric tenant

While you are in the Microsoft Purview Home page, we will register the
Fabric tenant

1.  Select **Data Map**

<img src="./media/image22.png" style="width:6.5in;height:2.56458in"
alt="A screenshot of a computer Description automatically generated" />

2.  On the left side navigation pane, select **Data sources** and then
    select **Register**.

<img src="./media/image23.png" style="width:6.5in;height:3.25in"
alt="A screenshot of a computer Description automatically generated" />

3.  Select **Fabric** as your data source and click on **Continue**.

<img src="./media/image24.png" style="width:6.37778in;height:9in" />

4.  Give your Fabric instance a friendly name

    1.  Data source name – **Fabric Datasource**.

    2.  Select **Register.** The data source is added successfully.

<img src="./media/image25.png" style="width:6.5in;height:6.85764in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image26.png" style="width:6.5in;height:3.64375in"
alt="A screenshot of a computer Description automatically generated" />

## Task 5 - Authenticate to Fabric tenant

1.  Switch back to  [Azure portal](https://portal.azure.com/), search
    for **Microsoft Entra ID**.

<img src="./media/image27.png" style="width:5.50881in;height:2.52522in"
alt="A screenshot of a computer Description automatically generated" />

2.  Expand **Manage** and select **Groups**.

<img src="./media/image28.png" style="width:2.77524in;height:3.76699in"
alt="A screenshot of a computer Description automatically generated" />

3.  Select **New group.**

4.  Enter the below details and click on **Create.**

    1.  Group Type: **Security**

    2.  Group Name – Security11

<img src="./media/image29.png" style="width:6.5in;height:4.38472in" />

<img src="./media/image30.png" style="width:6.5in;height:8.80833in" />

<img src="./media/image31.png" style="width:3.5952in;height:0.70862in"
alt="A close-up of a group Description automatically generated" />

5.  Refresh the page to the newly created group in the list.

<img src="./media/image32.png" style="width:6.5in;height:3.56736in" />

6.  On the Newly created Group page navigate to **members** on the left
    hand pane**,** click on add members, Select You Microsoft Purview
    Managed Identity ( the Microsoft Purview Account name that you
    created). Click on **Select.**

<img src="./media/image33.png" style="width:6.5in;height:3.79931in" />

<img src="./media/image34.png" style="width:6.5in;height:3.25in" />

7.  You will get a success notification that 1 member selected.

<img src="./media/image35.png" style="width:3.62647in;height:0.92746in"
alt="A white background with black text Description automatically generated" />

<img src="./media/image36.png" style="width:6.5in;height:4.45694in"
alt="A screenshot of a computer Description automatically generated" />

## Task 6 - Associate the security group with Fabric tenant

1.  Switch back to Fabric Portal.

2.  Select the **Settings** icon and Select **Admin Portal.**

<img src="./media/image37.png"
style="width:3.92971in;height:7.85942in" />

3.  Select the **Tenant settings** page. Search for  **Admin API
    settings** and then search for **Allow service principals to use
    read-only admin APIs**. Enable the toggle if it is not enabled. Add
    your Security group and select **Apply**

<img src="./media/image38.png"
style="width:6.49167in;height:4.59167in" />

<img src="./media/image39.png" style="width:4.59561in;height:1.04209in"
alt="A white rectangular frame with black text Description automatically generated" />

4.  Perform the above steps

    1.  **Enhance admin APIs responses with detailed metadata** 

    2.  **Enhance admin APIs responses with DAX and mashup
        expressions** 

<img src="./media/image40.png" style="width:6.35055in;height:5.06711in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image41.png" style="width:6.40055in;height:5.22545in"
alt="A screenshot of a computer Description automatically generated" />

no<img src="./media/image42.png" style="width:6.5in;height:5.34722in"
alt="A screenshot of a computer Description automatically generated" />

## Task 7 - Create scan

1.  Switch back to Microsoft Purview Portal.

2.  Navigate to **Data sources** \> Select your **Fabric Datasource.**
    Select **View Details**

<img src="./media/image43.png" style="width:6.5in;height:4.08611in" />

3.  Click on **New Scan.**

<img src="./media/image44.png" style="width:5.65882in;height:1.87516in"
alt="A screenshot of a computer Description automatically generated" />

4.  Enter/Update the below details and click on **Continue.**

    1.  Name – **FabricPurviewScan**

    2.  Credential – **Microsoft Purview MSI (System)**

    3.  Select **Test Connection**

<img src="./media/image45.png"
style="width:6.49167in;height:6.81667in" />

**Note** - If **Test Connection** failed, select **View Report** to see
the detailed status and troubleshoot the problem.

1.  **Access** - Failed status means the user authentication failed.
    Scans using managed identity will always pass because no user
    authentication required. If using service principal or delegated
    authentication, make sure your Key Vault credential was correctly
    set up and that Microsoft Purview has access to the key vault.

2.  **Assets (+ lineage)** - Failed status means the Microsoft Purview -
    Fabric authorization has failed. Make sure the Microsoft Purview
    managed identity is added to the security group associated in Fabric
    admin portal.

3.  **Detailed metadata (Enhanced)** - Failed status means the Fabric
    admin portal is disabled for the following setting - **Enhance admin
    APIs responses with detailed metadata**

<!-- -->

5.  On the **Scope your scan** page select **Yes(Purview)** to and click
    on **Continue.**

<img src="./media/image46.png" style="width:6.5in;height:3.96667in" />

6.  On the **Set a scan trigger**, Select **Once** and click on
    **Continue.**

<img src="./media/image47.png" style="width:6.5in;height:2.7in" />

7.  On **Review new scan**, select **Save and run** to launch your scan.

<img src="./media/image48.png" style="width:6.5in;height:4.84167in" />

8.  The scan is created.

<img src="./media/image49.png" style="width:6.5in;height:3.25in"
alt="A screenshot of a computer Description automatically generated" />

9.  The scan takes a while to complete.

<img src="./media/image50.png" style="width:6.5in;height:4.35417in"
alt="A screenshot of a computer Description automatically generated" />

Summary

You create a Microsoft Purview account and register Fabric tenant and
check the authentication. You create and run the scan that you created.
