

## Overview

This repo shows a basic example of using Cypress and Docker Compose to create simple end-to-end tests for any web application.

The File - Order_canceled_by_alexa_spec is not public enabled/available

Browser Firefox was used on Docker Compose File . ( you can change it if you need ) 

## Run end-to-end tests

Need to have:

Docker installed

(https://www.docker.com/products/docker-desktop)

Git clone the project


To execute the end-to-end tests for docker_cypress_alexa, enter the following commands:

```bash
cd e2e
docker-compose up --exit-code-from cypress
```

When the command completes, you will see test output on the console and a video of the test run will appear in the folder `e2e/cypress/integration/videos`.
