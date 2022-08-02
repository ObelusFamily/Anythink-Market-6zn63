# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Installation for Windows users:

Step 1: Install Docker Desktop for Windows
Step 2: After installing it open any terminal (except wsl), and write docker --version or docker -v
to check if docker is installed and working.
Step 3: Go to the project folder and go inside the backend directory and then run the "docker-compose up" command.
Step 4: now point your browser to http://localhost:3000/api/ping

## For WSL users:

Step 1: Similar to windows users go to the website and install Docker Desktop for Windows
Step 2: now go to docker desktop settings and under resources tab you will find WSL integration
Step 3: click on WSL integration and you will find your WSL distro enable the one you will be using for running docker
Step 4: for those people who can't find any of their WSL distro go to powershell
Step 5: in powershell write "wsl -l" and you will see the list of your distros
Step 6: it may be working but the problem would be that it is not WSL 2, they might be WSL only. To Switch to WSL 2 write command "wsl --set-version <distro name> 2" and run it.
Step 7: Now go back to WSL integration and you will see the list of your distros.
Step 8: enable it and then run command "docker -v" in your wsl terminal.
