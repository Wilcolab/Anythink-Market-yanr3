# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/)
2. Run `docker -v` and `docker-compose -v` to make sure docker is installed
3. Run `docker-compose up` from the project root directory 
4. Test it by pointing your browser to [http://localhost:3000/api/ping](ttp://localhost:3000/api/ping)
5. Test the frontend by accessing [http://localhost:3001/register](http://localhost:3001/register) and creating a new user
