# OpenProject SalesPanthera Version installation with Docker Compose

## Install

Clone this repository:

    git clone git@github.com:jpmagido/openproject-deploy.git

Go to the compose folder: 

    cd openproject/compose

Make sure you are using the latest version of the Docker images:

    docker-compose pull

Copy the example `.env` file and edit any values you want to change:

    cp .env.example .env
    vim .env

## Docker Compose commands

    $ `docker-compose up -d`  
    $ `docker-compose down`

## Logs

    $ `docker-compose logs [image_id] -f`
