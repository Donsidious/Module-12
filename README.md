# SQL-Employee-Tracker
Week-12 Challenge 

## Table of Contents

 * [Description](#description)

 * [Live-Screen-Recording-of-Application-Functionality](#live-screen-recording-of-application-functionality)

 * [Screenshots](#screenshots)

 * [Technologies-Used](#technologies-used)

 * [Installation](#installation)

 * [Features](#features)

 * [Usage-Information](#usage-information)

 * [License](#license)

## Description

This application simplifies business owners' tasks by enabling them to effortlessly manage departments, roles, and employees using a MySQL database integrated with the sequelize dependency for JavaScript interaction, eliminating the need for complex query statements. During its development, I acquired skills in database seeding using MySQL and sequelize, joining tables, creating objects with .map(), using the inquirer dependency, and accessing data within objects. Future plans for the application include adding features to update employee managers, view employees by manager or department, delete departments, roles, and employees, and calculate departmental budgets by summing employee salaries.te some animation within the terminal, making the application more polished.

## Live Screen Recording of Application Functionality



## Screenshots

![Screenshot1-week-12-challenge](https://user-images.githubusercontent.com/120127903/235738338-75c97105-7ef1-40f5-b00e-b0951f1d504d.png)

![Screenshot2-week-12-challenge](https://user-images.githubusercontent.com/120127903/235738376-e099a758-b20e-4a72-b56c-9bc58472d10f.png)

![Screenshot3-week-12-challenge](https://user-images.githubusercontent.com/120127903/235738400-31819eff-205e-4154-81df-61d214a3af13.png)

![Screenshot4-week-12-challenge](https://user-images.githubusercontent.com/120127903/235738416-1289849b-4e79-4b97-864d-85c88a980095.png)

## Technologies Used

This application runs on Node.js (v16.19.1) and uses a combination of JavaScript and SQL. It relies on essential npm dependencies, including sequelize (v6.31.0), mysql2 (v3.2.4), dotenv (v16.0.3), inquirer (v8.2.4), and chalk (v5.2.0).

## Installation

1. Begin by cloning the repository using the following command:
   ```
   git clone https://github.com/Donsidious/Module-12
   ```

2. Open the project in Visual Studio Code. If you don't have Visual Studio Code installed, make sure to install it.

3. In your terminal, install Node.js version 16. If you're using Homebrew, you can use the command `brew install node@16`. Please note that the installation process may vary, so consult the documentation if needed.

4. After successfully installing Node.js version 16, initialize your project by running the command `npm init -y`. This will create a `package.json` file to manage your project's dependencies.

5. Next, use the terminal to install the required dependencies for this application. Developers can install each dependency separately using the following commands:
   - For Sequelize: `npm i sequelize`
   - For mysql2: `npm i mysql2`
   - For dotenv: `npm i dotenv`
   - For inquirer (version 8.2.4): `npm i inquirer@8.2.4`
   - For chalk: `npm i chalk`

6. Once all dependencies are installed, it's time to create the database. Navigate to the `db` directory, which contains the `schema.sql` file. Open a MySQL shell and run the command `source schema.sql` to create the database structure.

7. With the database created, proceed to seed it, which will also generate the model structure for the tables. Navigate back to the root directory and run the appropriate seed files using commands like:
   - `node ./seeds/departments`
   - `node ./seeds/roles`
   - `node ./seeds/employees`

8. After successfully seeding the database, you can run the application by executing `npm start` from the root directory. This command will start the application.

## Features

This application offers various capabilities, enabling users to effortlessly oversee and control their company's departments, roles, and employees, all from the command line. It leverages sequelize, enabling direct database interaction through JavaScript, resulting in a dynamically interactive user experience.

## Usage Information

Using this application is straightforward. After starting the application (refer to the installation section for setup instructions), the user will receive prompts to make selections. These choices include viewing Department, Role, or Employee tables, adding a Department, Role, or Employee to the database, or updating an Employee's Role. If the user opts to add or update data in the database, the changes will be visible when they view the respective table that was modified.

## License

NOTICE: This application is covered under the MIT License
