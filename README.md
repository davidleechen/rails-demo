# Rails Starter
This repo aims to provide a demonstration of a fast way to spin up Rails application development environments. It is meant to provide the
fastest, easiest way to get a new application ready to go on Rails 6.0 with the least amount of time spent configuring
a local development environment - for that, Docker containers used.

## How to use this repository
1. Install docker
1. Install docker-compose
1. Clone this repository
    ```shell script
    git clone git@github.com:davidleechen/rails-starter.git
    ```
1. Build the main container that houses the web application
    ```shell script
    docker-compose build
    ```
1. Setup application dependencies
    ```shell script
    docker-compose run web ./bin/setup
    ```
1. Run the Docker compose command to spin everything up
    ```shell script
    docker-compose up
    ```
1. Browse to http://localhost:3000

All done!
