# README

# esbuild setup steps
 - https://blog.dennisokeeffe.com/blog/2022-02-19-rails-7-using-react-with-esbuild?utm_campaign=Den%20Dribbles%20Weekly%20Newletter&utm_medium=email&utm_source=Revue%20newsletter
 
## Create React App
create rails app using `rails new myapp -d postgresql -j esbuild --skip-test --skip-bundle`

## Make some folders and files for our React application
`mkdir app/javascript/components`
`touch app/javascript/components/application.tsx`

## Add in our React dependencies
`yarn add react react-dom`

## Create a basic components controller
`bin/rails g controller components index`

## Start the server - we use `bin/dev` instead of `bin/rails s`
`bin/dev`




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
