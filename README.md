# Text Editor 
Module 19 Challenge: Just Another Text Editor

The J.A.T.E app is a Progressive Web App that allows you to write and save snippets of code with color-coded syntax. It capitalizes on webpack and workbox libraries to increase application performance by bundling files to serve up to the browser. It uses a registered service worker and manifest file to allow the app offline capabilites, and to cache assets as the creator deems appropriate while providing data about the project. The app is installable via button, which serves up the app in a headless broswer, complete with an icon in the dock. Data is cached using the indexeddb library in a databse named "jate," as well as saving data to localstorage. The codemirror library provides the text with easy-on-the-eyes color coding. Runtime scripts in the package.json file use a dev dependency called "concurrently," which allows the creator to build the app and start the server conveniently from the root in one command but "cd-ing" into the client and server folders.

link to repository: https://github.com/mconanan/Text-Editor
link to heroku deploy: https://text-editor-jate-maddy.herokuapp.com/