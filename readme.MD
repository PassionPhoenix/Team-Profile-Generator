# Team Profile Generator
Daniel Vera
___

![mit](https://img.shields.io/badge/license-MIT-brightgreen)

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Screenshots](#screenshots)
* [walkthough](#Walkthrough)
<br><br>
## Description <br>
```
This Apppication allow the user to generate a Team Profile that display HDML after putting the infomation on the team.
```
### User Story
```
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```
```
GIVEN a command-line application that accepts user input
WHEN you are prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN you click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN you click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN start the application
THEN you are prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN you enter the team manager’s name, employee ID, email address, and office number
THEN you are presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN you select the engineer option
THEN you are prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN you select the intern option
THEN you are prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN you decide to finish building my team
THEN you exit the application, and the HTML is generated
```
## Installation

Users will need to install the following in their command line:
```
npm i
```


## Usage

After the installation process, users will then need to run the following in their command line:
```
node index.js
```
This will start the team profile generator process for the users. Once they have answered the prompts to the best of their ability, a new file called, `index.html`.


## Technologies

The technologies used to create this program were: 
Javascript
Node
Express
Inspire
<br><br>