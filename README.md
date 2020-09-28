# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Intro and Purpose:

This project describes the MVC (model-view-controller) based photo-sharing website using Ruby-on-Rails with SQLite database and deploying into an Amazon EC2 instance.
The objective of this project is to get hands on experience in creating a photo-site application in Ruby on Rails, creating and using a Docker Container, deploying Ruby on Rails system into Docker Container and Docker Container to an EC2 (AWS) instance.

•	Creating Photo-site Application
•	Create and use Docker container, deploy Ruby on Rails system into this Docker Container.
•	Deploy using the Docker Container to an EC2 (AWS) instance.

We start the with creating of three models- User, Photo, Comment.
Migration files are updated to create tables in database and Controller is created to get the data from database. Create controllers and views that implement two URLs.

Following URLs are created:
1.	localhost:3000/user/index - displays a list of all users in the database.
2.	localhost:3000/user/photo/id – return a web page displaying all of the photos belonging to that user.
