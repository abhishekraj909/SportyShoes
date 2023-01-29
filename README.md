# SportyShoes.com
<img alt = "Home Screen" src = "https://github.com/abhishekraj909/SportyShoes/blob/main/Homepage.png">

## General Info

This is a Full Stack Developer - Backened Project.

# Description

### Project objective:
Sporty Shoes is a company that manufactures and sells sports shoes. They have a walk-in store, and now, they wish to launch their e-commerce portal sportyshoes.com.
You’re asked to develop a prototype of the application. It will be then presented to the relevant stakeholders for budget approval. Your manager has set up a meeting where you’re asked to do the following:

* Presenting the specification document which has the product’s capabilities, appearance, and user interactions
* Setting up Git and GitHub account to store and track your enhancements of the prototype 
* Explaining the Java concepts used in the project 
* Discussing the generic features of the product:
* There will be an admin to manage the website. An administrator login will be required to access the admin page. 

 
 
The admin should be able to change his password if he wants, he should be able to:

* Manage the products in the store including categorizing them
* Browse the list of users who have signed up and be able to search users
* See purchase reports filtered by date and category
     
The goal of the company is to deliver a high-end quality product as early as possible. 

## File Structure

```
src
├── main
│   ├── java
│   │   └── com
│   │       └── cisco
│   │           └── sportyShoes
│   │               |   └──SportyShoesApplication.java
|   |               |
│   │               ├── controller
│   │               │   └── CommomController.java
│   │               │  
│   │               ├── dao
│   │               │   ├── OrderDao.java
│   │               │   └── ShoesDao.java
|   |               |   └── UsersDao.java
|   |               |
│   │               ├── exception
│   │               │   └── GlobalExceptionHandeler.java
|   |               |
│   │               ├── model
│   │               │   ├── OrderedShoeModel.java
│   │               │   └── ShoesDataModel.java
|   |               |   └── UserInfoModel.java
|   |               |
│   │               ├── service
│   │               │   ├── OrderService.java
│   │               │   └── ShoesService.java
|   |               |   └── UsersService.java
|   |               
│   │             
│   │                 
│   └── resources
│       └── application.properties
└── main
    ├── webapp
           └── WEB-INF
                   └── View
                   |     └── .jsp (All file)
                   └── style.css



## Technologies Used

| Java 19 |
| ------ |
| Spring Boot |
| Eclipse  |
| MySql |
