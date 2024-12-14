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


## Check for Understanding

1. Define CRUD.
    > CRUD is a series of essential functionalities that are used to manage data.  It stands for Create, Read, Update, and Delete.

2. Define MVC.
   > MVC stands for Model, View, and Controller, and is a design pattern that seperates a project into three more managable components.  The model manages the logic that users work with, aka the CRUD operations. The view is responsible for rendering data in a specific format. The controller receives user input and interprets it to update the model and the view.

3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
    > To get the app to respond to a GET request you will need the task_controller.rb and the routes.rb files.

4. What are params? Where do they come from?
    > `params` is an object that is returned from the ActionController::Parameters and `params[:id]` retrieves the value at the key `id` of the params.  This object contains the controller, action, and id of the api call being made.

5. What is the purpose of a serializer?
   > A serializer is used to format the results of a POST call so specific data is dispalyed in a specific way. 