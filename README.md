# Cookbook Recipes - By Juliet Gardener

**Third Milestone Project: Data Centric Development - Code Institute**

This is an online recipe cookbook database web application, specifically designed for users to easily access, store, edit and 
update cooking recipes.

## Demo

A live demo can be found [here](https://raw.githubusercontent.com/julietisstudent/Milestone-Project-3/master/static/images/images.png)

## UX

My goal in the design was to create a user friendly recipe storage web application, that was built for simplicity allowing all necessary 
user functions that were inline with CRUD operations. To help start the design of the cookbook I wireframed 
![alt text](https://raw.githubusercontent.com/julietisstudent/Milestone-Project-3/master/static/images/Wireframes%20Pic.jpg)
layouts to create some ideas.

## Technologies

* HTML5
    * The structure for site
* CSS 
    * The style format for the site
* Materialize (0.100.2)
    * Modern responsive framework for site
* jQuery 
     * To manipulate the Document Object Model
* JavaScript
     * To create interactive data design
* Python
     * To create and develop the web application
* Flask
     * The microframework used for python
* MongoDB
     * For the document-oriented database

## Features

The site features the Navbar from Materialize with an extra javasript function added, that creates a responsive collapsible effect 
for use on multiple browsers and devices.

## Testing

The site was tested by inputing data recipes into the frontend web application, I then checked to see if the information fired through
to the backend database MongoDB.Atlas and vice versa.
All of the CRUD operations on the web application were checked through trial and data input.
The site was also tested across multiple browers and mobile devices to ensure responsiveness.
Chrome developer tools was used against the site to check compatibility.

## Deployment

The site has been deployed onto the Heroku platform. Version control was maintained by pushing new commits to the
repository for each new updated piece of functionality using git and github.

## Credits

### Content
The contents of the site were written by me 

### Media
The image used on this site was obtained from
[here](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbRtAK2DU4-0BpYfMHhJl5v335qI6UI6FrGFcVRo2jaNoYj_QlmQ).

### Acknowledgements
The information for recipes for the site and database were taken from
[here](https://www.absolute-croatia.com/cookbook/item/croatian-pumpkin-soup), and 
[here](https://en.wikibooks.org/wiki/Cookbook:Chicken_Tikka_Masala), and
[here](https://www.fantasy-ireland.com/Irish-dessert-recipe.html).

The icons used for the application were taken from this [site](https://material.io/tools/icons/?style=baseline).

The media query for the collapsible responsive navbar was taken from this [site](http://archives.materializecss.com/0.100.2/navbar.html).

The backend document database storage used was registered with this [site](https://www.mongodb.com/cloud/atlas).
