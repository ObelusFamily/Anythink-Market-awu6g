# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker. Follow the instructions for your platform in [Docker's Documentation Page](https://docs.docker.com/engine/install/).
2. run `docker compose up` or `docker-compose up`. Depending on the version of Docker that you installed.
3. Test the backend by going to [http://localhost:3000/api/ping](http://localhost:3001/register). Make sure that your computer has access to the Internet, the ping endpoint also sends some requests over the Internet.
4. Test front end by navigating to [http://localhost:3001/register](http://localhost:3001/register).

If you manage to successfully complete all the steps you are ready to start working on specific tasks.
