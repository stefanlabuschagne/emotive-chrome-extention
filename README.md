# Emotive Hello World

A minimal Chrome Manifest V3 extension with a PyScript-powered popup that displays **Hello World**.

## Load it in Chrome

1. Open `chrome://extensions`.
2. Turn on **Developer mode**.
3. Choose **Load unpacked** and select this repository directory.
4. Click the extension icon to open the popup.

The popup uses PyScript 2024.1.1 from its official CDN. Chrome extension policies generally prohibit remotely hosted executable code in published extensions, so for Chrome Web Store distribution, bundle a compatible PyScript runtime locally and update the script reference in `popup.html`.
