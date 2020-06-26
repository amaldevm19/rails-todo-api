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

Open your current working directory in terminal
run #rails new appName --api --database=postgresql
create database in your postgres using pgdmin4 or run rails db:create - database name can found from config/database.yml development mode
postgres is the default user without password
modified route parameter from /todos to /api/todos using 
--resources :todos, defaults: {format: :json}, path: '/api/todos'--




