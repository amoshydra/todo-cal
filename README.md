# Todo Calendar

> A Todo app + a calender view, that allow users to quickly record down their todos and organise them easily.

[![CircleCI](https://circleci.com/gh/amoshydra/todo-calendar.svg?style=svg)](https://circleci.com/gh/amoshydra/todo-calendar)
[![Known Vulnerabilities](https://snyk.io/test/github/amoshydra/todo-calendar/badge.svg)](https://snyk.io/test/github/amoshydra/todo-calendar)
[![Maintainability](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/maintainability)](https://codeclimate.com/github/amoshydra/todo-calendar/maintainability)

<img height="10px">

## Getting started in development

### 1. Initialise the repository
```bash
git clone git@github.com:amoshydra/todo-calendar.git
cd todo-calendar
yarn
```

<img height="30px">

### 2. Configure the project
This project uses some of the Google APIs. You are required update the
`GOOGLE_CLIENT_ID` and `GOOGLE_API_KEY` inside the `.env` file at the root of this repository.

For instruction on how to obtain a Google Client ID,  
see https://developers.google.com/identity/sign-in/web/devconsole-project.

Then, create a new API Key for `GOOGLE_API_KEY` at https://console.cloud.google.com/apis/credentials

<img height="30px">

### 3. Run the project
Once you have done configuring the project,  
run `yarn dev` to start developing!

This project is based on https://github.com/nuxt/nuxt.js.  
For detailed explanation on how things work, checkout the  
- [guide](https://github.com/nuxt/nuxt.js)

<img height="30px">

### 4. Build and deploy the project
`yarn build` to build the project into the `dist` folder.  

This project usese [surge.sh](http://surge.sh/) for deployment.  
`yarn publish` will deploy the `dist` folder to todo-calendar.surge.sh (you can change this in [`package.json`](https://github.com/amoshydra/todo-calendar/blob/master/package.json))

<img height="30px">

## More information:
1. [Background](https://github.com/amoshydra/todo-calendar/wiki) of this project
2. On-going [tasks](https://github.com/amoshydra/todo-calendar/wiki/Tasks)
