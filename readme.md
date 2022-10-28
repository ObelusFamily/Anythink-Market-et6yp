# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Make sure you have Docker installed and running.
2. Clone this repo
3. run `docker-compose up` and wait for the containers to be up.
4. on `localhost:3000` you have the backend
    * this could be check with the `http://localhost:3000/api/ping` api
5. on `localhost:3001` you have the frontend
    * you can visit `http://localhost:3001/register` to register a user.
