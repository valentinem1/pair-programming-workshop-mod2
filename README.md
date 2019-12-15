# README
The goal is to create a Restaurant model, view, and controller. 

##Create a model
In the terminal, run

`rails g model Restaurant name city state postal_code street_address`

##Create a controller
In the terminal, run
`rails g controller restaurants index show`

##Migrate and seed
The controller generator also generates view pages for us. The final step is to run,
`rails db:migrate`
`rails db:seed`