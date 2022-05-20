# E-cinnerce Back End - Challenge 13

## Description
This project is the thirteenth challenge of the coding bootcamp.

User Story: As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies, so that my company can compete with other e-commerce companies.

Starting from minimal starter code, this challenge required writing additional code to do the following:
*   GIVEN a functional Express.js API
        -WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
        -THEN I am able to connect to a database using Sequelize

        -WHEN I enter schema and seed commands
        -THEN a development database is created and is seeded with test data

        -WHEN I enter the command to invoke the application
        -THEN my server is started and the Sequelize models are synced to the MySQL database

        -WHEN I open API GET routes in Insomnia for categories, products, or tags
        -THEN the data for each of these routes is displayed in a formatted JSON

        -WHEN I test API POST, PUT, and DELETE routes in Insomnia
        -THEN I am able to successfully create, update, and delete data in my database

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Made Using:
* Node.js

## Installation
* to install, clone the repository from GitHub, run the command 'npm i' while in the project directory, and then run 'node app' to launch the employee tracker within the terminal/command line.  if database does not exist, additionally please run schema.sql, and seeds.sql to populate data into the database.  this can be done in the terminal - using the command 'mysql -u root -p', and then entering the mysql password.  if your mysql username is not root, please substitute your username in that command.  within mysql, run 'source db/schema.sql' to run the schema, and to seed, run 'source db/seeds.sql'.  running 'node app' in terminal after should result in a populated database.

## Usage
* this can be used to manage a company's employee database

## Contributing
* no outside contributions at this time

## License
* MIT License

[Click here for more license info!](https://choosealicense.com/licenses/mit/)

## Tests
* tests can be run by creating departments, roles, employees, and then viewing any entered data and updating if necessary.  a 'seeds.sql' will be included in the repository, which can be run populate the database with test data.

## Questions
* any questions, please feel free to reach out via email to rdpodols@gmail.com

## Link to Project & Screenshot
![Employee Tracker Screenshot)](/assets/images/applicationImage1.png)
[Click here to view the project!](https://rpodols.github.io/employee-tracker/)

## Walkthrough Video
* video walkthrough to show full capabilities of app:
    - Click here: https://drive.google.com/file/d/1gUJV8sb8AmwvVB58IEnCluxtTwOpJsbs/view
