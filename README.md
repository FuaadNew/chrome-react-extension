Chrome Extension with React + Parcel
A boilerplate project for building Chrome extensions using React and Parcel. This extension renders a React app directly into the content of a website when the user clicks the extension icon. It's designed to be a starting point for Chrome extension development using modern JavaScript tools.


Features
Render a React app in the visited website when a user clicks the extension icon.
Popup to trigger rendering of the React app.
Communication between popup and content script using chrome.tabs.sendMessage.
Injects the React component dynamically into the webpage DOM.
Prerequisites
Node.js and npm installed on your system.
Basic knowledge of JavaScript, React, and Chrome Extensions.
Getting Started
1. Clone the repository
Clone this repository to get started:


git clone https://github.com/your-username/chrome-extension-react-parcel.git
cd chrome-extension-react-parcel

2. Install dependencies
Run the following command to install the required dependencies:


npm install


3. Set up the project
Ensure the structure is as described, particularly the manifest.json and popup.html files.

4. Build the project
Use Parcel to build and watch your project files. Run the following command to build the extension:


npm run build
You can also watch for changes with:


npm run watch

5. Load the extension in Chrome
Open Chrome and navigate to chrome://extensions.
Enable Developer Mode.
Click Load Unpacked and select the project folder (the root directory where manifest.json is located).
Your extension should now be loaded.

7. Test the extension
Click on the extension icon in the Chrome toolbar. The React app should render in the current webpage when you press the "Render App" button in the popup.

8. Debugging
You can open the developer tools in Chrome and inspect the extension's injected content.


Project Scripts
npm run build: Compiles the React app and builds the content script.
npm run watch: Watches for changes and rebuilds the content script automatically.

Acknowledgments
React for building UI components.
Parcel for bundling the project.
Chrome Extensions Documentation for guidance.
