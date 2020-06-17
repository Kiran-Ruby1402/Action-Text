# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version-2.7.1

* Rails Version-6.0.3.1

* Create new application with postgresql Database
  rails new ActionText -d=postgresql
  
* Setup Action Text
   rails action_text:install
   Above code will do the setup for action_text rich_text and the active_storage dynamically.
   
* Database creation
  rails db:create
  rails db:migrate

* Add has_rich_text :body in your model.

* Add input type as rich_text_area
  E.g. <%= form.rich_text_area :description %>

* run rails application rails s

Then check your form.

