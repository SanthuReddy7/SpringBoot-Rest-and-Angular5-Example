Spring Boot : REST API with Angular5 frontend

Steps To Run The backened Code:-
Go to SpringBootAngularRest\src\main\java\com\springBootApplication
Right click on SpringBootAngularApplication.java

Select Run as Java Application 
When Spring boot started got to http://localhost:8080/api/customer

1.
TO Check the Post method is running got to the SoapUI/ Postman and use the below url 
http://localhost:8080/api/customer
and add below json format 


{
"fName":"any name",
"lName":"any name ",
"age":"24"
}
click on Submit request

You will see the status as ok 

2.

TO check the get method is running got to the SoapUI/ Postman and use the below url
http://localhost:8080/api/customer

3.

TO check the put method choose any id i.e if you want to edit details of any data take that id and put at the end of the url in postman/soap ui/ browser
EX:- http://localhost:8080/api/customer/1
and Insert in JSON data as 
{
"id":"1"
"fName":"any name",
"lName":"any name ",
"age":"24"
}

Now change any field in the above JSON and hit enter =>  data gets updated at the UI page.

4.
TO check the delete method choose any id i.e if you want to delete details of any data take that id and put at the end of the url in postman/soap ui/ browser
EX:- http://localhost:8080/api/customer/1

Hit enter and when you go to the UI page the data gets deleted.


 



UI:-

Go to UI directory and open the command prompt in the directory

Run Commamd: npm install
and after installing ng-Module 
run command:- npm start 
when the node server starts got to URL:- http://localhost:4200/angular/customer


Now you would see the web page. Please fill the fields and hit submit and go to customers tab to see the data 

Click on the Id to update or delete th data.


 



