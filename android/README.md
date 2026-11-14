# AI Earning Agent Android APK

This is a standalone Android WebView wrapper for the AI Earning Agent website.
It lives only in the AI-Earning-Agent repository and does not share code or files with DigiHisaab.

## Build
GitHub Actions builds a debug APK when files in this folder change or when the workflow is run manually.
The APK is uploaded as the workflow artifact named **AI-Earning-Agent-APK**.

The app loads the hosted AI Earning Agent website, so an internet connection is required. Gemini API usage and its quota remain subject to the user's Google AI Studio account and current limits. The API key is stored by the website in the app's WebView browser storage if the user opts in; do not use that option on shared devices.

The debug APK is suitable for personal testing and installation. It is not a Play Store release build and is not signed with a private release key.
