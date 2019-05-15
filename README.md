## React-Clicky-Game
* Memory game built with React.


# Environment Setup
1. Download and Install the latest version of Node.js & npm on you computer.

# Getting Started
1. Either download the zipped project from GitHub or clone the repo into your local machine. The rest of the steps need to be executed in the Terminal:
2. cd into the directory clicky-game.
3. To install all of the dependency packages for the project locally, run: npm install
4. To start up the app, execute: npm start or npm run start or npm run-script start

# Live App:
Check out the app on Heroku here:
https://aqueous-taiga-55193.herokuapp.com/

# Overview
For this assignment, I created a memory game with React. This assignment required me to break up my application's UI into components,manage component state, and respond to user events.

# Instructions
* Created a new React application using Create React App.

* The application renders different images to the screen. Each image listens for click events.

* The application keeps track of the user's score. The user's score is incremented when clicking an image for the first time. The user's score resets to 0 if they click the same image more than once.

* Every time an image is clicked, the images rendered to the page shuffle themselves in a random order.

* Once the user's score is reset after an incorrect guess, the game restarts.