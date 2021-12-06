# ProfessionalEyes

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

_"You can vent and we'll fix it before it's sent."_

ProfessionalEyes is a full-stack web application that filters user inputted message content in order to produce a more professional email, effectively communicating the user's desired message.

Using the Model-View-Controller paradigm in conjunction with server-side APIs and user authentication, ProfessionalEyes was built via collaborative workflow and agile development methodologies.

## User Story

```
AS A user unable to control my emotions while writing an email
I WANT to cleanse my written message content
SO THAT I can produce a more professional email for the recipient
```

## Technologies Used

- Node.js and Express.js
- MySQL and Sequelize
- Handlebars.js - template engine
- Express-session - cookies/user authentication
- WordPOS - part-of-speech analysis
- Twinwords API - sentiment analysis
- PurgoMalum API - filtering profanity
- Merriam Webster API - synonyms/antonyms

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```
npm i
```

## Usage

The following link can be used to view the deployed full-stack web application on Heroku:

[ProfessionalEyes](https://professionaleyes.herokuapp.com/)

Upon registering as a new user via the sign up form, the user can input an email within the text box. Clicking the cleanse button will return a sanitized version of the email. The profile page allows the user to view all the previously sanitized emails on the account.

For security purposes, the dotenv package was used to conceal the database credentials of the user. In order to connect to the database locally, a `.env` file must be created containing populated `DB_USER=`, `DB_PASSWORD=` and `DB_NAME=` entries appropriate for the user.

A screenshot of the deployed application:

![ProfessionalEyes Screenshot](/public/assets/pe-screenshot.png)

Presentation Slides:

[Project Presentation Slides](https://docs.google.com/presentation/d/18AcMHJFImuzU1fyoPVsd-pQc5mIpu1bee8zcrXF5MeY/edit?usp=sharing)

## License

This project is licensed under the MIT license.

## Contributing

Please contact me or my team members. Thank you!

[Courtney Long](https://github.com/courtbourt12), [Joshua Watkins](https://github.com/joshuakwatkins), [Griffin Wilkens](https://github.com/gwilkens96)


## Tests

This project does not contain any tests.

## Questions

If you have any questions about the repo, open an issue or contact me directly at abrahamin.html@gmail.com. You can find more of my work at [https://github.com/abrahamin/](https://github.com/abrahamin/).