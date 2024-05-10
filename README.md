# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: v3.3.0

* Rails version: v7.1.3

* System dependencies
  - PostgreSql v14.11

* Configuration
  - In the file `config/database.yml`, set user and password of the database

* Database creation
  - bundle exec rails db:create

* Database initialization
  - `bundle exec rails db:migrate`

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Initialize
  - `bundle exec rails s -p 3001`

* Api Doc
  - Generate: `bundle exec rswag:specs:swaggerize`
  - Access: `http://localhost3001/api-docs`
