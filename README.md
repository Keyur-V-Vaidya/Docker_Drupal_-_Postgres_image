# Docker_Drupal_-_Postgres_image
Building Compose file for Multiple Container

using drupal image along with the postgres image

Exposing drupal on 8080 so thst we can localhost:8080

walk through drupal setup via browser

Setps to execute

Before importing the docker-compose file, make a seperate folder and pull the docker-compose.yml file there.

In terminal change directory to the folder where you have the docker-commpose.yml file

Before you execute the compose file, it is a good practice to inspect the drupal image to double check the configurations. 

fire up the following command
  docker-compose up

After this command it will show you the steps that how is creating the images and network

Type localhost:8080 in your browser url,

if you see drupal running there, congratulations it's working.
 
 
