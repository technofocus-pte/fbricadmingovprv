# Lab 08 - Managing Power BI visuals admin settings

Objectives

- In this Lab, you will enable the power BI visuals under tenant
  settings

- Adding the visual from the file

- Scheduling a Refresh and analyzing the logs in the PBO Desktop

## Task 1 – Configuring Power BI visuals tenant settings

1.  Open a browser. Login to [Fabric
    Portal](https://app.fabric.microsoft.com/) with your credentials.

2.  Select **Settings \> Admin Portal**<img src="./media/image1.png"
    style="width:3.74199in;height:7.54232in" />

3.  Select **Tenant Settings.**

<img src="./media/image2.png" style="width:2.85025in;height:3.892in"
alt="A screenshot of a computer Description automatically generated" />

4.  Enter Power BI visuals in the search area. These settings allow you
    to control the following actions for Power BI visuals in your
    organization

<img src="./media/image3.png" style="width:6.49167in;height:3.15in" />

5.  Select Enable for the visuals available.

    1.  **Allow visuals created using the Power BI SDK** – Toggle this
        button to enable uploading *.pbiviz* and AppSource visuals

> <img src="./media/image4.png"
> style="width:6.49221in;height:4.36635in" />

2.  **Allow access to certified Power BI visuals only –** When this
    setting is enabled , only certified Power BI visuals render in your
    organization's reports and dashboards.

3.  **Allow downloads from custom visuals onto your storage device –**
    When this setting is enabled, users can download data from a custom
    visual into a file on their storage device.

4.  **Obtain Microsoft Entra access token –** When this setting is
    enabled, AppSource Custom Visuals can obtain Microsoft Entra ID
    (formerly known as Azure Active Directory) access tokens with
    restricted audiences for signed-in users, utilizing
    the Authentication API. 

5.  **Allow custom visuals to store data on the user's local machine –**
    When this setting is enabled, allows visuals to store data on the
    browser's local storage which helps improve performance

## Task 2 - Add a visual from a file

1.  On the **Admin portal**, select **Organizational visuals**

<img src="./media/image5.png" style="width:2.80858in;height:4.48372in"
alt="A screenshot of a phone Description automatically generated" />

2.  Select **Add visual \> From a file.**

<img src="./media/image6.png" style="width:5.26712in;height:2.50855in"
alt="A screenshot of a computer Description automatically generated" />

3.  Enter the below fields

    1.  **Choose a .pbiviz file** - Select a visual file to upload.

    2.  **Name your visual** - Give a short title to the visual, so that
        report authors can easily understand what it does.

    3.  **Icon** - Upload an icon file to be displayed in the
        visualization pane.

    4.  **Description** - Provide a short description of the visual to
        give more context for the user.

    5.  **Access** - Select whether users in your organization can
        access this visual. This setting is enabled by default.

    6.  Select **Add**.

<img src="./media/image7.png" style="width:5.675in;height:5.78333in" />

<img src="./media/image8.png" style="width:5.66667in;height:7.05in" />

4.  After it's uploaded, the visual displays in the organizational
    visuals list.

<img src="./media/image9.png" style="width:6.20054in;height:2.56689in"
alt="A screenshot of a computer Description automatically generated" />

**Task 3 - Add a visual from AppSource**

Use this method to add a new Power BI visual from AppSource. AppSource
Power BI visuals are automatically updated. Users in your organization
will always have the latest version of the visual.

1.  Select **Add visual \> From AppSource.**

<img src="./media/image10.png" style="width:3.78366in;height:2.44188in"
alt="A screenshot of a computer Description automatically generated" />

2.  In the **Power BI visuals** window, find the AppSource visual you
    want to add, and select **Add**. After it's uploaded, the visual
    displays in the organizational visuals list.

<img src="./media/image11.png"
style="width:6.49167in;height:3.84167in" />

<img src="./media/image12.png" style="width:6.24221in;height:3.45863in"
alt="A screenshot of a computer Description automatically generated" />

## Task 3 – Scheduling a Refresh

1.  Select **Refresh summary** on the left navigation pane.

2.  Select the capacity you want to review from the **choose a
    capacity** dropdown menu.

<img src="./media/image13.png" style="width:6.5in;height:3.80208in"
alt="A screenshot of a computer Description automatically generated" />

3.  Use the **refresh** button to refresh the table's results.

<img src="./media/image14.png" style="width:6.5in;height:4.26597in"
alt="A screenshot of a computer Description automatically generated" />

4.  Click on the **Export** button to export a .csv file.

<img src="./media/image15.png" style="width:6.5in;height:3.13819in"
alt="A screenshot of a computer Description automatically generated" />

## Task 4 – Audit Logs in PBI Desktop

1.  To access the audit logs, in Fabric select **Audit logs,** and then
    select Go to **Microsoft 365 Admin Center**.

<img src="./media/image16.png" style="width:6.5in;height:1.98125in"
alt="A screenshot of a computer error Description automatically generated" />

2.  Click on **Start recording user and admin activity,** on the next
    window click **Yes** complete organizational setup.

<img src="./media/image17.png" style="width:6.5in;height:3.26528in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image18.png" style="width:6.25253in;height:2.02165in"
alt="A screenshot of a computer Description automatically generated" />

3.  You can search the audit logs using the filters in the list that is
    visible. When you combine filters, the search results show only
    items that match all of the filter criteria.

<img src="./media/image19.png" style="width:6.5in;height:2.90208in"
alt="A screenshot of a computer Description automatically generated" />

**Summary**

- You enabled the power BI visuals under tenant settings and added the
  visual from the file. Additionally, schedule a Refresh and analyze the
  logs in the PBO Desktop
