# HW 09 Node.js & ES6+: Good README Generator 

  ## Description 
  
  *The what, why, and how:* 
  
  A simple CLI application that generates effective README.md files using Node.js and user inputted text.  Fun fact: This README was generated with it.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [License](#license)
  
  ## Installation
  
  *Steps required to install project and how to get the development environment running:*
  
  First, run 'npm install' in order to install the necessary npm package dependencies that are defined in 'package.json'
    1. [`npm inquirer`] - prompts user for inputs from command line
    2. [`axios`] - to fetch user info from GitHub API

  After npm install, just enter `node index.js` into the terminal to run the application.  
  
  ## Usage 
  
  *Instructions and examples for use:*
  
  After running 'node index.js' , the application uses the inquirer package to prompt the user with a series of questions about the project as well as your GitHub.

  After collecting the user's responses, the application uses `axios` to fetch your GitHub profile from the GitHub API which includes your GitHub profile picture and email.

  The application generates markdown and a table of contents for the README file based on the inquirer prompt responses.

  To finish, `fs.writeFile` is used to generate the README.md file.


  
  ## License
  
  MIT License
  
  ---
  
  ## Questions?
  
  ![Developer Profile Picture](https://avatars2.githubusercontent.com/u/60358344?v=4) 
  
  For any questions, please contact me with the information below:
 
  GitHub: [@samdotkim](https://api.github.com/users/samdotkim)
  