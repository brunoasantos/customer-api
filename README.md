# Customer API

Basic API to manage Customers using **Rails**, **PostgreSQL** and **Grape**.

## Technologies

* Ruby 2.3.0
* Rails 4.2.5.1
* PostgreSQL 9.3
* Grape 0.14.0

## Setup

Install gems

`bundle install`

Create a `.env` based on `.env.sample` and change the values to match your database.

Prepare database

`rake db:setup`

## Running

`rails server`

## Usage

See [http://docs.brunocustomerapi.apiary.io](http://docs.brunocustomerapi.apiary.io)

Alternatevely, you can access the documentation using Swagger UI pointing to `/api/v1/swagger_doc`
