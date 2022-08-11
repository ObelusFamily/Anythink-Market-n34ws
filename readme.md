# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Docker here https://docs.docker.com/desktop/install/mac-install/

2. Check your Docker version by navigating to the root of the main branch and running docker -v and docker-compose -v

    If this returns version you're set if not please reinstall docker

3. Run docker-compose up from the project root directory to start the docker container

4. Once Docker displays that the container is running navigate to your browser and go to http://localhost:3000/api/ping. If you receive the message `pong` that's good

5. Next go to http://localhost:3001/register and register a user.

## If you ever need to to start the container use `docker-compose up` in the project root directory and run commands with `docker exec`
