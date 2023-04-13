# Notes-NPM
A repository where I will put my NPM notes
## npm init
This command creates a file called package.json, which includes multiple data related to our project, such as its name, version, license, author, etc. We can take the default options by using **npm init -y**
## Installing dependencies

There are 3 types of dependency:

### Local dependencies

Mandatory dependencies for our project. They are installed with the command: **npm install (package) / npm install (package) --save**

#### Optional dependencies
Dependencies that don't necessarily need to be installed. Just need to add a **-O** at the end of the installation.

### Dev dependencies

Dependencies that are not mandatory in our project to work, they are used to improve our code quality and optimization. They are installed with the following commands: **npm install (package) / npm install (package) --save-dev**

### Global dependencies

Dependencies that will be available for all the projects in our PCs, they are installed with the following command: **npm install (package) --global**


The package.json file contains all these dependencies.

We can install specific versions of a dependency by adding a **@[version]** at the end of the installation. We can also add a **@latest** for the last version.

We can simulate an installation by adding **--dry-run**.

If you want to install every single dependency that is on the package.json file, just use **npm install**.

## npm list

Provide us with a list of the multiple packages we are using.

## Scripts
We can create our own scripts on the "scripts" section, we can run them with **npm run [ name ]**

We can execute a NPM command remotely with NPX

## Update
Dependencies can be updated by using npm install package@latest

You can visualize the packages that are not updated by using **npm outdate**

When we install dependencies, it can show warning due to outdated packages, we can see this errors by using **npm audit** and fix them with **npm audit fix & npm audit fix --force**

To uninstall a dependency just do **npm uninstall package** or we can manually delete it on the package.json file, deleting node_modules and doing npm install again.