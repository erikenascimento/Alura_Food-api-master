This is the backend files for the API to the repository: https://github.com/erikenascimento/Alura-Food

The API will require docker, the version utilized by me was:
Docker version: 27.1.0, build 6312585

Then it will be necessary to run the commands:

docker-compose build
docker-compose up

you may need to run those commands with admin privilege depending on the way your docker is configured locally

if everything works correctly, the development server should be up using the door 8000.
to access it, simply type: localhost:8000 on your browser

There is information on how to use the api in the manAPI.md file in this repository.
