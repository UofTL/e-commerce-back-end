# e-commerce-back-end

Repo URL:https://github.com/UofTL/e-commerce-back-end.git

This a back-end app will explore the ORM. This e-commerce app that will allow user to see all different (Tags, Categories, Products). The user will have the opportunity to use the CRUD to make some modifications (CREATE, READ,UPDATE, DELETE)

* For a video on using the app click [here.](https://screencast-o-matic.com/watch/crQbVGV66Q7)
* ![markdown-preview-image](./demo/demo.gif)
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
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Install

Clone project.
Run the following line of code in your terminal to install all the needed packages: 
```
npm i
```

## Usage

Once all the packages have been installed, open terminal and run the following code in command line : 
```
node server.js

```
You will have a message in the terminal "App listening on port 3001!" Then you can make request (GET, POST, DEL,PUT) and visualize on Insomnia and check the response (200:OK, 400:Bad request, 500:Server issue)

## Built With
- SQL
- GitBash
- GitHub
- Insomnia
- Screencast-O-Matic
- Screencastify 
- JavaScript
- Node.js
  - MySQL2
  - Sequelize
  - Express
  - dotenv

## Screen shots
![Insomnia](https://user-images.githubusercontent.com/84641285/133714371-b35aea73-0ea9-4bd8-858c-a07a86e05e8d.png)
![Terminal](https://user-images.githubusercontent.com/84641285/133714616-8ea54851-7b78-47d0-b68d-41ecc7bb5882.png)