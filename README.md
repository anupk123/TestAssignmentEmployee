# TestAssignmentEmployee

Due file size limitation,There are 4 zip files present for this project.Please extract these all.
WebApiInMVC_Part1.Zip file package contains database folder. In that folder there is database script.
Create a new database and Please execute it on database.this will create a table of employee.
After extracting all zip file htere 2 projects API and MVC.please change connection string in web.config 
file in API project. 
In API project is acts like a server in which api methods are written.
In MVC project is client one which will consume api.
Select API project as startup project.run this project. port on which it is running, copy this port into
MVC project there is static class called "GlobalClass".
Please change port number in line number 15 i.e.
WebApiClient.BaseAddress = new Uri("http://localhost:61014/api/Employees");
right now it is set to 61014. please change this.
Right click on solution explorer. go to properties.Select option multiple start up project.
Click option run in Action column.and run tihs solution. thanks!!!.
