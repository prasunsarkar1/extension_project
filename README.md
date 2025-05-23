#  Webpage to PDF Converter Extension

A browser extension that enables users to convert webpage text into downloadable PDF files seamlessly.

#  Features

- 🖱️ One-click conversion of webpage text to PDF.
- 🧹 Clean and readable PDF output.
- 🌐 Compatible with major browsers (Chrome, Firefox, etc.).

#  Project Structure
extension_project/
├── extension/ # Browser extension source code
├── pdfs/ # Directory for storing generated PDFs
├── views/ # HTML templates or frontend views
├── server.js # Node.js backend server
├── package.json # Project metadata and dependencies
├── package-lock.json # Exact versions of installed dependencies
└── .gitignore # Files and directories ignored by Git

## 🛠️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prasunsarkar1/extension_project.git

2.Navigate to the project directory:


cd extension_project

3.Install dependencies:

npm install

4.Start the backend server:

node server.js

5.Load the extension in your browser:

-Open your browser's extension management page.
-Enable "Developer mode".
-Click on "Load unpacked" and select the extension/ directory.

#🧪 Testing

-Navigate to any webpage.
-Click on the extension icon in your browser toolbar.
-The extension should process the page and provide a downloadable PDF.

