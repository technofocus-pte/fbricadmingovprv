# Lab 07 - Installing the Microsoft Fabric capacity metrics app

**Objectives**

- In this Lab, you install the Microsoft Fabric Capacity Metrics App and
  run the app

## Task 1 – Installing the Microsoft Fabric Capacity Metrics App

To install the *Microsoft Fabric Capacity Metrics* app for the first
time, follow these steps:

1.  Go to AppSource \> Microsoft Fabric Capacity Metrics and
    select **Get it now**.

> https://appsource.microsoft.com/en-us/product/power-bi/pbi_pcmm.microsoftpremiumfabricpreviewreport?exp=ubp8

<img src="./media/image1.png" style="width:6.5in;height:3.40833in" />

2.  You will be navigated to Power BI apps to complete the process.

<img src="./media/image2.png" style="width:5.49167in;height:1.875in" />

3.  Provide your Admin email address to proceed and select **Submit**.

<img src="./media/image3.png"
style="width:5.06667in;height:4.56667in" />

4.  The app takes you to Microsoft Fabric to complete the process.
    Select **Install** to continue.

5.  In the *Install this Power BI app* window, select **Install**.

<img src="./media/image4.png" style="width:6.5in;height:2.75833in"
alt="A screenshot of a computer Description automatically generated" />

6.  Wait a few seconds for the app to install.

<img src="./media/image5.png"
style="width:4.99167in;height:1.28333in" />

7.  The App is successfully installed. Click on the App to run it for
    the first time.

<img src="./media/image6.png"
style="width:6.48333in;height:1.10833in" />

## Task 2 - Run the Metrics App

To complete the installation, configure the Microsoft Fabric Capacity
Metrics app by running it for the first time.

1.  In Microsoft Fabric, select **Apps**.

2.  Select the **Microsoft Fabric Capacity Metrics** app.

3.  When you see the message – “*You have to connect to your own data to
    view this report”*, select **Connect**.

<img src="./media/image7.png" style="width:6.5in;height:2.65in" />

4.  In the **Connect to Microsoft Fabric Capacity Metrics** first
    window, fill in the below details:

<table>
<colgroup>
<col style="width: 17%" />
<col style="width: 18%" />
<col style="width: 16%" />
<col style="width: 47%" />
</colgroup>
<thead>
<tr class="header">
<th>Field</th>
<th>Required</th>
<th>Value</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Capacity ID</td>
<td>Yes</td>
<td>An ID of a capacity you're an admin of</td>
<td>You can find the capacity ID in the URL of the capacity management
page. In Microsoft Fabric, go
to <strong>Settings</strong> &gt; <strong>Governance and
insights</strong> &gt; <strong>Admin
portal</strong> &gt; <strong>Capacity settings</strong>, then select a
capacity. The capacity ID is shown in the URL
after <em>/capacities/</em>. For
example, 9B77CC50-E537-40E4-99B9-2B356347E584 is the capacity ID in this
URL: https://app.powerbi.com/admin-portal/capacities/9B77CC50-E537-40E4-99B9-2B356347E584.<br />
After installation, the app will let you see all the capacities you can
access.</td>
</tr>
<tr class="even">
<td><strong>UTC_offset</strong></td>
<td>Yes</td>
<td>Numerical values ranging from 14 to -12.<br />
To signify a Half hour timezone, use .5. For example, for Iran's
standard time enter 3.5.</td>
<td>Enter your organization's standard time in Coordinated Universal
Time (UTC).</td>
</tr>
<tr class="odd">
<td><strong>Timepoint</strong></td>
<td>Automatically populated</td>
<td></td>
<td>This field is automatically populated and is used for internal
purposes. The value in this field will be overwritten when you use the
app.</td>
</tr>
<tr class="even">
<td><strong>Timepoint2</strong></td>
<td>Automatically populated</td>
<td></td>
<td>This field is automatically populated and is used for internal
purposes. The value in this field will be overwritten when you use the
app.</td>
</tr>
<tr class="odd">
<td><strong>Advanced</strong></td>
<td>Optional</td>
<td><strong>On</strong> or <strong>Off</strong></td>
<td>The app automatically refreshed your data at midnight. This option
can be disabled by expanding the <em>advanced</em> option and
selecting <strong>Off</strong>.</td>
</tr>
</tbody>
</table>

5.  You can find the capacity ID in the URL of the capacity management
    page. In Microsoft Fabric, go to **Settings** \> **Governance and
    insights** \> **Admin portal** \> **Capacity settings**, then select
    a capacity. The capacity ID is shown in the URL
    after */capacities/*. For
    example, 9B77CC50-E537-40E4-99B9-2B356347E584 is the capacity ID

<img src="./media/image8.png" style="width:6.5in;height:3.22569in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image9.png" style="width:6.5in;height:5.35417in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image10.png" style="width:6.5in;height:6.69444in"
alt="A screenshot of a computer Description automatically generated" />

<img src="./media/image11.png" style="width:6.15in;height:5.08333in" />

6.  Select **Next**.

7.  In the **Connect to Microsoft Fabric Capacity Metrics** second
    window, complete the following fields:

    1.  **Authentication method** - Select your authentication method.
        The default authentication method is *OAuth2*.

    2.  **Privacy level setting for this data source** -
        Select *Organizational* to enable app access to all the data
        sources in your organization.

8.  Select **Sign in and continue**. Enter your tenant details to
    complete the sign in process.

> <img src="./media/image12.png" style="width:6.5in;height:6.66667in"
> alt="A screenshot of a computer Description automatically generated" />

9.  After you configure the app, it can take a few minutes for the app
    to get your data. If you run the app and it's not displaying any
    data, refresh the app. This behavior happens only when you open the
    app for the first time.

<img src="./media/image13.png" style="width:6.5in;height:3.34028in" />

Summary

- You have installed the Microsoft Fabric Capacity Metrics App and run
  the app
