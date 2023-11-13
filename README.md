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

1. **Clone the repository:**
   ```
   git clone https://github.com/Donsidious/Module-12
   ```

2. **Open the project in Visual Studio Code.**
   - If you don't have Visual Studio Code installed, make sure to install it.

3. **Install Node.js version 16:**
   - For Homebrew users:
     ```
     brew install node@16
     ```
   - Note: The installation process may vary; consult the documentation if needed.

4. **Initialize your project:**
   ```
   npm init -y
   ```
   - This creates a `package.json` file to manage dependencies.

5. **Install required dependencies:**
   - For Sequelize:
     ```
     npm i sequelize
     ```
   - For mysql2:
     ```
     npm i mysql2
     ```
   - For dotenv:
     ```
     npm i dotenv
     ```
   - For inquirer (version 8.2.4):
     ```
     npm i inquirer@8.2.4
     ```
   - For chalk:
     ```
     npm i chalk
     ```

6. **Create the database:**
   - Navigate to the `db` directory.
   - Open a MySQL shell and run:
     ```
     source schema.sql
     ```
   - This command creates the database structure.

7. **Seed the database and generate model structure:**
   - To seed departments:
     ```
     node ./seeds/departments
     ```
   - To seed roles:
     ```
     node ./seeds/roles
     ```
   - To seed employees:
     ```
     node ./seeds/employees
     ```

8. **Run the application:**
   ```
   npm start
   ```
## Features

This application offers various capabilities, enabling users to effortlessly oversee and control their company's departments, roles, and employees, all from the command line. It leverages sequelize, enabling direct database interaction through JavaScript, resulting in a dynamically interactive user experience.

## Usage Information

Using this application is straightforward. After starting the application (refer to the installation section for setup instructions), the user will receive prompts to make selections. These choices include viewing Department, Role, or Employee tables, adding a Department, Role, or Employee to the database, or updating an Employee's Role. If the user opts to add or update data in the database, the changes will be visible when they view the respective table that was modified.

## License

NOTICE: This application is covered under the MIT License
