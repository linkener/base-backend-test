# Linkener Senior Backend Developer Test

Welcome to the test for the position of Senior Backend Developer.

In this test we will ask you to create a RESTful microservice that registers readings coming from a fictional measuring device.  The definition of the service is defined in the [api.yaml](./api.yaml) file.  

***PLEASE NOTE*** the readings should reside in memory, no need to use a database.  We *will* be asking about JPA & JDBC in the interview though.


## Deliverables

A link to your git project where the source code resides.  The repository must have the pom.xml file required to build your project.

We will only build using `maven package` and nothing else.  The maven version is 3.5.2, java version is 8, if your solution is a war file, it should run on tomcat 9.  The output of maven package should be a runnable fat jar file or a self contained .war.

If maven builds a .jar file we will only run `java -jar yourproject.jar` and expect it to work as it is.

If maven builds a .war file we will copy it to a tomcat9 and expect it to work as it is.

Feel free to use the framework of your choice.  There is no time limit for the test.
 
## What we will evaluate

1) Clarity of your code, usage of SOLID principles.
2) Performance of your choice of algorithms and data structures.
3) Unit Tests.
