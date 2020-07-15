# HW 09 Node.js & ES6+: Good README Generator 

  ## Description 
  
  *A short description (i.e what, why, and how):* 
  
  A simple CLI application that generates effective README.md files using Node.js and user inputted text.  Fun fact: This README was generated with it.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [License](#license)
  
  ## Installation
  
  *How to install and run the project:*
  
  First, run 'npm install' in order to install the necessary npm package dependencies that are defined in 'package.json'
    1. [`npm inquirer`] - prompts user for inputs from command line
    2. [`axios`] - to fetch user info from GitHub API

  After npm install, just enter `node index.js` into the terminal to run the application.  
  
  ## Usage 
  
  *How the app is used:*
  
  After running 'node index.js' , the application uses the inquirer package to prompt the user with a series of questions about the project as well as your GitHub.

  After collecting the user's responses, the application uses `axios` to fetch your GitHub profile from the GitHub API which includes your GitHub profile picture and email.

  The application generates markdown and a table of contents for the README file based on the inquirer prompt responses.

  To finish, `fs.writeFile` is used to generate the README.md file.

![use demo](demo.gif)
  
  # Contributing

  N/A 
  
  ## License
  
  MIT License
  
  ---
  
  ## Questions?
  
  ![Developer Profile Picture](https://avatars2.githubusercontent.com/u/60358344?v=4) 
  
  For any questions, please contact me with the information below:
 
  GitHub: [@samdotkim](https://api.github.com/users/samdotkim)
  