# Team-Profile-Generator

## Description
This `CLI` application will take in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person. Using this application, you will generate an html called team.html containing a profile card for each Team Member. You will answer a brief series of questions to populate the information within the card. 

## Prerequisites
You must have node.js installed and npm (Node Package Manager) on your computer to install this application.

## Features
* Collect and display information about team members.
* Generate a responsive webpage with team member profiles.
* Include details such as name, role, email, and other relevant information.
* User-friendly interface for adding and editing team members.

## Technologies Used
Built with:
* HTML
* CSS
* (Bootstrap)
* JavaScript
* Node

My application will use [Jest](https://www.npmjs.com/package/jest) for running the unit tests and [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command: node index.js

This application includes `Employee`, `Manager`, `Engineer`, and `Intern` classes. The tests for these classes (in the `_tests_` directory) ALL pass.

The first class is an `Employee` parent class with the following properties and methods:

* `name`

* `id`

* `email`

* `getName()`

* `getId()`

* `getEmail()`

* `getRole()`&mdash;returns `'Employee'`

The other three classes will extend `Employee`.

In addition to `Employee`'s properties and methods, `Manager` will also have the following:

* `officeNumber`

* `getRole()`&mdash;overridden to return `'Manager'`

In addition to `Employee`'s properties and methods, `Engineer` will also have the following:

* `github`&mdash;GitHub username

* `getGithub()`

* `getRole()`&mdash;overridden to return `'Engineer'`

In addition to `Employee`'s properties and methods, `Intern` will also have the following:

* `school`

* `getSchool()`

* `getRole()`&mdash;overridden to return `'Intern'`

## Installation
N/A

## Usage
* Open a terminal and navigate to the project directory.
* Run the application using node app.js.
* Follow the prompts to enter information about each team member.
* Once all information is entered, a team profile page will be generated in the output directory.
* Open the generated HTML file in your browser to view the team profile.

## Project Link
Application can can be viewed here: 
* [Repository](https://github.com/yvonnesarah/Team-Profile-Generator)

## Screenshot
Team Profile
![Screenshot](assets/images/team-profile.png "Team Profile")

## Credit
N/A

## License
Please refer to the LICENSE in the repo.

