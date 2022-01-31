# Rails Engine

[Rails Engine](https://backend.turing.edu/module3/projects/rails_engine/) is a Ruby on Rails application designed by [Turing School of Software and Design](turing.io). This is the frontend application, which is designed to make calls to the paired backend API and display relevant information about merchants, items, transactions, and invoices to the user. The backend application can be located [here](https://github.com/AlexMMcConnell/rails-engine).

## Versions

- Rails 5.2.6
- Ruby 2.7.2

## Setup

- Clone this repository and run the following commands:
- `$ bundle exec rails db:create`
- `$ bundle exec rails db:migrate`
- `$ bundle exec rake csv_import:destroy_data`
- `$ bundle exec rake csv_import:seed_data`
- Run this application using `rails s` while the backend application is also running.

## Testing
`$ bundle exec rspec`

