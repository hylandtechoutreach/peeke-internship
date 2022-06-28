# Environment Setup - Yellow Group
Follow these steps to ensure you have the proper setup to start working on the project.

## Things to Download and Install
You will want to download and install all of these things to begin.

- [VS Code](https://code.visualstudio.com/Download)
- [NodeJS](https://nodejs.org/en/download/)
- Git:
  - [Download for Mac](https://git-scm.com/downloads)
  - [Download for Windows](https://gitforwindows.org/)

## Running the Project
There are a few basic steps you'll want to follow to get the project up and running.

1. [Create a GitHub account](https://github.com/signup)
1. [Clone the UCT Locator repository locally](https://github.com/hylandtechoutreach/uct-locator)
  - Click the green "Code" dropdown button and copy the "HTTPS" URL
  - In VS Code, press `Ctrl`+`Shift`+`p` and enter "Git: Clone"
  - Select a folder, then open the folder
1. Follow the instructions on the GitHub Repository README
  - Make an account on MongoDB Atlas, and create a free DB
  - Create a file in the **back-end** folder named **.env**
  - Get the URI for the db, and paste it into the `MONGO_URI="<secret uri>"` area
  - On the next line, create a `SECRET_KEY="<secret key>"` with any value
  - Run the `npm install` command from the command line in the main folder

Once everything is properly setup, you should be able to run the front-end and back-end and see the app locally.