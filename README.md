# PHP MVC STRUCTURE

## Table of Contents

1. [Introduction](#introduction)
   - What is MVC?
   - Controllers
   - Models
   - Views
   - Routing

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

# Introduction {#introduction}

Model-View-Controller (MVC) is a software design pattern that separates the different components of a web application into three distinct parts:

1. Model
2. View
3. Controller

## 1. Model {#model}

The model is responsible for managing the data of the application and performing any necessary logic to manipulate that data.

## 2. View {#view}

The view is responsible for displaying the data to the user and handling any user input.

## 3. Controller {#controller}

The controller is responsible for coordinating the interactions between the model and the view, and for handling user requests.

## Routing {#routing}

To use the MVC pattern in your application, you would typically create a router that maps URLs to controller actions. When a user requests a URL, the router determines which controller action to execute and passes the request to the appropriate controller. The controller then handles the request, updates the model as needed, and renders the appropriate view template to the user.

## How MVC works {#how-mvc-works}

Here's a high-level overview of how the MVC pattern works:

1. The user interacts with the view, such as by clicking a button or filling out a form.
2. The view sends a request to the controller.
3. The controller processes the request and updates the model as needed.
4. The model updates the view with any new data.
5. The view is displayed to the user with the updated data.

## Conclusion

The MVC pattern helps to make web applications more maintainable and extensible by allowing developers to work on different parts of the application separately. The model handles the data, the view handles the user interface, and the controller handles the interactions between the two.


