# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.
Install Docker if you don't have it. 

From the root of the project, in your terminal, run `docker -` and `docker-compose -v`, to ensure you have installed Docker correctly. You'll see version numbers for each if you've installed Docker correctly. You

Run `docker-compose up` and wait!

Check to see if your database is running by going to `http://localhost:3000/api/ping` in your browser.

If everything is working properly, you’ll be able to create a new user on `http://localhost:3001/register`

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
