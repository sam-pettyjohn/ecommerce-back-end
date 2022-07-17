![MIT](https://img.shields.io/badge/License-MIT-blue)
# # E-Commerce Back End

## Description

Custom built back end for an e-commerce site using Express.js API and configured to use Sequelize to interact with a MySQL database. 

Please use this [video](TBD) for a walkthough tutorial of this project.

## Table of Contents

- [E-Commerce Back End](#E-Commerce-Back-End)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [User Story](#user-story)
  - [Mock-Up](#mock-up)
  - [Acceptance Criteria](#acceptance-criteria)
    - [Additional Criteria](#additional-criteria)
  - [Contributing](#contributing)
  - [Built With](#built-with)
  - [Questions](#questions)
  - [License](#license)

## User Story
~~~
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
~~~

## Acceptance Criteria
~~~
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
~~~

### Mock-Up
The following animations show examples of the application's API routes being tested in Insomnia.

The first animation shows GET routes to return all categories, all products, and all tags being tested in Insomnia:
![image](./assets/images/mockup-1.gif)
<br>
<br>
The second animation shows GET routes to return a single category, a single product, and a single tag being tested in Insomnia:
![image](./assets/images/mockup-2.gif)
<br>
<br>
The final animation shows the POST, PUT, and DELETE routes for categories being tested in Insomnia:
![image](./assets/images/mockup-3.gif)

### Additional Criteria

**Deliverables**

- Your GitHub repository containing your application code.

**Walkthrough Video**

- A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your README file.
- The walkthrough video must show all of the technical acceptance criteria being met.
- The walkthrough video must demonstrate how to create the schema from the MySQL shell.
- The walkthrough video must demonstrate how to seed the database from the command line.
- The walkthrough video must demonstrate how to start the application’s server.
- The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia.
- The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia.
- The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.

**Technical Acceptance**

- Satisfies all of the preceding acceptance criteria plus the following:
- Uses the MySQL2 (Links to an external site.) and Sequelize (Links to an external site.) packages to connect to a MySQL database.
- Uses the dotenv package (Links to an external site.) to use environment variables to store sensitive data, like a user’s MySQL username, password, and database name.
- Syncs Sequelize models to a MySQL database on the server start.
- Includes column definitions for all four models outlined in the Challenge instructions.
- Includes model associations outlined in the Challenge instructions.

**Repository Quality**

- Repository has a unique name.
- Repository follows best practices for file structure and naming conventions.
- Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
- Repository contains multiple descriptive commit messages.
- Repository contains a high-quality README with description and a link to a walkthrough video.

## Contributing

For any ideas or feedback, please see my contact information [below](#questions).

## Built With

- JavaScript
- SQL
- node.js
    - Sequelize package
    - MySQL2 package
    - dotenv package
    - express
- markdown

## Questions

For any questions, please reach out to me through the following resources:

Name: Samuel Pettyjohn <br>
Title: Aspiring Developer <br>
Email: <sammpj47@gmail.com> <br>
GitHub: <https://github.com/sam-pettyjohn/> <br>

## License

MIT License

Copyright (c) 2022 Samuel Pettyjohn
            
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
            
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
            
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 