# Project 5: FEND Capstone Project: Travel App


## Project Overview
This is the Capstone Project in Udacity's Front End Development Nanodegree.
This project is a web tool that aims to help users plan for their trips and get the required information about the destination 
like weather and an image of the location using information obtained from external APIs. 
_____________________________________________________________________________________________________________
## Teach stack
<div align="center">
  <img width="55" src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/express.svg"/>
  <img width="55" src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/jest.svg"/>
  <img width="55" src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/loader.svg"/>
  <img width="55" src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/node-sass.svg"/>
  <img width="55" src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/webpack.svg"/>
  <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>CSS3</title><path d="M1.5 0h21l-1.91 21.563L11.977 24l-8.565-2.438L1.5 0zm17.09 4.413L5.41 4.41l.213 2.622 10.125.002-.255 2.716h-6.64l.24 2.573h6.182l-.366 3.523-2.91.804-2.956-.81-.188-2.11h-2.61l.29 3.855L12 19.288l5.373-1.53L18.59 4.414z"/></svg>
</div>
The practical knowledge that you will gain through this project:
- Java Script Coding and DOM.
- Sass styles
- Creating layouts and page design
- Setting up Webpack
- Webpack Loaders and Plugins
- Dev and Prod modes
- Service workers
- Express
- Using APIs and creating requests to external urls
- Basic Jest testing

_____________________________________________________________________________________________________________
## Hosting
Live Demo : https://travel-planner-0.herokuapp.com/
_____________________________________________________________________________________________________________

## Setting up the Project
1- Fork the project Github repository.
2- Clone it onto your local machine OR download the zip file locally.
3- Get inside the project directory using `cd` command.
4- install all dependencies using `npm install` command.
_____________________________________________________________________________________________________________

## APIs
In this project I am using three APIs :
- [Geonames API](http://www.geonames.org/export/web-services.html)
- [DarkSky API](https://darksky.net/dev)
- [Pixabay API](https://pixabay.com/api/docs/)
To make sure that the project will work with you correctly. You need to register to these APIs and get your credential Keys. _____________________________________________________________________________________________________________

## Run the project
There is two environments (Mode) setup for this project:

> Development environment(Mode)
if you are going to apply some changes to the project and want the server to automatically re-build the application and reloads the page.
So you should use this command:
```
npm run build-dev
``` 
and it will open a new window in your browser with the app running on `localhost:3300`

> Production environment(Mode)
if you are going to run the project for production (with express server). 
So you should use these commands:
```
npm run build-prod
npm run start
```
and it will open a new window in your browser with the app running locally on port `localhost:7000`
_____________________________________________________________________________________________________________

## Project Testing
This project uses the Jest framework that provides us the ability to create, and run tests.
So you should use this command to run your tests:
- `npm run test`
_____________________________________________________________________________________________________________

### Project Preview  
>>> ![Screenshote for web page](Project_Review.png)

______________________________________^MOHAMED_SABER_SAYED_HAFEZ^____________________________________________
