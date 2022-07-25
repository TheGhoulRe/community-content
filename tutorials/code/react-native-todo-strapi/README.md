# Introduction

![Cover](https://github.com/fabio-nettis/react-native-todo-strapi-tutorial/blob/master/screenshots/article-cover-medium.png?raw=true)

This repo is a project for the strapi blog on [Creating a react-native app with Strapi as your backend](https://strapi.io/blog/creating-a-react-native-app-with-strapi-as-backend).

# Prerequisites

This project requires the follwing installed to your system:
* NodeJS
* Yarn or NPM

Your system also need one of the following to emulate the application:
* Xcode, for IOS development
* Android studio, for android development

# Getting started

To get this application running, you should:
1. start up the strapi API.
2. begin mobile emulation.

To start up the strapi backend, open the `react-native-todo-strapi` folder in your terminal, and run the below command:
```bash
yarn develop
```

To perform any admin operation on the Strapi backend, login to the admin dashboard with the following details:
* **Email**: random@email.com
* **Password**: Random@123

Then, begin mobile emulation by opening the `TodoApp` folder in another termial, and running the command below:
```bash
# android

yarn android

# IOS

yarn ios
```