# Students-Database-flask-
Creating students database system with flask framework and making CRUD operations. 
my Flask application has three View functions.

1.Submit form:
The first new_student() function is bound to a URL rule ('/enternew').It presents an HTML file that contains a student information form.

2.Add record:
As can be seen, the form data is published to the ‘/addrec’ URL of the binding addrec () function.

The addrec () function retrieves the form’s data through the POST method and inserts the student table.The message corresponding to the success or error in the insert operation will be rendered as ‘result.html’.
The HTML script for result.html contains an escape statement , which displays the result of the Insert operation.

3.List items:
The application contains another list () function represented by the ‘/list’ URL.It populates’rows’ as a Multidict object that contains all records in the student table.This object is passed to the list.html template.
Finally, the ‘/‘ URL rule renders ‘home.html’, which is the entry point of the application.
