# OBS Overlay Setup Guide ⚙️

This guide provides step-by-step instructions for setting up the Shabad Type and Translate Machine (STTM) overlay in OBS Studio.

---

## Step 1: Configure the Initial OBS Overlay

1.  Download the `OBS Overlay` folder from the Google Drive shared by `dodrasevaapp@gmail.com`.
2.  Open **OBS Studio** on your computer.
3.  In the **Sources** box, click the **+** button and select **Browser**.
4.  Name the new source (e.g., `Overlay`) and click **OK**.
5.  In the properties window:
    * For the **URL** field, enter the local file path to the overlay's HTML file.
        * *Example:* `file:///C:/path/to/OBS Overlay/index.html`
    * Set the **Width** to `1280`.
    * Set the **Height** to `720`.
6.  Click **OK**.
7.  Position and resize the overlay in the OBS preview window as needed.

---

## Step 2: Configure the STTM Laptop 💻

1.  Ensure the **STTM** application is running and the laptop is connected to the **same Wi-Fi network** as the OBS laptop.
2.  Disable the Windows Firewall.
3.  In the STTM Bani Overlay settings, make the following changes:
    * Change the them to a **A New Day**.
    * Set the STTM view to display on the **top only**.
4.  Navigate to the Bani Overlay page within STTM and **copy the local network URL** it provides.
5.  On the OBS laptop, open a web browser and paste the copied URL to confirm the overlay displays correctly.

---

## Step 3: Integrate STTM with OBS 🔗

1.  On the **OBS laptop**, return to OBS Studio.
2.  In the **Sources** box, click the **+** button and choose **Browser**.
3.  Name the new source (e.g., `STTM`) and click **OK**.
4.  In the properties window:
    * In the **URL** field, paste the STTM network URL you copied earlier.
    * Set the **Width** to `1280`.
    * Set the **Height** to `720`.
5.  Click **OK**.
6.  Resize and position the new STTM browser source in the OBS preview as needed. You are now ready to stream! 🎉
