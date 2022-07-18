# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Before you run the application for the first time, ensure you have `docker` and `docker-compose` installed by running `docker -v` and `docker-compose -v`. If you don't have them installed yet, go to [the docker website](https://docs.docker.com/get-docker/) to install the latest version.

Once you have Docker installed, to run the app for the first time using Docker, navigate on your terminal to the root folder of the project and run the `docker-compose up` command.

After the `docker-compose up` command is done running, you should be able to ping the back-end by visiting [http://localhost:3000/api/ping](http://localhost:3000/api/ping) to confirm that the back-end is running.

After you've confirmed that the back-end is running correctly, you can go to [http://localhost:3001/register](http://localhost:3001/register) to open the front-end of the application and create a test user.
