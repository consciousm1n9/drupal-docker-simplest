# drupal-docker-simplest
The easiest setup to run Drupal project based on docker containers.

Features:
- Postgres 13.4
- Drupal 9.3.9
- Php 8.0 
- Nginx 1.21.1

Postgres: db, password and user is 'postgres'; The port '2030' is being outsourced to accept connections directly from your favorite Sql client software.
Nginx: The configuration file is externalized for easy customization in path: "nginx/conf/nginx.conf".

Requirements:
1. Docker running.

Quick start:
1. Clone this repository and move to where the docker-compose file is located.
2. Run the command: "docker-compose up".
3. Go to "localhost:8010" in the browser and set up your first Drupal project.
