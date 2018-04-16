# Rails5 Boilerplate

This is starter application template for Ruby on Rails 5.2 - upgraded from the following:

![Rails5 Boilerplate Top Page](https://raw.githubusercontent.com/takp/rails5-boilerplate/master/app/assets/images/rails5-top-page.png "Rails5 Boilerplate")

## Versions

- Rails 5.2.0

## Features

- [Ruby on Rails](http://rubyonrails.org/)
- [SQLite3](https://sqlite.org/index.html)
- [Bootstrap 4.1.0](https://rubygems.org/gems/bootstrap)
- [FontAwesome](https://github.com/FortAwesome/font-awesome-sass)
- [Slim Template Engine](http://slim-lang.com/)
- [Rspec](https://github.com/rspec/rspec-rails)
- [Devise](https://github.com/plataformatec/devise)
- [ActiveDecorator](https://github.com/amatsuda/active_decorator)

## Architecture

MVC + Service + Decorator

- Models: app/models
- Views: app/views
- Controllers: app/controllers
- Services: app/services
- Decorators: app/decorators

## Quick Start

```
$ git clone git@github.com:maxgrok/rails5-boilerplate.git
$ cd rails5-boilerplate
$ bundle install
```
### Database 
```
$ rake db:create
$ rake db:migrate
```

### Configurations

```
cp config/database.yml.sample config/database.yml
```

Input your database credentials into `config/database.yml` file.

```
default: &default
  development: &default
  adapter: sqlite3
  database: db/development.sqlite3
  pool: 5
  timeout: 5000
```

### Run

After finish the database configuration,

```
$ bin/rails server
```

and go to [http://localhost:3000/](http://localhost:3000/).


## How to run the test suite

```
$ bundle exec rspec
```

## Deployment instructions
