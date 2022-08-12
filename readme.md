# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Ensure that [Docker](https://docs.docker.com/get-docker/) is installed. You can verify your installation with the following commands:

```
$ docker -v
$ docker-compose -v
```

Launch the docker environment with `docker-compose up`.

Check that everything is up and running by pointing your browser to the following urls:

http://localhost:3000/api/ping (backend)

http://localhost:3001 (frontend)