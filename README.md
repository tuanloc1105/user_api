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

Command that I used

```bash
rails generate --help
rails generate middleware RequestLogger
rails generate controller api/v1/users --api
rails db:migrate
rails generate model User name:string email:string age:integer
rails db:create
rails new user_api --api -d postgresql --skip-git
rails new user_api --api --skip-git
rails new user_api --api -d postgresql
gem install rails
```