# Configure GCP for GA4Dataform Installer

This tutorial guides you through configuring Google Cloud Platform (GCP) to prepare for running the GA4Dataform installer. Before proceeding, ensure you meet the prerequisites and understand the steps involved.

## Step 1: Introduction

Before starting the configuration, verify that you have:

- Proper access to manage APIs and services in your Google Cloud project.
- A Google Cloud project set up with an active billing account.
- GA4 linked to BigQuery for exporting data.

In the following steps, we will guide you through:

1. Checking access permissions.
2. Enabling the required APIs.
3. Verifying your BigQuery and billing setup.

Once the prerequisites are confirmed, proceed to Step 2 to begin the configuration process.

---

## Step 2: Check Access Permissions

Ensure that you have the necessary permissions to manage APIs and services within your Google Cloud project.

1. Open the [**IAM & Admin**](https://console.cloud.google.com/iam-admin)
2.
<walkthrough-spotlight-pointer cssSelector="[_nghost-ng-c2843449187][_ngcontent-ng-c2295059878]">
Use the email filter to quickly find your account.
</walkthrough-spotlight-pointer>
4. Verify that your account has one of the following roles:
   - `roles/owner`
   - `roles/editor`
   - `roles/serviceusage.admin`

**Annotation:** If your account does not have the necessary permissions, contact your GCP administrator to request access.

---

## Step 3: Navigate to the API Library

Use the search bar in the API Library to find and access the **Service Usage API**.

1. From the [**GCP Homepage**](https://console.cloud.google.com/), click on **API & Services** in the left-hand menu.
2. Click on **Library**.
3. Type **Service Usage API** into the search bar and press Enter.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar here.
</walkthrough-spotlight-pointer>

**Annotation:** The API Library search bar is located at the top of the page and labeled with a magnifying glass icon.

---

## Step 4: Enable the Service Usage API

Activate the **Service Usage API** to allow the GA4Dataform installer to function.

1. On the **Service Usage API** page, click the **Enable** button.
2. Wait for the confirmation that the API has been enabled.

<walkthrough-spotlight-pointer cssSelector="button[aria-label='Enable']">
Highlight the Enable button here.
</walkthrough-spotlight-pointer>

**Annotation:** The Enable button is typically blue and located near the top of the page. Ensure it changes to "Disable" after activation.

---

## Step 5: Verify API Status

Ensure that the **Service Usage API** is enabled in your project.

1. Return to the **Enabled APIs & Services** page.
2. Look for **serviceusage.googleapis.com** in the list of enabled APIs.

<walkthrough-spotlight-pointer cssSelector="nav-item-link[title='Enabled APIs & Services']">
Highlight the Enabled APIs link here.
</walkthrough-spotlight-pointer>

**Annotation:** Use the search bar on the **Enabled APIs & Services** page if the list is extensive.

---

## Step 6: Verify GA4 BigQuery Export Setup

Confirm that your project includes the necessary GA4 BigQuery export dataset.

1. Navigate to **BigQuery** from the left-hand menu.
2. Check for a dataset named after your GA4 property.
3. Ensure the dataset contains tables, such as `events_YYYYMMDD`.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate BigQuery here.
</walkthrough-spotlight-pointer>

**Annotation:** If the dataset or tables are missing, ensure that GA4 BigQuery linking is properly configured in the GA4 interface.

---

## Step 7: Check Billing Status

Ensure your project has an active billing account.

1. Navigate to **Billing** in the left-hand menu.
2. Verify that a billing account is linked to your project.
3. Confirm the status of the billing account is "active."

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate Billing here.
</walkthrough-spotlight-pointer>

**Annotation:** Without an active billing account, BigQuery exports and other paid GCP services will not function.

---
