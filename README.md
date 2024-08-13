# Docker-Airflow-Demo

## Overview
Welcome to the Demo Docker with Airflow project. This repository is intended as a demonstration for setting up Docker with Apache Airflow for the first time.

## Getting Started
To get started with this project, follow these steps:

## Clone the Repository
```yaml
git clone https://github.com/Grittapop/Docker-Airflow-Demo.git
```
```yaml
cd Docker-Airflow-Demo
```

## Build and Start the Containers
```yaml
docker-compose up -d --build
```
This command will build new Docker images or update existing ones based on changes and start the containers in the background.

## Access Airflow
Once the containers are running, you can access the Airflow web interface at **http://localhost:8080**.

## Stop the Containers
To stop and remove the containers, run:
```yaml
docker-compose down
```

## Configuration
You can customize Airflow's configuration by editing the **airflow.cfg** file located in the airflow directory. To adjust Docker settings, modify the **docker-compose.yml** file.

## Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and passes all tests.

## References
- [Apache Airflow Docker Compose Documentation](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html)- Learn how to set up and configure Apache Airflow using Docker Compose.

 





