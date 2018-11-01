# Nextcloud

This repositroy includes a docker-compose.yml file which installs Nextcloud version 12 and MySQL as Docker containers.

## Prerequisites

* Docker should be installed

## Usage

By default, an admin user (named: Admin) is created with the following password: admin123.
You can change the default user and password by editing the .env file before running the docker-compose command.
Run the following command in order to start the containers: docker-compose up -d
When the containers are up & running, use the following URL: http://localhost:8080
