# ConorAssign2
# Assignment 2 - Web API.

Name: Conor Carty

## Features.
-Authentication functionality was added
-A proxy router was added (package JSON)
-A Login page with a api route was added
-A Sign up page with a api route was added

## Setup requirements.

[ Outline any non-standard setup steps necessary to run your app locally after cloning the repo.]
The movies api folder needs to be running in the background, also so do mongo and mongod for the login to work.
- an env. file might also be requiered.

## API Configuration

NODE_ENV=development
PORT=8080
HOST=
MONGO_DB=(MongoURL)
SEED_DB=True
SECRET= (yoursecret)
REACT_APP_TMDB_KEY= (key goes here)

## API Design
Give an overview of your web API design,

- http://localhost:8080/api/movies | GET | Gets all movies
-http://localhost:8080/api/users?action=authenticate | POST | Authenticates the users



## Security and Authentication

The authentication/security implemented on the API using login and sign up. my favorites are protected.

## Integrating with React App

to login to the react app i opened a terminal in the movies api and used the npm dev run in the directory.