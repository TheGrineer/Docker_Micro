##Project Online Ordering Project

Microservices With Docker

Develop an application using a microservices architecture and the key to design and \
integrate the microservices that'll make up this application is to learn \
how to use your Docker skills to Dockerize a microservices-based application.

Microservices With Docker.
Develop an application using a microservices architecture and \
the key to design and integrate the microservices that'll make up this application is to \ 
learn how to use your Docker skills to Dockerize a microservices-based application.

Target:
Describe the benefits of using Docker to develop microservices-based applications.
Describe how to use Docker Compose to define the services that makeup a microservices-based application.

Approach should be :
Use a multi-stage Dockerfile to create Docker images for development and production.
Use a Dockerfile to create a container for a Node/Express API application.
Use a Compose service to control the creation and startup of a Node/Express API application container
Use a .env file to define variables to avoid hard-coding configuration values in a docker-compose.yml file
Use the COMPOSE_PROJECT_NAME variable to configure the Compose project name to customize the Docker item name prefix
Use a wait-for script to detect when a container is started and ready to accept connections
Use the Compose networks option to configure custom networks to prevent unintended access between microservices
Use a Dockerfile to create a container for a React application created by the Create React App tooling
Use a Compose service to control the creation and startup of a React application container created by the Create React App tooling.

Flow diag.

├── backend
│   ├── catalog-management
│   ├── customer-support
│   └── order-processing
└── frontend

