# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
  changes to read me to test push to github was successful

PROCESS
Rails new todo  
Bundle install
Git init
Ls- a
git remote add origin https://github.com/TMWcodes/TO_DO_APP.git
Git push --set-upstream origin main
git push -f origin main

- rails g scaffold list description:string completed:boolean
  invoke active_record
  create db/migrate/20220220132130_create_lists.rb
  create app/models/list.rb
  invoke test_unit
  create test/models/list_test.rb
  create test/fixtures/lists.yml
  invoke resource_route
  route resources :lists
  invoke scaffold_controller
  create app/controllers/lists_controller.rb
  invoke erb
  create app/views/lists
  create app/views/lists/index.html.erb
  create app/views/lists/edit.html.erb
  create app/views/lists/show.html.erb
  create app/views/lists/new.html.erb
  create app/views/lists/\_form.html.erb
  create app/views/lists/\_list.html.erb
  invoke resource_route
  invoke test_unit
  create test/controllers/lists_controller_test.rb
  create test/system/lists_test.rb
  invoke helper
  create app/helpers/lists_helper.rb
  invoke test_unit
  invoke jbuilder
  create app/views/lists/index.json.jbuilder
  create app/views/lists/show.json.jbuilder
  create app/views/lists/\_list.json.jbuilder

t.boolean :completed, default: false #make boolean false by default.

      rails db:migrate

\*\*bootstrap
gem 'bootstrap', '~> 5.1.3'
@import "bootstrap"; to bootstraply.css.scss or application.css
made javascripts and application.js file added
[require jquery3
require popper
require bootstrap-sprockets]

    added class="container" to div surrounding yield

    added rubocop gem and rspec --init
    added rspec rails
    added simplecov

\*\*changed database to postgres
update postgresql_adapter

config - database.yml

bin/rails db:create
Created database 'mydb_development'
Created database 'mydb_test'

== 20220227132631 CreateLists: migrating ======================================
-- create_table(:lists)
-> 0.0112s
== 20220227132631 CreateLists: migrated (0.0112s) =============================

if conflict use 'rake db:reset'

changed to gem 'tzinfo-data', '>= 1.2021.5'
bundle install - rails db:migrate frozen : rake db:migrate frozen.
cannot connect to localhost:3000

22/07
node v16.13.0
Rails 7.0.2.2
Yarn 1.22.15
SQLite version 3.8.7.2 2014-11-18 20:57:56
Ruby 3.1.0p0 (2021-12-25 revision fb4df44d16) [x64-mingw-ucrt]
