# Spring Boot + Angular 8: CRUD example

In this tutorial, I will show you how to build a full-stack (Spring Boot + Angular 8) example with a CRUD Application. The back-end server uses Spring Boot, Spring Data for REST APIs, front-end side is an Angular 8 App with HttpClient and Form Module.

The Tutorial Application in that:
- Tutorial has id, title, description, published status.
- User can create, retrieve, update, delete Tutorials.
- There is a search box for finding Tutorials by title.

Add an object:

![spring-boot-angular-8-crud-example-create-tutorial](spring-boot-angular-8-crud-example-create-tutorial.png)

Retrieve all objects:

![spring-boot-angular-8-crud-example](spring-boot-angular-8-crud-example.png)

Click on **Edit** button to go to a Tutorial page:

![spring-boot-angular-8-crud-example-retrieve-tutorial](spring-boot-angular-8-crud-example-retrieve-tutorial.png)

On this Page, you can:

- change status to *Published* using **Publish** button
- delete the Tutorial using **Delete** button
- update the Tutorial details with **Update** button

![spring-boot-angular-8-crud-example-update-tutorial](spring-boot-angular-8-crud-example-update-tutorial.png)

Search Tutorials by title:

![spring-boot-angular-8-crud-example-search-tutorial](spring-boot-angular-8-crud-example-search-tutorial.png)

## Angular 8 & Spring Boot CRUD Architecture
This is the application architecture we will build:

![spring-boot-angular-8-crud-example-architecture](spring-boot-angular-8-crud-example-architecture.png)

- Spring Boot exports REST Apis using Spring Web MVC & interacts with embedded Database using Spring Data JPA.
- Angular Client sends HTTP Requests and retrieve HTTP Responses using axios, shows data on the components. We also use Angular Router for navigating to pages.

## Video
This is our Angular Spring Boot CRUD application demo and brief instruction, running with MySQL database:

[![Angular Spring Boot CRUD application demo](http://img.youtube.com/vi/K8mV6XWA_EY/0.jpg)](http://www.youtube.com/watch?v=K8mV6XWA_EY "Angular Spring Boot CRUD application demo")

In the video, we use Angular 10, but it has the same logic & UI as Angular version 8 and H2 database in this tutorial.

Tutorial link: [Spring Boot + Angular 8: CRUD example](https://www.bezkoder.com/angular-spring-boot-crud//)

More Practice:
> [Angular 8 + Spring Boot + MySQL](https://www.bezkoder.com/angular-spring-boot-mysql/)

> [Angular 8 + Spring Boot + PostgreSQL](https://www.bezkoder.com/angular-spring-boot-postgresql/)

> [Angular 8 + Spring Boot + MongoDB](https://www.bezkoder.com/angular-spring-boot-mongodb/)

> [Angular 8 + Spring Boot: File Upload example](https://www.bezkoder.com/angular-spring-boot-file-upload/)

Security:
> [Angular 8 + Spring Boot: JWT Authentication & Authorization example](https://www.bezkoder.com/angular-spring-boot-jwt-auth/)
