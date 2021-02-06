# Vue.js + RoR on Docker

Vue.js (^3.0.0) & Ruby on Rails ((^6.0.0) & MySQL (8.0) development environment on Docker

# How to setup

Please exec:

`$ docker-compose up`

# Maintenance

If you want to run bundle install:

`$ docker-compose run web bundle install`

If you see this error `Webpacker configuration file not found`:

`$  docker-compose run backend rails webpacker:install`

If you see this error `ActiveRecord::NoDatabaseError`:

`$ docker-compose run backend rails db:create`