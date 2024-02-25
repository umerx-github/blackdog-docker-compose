# blackdog-docker-compose

## Getting started

-   Clone the repository
-   Copy the `.env.example` file to `.env` and fill in the required environment variables.
-   If planning to use dev environment, you will also want to copy `dev/.env.example` to `dev/.env` and fill in the required environment variables.

## Running the application

-   `bash run.sh up` to start the application
-   `bash run.sh down` to stop the application

## Switching environments

-   The `run.sh` script will run in the `dev` environment by default.
-   To switch to the `prod` environment, run `ENVIROMENT=prod bash run.sh up` or `ENVIROMENT=prod bash run.sh down` to stop the application.
