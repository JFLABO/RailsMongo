# RailsMongo

gem 'mongoid', '~> 6.0.0'

gem 'bson_ext'

bin/rails g mongoid:config

bin/rails g model Article --timestamps

再起動

bin/rails c
