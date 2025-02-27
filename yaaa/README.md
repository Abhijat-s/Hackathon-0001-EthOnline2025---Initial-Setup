# Using the Datascraping-To-Earn tool in a Chrome Extension.

This code demonstrates how to use the Datascraping in a Chrome Extension.

Components:
1. Dillion to store the private data in a decentralized format

## Overview

The extension provides a chat interface for the Gemini API. To learn more about the API head over to [https://ai.google.dev/](https://ai.google.dev/).

## Running this extension

1. Clone this repository.
2. Download the Gemini API client by running:
   ```sh
   npm install
   ```
3. [Retrieve an API key](https://ai.google.dev/gemini-api/docs/api-key) and update [functional-samples/ai.gemini-in-the-cloud/sidepanel/index.js](functional-samples/ai.gemini-in-the-cloud/sidepanel/index.js) (only for testing).
4. Compile the JS bundle for the sidepanel implementation by running:
   ```sh
   npm run build
   ```
5. Load this directory in Chrome as an [unpacked extension](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked).
6. Click the extension icon.
7. Interact with the prompt API in the sidebar.


Installed NodeJS
Browerify (browserify -r markdown -o bundle.js)
Include bundle.js in the main html file
