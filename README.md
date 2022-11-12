# CPSC 310 Project, Query Engine
# By Diwakar Gupta and Aaron Tsang  

## Configuring your environment for the project

1. [Install git](https://git-scm.com/downloads) (v2.X). After installing you should be able to execute `git --version` on the command line.

1. [Install Node LTS](https://nodejs.org/en/download/), which will also install NPM (you should be able to execute `node --version` and `npm --version` on the command line).

1. [Install Yarn](https://yarnpkg.com/en/docs/install) (v1.22+). You should be able to execute `yarn --version` afterwards.

## Project commands

Setup and running code:
In the project folder:

1. `yarn install` to download the packages specified in your project's *package.json* to the *node_modules* directory.

1. `yarn build` to compile your project. You must run this command after making changes to your TypeScript files.

1. `yarn test` to run the test suite.

## FAQ

- What is this project? What does it do?
This is a query engine which parses data on UBC courses(from JSON files) and buildings(from HTML files) and then allows you to run queries on it. This was done as part of a group for CPSC310 at UBC. 

## Functionality
- Parse JSON/html files for information on UBC classes and buildings, and store that information locally. 
- Run queries on the data, such as finding courses under a certain department with an average over 70 etc. 

