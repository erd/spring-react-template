# Spring React Template

This template project shows how to setup a web application with a Spring
Boot backend and React frontend. Rather than have two apps and serve APIs
with CORS, this template project builds the frontend as a webjar and adds
it as a dependency of the backend.

## Build and Run

Build the app by running:

    ./gradle assemble

Start the app by running:

    java -jar backend/build/libs/backend.jar
