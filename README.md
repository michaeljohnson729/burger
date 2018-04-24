# Eat-Da-Burger!

This is a full stack web application built using the MVC model. It includes MySQL database integration with JAWSDB when deployed on Heroku and integration for a localhost if not accessed via the Heroku deployed site. MySQL integration allows for persistant data in the event of multiple visits to the site. The database connected to this application has example data preloaded. Below is a brief overview of the application's functionality followed by instuctions for installing it onto a local machine if needed.

Heroku Deployed Site: https://burgersapphw.herokuapp.com/
# Functionality

# ![screenshot of app](/public/assets/img/screenshot.png)

When the user visits the page, they are presented with two lists of "burgers" and an input section that can accept new burgers and place them on the "Burgers to Eat" list. When a user wants to "devour" a burger, they can press the "Devour" button to the right of the burger they'd like to "devour." The screenshot below shows an example of what happens when a user presses the "Devour" button for the "Bacon Swiss" burger.

# ![screenshot of app2](/public/assets/img/screenshot2.png)

As you can see in the screenshot above, the "Bacon Swiss" burger moved from the "Burgers to Eat" list to the "Burgers Eaten." 

Adding a burger to the list is easy. In the following screenshots, you can see what happens when a user adds a "Veggie" burger to the list.

# ![screenshot of app3](/public/assets/img/screenshot3.png)
# ![screenshot of app4](/public/assets/img/screenshot4.png)

The "Veggie" burger is now on the "Burgers to Eat" list and ready to devour!

# Installation (if not on Heroku deployed site)

This app requires Node.js and the dependencies body-parser, express, express-handlebars, and mysql. To install these dependencies, first make sure you have node.js installed on your machine and then:
1. Open the "burgers" folder in terminal
2. Type the following command to install the dependencies: npm i

Now that the dependencies have been installed, you can run the application by typing the following command: node server.js

# ![screenshot of app5](/public/assets/img/screenshot5.png)

Now navigate to http://localhost:8080 using any browser and you're up and running and ready to devour some burgers!
