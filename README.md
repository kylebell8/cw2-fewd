# Fewd Coursework 1 
<br>
Name: Kyle Bell<br>
E-mail: kbell209@caledonian.ac.uk<br>
Student Number: S1911702<br>

This is the Practical coursework submission for Front-End Web Development, it's a single-page recipe application that allows a user to filter various recipes, view them, review them, and add the ingredients to a shopping list or the recipe to a menu. The application is also hosted on Heroku via the link https://cw1-test.herokuapp.com/ . This application may take a while to run, and sometimes, it takes a couple of seconds for the recipes to be gathered and displayed from the database. 

## Functionality
As previously mentioned, the application primarily revolves around creating a single-page application, mostly made with React, to view and manipulate different food recipes.

In terms of functionality in relation to the specification the app includes the ability to:
* Filter recipes based on allergens
* Search and filter recipes based on their name
* Search and filter recipes based on their ingredients
* Add a recipe to the menu
* Add the recipe's ingredients shopping list
* Add reviews to a recipe

## How To Run
### Install

Initially, the application must be cloned via the repository https://github.com/kylebell8/fewdcw1

After this has been cloned, you will install the packages relevant to the application. First, there are the necessary backend packages, this is installed via the command "npm install" in the root directory.

After the backend packages have been installed, the frontend folder must be navigated into via the command "cd frontend", and then "npm install" must be run again to install the respective packages for the frontend.

Finally, for general ease with the next steps in running the application, simply use the command "cd .." to navigate back to the root folder.

### Running the app

In order to run the app, there are a few extra steps and commands to run. 

Initially the Backend must be initialised, this is done with the command "node index" within the root folder of the application. On completion, in the terminal, you will see some output similar below.

{ filename: 'recipe.db', autoload: true }
recipe connected to [object Object]
Server listening on 3001

Then you must launch the frontend, either by right-clicking the frontend and clicking "Open in Integrated Terminal" or by simply opening another instance of the terminal and navigating to frontend via "cd frontend", then run the app via entering the command "npm start".

Finally, you will now see there is a database running on port 3001, and a react app running on 3000, to use the application simply use the URL http://localhost:3000/

## Reflection & Considerations
Despite the application being finished, there is a couple of considerations for improvements in the future:

* A Register and Sign in system to give each user  a unique experience with them having their own corresponding menus and shopping lists tied to their accounts
* In general, more interactivity with the  database such as actively modifying data in the backend would allow for extra functionality such as adding recipes or editing recipes
* The ability to remove items from the menu & shopping list without having to navigate from other tabs to re-render the page
* The ability to view the nutrition based on each ingredient within the recipe alone, as opposed to the nutrition details of the recipe as a whole

## Deployment 
The live application can be accessed via this line:<br />
https://fewdpracticalcw.herokuapp.com/<br />