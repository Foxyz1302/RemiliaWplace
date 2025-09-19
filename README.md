# Takorin (Namako-daibakuhatsu) Overlay Project

A collaborative repository for fans and "milkers" of the `takorin` (Namako-daibakuhatsu) community. This project provides the JSON configuration files needed to run an advanced overlay for Wplace (or similar place events) using a userscript manager.

To get started, you will need to install a browser extension and then import our custom configuration.

---

## Prerequisites

Before you begin, you need a userscript manager extension for your browser.

*   **Tampermonkey** ([Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/) | [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)) - *Recommended*
*   **Violentmonkey** ([Chrome](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) | [Firefox](https://addons.mozilla.org/firefox/addon/violentmonkey/) | [Edge](https://microsoftedge.microsoft.com/addons/detail/violentmonkey/eeagobfjdenkkddmbclomhiblgggliao))

Install one of the above extensions before proceeding.

---

## Installation Guide (Step-by-Step)

### Step 1: Install the Base Overlay Script
You first need the "Wplace Overlay Pro" userscript, which our JSON files configure.

1.  Open your userscript manager (Tampermonkey/Violentmonkey) from your browser's toolbar.
2.  Go to the **Dashboard**.
3.  Navigate to the **Utilities** tab.
4.  In the "Install from URL" section, paste the following URL:
    ```
    https://github.com/q2p1to435/place-overlay-pro/raw/main/overlay.pro.user.js
    ```
5.  Click the **Install** button and confirm any prompts to install the script.
6.  Refresh the Wplace page. You should now see an "Overlay PRO" button or menu on the page.

### Step 2: Import the Configuration Files
Now, import the two JSON files from this repository to apply the `takorin` template.

1.  **Download the JSON files:**
    *   Click on the JSON file in this repository (e.g., `overlay.json`).
    *   Click the "Raw" button to view the raw file content.
    *   Right-click anywhere on the page and select **Save As...** to save the file to your computer. Repeat this for the second JSON file (e.g., `priorities.json`).

2.  **Open the Overlay PRO menu:** On the Wplace page, click the "Overlay PRO" button.

3.  **Import `overlay.json`:**
    *   In the Overlay PRO menu, find the **Templates** section.
    *   Click on **Import**.
    *   Click **Choose File** and select the `overlay.json` file you downloaded.
    *   The overlay image should now appear on the canvas, showing you exactly where to place pixels.

4.  **Import `priorities.json` (Optional but Recommended):**
    *   In the Overlay PRO menu, find the **Priorities** section.
    *   Click on the import/export icon (usually 📤📥).
    *   Click **Import** and then **Choose File**.
    *   Select the `priorities.json` file you downloaded. This will load a pre-defined order of which parts of the artwork are most important to defend or build first.

---

## Contributing & Help

We absolutely need all the help we can get! This is a community effort.

Let's work together to make our mark!

---

## Disclaimer

This project is a fan-made tool and is not officially affiliated with Wplace, or the original creators of the "Overlay PRO" userscript. Use it at your own discretion.
