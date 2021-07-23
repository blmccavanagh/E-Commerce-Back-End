# E-Commerce-Back-End

## This GitHub repository contains back-end code and database schema for an E-Commerce application.

---

### This application provides a database schema and seed files for the back-end of an E-Commerce application. The seed files contain a suitable database schema and sample data to demonstrate how data is stored within the database. Code for a basic API is also included, which allows for API calls to view, update or delete data from the database.

---

## Table of Contents

* [Installation and Usage](#installation-and-usage)
  * [Installation](#installation)
  * [Usage and Testing](#usage-and-testing)
* [Motivation and Research](#motivation-and-research)
* [Development](#development)
  * [Web development technologies](#web-development-technologies)
  * [Challenges](#challenges)
  * [Future Development Opportunities](#future-development-opportunities)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)
* [Repository Link](#repository-link)
* [Walkthrough Video](#walkthrough-video)

---

## Installation and Usage

### Installation

Clone the repository and then run this command within the repo directory:

```npm install```

You need to have <a href="https://www.mysql.com/">MySQL</a> installed and running on your local machine to create and use the database.

Use <a href="https://www.mysql.com/products/workbench/">MySQL Workbench</a> to view and manipulate the database and it's information. Alternatively you can install the <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.vscode-mysql">MySQL extension</a> in Visual Studio Code.

### Usage and Testing

Ensure you are running the terminal from the root path of the directory and that your MySQL server is running.

Run the SQL provided in `schema.sql` to create the database.

To seed the data to the database use:
<br>
`npm run seed`

To start the application use:
<br>
`npm start`
*or*
`node server.js`

---

## Motivation and Research

The motivation behind this project was to begin working with the concepts of routes and developing a basic API which was capable of accepting and processing requests, allowing for API calls to be made that would display and modify the data stored within the SQL database.

The application is designed to provide the basis for an E-Commerce website backend, with data being stored within the database for use with a future front end interface. Updates to the data can be performed using the provided API, allowing for Products, Product Categories and Product Tags to be created, modified, viewed or deleted.

The application is command line driven, and simple to use.

Routing in web development is a mechanism where HTTP requests are routed to the code that handles them. To put simply, Routing allows us to determine what should happen when a user makes a certain request via a HTML request, for instance to view a particular item on a shopping website, and how that data should be displayed to the user.

---

## Development

### Web development technologies

Development of the project was centered around using Express and MySQL/Sequelize, back end web applications for Node.js that are installed using the node package manager (NPM).

Node.js, an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

MySQL is the world's most popular open source database, and provides a database to contain data used by the application.

Sequelize is a promise-based, Node.js ORM (Object-relational mapping) for MySQL. It features solid transaction support, relations, eager and lazy loading, read replication, and other features.
 
Links to the languages and tools used to build this project are included below:

* Javascript ES6
* Node.js :
    * https://nodejs.org/
* NPM :
    * https://www.npmjs.com/
* NPM Packages :
    * Dotenv :
        * https://www.npmjs.com/package/dotenv
    * Express :
        * https://expressjs.com/
    * Jest :
        * https://jestjs.io/
    * MySQL2
      * https://www.npmjs.com/package/mysql2
    * Sequelize
        * https://sequelize.org/

### Challenges

The development of this application required the use of several NPM packages, including the installation of Dotenv, Express, MySQL2 and Sequelize.

Using MySQL and Sequelize provided a suitable database to contain the data for the application.  The provided seed files populated the database with sample data and a suitable schema for the application while Sequelize defined the various objects such as tables and other contents within the SQL database.

Developing a API using routing to control how the HTTP requests were processed was a new area of learning and required trial and error and research to understand how to best utilise the various API commands (GET, POST, PUT and DEL) and the associated formatting required to make API calls that had the correct syntax.

Using Insomnia Core to test functionality and develop a working application was also new for me. I built API request tests in Insomnia Core to become familiar around the concepts of planning testing as part of the development process, and to ensure that the API performed as expected when modifying the underlying database.

### Future Development Opportunities

Future development opportunities for the application can be focused primarily on the front end.

Development of a front end web interface using a combination of HTML, CSS and technologies such as Tailwind (a CSS framework) or React would provide a usable design for an E-Commerce based website, allowing for a visual presentation of the data stored within the database.

Development of a user interface would also allow for data to be filtered or displayed in a more targeted way by utilizing data such as category or tag to define the relationships between the data, and then allow for the display of data to be filtered by using these relationships.

Developing the front end interface with a consistent branding experience for the UI and other presentation based artifacts that is aligned to my other applications is also planned, reflecting my professional brand and providing a consistent UI experience across all of my developed applications.

---

## License

This repository is licensed under the MIT license.

---

## Contributing

No contributions at this time.

---

## Questions

If you have any questions, check out my <a href="https://www.github.com/blmccavanagh">GitHub</a> or email me <a href="mailto:blmccavanagh@gmail.com">here</a>.

---

<div align="center">

**Thank you for visiting.**

</div>

---

### Repository Link

* https://github.com/blmccavanagh/E-Commerce-Back-End

---

### Walkthrough Video

<div align="center">

*E-Commerce Back End Application Walkthrough Video*

</div>

<a href="https://drive.google.com/file/d/1qKMT8UdvrqDdoUiyiFrV9ZTrKA1ru0Vs/view?usp=sharing">Click here to watch the video!</a>

---