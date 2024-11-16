# Configure GCP for GA4Dataform Installer

This tutorial guides you through configuring Google Cloud Platform (GCP) to prepare for running the GA4Dataform installer. Before proceeding, ensure you meet the prerequisites and understand the steps involved.

## Step 1: Introduction

Before starting the configuration, verify that you have:

- Proper access to manage APIs and services in your Google Cloud project.
- A Google Cloud project set up with an active billing account.
- GA4 linked to BigQuery for exporting data.

In the following steps, we will guide you through:

1. Checking access permissions.
2. Enabling the Service Usage API
3. Check your Ga4 BigQuery Export
4. Verify your billing status

Once the prerequisites are confirmed, proceed to Step 2 to begin the configuration process.

<walkthrough-tutorial-duration duration="30"></walkthrough-tutorial-duration>

<walkthrough-footnote>FOOTNOTE_TEXT</walkthrough-footnote>

<walkthrough-enable-apis apis="serviceusage"></walkthrough-enable-apis>

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

## Step 3: Check Billing Status

Ensure your project has an active billing account.

1. Navigate to [**Billing**](https://console.cloud.google.com/billing)  

If you can access your overview page it mean that the billing account is enable. you can move ot the next step.

If you see a dialogue saying ""This project has no billing account" you need to activate your billing account. 

[**Configure your billing account**](https://cloud.google.com/billing/docs/how-to/modify-project)

**Annotation:** Without an active billing account, BigQuery exports and other paid GCP services will not function.

---

## Step 4: Enable the Service Usage API

Activate the **Service Usage API** to allow the GA4Dataform installer to function.

1. opem the [**Service Usage API**](https://console.cloud.google.com/marketplace/product/google/serviceusage.googleapis.com)
2. check if the API is **Enable** button.
2. Wait for the confirmation that the API has been enabled.

<walkthrough-spotlight-pointer cssSelector=".mp-banner-status-message.ng-star-inserted">
Highlight the status message element here.
</walkthrough-spotlight-pointer>

**Annotation:** The Enable button is typically blue and located near the top of the page. Ensure it changes to "Disable" after activation.

---

## Step 5: Verify GA4 BigQuery Export Setup

Confirm that your project includes the necessary GA4 BigQuery export dataset.

1. Navigate to **BigQuery** from the left-hand menu.
2. Check for a dataset named after your GA4 property.
3. Ensure the dataset contains tables, such as `events_YYYYMMDD`.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate BigQuery here.
</walkthrough-spotlight-pointer>

**Annotation:** If the dataset or tables are missing, ensure that GA4 BigQuery linking is properly configured in the GA4 interface.

## Step 6: Conclusion

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>


---


