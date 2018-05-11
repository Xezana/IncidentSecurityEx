Spring boot coding test
Time: 45 min.

We want to create an incident management application.
•	Setup a new project. (5pts)
•	Create an Incident class. (10pts)
o	An incident has an id and a description. The id is the Incident identifier in the database.
o	id is an Integer, description is a String

•	Create an IncidentRepository to store and fetch the incidents. (20pts)
o	We assume here the use of an embedded hsqldb in memory database which will be created on startup, which is the default behavior of Spring boot.
o	Initialize the application with one incident in the database. (Create it on startup)

•	Integrate a service between the controller and the repository (5pts). 

•	Create a REST controller which will enable to create an incident, list the existing incidents, get an incident by its id, and delete an incident. (25pts)
o	For this exercise, we will skip the update method.
o	Standard HTTP verbs should be used.

•	Create a controller which will display all existing incidents on a web page (url : /) (20pts)
o	Incidents should appear in an HTML table
o	You can use either jsp or thymeleaf

•	Respect of standards of coding: (10pts)
•	Usage of git (5pts)

