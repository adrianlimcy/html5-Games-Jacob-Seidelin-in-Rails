# README

An example made from the book HTML5 Games

1. rails new jewel_warrior
2. add gems & bundle
- gem 'dotenv-rails', require: 'dotenv/rails-now'
- gem "slim"
- gem "slim-rails", :require => false
3. bundle
4. rails secret
5. put .env in gitignore
6. rails g controller home index
7. root 'home#index', as: 'home_index', via: :all
