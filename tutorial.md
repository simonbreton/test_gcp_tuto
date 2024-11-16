# Search for the Service Usage API

## Step 1: Navigate to the API Library

Use the search bar in the API Library to find the **Service Usage API**. Type **Service Usage API** and press Enter.

```html
<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar here.
</walkthrough-spotlight-pointer>
```

---

## Step 2: Enable the API

On the **Service Usage API** page, click the **Enable** button to activate it for your project.

```html
<walkthrough-spotlight-pointer cssSelector="button[aria-label='Enable']">
Highlight the Enable button here.
</walkthrough-spotlight-pointer>
```

---

## Step 3: Verify the API is Enabled

Return to the **Enabled APIs & Services** page to confirm the Service Usage API is active. Look for **serviceusage.googleapis.com** in the list.

```html
<walkthrough-spotlight-pointer cssSelector="nav-item-link[title='Enabled APIs & Services']">
Highlight the Enabled APIs link here.
</walkthrough-spotlight-pointer>
```

---

## Step 4: Check Permissions

Ensure that your account has the necessary permissions to use the Service Usage API. 

1. Navigate to the **IAM & Admin** section of the console.
2. Look for your account in the list of members and confirm it has the `roles/serviceusage.viewer` or `roles/owner` role.

```html
<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to help locate IAM & Admin here.
</walkthrough-spotlight-pointer>
```

---

## Step 5: Check Service Usage API Status

1. Go to **Enabled APIs & Services**.
2. In the list of APIs, confirm the **Service Usage API** is active.
3. If it is not enabled, return to Step 2 to enable it.

```html
<walkthrough-spotlight-pointer cssSelector="nav-item-link[title='Enabled APIs & Services']">
Highlight the Enabled APIs link here.
</walkthrough-spotlight-pointer>
```

---

## Step 6: Check GA4 BigQuery Export

1. Navigate to **BigQuery** in the left-hand menu.
2. Look for your GA4 export dataset in the list of datasets.
3. Ensure the dataset contains tables for events, such as `events_YYYYMMDD`.

```html
<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate BigQuery here.
</walkthrough-spotlight-pointer>
```

---

## Step 7: Check if Billing is Enabled

1. Go to **Billing** in the left-hand menu.
2. Ensure a billing account is linked to your project.
3. Check the status of the billing account. It should be active.

```html
<walkthrough-spotlight-pointer cssSelector="#pcc-search-container">
Highlight the search bar to locate Billing here.
</walkthrough-spotlight-pointer>
```

---


