2024-01-17
1812
Review : Part 1 ,2 ,and 3 : Get Started, Add a Controller, and Add a View)

Overview:

MVC, which stands for Model-View-Controller, is a widely employed design pattern in software development aimed at structuring code to enhance separation of concerns and foster modularity. 
This pattern comprises three primary components:

Model:  This component embodies the application's data and business logic, taking on the responsibility of 
		handling and overseeing the data while also informing observers, typically views, of any alterations.

View:   The View is the part of the software that shows things to the user and lets them interact. It takes data from the program and makes it 
		user-friendly. It also informs the rest of the program about user actions.

Controller: The Controller is like a middle person between the user interface (View) and the brain of the software (Model). 
			It takes what the user does, thinks about it, and then tells the Model to change if needed. Finally, it updates the View to show any changes.




2024-01-18
1335
Review : 4th Part : Add a Model)

OverView: The Model in ASP.NET Core MVC is like the brain of the app, managing data and how it's used. Adding a model involves creating structures for what the app deals with. These models handle 
database communication, user input, and connections between different parts of the app. The DataType attribute on something like ReleaseDate helps users by allowing them to enter only the 
date, not the time, and when displayed, only the date shows up.




2024-02-08
1823

OverView :

	You faced SQL errors and had to rebuild the project. The migration file "20240208185139_InitialCreate" captures the initial database structure. Working with a database means efficiently managing
data, using a Database Management System (e.g., MySQL), and "seeding" the database involves adding initial data for testing or default values.


Review : 6th Part : controller methods and views)

Controllers manage the app's logic by handling input, interacting with the model (database), and displaying views. Views serve as the presentation layer using HTML, CSS, and sometimes JavaScript.
Controller actions are methods that process user requests, manage data, and connect the user interface with the data layer. This separation ensures a clear structure: controllers handle logic, 
views handle presentation, and they communicate to provide the final HTML output to the user's browser.



Review : 7th and 8th Part : Add a Search and A new File)

OverView:

Add Search:
Enables users to find specific information.
Involves creating a search form for user input, processing it on the backend to fetch relevant data from the database, and displaying results to the user.

Add a New Field:
Involves modifying the database schema to include a new column or attribute.
Requires updates to the application's codebase to handle the new field, including modifications to forms, database queries, and views.

Example: Adding a "description" field to a product table or a "birthdate" field to a user profile.



Review: 9th and 10th Part : Add validation and Examine Details and Delete )

OverView: 

Adding Validation:
Ensures user-entered data meets specific criteria before saving to the database.
Includes checking for required fields, validating input formats (e.g., emails), ensuring data falls within certain ranges, and preventing malicious input (like SQL injection).
Maintains data integrity and prevents storage of erroneous or incorrect data.

Examine Details and Delete:
Allows users to view detailed information about a record on a dedicated "details" page.
Users can delete records, often through a "delete" button, permanently removing them from the database. Implementing confirmation dialogs or safeguards is crucial to prevent accidental deletions.
