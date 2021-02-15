# superlist
to-do list in python
The Exercise
The goal of the exercise is to develop a simple to-do list application. The application will consist of at least a backend API and a frontend web interface.
A to-do item should have the following attributes:
● Name: single-line string (required)
● Description: multi-line string < 500 characters (optional)
● Due Date: date field, without time (optional)
● Status: ​pending o​ r d​ one ​(required)
The backend:
● Should be written in Python as a RESTful API.
● May use any Python framework you prefer.
● Does not need to implement any user authentication.
● Assumes all to-dos are global, with anyone accessing the API able to perform any action
on any to-do item (or new to-do item).
● Should maintain to-do data between backend process lifetimes.
○ Preferably store to-do data in a persistent database of some sort. The frontend:
● Should be a single page web application
● Written using HTML5 and Javascript
○ may use whatever Javascript framework you prefer.
The application is expected to implement at least the following features:
● List view of all to-do items:
○ Filterable by Status and/or Due Date
○ Sorted by due date
○ Mark to-dos as done from the to-do list view
○ Delete to-do
● New to-do form
○ Add a new to-do item
● Detail view of a specific to-do:
○ Displaying all attributes of a specific to-do item
○ Mark to-do as done
○ Delete to-do
○ Edit to-do
Additional requirements:
● Store all your code in a ​Git r​ epository and commit changes regularly during your development,
○ Include meaningful commit messages along the way.
○ Feel free to use Git branches if helpful.
○ Keep the ​.git​ directory in your archive file for submission.
● Include a ​README.md​ file in the base directory of the project that explains how to run
       Superloop (Services) Pty Ltd Ph 1300 558 406 ABN 68 621 677 576 info@superloop.com
Level 1, 545 Queen St, Brisbane, QLD,
4000 superloop.com GPO Box 2776, Brisbane, QLD, 4001
the application components and how to interact with the API and web interface.
● Use comments as you would in a production codebase maintained by a wider team.
● Include automated tests with good coverage for both the backend and frontend
applications.
● You may use any frontend library or framework you prefer, but make sure the web
interface is reasonably responsive and usable on different form factor clients, i.e. desktop,
tablet, smartphone etc.
● Validate incoming changes to data in the backend API and display validation errors
generated by this in the frontend web interface.
● Front end validation is o​ ptional ​- feel free to include it where it enhances the user
experience.
● Ensure that your REST endpoints follow de facto industry standards for RESTful APIs over
HTTP.