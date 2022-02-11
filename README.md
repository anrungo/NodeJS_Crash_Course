NPM - Node Package Manager

 - Install 3rd party packages (frameworks, libraries, tools,etc)
 - Packages get stored in the "node_modules" folder
 - All dependencies are listed in a "package.json" file
 - NPM scripts can be created to run certain tasks such as run a server

 `npm init`                     Generates a package.json file
 `npm install express`          Installs a package locally
 `npm install -g nodemon`       Installs a oackage globally

NODE Modules

 - Node Core Modules (path, fs, http, etc)
 - 3rd party modules/packages installed via NPM
 - Custom modules (files)

 `const path = require('path');`
 `const myFile = require('./myFile);`

`"scripts": {
    "start": "node index",
    "dev": "nodemon index"
  },`

 `npm run dev`

 For deployment:
 - sign up for heroku.com
 - you will need heroku cli: https://devcenter.heroku.com/articles/heroku-cli to download and install
 - once installed, on the terminal or command prompt: heroku --version
 - login through terminal: heroku login
 