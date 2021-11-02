# 💻 darkins_orm-e-commerce_wk13

## Description
*The what, why, and how:*<br>
❓ Complete backend logic that utilizes latest technologies to improve performance and function of e-commerce applications in an increasingly competitve digital marketplace

Please follow THIS LINK to view a working video tutorial of the application.

Below are screenshots that provide further reference:
![screenshot_1](https://user-images.githubusercontent.com/84754257/139790002-91c64606-ba3e-4598-9f51-deaa547480f9.png)
![screenshot_2](https://user-images.githubusercontent.com/84754257/139790011-ae9af357-5487-4a1a-b8f1-73768ad06a58.png)
![screenshot_3](https://user-images.githubusercontent.com/84754257/139790030-171fad86-4def-4237-9a9a-1348a0034632.png)


## Table of Contents

* [Installation](#installation)
* [Language](#language)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Features](#feature)
* [Questions](#Questions)

## Installation
*Steps required to install project and how to get the development environment running:* 
<br>
🔌 In order to run the application successfully, the user needs to install the following dependencies via their terminal:

* node.js package.json - `npm init -y`
* mysql2 - `npm i mysql2`
* express - `npm i express`
* sequelize - `npm i sequelize`
* dotenv - `npm i dotenv`

## Language 
*The following programming languages were utilized when completing this project:*
<br>
![Javascript](https://img.shields.io/badge/Language-javascript-yellow.svg)![Node.JS](https://img.shields.io/badge/Language-Node.JS-ff69b4.svg)

## Usage
*Instructions and examples for use:*
<br>
🏁 Begin by cloning the Github repository to your local computer, and opening in your code editor:

* Open your terminal, navigate to the db sub-directory and login to MySql with the following command:
    * `mysql -u root -p`
* After entering a password, access the project database with the following command:
    * `SOURCE schema.sql`
* `EXIT` the SQL shell and navigate to a new terminal window
* Open the `.env` file and edit the values to match your personal SQL specifications
* Import seeded data into the database for testing with the following command:
    * `npm run seeds`
* If data is seeded successfully, the following console.log messages will appear the corresponding console:
    * `PRODUCT TAGS SEEDED`
    * `TAGS SEEDED`
    * `PRODUCTS SEEDED`
    * `CATEGORIES SEEDED`
    * `DATABASE SYNCED`
* Initiate the synch between Sequelize models and the MySQL database typing the `npm start` command into your terminal
    * If successful, a console.log message reading `Now listening`
* Navigate to the Insomnia REST application and begin testing each of the POST, GET, PUT and DELETE routes associated with the application's models using `localhost:3001`.

## Credits
*A thank you to those who helped make this happen:*
<br>
💳 A special shout out to the AskBCS Learning Assistant team for clarificaiton on a server erorr.
Recognition is also in order to my tutor Amanda Chapman, who suggested updating one of the products from 'cargo shorts', to 'parachute pants.' Thank You

  ## License
*This project is licensed under:* <br>
![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)<br>
<a href= https://opensource.org/licenses/MIT)>MIT License Link</a><br>

## Features
*These features make up the core tenets of this project:*
<br>
🌟 Dynamic organization that follows Model and Controller best practices

## Contributing
👐 This project adheres to standards set by the <a href = https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md>Contributor Covenant</a>.<br>
Please consult this documentation before contributing to this project.

## Questions
![Profile Pic](https://user-images.githubusercontent.com/84754257/139790099-cf4bfa2b-7f7b-45d3-9b52-db9f6c7255c1.jpg)

If you have any questions regarding the development process of this application, or specific questions about contributing, feel free to reach me by email or on Github.
* Email 📪 willdarkins@gmail.com
* Github 🗿 [willdarkins](https://github.com/willdarkins) 
