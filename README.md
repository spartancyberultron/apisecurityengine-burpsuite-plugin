# How to Install and Configure our Burp Suite Extension

Follow these steps to install the Burp Suite extension from a JAR file and configure it to start analyzing traffic:

## 1. Download the Extension JAR File

Obtain the JAR file for the Burp Suite extension from this repository code.

## 2. Open Burp Suite

Launch Burp Suite on your machine. If you don't have Burp Suite installed, download and install it from the official website.

## 3. Install the Extension

- In Burp Suite, go to the **"User Options"** or **"Extensions"** tab, depending on your version.
- Look for a section related to extensions or plugins. Click on the **"Add"** or **"Load"** button.
- Choose the **"Java"** extension type and browse to the location where you downloaded the `plugin.jar` file. Select the file and confirm the installation.

## 4. Configure the Extension

After installing the extension, locate it in the list of installed extensions. Click on the extension to open its configuration settings.

Set the following variables in the extension's settings:
- **API_KEY**: Your unique API key for the analysis service. Replace with your actual key.
- **HOST**: The hostname or IP address of the server where traffic is being captured from. Use `localhost` if the traffic is local.
- **PORT**: The port number on the host where traffic is being captured. Enter the specific port number (e.g., `5002`).

## 5. Start Traffic Analysis

With the extension installed and configured, start capturing traffic in Burp Suite. The extension will send captured traffic to the analysis service using the provided API key and settings.

Ensure that the extension is correctly configured with the appropriate API key, host, and port to ensure accurate traffic analysis.
