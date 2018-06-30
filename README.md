# NYT-React
----------
## Table of Contents 
1. [Overview](#overview)
2. [Technologies](#technologies)
3. [Local Installation](#installation)
4. [App Display](#display)

<a name="overview"></a>
## Overview 
NYT-React is a React framework web app that allows users to search for articles via the New York Times API and to store and delete articles using MongoDB. 

<a name="technologies"></a>
## Technologies
 - Express.js 
 - Bootstrap
 - New York Times API
 - React 4 
 - Mongoose 
 - MongoDB
 	- Local database
 - mLab 
 	- Deployed Heroku database 

<a name="installation"></a>
## Local Installation
### Step 1: Git Clone
Clone NYT-React to your local git repo like the following:
> git clone https://github.com/meghnanag/nytreact
The NYT-React project and its files should now be in your project folder.

### Step 2: Install Dependencies
Install the following dependencies listed in the `package.json` file: 

> npm install

Once completed, you will see a `node_modules` folder in your local repo.

The dependencies should now be in the local `node_modules` folder.

### Step 3: Launch app 
Via terminal type in these bash command once you are in the NYT-Reat root directory 
> node server.js 

This step will automatically create the necessary MongoDB. 

Go to your browser and type in `localhost:3000` in your URL bar. Now you should see the application open locally.
To visit deployed application, go to 

<a name="display"></a>
## App Display
### Demo
![Demo](/public/assets/images/demo.gif)
