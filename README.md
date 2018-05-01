# Burger

A full stack dynamic site. Model-View-Controller (MVC) application, uses (POST) to create a burger, (GET) to view list of burgers, (PUT) to eat burgers, (DELETE) to remove the burger once eaten. 

## Table of Contents
* [About App](#about-app)
* [Project Structure](#project-structure)
* [Techologies Used to Build App](#technologies-used-to-build-app)

## <a name="about-app"></a> About App 

Burger is a dynamic full stack application in which the user can place an order for a burger. When the user places an order in the form field, the order is added to the list of burgers on the left side. Each burger has a Devour me button, when clicked the burger moves from the left list to the right list. Once a burger is moved to the right side list the burger has been devoured. The burgers on the devoured list have a Throw away button, which when clicked deletes the burger from the MySQL database and the user interface.

## <a name="project-structure"></a> Project Structure

MVC
This application is designed with a (Model-View-Controller) pattern design. The MVC pattern separates an application into three main logical components: the model, the view, and the controller. Each component handles specific aspects used to develop the app.

* The View:
The view component is visible (in the user interface) to the user. The displays data from the applications's model. The contoller connection to the model allows the user interface to stay constant with any changes made to the model.

* The Controller:
The controller component controls data flow between the view and the model (serves as an intermediary between the the interface view and the model). The controller is an open communicator for changes made between the model and the user interface or view.

* The Model:
The model component manages data.When data is updated in the model the chages are communicated to the view through the controller connection. 

## <a name="technologies-used-to-build-app"></a> Techologies Used to Build App

Burger uses express for the backend web framework and ORM(Object Relational Mapping). Node and MySql query and route data in the application. Handlebars are used to templat the static HTML files.

The front end of Burger is build with static file such as: HTML, CSS, Javascript, and the Bootstarp templates.
