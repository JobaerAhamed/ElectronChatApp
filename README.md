# ElectronChatApp
A full functioning Chat app up till Slack

My main chat app.
This is live on http://chatapp.enscaled.sg/

Its a complete communication tool like slack/ even better.

This repo is for the desktop executable version of the main web application
This is being done by Electron Framework. It alows us to create cross platform desktop app using javascript.

How to run this:  
  # you must have
      1. NodeJS
      2. Electron (https://www.npmjs.com/package/electron) [npm i electron]
      3. Eelectron-packager (https://www.npmjs.com/package/electron-packager) [npm install electron-packager -g]

>clone this repo to your machine.

>hit [npm install]

>to run locally hit [electron main.js]. You should see a desktop window popup rinning the app.

>to compile into a desktop exe hit [electron-packager .]. You should get a folder created and there you can find the exe file with the app name

>to create a distributable windows installer any tool like Advance installer (https://www.advancedinstaller.com/download.html).

>the end product is the appname.msi file that is the Desktop Programme of the web aplication
