# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To run the dev environment on your computer:
1. Execute `docker-compose up` 
2. Check the backend is running by visiting http://localhost:3000/api/_ping
3. Verify the frontend is working with the backend by creating a new user [here](http://localhost:3001/register).
