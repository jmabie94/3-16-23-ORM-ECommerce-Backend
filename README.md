# Sequelize E-Commercde Back-End - John Mabie

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
---
### This project is designed to allow a user to use and update a functional inventory database for their E-commerce business on the back-end.

#### Here is the link to the GitHub repository: https://github.com/jmabie94/3-16-23-ORM-ECommerce-Backend
---
## Contents
1. [About](#about)
    1. [User Story](#user%20story)
    2. [Acceptance Criteria](#acceptance%20criteria)
    3. [Media](#media)
2. [Installation](#installation)
3. [License](#license)
4. [Contributing](#contributing)
5. [Tests](#tests)
6. [Authors and Acknowledgments](#authors%20and%20acknowledgments)
---
## About

#### Using Express.js and Sequelize, this application allows the User to use a custom API to see the inventory of their E-Commerce site, create new inventory products, product tags and product categories, update any aspect of their inventory and delete items from their inventory as needed.
---
## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
---

## Media:

Video Walkthrough of the Application and all functions:

![Video Walkthrough](./media/ORM%20Video%20Walkthrough.webm)

---

## Installation:

Utilizing the Application is simple!

First, clone the repo:
    
    git clone git@github.com:jmabie94/3-16-23-ORM-ECommerce-Backend.git

Next, open an integrated terminal in your cloned folder and do the following:
    
    run "npm init -y"
    run "npm i"

After Node Packages have installed, open your MySQL:

    "mysql -u root -p"
    *enter your password*
    "SOURCE db/schema.sql"
    "exit"


Finally, after exiting MySQL:

    run "npm run seed"
    run "npm start"

Then, utilize Insomnia to test the routes and use the database!
    
---

## License
License used for this project - MIT
* For more information on license types, please reference this website for additional licensing information - [https: //choosealicense.com/](https://choosealicense.com/).
---
## Contributing:
To contribute to this application, create a pull request.
Here are the steps needed for doing that:
- Fork the repo
- Create a feature branch (git checkout -b NAME-HERE)
- Commit your new feature (git commit -m 'Add some feature')
- Push your branch (git push)
- Create a new Pull Request
Following a code review, your feature will be merged.
---
## Tests:

### No tests were used
---
## Authors and Acknowledgments:

### Primary Author: Jack Mabie

### Resources Used: Express.js, Sequelize & MySQL

---
## Contact Information:
* GitHub Username: jmabie94
* Email: johnmabie94@gmail.com