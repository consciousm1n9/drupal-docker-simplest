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

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/67773113/177889050-c1f8970b-bf3e-40f1-975c-46049422cb05.gif)
