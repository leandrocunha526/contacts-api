# Contacts API Ruby on Rails

Rails is a web-application framework that includes everything needed to create database-backed web applications according to the Model-View-Controller (MVC) pattern.

**NOTE: Use podman-compose.yml (podman-compose) to use the versions of Ruby and PostgreSQL (Docker registry) compatible with this application (Debian Buster is an LTS version and from next year it will be ELTS supported by Frexian).**

## Installation guide

[Install Rails guide](http://guides.railsgirls.com/install)

## Setting to execute

Install dependencies:

`bundle install`

Database create

`rails db:create`

**Warning: don't forget to configure the `config/database.yml` file according to the your database settings.**

Database migration

`rails db:migrate`

Running

`rails server`

## Requirements

- API use Rails 5.2.5 version
- Ruby 2.5.5
- API use PostgreSQL as database

## Docs

- [API Ruby on Rails 5.2.5 version](https://api.rubyonrails.org/v5.2.5/)
- [PostgreSQL 11 version](https://www.postgresql.org/docs/11/index.html)
- [Authentication with Devise guide](http://guides.railsgirls.com/guides-ptbr/devise)
- [Rails Girls App Tutorial](http://guides.railsgirls.com/)
- [Jbuilder](https://github.com/rails/jbuilder)
- [Sprint](https://github.com/rails/spring)
- [Ruby on Rails guide 5.2 version](https://guides.rubyonrails.org/v5.2/)
- [Ruby Gems guide](https://guides.rubygems.org/)
