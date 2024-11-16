# Search for the Service Usage API

## Step 1: Check Permissions

Ensure that your account has the necessary permissions to use the Service Usage API. 

1. Navigate to the [**IAM & Admin**](https://console.cloud.google.com/iam-admin?tab=0) section of the console.
2. Look for your account in the list of members and confirm it has the `roles/serviceusage.viewer` or `roles/owner` role.

<walkthrough-spotlight-pointer sandboxuid="4">
Highlight the email filter option here to quickly locate your account.
</walkthrough-spotlight-pointer>

**Annotation:** The "IAM & Admin" section is found in the left-hand menu. Use the email filter option to simplify searching for your account.

---

## Step 2: Navigate to the API Library

Use the search bar in the API Library to find the **Service Usage API**. Type **Service Usage API** and press Enter.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar here.
</walkthrough-spotlight-pointer>

**Annotation:** Look for the search bar located at the top of the API Library page. It is labeled with a magnifying glass icon.

---

## Step 3: Enable the API

On the **Service Usage API** page, click the **Enable** button to activate it for your project.

<walkthrough-spotlight-pointer cssSelector="button[aria-label='Enable']">
Highlight the Enable button here.
</walkthrough-spotlight-pointer>

**Annotation:** The Enable button is typically blue and located near the top of the API page. Make sure it changes to "Disable" after activation.

---

## Step 4: Verify the API is Enabled

Return to the **Enabled APIs & Services** page to confirm the Service Usage API is active. Look for **serviceusage.googleapis.com** in the list.

<walkthrough-spotlight-pointer cssSelector="nav-item-link[title='Enabled APIs & Services']">
Highlight the Enabled APIs link here.
</walkthrough-spotlight-pointer>

**Annotation:** Navigate to the "Enabled APIs & Services" page from the left-hand menu. Use the search bar on this page if the list is long.

---

## Step 5: Check Service Usage API Status

1. Go to **Enabled APIs & Services**.
2. In the list of APIs, confirm the **Service Usage API** is active.
3. If it is not enabled, return to Step 3 to enable it.

<walkthrough-spotlight-pointer cssSelector="nav-item-link[title='Enabled APIs & Services']">
Highlight the Enabled APIs link here.
</walkthrough-spotlight-pointer>

**Annotation:** Double-check the API list for "Service Usage API" to ensure it shows as enabled. You can use the search bar on this page if needed.

---

## Step 6: Check GA4 BigQuery Export

1. Navigate to **BigQuery** in the left-hand menu.
2. Look for your GA4 export dataset in the list of datasets.
3. Ensure the dataset contains tables for events, such as `events_YYYYMMDD`.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate BigQuery here.
</walkthrough-spotlight-pointer>

**Annotation:** In BigQuery, datasets are listed under your project name. Use the dropdown to expand and view individual datasets.

---

## Step 7: Check if Billing is Enabled

1. Go to **Billing** in the left-hand menu.
2. Ensure a billing account is linked to your project.
3. Check the status of the billing account. It should be active.

<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate Billing here.
</walkthrough-spotlight-pointer>

**Annotation:** The Billing section shows all linked billing accounts. Confirm the status is "active" and linked to the correct project.

---

