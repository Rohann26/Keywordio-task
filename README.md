# Keywordio-task

LIBRARY MANAGEMENT SYSTEM

About:
This File contains a single application Django based project for creating a library management system where multiple admin can signup/login and upload their respective books and are able to perform basic operations CRUD( create, read, update and delete) to their respective books and student can just view the books.

Technologies: 
Python, Django, HTML, CSS, Jinja, Bootstrap

Inside the Folder:
The project file is the “booklib” file which contains the basic configurations files of the project, the app file is named “library”.


About the app:

Models:
In the models file I have created table for the admin and a table for the books, where the admin will be a foreign key in the book entries.

Views:
In the Views file I have created all the views related to the admin functions and also the REST API function as well.


Addition Information:
	•	The basic local host url will take you to the homepage which the students can access in order to see all the books
	•	The home page will also have the option to login/signup as admin, once logged in you will get the option to perform the CRUD operation
	•	For calling the API functions please write ‘/api’ after the local host number and the respective function as mentioned in the controller urls 

Admin accounts created by me for testing are as follows:
	1)	email - admin1@gmail.com
      password - education
	2)	email - admin2@gmail.com
	    password- education

Superuser account created be me:
	username - admin
	password- education
	
	





