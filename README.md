<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End 👋</h1>
    
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>
   
## Description

🔍 A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
  
💻 Below is the gifs showing the functionality of the application:
  
![DB Setup and Start](./walkthroughs/functionality.gif)

Tags walkthrough

![TAGS](./walkthroughs/tags_walkthrough.gif)

Products walkthrough

![PRODUCTS](./walkthroughs/product_walkthrough.gif)

Categories walkthrough

![CATEGORIES](./walkthroughs/categories_walkthrough.gif)

  
🎥 The full movie files showing functionality of the application can be found in the walkthroughs directory
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
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
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
💾   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
💻   
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when prompted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## Testing
✏️

Insomnia

## Contributing
:octocat: [Aaron Bean](https://github.com/arbean1978)

## Questions