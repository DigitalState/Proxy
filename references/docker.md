# Docker

The DigitalState Proxy microservice docker information.

## Table of Contents

- [Environment Variables](#environment-variables)

## Environment Variables

| Name | Description | Default |
| :--- | :---------- | :------ |
| `COMPOSE_PROJECT_NAME` | The docker-compose project name. This is used to properly namespace docker containers in the event where you are running multiple instances of the platform on the same machine. | `dsproxy` |
| `DIRECTORY` | The base directory the docker-compose files are located. This is used to properly configure the base directory for DockerForWindows and DockerForMac based machines. | `.` |
| `PORT` | The published port of the proxy container. | `443` |
| `UI_PORT` | The published port of the proxy ui container. | `444` |
| `DISCOVERY_TOKEN` | The acl http token. This value is used by the proxy container to synchronize with the discovery services catalog. | `` |
