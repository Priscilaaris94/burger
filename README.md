# Burger

A full stack dynamic site. Model-View-Controller (MVC) application, uses (POST) to create a burger, (GET) to view list of burgers, (PUT) to eat burgers, (DELETE) to remove the burger once eaten. 

## Table of contents
* [About app](#about-app)
* [Techologies used to build app](#technologies-used-to-build-app)

## <a name="about-app"></a> About app 

Burger is a dynamic full stack application in which the user can place an order for a burger. When the user places an order in the form field, the order is added to the list of burgers on the left side. Each burger has a Devour me button, when clicked the burger moves from the left list to the right list. Once a burger is moved to the right side list the burger has been devoured. The burgers on the devoured list have a Throw away button, which when clicked deletes the burger from the MySQL database and the user interface.

## <a name="technologies-used-to-build-app></a> Techologies used to build app

Burger uses express for the backend web framework and ORM(Object Relational Mapping). Node and MySql query and route data in the application. Handlebars are used to templat the static HTML files.

The front end of Burger is build with static file such as: HTML, CSS, Javascript, and the Bootstarp templates.
