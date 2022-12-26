# PHP MVC STRUCTURE

## Table of Contents

1. [Introduction](#introduction)
   - What is MVC?
   - Why use MVC?
2. [Application structure](#application-structure)
   - Controllers
   - Models
   - Views
3. [How MVC works](#how-mvc-works)
   - User interacts with the view
   - View sends request to the controller
   - Controller updates the model
   - Model updates the view
4. [Conclusion](#conclusion)
   - Recap of MVC
   - Benefits of using MVC

Model-View-Controller (MVC) is a software design pattern that separates the different components of a web application into three distinct parts:

## Model

The model is responsible for managing the data of the application and performing any necessary logic to manipulate that data.

## View

The view is responsible for displaying the data to the user and handling any user input.

## Controller

The controller is responsible for coordinating the interactions between the model and the view, and for handling user requests.

## Routing

To use the MVC pattern in your application, you would typically create a router that maps URLs to controller actions. When a user requests a URL, the router determines which controller action to execute and passes the request to the appropriate controller. The controller then handles the request, updates the model as needed, and renders the appropriate view template to the user.

## Controllers

Controllers handle user requests and coordinate the interactions between the model and the view. They update the model as needed and render the appropriate view template to the user.

## Models

Models manage the data of the application and perform any necessary logic to manipulate that data.

## Views

Views display the data to the user and handle any user input.

## Conclusion

The MVC pattern helps to make web applications more maintainable and extensible by allowing developers to work on different parts of the application separately. The model handles the data, the view handles the user interface, and the controller handles the interactions between the two.


