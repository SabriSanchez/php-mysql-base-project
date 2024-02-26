# php-mysql-base-project
Base scaffolding for a PHP + MySQL + Bootstrap project with Docker containers

## Dependencies
1. Docker
2. Compose

## How to develop
1. Put all your PHP files in the www directory
2. If you need an initial database structure, put you DDL and SQL into the /docker/mysql/init-db.sql
3. You will find the Bootstrap js file into the /www/js directory and the Bootstrap css file into the /www/css directory that you will need to include accordingly in your webpages

## How to run it
- In the root directory run the command "docker-compose up --build -d" to run and install all needed dependencies (the first time will take longer)

## How to stop the servers when your are done
- docker-compose down

## URL
- Web: http://localhost:8080/
- MySQL database: localhost:3306/test_database
- MySQL credentials: See docker-compose.yml file
