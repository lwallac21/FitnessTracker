# FitnessTracker

## Description

In this **Fitness Tracker** application, I used node, Mongo db, express, and mongoose to create a way to store a users fitness information. When a user gets on to the webpage, an api call is made to display the date and some of the totals of the previous workouts information. Then, a user can click on "New Workout" to fill out a form to be added to the database in mongo db. Multiple exercises may be added to a single workout, which is handled in the fitnessRoutes js file. When the user checks the dashboard, the front end makes an api call, and the back end runs a find all function to send data that can be rendered by the front end JavaScript. 

## More information
Mongoose proved to be a powerful tool for operating the Mongo DB queries, the syntax of the latter is difficult for me to remember. I am getting pretty good at the server files. Not sure what the morgan npm package was for though. 