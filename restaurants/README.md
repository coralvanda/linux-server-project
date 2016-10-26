# What is it?

This is a project completed as a part of the Udacity Full-stack 
Developer Nanodegree program.  When run, the files create a 
database to store information about restaurants and their menus, 
which is displayed on a webpage that users can interact with.  
Secure logins are enabled with Google and Facebook accounts,
giving users the ability to register their own restaurants and 
menus, which can be edited or deleted only by the user who entered 
them into the database.

## How to use

With the files located in the same directory:

   1. Navigate to that directory with the command line
   2. Type `python database_setup.py` to initialize the database.  
   3. Type `python lotsofmenus.py` to populate the database with 
restaurants and menu items (Optional).  
   4. Type `python project.py` to run the Flask web server. 
   5. In your browser visit http://localhost:5000 to view the
restaurant menu app.  

You should be able to view, add, edit, and delete menu items and 
restaurants.

### A note on client secrets

Client secrets were used in this project to allow for secure user 
logins. The files containing client secrets have not been included 
as a part of the Github repository, for security purposes.  This 
may impact functionality, and users are asked to notify the author 
if they encounter such issues.