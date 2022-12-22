# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Routes
** List
rails routes --expanded

* Database
** Create a Migration Table
rails generate migration create_articles

** Run Migration
rails db:migrate

** Run Migration Rollback
rails db:rollback

* How to run the test suite

* Generating a migration, model, view, controller
rails generate scaffold Article title:string description:text

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Run
** Application
rails s
** Rails Console
rails c
