
# [(ORM)E-commerce Back End](https://github.com/mlarkin14/ORM-backend)
  

## Description

  Example of ORM to build the back end for an e-commerce site with a working Express.js API and configure it to use Sequelize to interact with a MySQL database.
  
## Installation

Installation is a process of installing the dependencies required.
Intialize node package manager and then run the following commands;  
`npm install mysql2`\
`npm install sequelize`\
`npm install dotenv`

## Usage

 In order to use the application, first ensure that MySQL is installed in your environment.\
 Then, from the project root folder enter the sql shell and run the following command:\
`source db/schema.sql`\
Exit the sql shell and return to the command line still within your root project folder.\
Run the following commands:\
`npm run seed`\
`npm start`