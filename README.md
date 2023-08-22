Employee review system app used for reviewing employee.

Description
A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.

App built using
Node , Express, Mongodb , EJS , javaScript , html, css, jQuery and PassportJS

Features
Sign up / Sign in forms for employees.
You can review the employees.
The admin has the special power to assign, the task to employee, remove the employee, add new admin, and also employee.
The admin can also update the reviews for any employee and can also delete any employee's reviews.
the employee can review their co-employees.
employees can view their review which are given by other employees.
Setup
Run npm install to install required dependencies

Config.env File (DOTENV): create a cofig.env file in the root of your project and add the below given data

1. PORT = [Your Port]
2. SESSION_SECREAT = [Your Secret]
3. DB = [Your MongoDB Ur]
4. ASSETS_PATH = [Your Assets Files To Access From]
