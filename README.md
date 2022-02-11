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
 - using git for: git init, git add ., git commit -m "text"
 - heroku create:
 `Creating app... done, ⬢ peaceful-ravine-71664

https://peaceful-ravine-71664.herokuapp.com/ | https://git.heroku.com/peaceful-ravine-71664.git`

 - It's going to create a new app with a domain name
 - And when you go back to dashboard on heroku you can see the app created
 - Click on that and go to 'Deploy' tab
 - We grab the comand as our reposotory: `heroku git:remote -a peaceful-ravine-71664`
 - Copy and Paste that on terminal
 - Now that it's added as repository: `set git remote heroku to https://git.heroku.com/peaceful-ravine-71664.git`
 - Now we have to push to heroku master: `git push heroku master`
 - Now you can go to heroku url or just do `heroku open` it open to new browser


