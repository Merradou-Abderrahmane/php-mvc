# PHP MVC STRUCTURE 

## Description

Model-View-Controller (MVC) is a software design pattern that separates the different components of a web application into three distinct parts:

#### 1.Model: The model is responsible for managing the data of the application and performing any necessary logic to manipulate that data.

#### 2.View: The view is responsible for displaying the data to the user and handling any user input.

#### 3.Controller: The controller is responsible for coordinating the interactions between the model and the view, and for handling user requests.

The MVC pattern helps to make web applications more maintainable and extensible by allowing developers to work on different parts of the application separately. The model handles the data, the view handles the user interface, and the controller handles the interactions between the two.

To use the MVC pattern in your application, you would typically create a router that maps URLs to controller actions. When a user requests a URL, the router determines which controller action to execute and passes the request to the appropriate controller. The controller then handles the request, updates the model as needed, and renders the appropriate view template to the user.