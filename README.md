## Zeit Now Demo w/ Express App
_Showing the ease of deploying a simple Node/Express application._

The below steps will walk through the installation of this application, as well as getting a very basic start with Zeit Now.

Prerequisites for this humble tutorial are as follows:

1. Basic familiarity with the command line
2. Having Node and NPM installed on your machine. Please follow the instructions at <https://www.npmjs.com/get-npm> if necessary.


### Clone the repository
From the command line, navigate to where you would like to install the project, then clone the repository:
```
git clone https://github.com/skyetroll/zeit-now-express-demo.git
```

### Install dependencies
Move into the folder for the project and install the node dependencies:
```
cd zeit-now-express-demo
npm install
```

### Install Zeit Now's npm package
Globally install `now` to utilize its CLI
```
npm install -g now
```
_Alternatively, you can [download their desktop application](https://zeit.co/download), which will also install the CLI. Additionally, it will walk you through a signup process upon opening it for the first time._

### Deploy!
Run the command to deploy the project!
```
now
```

If this is the first time you have run this command (and you did not sign up through the desktop application), you will be prompted for an email address in order to set up a new account.

After this, you will see logs of the deployment process as your unique instance is created, including a new, unique, publicly accessible url where the instance can be visited.