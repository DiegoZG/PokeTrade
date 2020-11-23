# PokeTrade 
A website that allows you to show off your Pokemon card collection and set up a trade with other users through the Trade forum!

Flatiron School's module 2 project by Diego Zegarra and Esther Kang

## Project Details
- This project was made with Ruby on Rails and the CSS framework, Bulma. 
- With password protected log-in and log-out functionality, you can access other user's profiles, which showcases their Pokemon card collection, and a trade forum that allows you to post about a trade request or event. 

Video Demo link: https://vimeo.com/437194426

This application gathers its Pokemon Card data from the API: https://pokemontcg.io/

## Installation Instructions
1. Clone repository to your computer.
2. Run `bundle install` to install required Gems.
3. Run `rake db:migrate` to migrate the schema.
4. Run `rails db:seed` to add Pokemon Cards.
5. Run `rails s` to start the server.
6. In your web browser, enter https://localhost:3000 to start the application

Installed gems include:
- `gem 'better_errors', '~> 2.7', '>= 2.7.1'` (Must be in placed in `group :development`)
- `gem "bulma-rails", "~> 0.9.0"`
- `gem 'bulma_form_builder', '~> 0.1.1'`
- `gem 'simple_form', '~> 5.0', '>= 5.0.2'`
- `gem 'rest-client'`
- `gem 'json'`
- `gem "pry"`
