Employee Data Entry Form
A simple web-based form to manage employee records right in your browser, no server or database setup needed.

What it does
This form lets you add and update employee records with the following details:

Employee ID

Employee Name

Salary, HRA, DA, and Deduction

The Employee ID acts as a unique identifier (primary key), so no two employees can share the same ID.

How to use it
Just open index.html in any browser — that's it. No installation required.

Adding a new employee:

Enter an Employee ID that doesn't exist yet

The form unlocks and lets you fill in the rest of the details

Hit Save and the record is stored

Updating an existing employee:

Enter an Employee ID that already exists

The form loads that employee's data automatically

Edit whatever you need and hit Change to save the updates

Reset clears the form and takes you back to the start at any point.

Tech used
HTML & JavaScript

Bootstrap 5

IndexedDB (browser-built-in storage — data persists even after closing the tab)

Notes
Data is stored locally in your browser under a database called EMP-DB

No internet connection needed after the page loads

Works on any modern browser (Chrome, Firefox, Edge)
