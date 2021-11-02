Tools required

visual studio 2013
sql server 


Steps

1-Download the project code from https://github.com/samirasaeed/task
2- run the attached script on sql server (script.sql)
3-open the solution on the visual studio and run the api project
to get the url port for the api 
for example http://localhost:12229
4- You can test the API directly with a tool such as Postman 
Note : the collection file exists with the project 
5-Open Applicants.js file in the GUI project to replace the variable with the api url 

var apiPath = "http://localhost:12229";
 6- You can also start the application with CTRL+ F5

