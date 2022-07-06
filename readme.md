# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

run 'docker-compose up' from the project root directory to load Anythink's backend and frontend.
The backend will start listening on port 3000 and the frontend will start listening on port 3001.

- Test backend url - http://localhost:3000/api/ping
- Test frontend url - http://localhost:3001/register

You'll be able to create new user on the frontend test url.
You can also use 'docker exec' to run commands on a running container.
