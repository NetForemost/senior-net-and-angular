# .Net and Angular Test
The following explains the requirements of an app to assess the knowledge of an Angular and NET developer

Develop a web application that allows users to create and manage a to-do list.

# Backend specifications(.Net):
Esta prueba tiene como objetivo evaluar tu competencia en la construcción de una API en Ruby on Rails que consuma una API externa, almacene los datos obtenidos en una base de datos local PostgreSQL y permita a los usuarios recuperar la información almacenada.

  1.Create an api in .Net using some architecture.

  2.Create a database containing the following tables, this requires you to make use of migrations, you are free to use the database manager.

  Users: Id, FirstName(string), LastName(string), Email(string), Phone(string), CreatedAt(date), UpdatedAt(date)

  Priority: Id, Name(string)

  Tasks: Id, UserId, Title(string), Description(string), DueDate(date), Completed(bool), Deleted(bool), Tags(string), Id Priority, CreatedAt(date), UpdatedAt(date)

  - The api must have the following endpoints:

User
get: mydomain.com/api/user/{userId}

get: mydomain.com/api/user/{userId}

post: mydomain.com/api/user/user

Task:
get: mydomain.com/api/task/{userId}

post: mydomain.com/api/task

put: mydomain.com/api/task/{idTask}

delete: mydomain.com/api/task/{idTask}


- Add an apikey so that only apps with the apikey can make request to the api.

- Configure the cors so that only the Angular app can make request (optional).

- Create at least 2 unit tests.

# Frontend specifications (Angular):

This application must meet the following requirements:
The application must list all available users

- Clicking on any user must display the list of tasks corresponding to that user.

- Users must be able to create, edit and delete tasks.

- Tasks must have a title, a description and a due date, tags and priority level.

- Users should be able to mark tasks as completed.

- Tasks should be sorted by due date.

Routes: 
mydomain.com/
mydomain.com/user/{iduser}

- You must use a css library or framework.

Compliance with requirements: The application must meet all specified requirements.

- Code quality: The code must be well written and easy to maintain.

- Performance Efficiency: The application must be performance efficient.

- Integration of API Calls and Data Consumption

- Usability:The application should be easy to use for users.

- User Interface

- Security and Sensitive Data Handling

- Error handling

- Angular and .Net CLI Handling



# Questions

- Design Patterns(What is it? When should we use it?):
➡ ️What is Unit of Work Pattern?
➡ What is the Repository pattern?

- Explain to me the SOLID principle

- How to structure a .Net project using clean code in a Project?

- The best way to configure multiple languages in .NET?

- What is the difference between e2e, integration test and unit test?

- What strategies would you apply when having large numbers of records in the database to keep app performance optimal?

- Explain the difference between reactive forms and template-based forms.

- How to structure a scalable app in Angular?

- Do you know about abp framework?




