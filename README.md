# Electrician Overseer - Backend (WIP)
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This is my very first own project made for job-seeking purpose. Electrician Overseer is the pet-project that allows me to use my Java (and Spring) and TypeScript (and Angular) knowledge to build a business app.
EO is an application that allows us to create, delete and manage workers in an electrician business company.

This is back-end part of a project (RESTful API)

Basic plan of functionality:
- Use SpringMVC architecture to create and manage electrician company buissness logic and cover it with tests.
- EO should allow to process data sent from front-end part so assigning workers to certain tasks and technical documentation to tasks and locations.
- EO should manage roles in company so allow to access diffrent functionalities for manager, diffrent for engineer, technician etc.
- EO should use SpringSECURITY to secure whole app.
- EO should store its data in cloud (as soon as I learn cloud technologies...)
	
## Technologies
Project is created with:
- JAVA 8
- Spring Framework
- SpringBoot
- JUnit5 & Mockito
- H2 and MySQL databases (I plan to migrate it to AWS)

## Live 

Soon...
	
## Setup
Once you have configured your project in your IDE you can build it from there. However if you prefer you can use maven from the command line. In that case you could be interested in this short list of commands:

- mvn compile: it will just compile the code of your application and tell you if there are errors
- mvn test: it will compile the code of your application and your tests. It will then run your tests (if you wrote any) and let you know if some fails
- mvn install: it will do everything mvn test does and then if everything looks file it will install the library or the application into your local maven repository (typically under /.m2). In this way you could use this library from other projects you want to build on the same machine
