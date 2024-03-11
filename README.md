# Tasks

- Implement a mechanism for verifying a registered user's email;
- Limit the number of requests to your contact routes. Be sure to limit the speed of creating contacts for the user;
- Enable CORS for your REST API;
- Implement the ability to update the user's avatar. Use the Cloudinary service;

## General requirements

- All environment variables should be stored in the .env file. There should be no sensitive data in the "pure" form inside the code;
- Docker Compose is used to run all services and databases in the application;

## Additional task

- Implement a caching mechanism using the Redis database. Cache the current user during authorization;
- Implement a password reset mechanism for the REST API application;
