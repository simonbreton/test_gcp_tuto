# GCP Walkthrough: Enable the Compute Engine API

Welcome to this interactive walkthrough! In this tutorial, you will enable the **Compute Engine API** for your GCP project using the Cloud Shell.

---

## Step 1: Open Cloud Shell

1. Click the **Activate Cloud Shell** button at the top right corner of your Google Cloud Console.
2. Wait for the Cloud Shell to initialize.
3. Once initialized, your terminal should appear at the bottom of your screen.

---

## Step 2: Set Your Project ID

1. First, confirm your GCP project ID:
    ```bash
    gcloud config list project
    ```
    This will show your active project. If no project is set, you'll need to set one.

2. If you need to set a project, replace `[PROJECT_ID]` with your project ID and run:
    ```bash
    gcloud config set project [PROJECT_ID]
    ```

3. Verify that your project is set correctly:
    ```bash
    gcloud config get-value project
    ```

---

## Step 3: Enable the Compute Engine API

1. Run the following command to enable the Compute Engine API:
    ```bash
    gcloud services enable compute.googleapis.com
    ```

2. After running the command, you'll see confirmation that the API has been enabled.

---

## Step 4: Verify the API is Enabled

1. Check if the Compute Engine API is enabled by running:
    ```bash
    gcloud services list --enabled | grep compute.googleapis.com
    ```

2. If the Compute Engine API appears in the output, congratulations! You've successfully enabled the API.

---

## Next Steps

Now that the Compute Engine API is enabled, you can explore creating virtual machines and other resources using Compute Engine. 

For more tutorials, visit the [GCP Documentation](https://cloud.google.com/docs).
