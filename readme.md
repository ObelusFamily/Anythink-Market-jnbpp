# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Setting up a local environment with docker

1. Go to the official docker website: https://docs.docker.com/get-docker/
2. Select your operating system and install docker on your system.
3. After the installation is complete, open the docker application. (At this point, you can either skip/follow the tutorial provided in 
the docker app as per your convinience)
4. Open your terminal and run the commands docker -v and docker compose -v to check whether docker is running properly.
5. After ensuring that docker is working properly, navigate to the root directory of the anythink-market project and run the command 
docker compose up to create a comtainer. This will create anythink frontend and backend in your local system. 
6. Keep the processes running in the terminal and in your browser, naviogate to http://localhost:3000/api/ping
7. If a message shows up, this means that the local environment is setup and ready to be used.
8. To make sure that everything is working correctly, try creating a new user: http://localhost:3001/register/ If the new user is crated, 
the environment setup has been complete.
