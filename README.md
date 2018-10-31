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

1. The browser issues a request for the /users url
2. Rails routes /users to the index action in the Users controller
3. The index action ask the user Model to retrieve all users.all
4. The user model pulls all the users from the data Base
5. The user model returns the list of users to the controller
6. The controller captures the users in the  @users variable, which is passed to the index view.
7. The view uses embedded Ruby to render the page as html
8. The controller passes the HTML back to the browser
