# Lab 03 - Setting up workspace tenant

Objectives

- In this Lab, you will check the tenant settings in the Fabric and
  explore the settings

## Task 1 - Configuring the Tenant settings

1.  Login into [Microsoft Fabric](https://app.fabric.microsoft.com/)
    with your credentials and you will be navigated to the home page.

2.  Go to the admin portal by selecting Setting icon (Gear icon) on the
    top right corner of the home page.

<img src="./media/image1.png" style="width:3.625in;height:7.48333in" />

3.  Select **Tenant settings**.

<img src="./media/image2.png" style="width:2.92525in;height:3.817in"
alt="A screenshot of a computer Description automatically generated" />

4.  Check the below options accordingly:

- **Disabled for the entire organization**: Scroll down to **Export and
  sharing settings** and search for **Certification** option. This
  feature disabled will allow no one in your organization can use this
  feature.

<img src="./media/image3.png" style="width:6.15833in;height:2.93333in"
alt="Screenshot of disabled all state tenant setting." />

- **Enabled for the entire organization**: Under **Export and sharing
  settings** and search for **Download reports** option. This option
  enabled will allow everyone in your organization to use this feature.

<img src="./media/image4.png" style="width:6.03386in;height:3.65032in"
alt="A screenshot of a computer Description automatically generated" />

- **Enabled for the entire organization except for certain groups**:
  Under **Export and sharing settings** and search for **Export reports
  as XML documents** option. Everyone in your organization can use this
  feature except for users who belong to the specified groups.

<img src="./media/image5.png" style="width:6.28333in;height:4.20833in"
alt="Screenshot of enabled all except state tenant setting." />

- **Enabled for a subset of the organization**: We can enable specific
  security groups in your organization are allowed to use this feature.

<img src="./media/image6.png" style="width:6.28333in;height:4.19167in"
alt="Screenshot of enabled subset state tenant setting." />

- **Enabled for specific groups except for certain groups**: Here,
  members of the specified security groups are allowed to use this
  feature, unless they also belong to an excluded group. This approach
  ensures that certain users don't have access to the feature even if
  they're in the allowed group. The most restrictive setting for a user
  applies.

<img src="./media/image7.png" style="width:6.26667in;height:4.8in"
alt="Screenshot of enabled except state tenant setting." />

**Summary :**

You have successfully checked the tenant settings in the Fabric that are
required to execute the further labs
