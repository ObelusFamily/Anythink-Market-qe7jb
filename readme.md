# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
Make sure you have 
- Docker
- Git

Open terminal. Go to where the repo is placed.
Run the command `docker-compose -v` to verify Docker is installed
Then run the command `docker-compose up`

Now the backend and frontend will start up on respertively;
Backend `http://localhost:3000/api/ping`
Frontend `http://localhost:3001/register`

Create a new user here.


**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
