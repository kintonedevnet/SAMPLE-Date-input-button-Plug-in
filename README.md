# [Sample plug-in: Date Input Button Plug-in]
## Purpose of the Sample Plug-in
This sample plug-in is available for educational purposes.  
Use this plug-in to understand how Kintone plug-ins work, and how they are structured.
A non-packaged version written with a single JavaScript file can be found here https://developer.kintone.io/hc/en-us/articles/115005327527

## What the plug-in does
This plug-in displays a button on a Blank space field within a Kintone App.
When a user clicks the button, today's date is inserted into a Date field within the Kintone App.
The plug-in settings page allows the user to choose which Blank space field and which Date field will be used.

## Plug-in directory structure
This sample plug-in is created with the following directory structure.


src/  
├── html/  
│        └──── config.html  
├── css/  
│        ├──── 51-modern-default.css  
│        └──── config.css  
├── js/  
│        ├──── config.js  
│        └──── desktop.js  
├── image/  
│        └──── icon.png  
└── manifest.json  

## How to use
To simply test out the plug-in on your Kintone domain, follow these steps:

1. Download the plug-in zip file  
Reference: https://github.com/kintone/SAMPLE-Date-input-button-Plug-in/releases
2. Install the plug-in into your domain  
Reference: https://get.kintone.help/hc/en-us/articles/115001519707-Installing-Viewing-Plug-ins
3. Add the plug-in to a specific Kintone App  
Reference: https://get.kintone.help/hc/en-us/articles/115001511188-Adding-Plug-ins-to-an-App
4. Make sure that a Date field and a Blank Space field (with an Element ID set up) are placed in the form of your Kintone App. Access the plug-in settings, and set up the neccessary settings. Save the settings, and update the App.
5. Click the + button on the Record List page to start adding a new record. A button should appear in the Blank Space field.

## How to modify
1. Type the following into the terminal to clone the repo:
```
git clone https://github.com/kintone/SAMPLE-Date-input-button-Plug-in.git
```
2. Make changes to files under /src
3. Repackage the plug-in by:  
 i. Zipping the manifest.json file, css directory, html directory, image directory and js directory into one zip file.  
 ii. Drag and dropping the file into the [kintone plug-in packer](https://kintone.github.io/plugin-packer/).
