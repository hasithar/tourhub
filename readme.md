# Intelligent Tour Hub

## Overview

This repository contains the setup and configuration for the Intelligent Tour Hub project, which includes the main application and its associated microservices. The project is designed to offer a comprehensive solution for managing inbound tours, utilizing various microservices and Docker for a seamless development and deployment process.

## Repository Structure

- **`api-gateway/`**: Contains the configuration and code for the API gateway, which routes requests to various microservices.

- **`services/`**: Contains individual microservices, including:

- **`accommodation-service/`**: Manages accommodation-related data and operations.

- **`activity-service/`**: Manages activity-related data and operations.

- **`docker-compose.yml`**: Defines the Docker configuration for the entire project, including the API gateway and microservices.

- **`.env`**: Environment variables for the project. This file should be configured with appropriate values for local development.

## Setup and Development

1. **Clone the Repository**: Clone the repository to your local machine using the following command:

`git clone `

2. **Configure Environment Variables**: Set up environment variables by editing the `.env` file in the root directory. Ensure that the environment variables are correctly defined for local development and Docker usage.

3. **Docker Setup**:

- Build and run the Docker containers using:

`docker-compose up --build`

- To rebuild and start containers, use:

`docker-compose up --build`

- To stop the running containers, use:

`docker-compose down`

4. **Testing**:

- Ensure that the appropriate environment variables are set up.

- Run unit tests and integration tests using the test commands defined in the individual microservice repositories or by configuring test scripts in Docker.

## Directory-Specific Information

- **`api-gateway/`**: Contains configurations for routing requests to the microservices. Ensure that all API endpoints are correctly defined and that services are properly connected.

- **`services/`**: Each service folder contains its own `Dockerfile` and configuration. Services are defined with their respective ports and dependencies in the `docker-compose.yml` file.

## Git Management

- **`.gitignore`**: Specifies files and directories to be ignored by Git.

## Contributions

Contributions to the project are welcome. Please ensure that you follow the contribution guidelines and submit pull requests with detailed descriptions of changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please contact [your email address or contact information].
