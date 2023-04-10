# Notes-NPM
A repository where I will put my NPM notes
## npm init
This command creates a file called package.json, which includes multiple data related to our project, such as its name, version, license, author, etc. We can take the default options by using **npm init -y**
## Installing dependencies

There are 3 types of dependency:

### Local dependencies

Mandatory dependencies for our project. They are installed with the command: **npm install (package) / npm install (package) --save**

### Dev dependencies

Dependencies that are not mandatory in our project to work, they are used to improve our code quality and optimization. They are installed with the following commands: **npm install (package) / npm install (package) --save-dev**

### Global dependencies

Dependencies that will be available for all the projects in our PCs, they are installed with the following command: **npm install (package) --global**

The package.json file contains all these dependencies.

## npm list

Provide us with a list of the multiple packages we are using.