# Pup-Portal
![License: Apache](https://img.shields.io/badge/license-MIT-green.svg)

## Description
This application is designed to help dog shelter employees and volunteers to keep track of the dogs in their shelter. Employees can enter information about each dog into the database with all the important information about the dogs. Once dogs are in the database, employees logged into the database can also view a list of all the current dogs and the information about each dog.

Our motivation for this application was to create an easy way for shelters to add new dogs to their website and allow pet and pet information to be viewed. Many shelters can struggle with keeping current information ready and available for people to view. Hopefully this will help shelters stay up to date on their website so more dogs can be adopted! 

This project allowed our team to use a Model-View Controller file structure, a SQL database, Sequelize, Handlebars, and to create REST API routes. Our team also had the opportunity to practice using Heroku to deploy our application with a working database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Features](#features)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation
Pup Portal is deployed live at the following URL: https://protected-woodland-99005-7f5a7e5f2c52.herokuapp.com/ 
Users can interact with the application in their web browser, and do not need to install anything. However, users must login with an example user in the database (choose one of the following):  {"name": "Victoria", "email": "victoria@gmail.com", "password": "password12345"}
      {"name": "Cassie","email": "cassie@gmail.com","password": "password678910"},
      {"name": "Carolina","email": "carolina@gmail.com","password": "mypassword01234"},
      {"name": "Olivia","email": "olivia@gmail.com","password": "mypassword56789"},
      {"name": "Sadie","email": "sadie@gmail.com","password": "12345password"}

## Usage
Registered users in the database (dog shelter workers) can enter their login credentials by selecting the 'login' link, and then either select the link to view all dogs in the database or add a new dog. Users can select the "home page" button to navigate to the home screen and choose to add/view dogs. When finished, users can select the logout button to log out. 

![screenshot of Pup Portal main page with links](public/assets/images/pup-portal-screenshot.png)


## Credits
This project was created by the following people. Carolina Ochoa, Cassie Sprague, Olivia Skillings, Sadie Thongsavanh, and Victoria Greenwood. Following submission of the group assignment, CSS updates were added by Victoria Greenwood to add additional/complementary colors, button styles, and screen size responsiveness.

Collaborations and References/Resources:

Node .gitignore template:
Toptal. (n.d.). gitignore for Node. gitignore.io. Retrieved April 3, 2024, from https://www.toptal.com/developers/gitignore/api/node

Tailwinds CSS library documentation for use of/setup of library:
Tailwinds CSS. (n.d.). Tailwind CSS - Rapidly build modern websites without ever leaving your HTML. Retrieved April 11, 2024, from https://tailwindcss.com/

XPert AI:

-Debugged use of res.render in home routes: needed to pass logged in key value pair as object with curly braces
-Debugged syntax for correctly importing models into seeds.js file
-Formatting for event listeners

Google AI:
-Debugging syntax for logout button event listener JS file

Microsoft copilot AI:
Checking syntax and debugging CSS styles

Collaboration:
Torre Taylor (UT Bootcamp class instructor): 
-Debugging router exporting for dogRoutes, setup of MVC structure with correct module exports
-Assistance with debugging login routes
-Assistance with debugging handlebars loop to render data from database
-Assistance with debugging logout route and syntax for event listener JS file to connect logout route and logout button
-Assistance with debugging const names for new dog form handler to match the database fields

Walter Perry (class TA): assistance with understanding how to implement form handling JS file for dogRoutes
-Assistance with debugging database seeds/SQL
-Assistance with debugging routes for login



## License 
This project is licensed under the MIT license. See the repository license section for details or go to https://choosealicense.com/licenses/mit/ 

## Badges
N/A

## Features
This application features Node.js, Express.js, Handlebars.js, MySQL, Sequelize ORM for the database, GET and POST routes, MVC paradigm, authentication, a polished UI, is responsive and interactive, and uses Heroku and JawsDB.

## Contributing
We are not accepting contributers for this project at the moment.

## Tests
N/A

## Questions
For any questions about this repository, feel free to contact any of us through the following links to GitHubs. Thank you!


GitHub: [Cocho011](https://github.com/Cocho011)

GitHub: [cassiesprague](https://github.com/cassiesprague)

GitHub: [via-skillings](https://github.com/via-skillings)

GitHub: [Sadiethongsavanh](https://github.com/Sadiethongsavanh)

GitHub: [victoria-cg](https://github.com/victoria-cg)
