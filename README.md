Student Registration Web Application

This is a simple Student Registration Web Application made using Java Servlet, JSP, Maven, and Tomcat.

The project takes student details from a form and shows the submitted information on another page.

What this project does

The user enters:

Name
Email
Course
Age

After clicking the Register button, the data goes to the Servlet. The Servlet processes the data and sends it to the result JSP page.

Technologies Used
Java
JSP
Servlet
Maven
Apache Tomcat
HTML
Project Structure
servlet-jsp-student-registration
│
├── pom.xml
│
└── src
    └── main
        ├── java
        │   └── com
        │       └── servlet
        │           └── HelloServlet.java
        │
        └── webapp
            ├── student.jsp
            └── result.jsp
How it works
Student Form
     ↓
student.jsp
     ↓
HelloServlet
     ↓
Process Student Data
     ↓
result.jsp
     ↓
Show Student Details
How to Run

First, make sure you have:

JDK 17
Maven
Apache Tomcat 11

Build the project using:

mvn clean package

After building, you will get:

target/servlet.war

Copy this .war file into the webapps folder of Tomcat.

Then start Tomcat and open:

http://localhost:8080/servlet/student.jsp
What I Learned

From this project, I learned:

How JSP works
How Servlet and JSP work together
How to take data from an HTML/JSP form
How to send data from Servlet to JSP
How to use Expression Language (EL)
How to create a Maven web project
How to deploy a Java web application on Tomcat
Author

Mahendra Jangid
