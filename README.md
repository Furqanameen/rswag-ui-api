# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:
                                    # Gemfile
                                    gem 'rswag-api'
                                    gem 'rswag-ui'

                                    group :development, :test do
                                      gem 'rspec-rails'
                                      gem 'rswag-specs'
                                    end
                                    
                                    
                                    
                                    rails g rswag:api:install
                                      rails g rswag:ui:install
                                      RAILS_ENV=test rails g rswag:specs:install

                                      Create an integration spec to describe and test your API.

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
