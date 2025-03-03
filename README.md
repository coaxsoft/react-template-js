# React Template: coax-react-js

## Description
This is a custom React template, coax-react-js, which comes pre-configured with the essential settings for a quick start of a new React project.


# Quick Start

- To use this template, you need to run the following command:

```console
npx create-react-app "APP_NAME" --template coax-react-js
```
- Please replace "APP_NAME" with the name of your new project.
- After the installation is complete, navigate to project folder and run the following command:

```console
rm -rf node_modules && npm install
```

# Initial Setup
After installation, you need to update a few configuration files:

`CHANGELOG.md`

Provide the initial project name and description at the top of the `CHANGELOG.md` file. It might look something like this:

```console
# APP_NAME

## Project description
add your project description here
```

# Features
This template contains the following features:
 - Router
 - tests
 - lint
 - prettier
 - pre-commit
 - git actions
 - sonar

# Deployment

After the project is ready for deployment, you need to update the following files:

`package.json`

Update the version of the project in the `package.json` file.

Run the following command to publish the project:

```console
npm publish
```

