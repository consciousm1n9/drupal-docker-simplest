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
1. Donwload or clone this repository and move where docker-compose file is locate.
2. Execute command: "docker-compose up". Wait for download and run images.
3. Go to "localhost:8010" in browser and set up your first Drupal project.



https://user-images.githubusercontent.com/67773113/165457122-1b8ce731-25c2-4821-8798-275b9dc44532.mp4



