# Commands
### Install node for mac:

`brew install node`


### Check npm and node versions:

`node --version`

`npm --version`

### Install Firebase CLI Tools

`npm install -g firebase-tools`

###  Init Firebase in general

`firebase login`

### Clone the github repo

`git clone git@github.com:sidpagariya/test-app.git`

### CD into the repo

`cd test-app`

### Init Firebase in this project

`firebase init`

Then follow instructions to setup the rest of the options:

```
$ firebase init

     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

  /Users/sid/workspace/test-app

? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, t
hen Enter to confirm your choices. Firestore: Deploy rules and create indexes for Firestore, Functions
: Configure and deploy Cloud Functions, Hosting: Configure and deploy Firebase Hosting sites

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add,
but for now we'll just set up a default project.

? Please select an option: Use an existing project
? Select a default Firebase project for this directory: test-app-3fd61 (test-app)
i  Using project test-app-3fd61 (test-app)

=== Firestore Setup

Error: It looks like you haven't used Cloud Firestore in this project before. Go to https://console.firebase.google.com/project/test-app-3fd61/database to create your Cloud Firestore database.

Having trouble? Try firebase [command] --help
[13:43:41] sid@sidp ~/w/test-app (master|+2…) [1]
$ firebase init

     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

  /Users/sid/workspace/test-app

? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, t
hen Enter to confirm your choices. Firestore: Deploy rules and create indexes for Firestore, Functions
: Configure and deploy Cloud Functions, Hosting: Configure and deploy Firebase Hosting sites

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add,
but for now we'll just set up a default project.

? Please select an option: Use an existing project
? Select a default Firebase project for this directory: test-app-3fd61 (test-app)
i  Using project test-app-3fd61 (test-app)

=== Firestore Setup

Firestore Security Rules allow you to define how and when to allow
requests. You can keep these rules in your project directory
and publish them with firebase deploy.

? What file should be used for Firestore Rules? firestore.rules

Firestore indexes allow you to perform complex queries while
maintaining performance that scales with the size of the result
set. You can keep index definitions in your project directory
and publish them with firebase deploy.

? What file should be used for Firestore indexes? firestore.indexes.json

=== Functions Setup

A functions directory will be created in your project with a Node.js
package pre-configured. Functions can be deployed with firebase deploy.

? What language would you like to use to write Cloud Functions? JavaScript
? Do you want to use ESLint to catch probable bugs and enforce style? Yes
✔  Wrote functions/package.json
✔  Wrote functions/.eslintrc.json
✔  Wrote functions/index.js
✔  Wrote functions/.gitignore
? Do you want to install dependencies with npm now? Yes

> protobufjs@6.9.0 postinstall /Users/sid/workspace/test-app/functions/node_modules/protobufjs
> node scripts/postinstall

npm notice created a lockfile as package-lock.json. You should commit this file.
added 362 packages from 267 contributors and audited 362 packages in 29.961s

32 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities


=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? public
? Configure as a single-page app (rewrite all urls to /index.html)? No
✔  Wrote public/404.html
? File public/index.html already exists. Overwrite? No
i  Skipping write of public/index.html

i  Writing configuration info to firebase.json...
i  Writing project information to .firebaserc...
```

### Install Yarn

`npm i -g yarn`

### Install firebase in our project

`yarn add firebase`

### Install project dependencies

`yarn install`

### Run the app

`yarn start`