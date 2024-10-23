# kanban-board

## Description

 This application is a project management tool that helps teams visualize and organize their work to increase efficiency and collaboration. This app is specifically a template of a Kanban Board application that handles authentication with JSON Web Tokens(JWT) as it provides a secure and scalable method for verifying user identities. In its current state the Kanban works as a productivity tool, however, the user data is currently seeded in the backend.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

As it stands the app is usable as a tool. To use it from Render please check out the seed file to use any of the provided login data to access the board.
<https://kanban-board-u4xv.onrender.com>

If you'd like to use this app as a starting point for a bigger project, you will need close the code from my repo. Create a .env file in /server that will include "DB_NAME:kanban_db", "DB_USER:postgres", "DB_PASSWORD:[ your postgres password]", and "JWT_SECRET_KEY: [ your secret key]". At the root level please "npm install" in your terminal.  After, cd into server/db and launch your postgres shell and create the database, and initiate your schema file. Once postgres has been launched you can npm run build to create the front and backend connections and npm run start to start the server.

## License

This project is licensed under the terms of the MIT.

## Badges

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="254" height="20" role="img" aria-label="MIT: [https://opensource.org/licenses/MIT]"><title>MIT: [https://opensource.org/licenses/MIT]</title><linearGradient id="s" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/><stop offset="1" stop-opacity=".1"/></linearGradient><clipPath id="r"><rect width="254" height="20" rx="3" fill="#fff"/></clipPath><g clip-path="url(#r)"><rect width="31" height="20" fill="#555"/><rect x="31" width="223" height="20" fill="#4c1"/><rect width="254" height="20" fill="url(#s)"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110"><text aria-hidden="true" x="165" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="210">MIT</text><text x="165" y="140" transform="scale(.1)" fill="#fff" textLength="210">MIT</text><text aria-hidden="true" x="1415" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="2130">[https://opensource.org/licenses/MIT]</text><text x="1415" y="140" transform="scale(.1)" fill="#fff" textLength="2130">[https://opensource.org/licenses/MIT]</text></g></svg>

## How to Contribute

As contributors and maintainers of this project, we pledge to respect all people who contribute through reporting issues, posting feature requests, updating documentation, submitting pull requests or patches, and other activities.

We are committed to making participation in this project a harassment-free experience for everyone, regardless of level of experience, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, or religion.

If you'd like to contribute further to the development of this project you can do so like this:
As it stands, this app does not have its own sign-up functionality and runs on seed data. Expanding the functionality and even artistic creative contributions would be appreciated.

## Contact Us

For more information about this project please its' Github Repo <https://github.com/dafnefluna/kanban-board>  or email us at <dafne.faviola.luna@gmail.com>
