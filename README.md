# Datero data platform
Homepage for issues tracking &amp; discussions.

Datero is a containerized application that is shipped as a single Docker image.
It consists of three major parts:
- Datero engine
- Backend (Python client + REST API)
- Web UI

Some of these parts are open-source, while others are proprietary.
The open-source parts include Datero engine, python client and documentation.
The proprietary parts include web application and backend services.

All platform functionality is available through the python client.
Backend services are just a wrapper around the python client and act as a bridge between the client and the web application.
They also provide additional functionality like authentication and authorization.

The purpose of this repository is to provide a central place for tracking issues and discussions related to the Datero platform.
You are welcome to open new issues, ask questions, or provide feedback.

## Docker images
- Datero: https://hub.docker.com/r/chumaky/datero
- Datero engine: https://hub.docker.com/r/chumaky/datero_engine
- repository: https://github.com/chumaky/docker-images

## Documentation
- website: https://datero.tech/docs
- repository: https://github.com/chumaky/datero-docs

## Python client
- repository: https://github.com/chumaky/datero-python-client

## Postgres FDW specification
Datero is based on the PostgreSQL database with added set of FDW extensions.
The YAML specification of these extensions is available in the following repository:

- repository: https://github.com/chumaky/postgres-fdw-spec


## Releases
Details about the latest releases can be found in the [TBD: releases] section of this repository.



Thank you for your interest in Datero!

Datero Team.