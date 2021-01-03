# Employee Management System
Employee Tracker is a CLI applicaiton for building and maintaining companies employee data base. Built on MySQL and leveraging modularity in the structure of Employee Tracker, it can scale appropriatley with a companies growth without reconfiguring the core structure of the internal employee data base. This application can act as a foundation to continue to build upon. Employee allows managers or someone within the company to view all employees, roles, as well as departments. It also allows for adding employees, roles, departments and updating employees all from your CLI.

# The application gives you the following options:
* View all employees with the option by role, department, or manager.
* Add an employee, role, or department.
* Update an employee role or manager.
* Delete employee, role, or department.
* View department salary budgets.

## Installation
---
1. Run `npm install` to install all dependencies
2. Run `schema.sql` in MySQLWorkbench   
3. Edit MySQL connection properties in the `connectionProperties` object in `employee-tracker.js`

## Usage
---
1. Run `node employee-tracker.js` to start the application.
2. Select from the menu to view, add, remove, or update employees, roles, departments, or managers:

    ![menu](https://user-images.githubusercontent.com/71414528/103473881-264a6980-4d52-11eb-848e-215f54291ac5.gif)


3. Follow prompt if presented:

    ![](images/sample.png)

## Tool & Resources
---
* [Node.js](https://nodejs.org/en/) - JavaScript runtime environment
* [MySQLWorkbench](https://www.mysql.com/products/workbench/) - Visual database design tool
    ### Dependencies
    ---
    * [inquirer](https://www.npmjs.com/package/inquirer) 
   * [console.table](https://www.npmjs.com/package/console.table) 
    * [mysql](https://www.npmjs.com/package/mysql) 
    

