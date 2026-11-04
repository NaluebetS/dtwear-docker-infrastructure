
# DTwear — Docker Infrastructure

**Academic Team Project | 2025**

## Project Overview

DTwear is a university team project involving an e-commerce website built with WordPress and a MySQL database.

My main responsibility was preparing the Docker Compose configuration used to run and connect the application services.

## My Role

- Worked on the Docker Compose configuration for the project.
- Configured WordPress and MySQL service settings.
- Set up service dependencies and persistent storage volumes.
- Helped prepare the containerized environment for team development and integration.

## Technologies Used

- Docker
- Docker Compose
- WordPress
- MySQL

## Infrastructure Overview

The project uses two main services:

1. **WordPress** — Runs the e-commerce website.
2. **MySQL** — Stores application and website data.

Docker Compose defines the services and their configuration so they can run together in a containerized environment.

### Architecture

    User / Browser
          |
          v
    +-------------+
    |  WordPress  |
    |  Container  |
    +-------------+
          |
          v
    +-------------+
    |    MySQL    |
    |  Container  |
    +-------------+
          |
          v
    Persistent Storage

*Simplified diagram of the application and database services.*

## Implementation

My Docker Compose work focused on:

- Defining the WordPress and MySQL services.
- Configuring environment variables and service connections.
- Setting up volumes for persistent data.
- Managing container dependencies.

## Validation

The project was developed collaboratively as part of a university course.

Configuration files and supporting testing evidence will be added after review.

## My Contribution vs. Team Work

My individual contribution focused on Docker Compose and container infrastructure.

Website design, WordPress content, and other application features were handled collaboratively by the team.

## Project Status

Academic project. Documentation is available in this repository, with sanitized configuration files to be added.

## Security Note

Real passwords, database credentials, environment files containing secrets, and private deployment information are not published.

## Project Status

**Academic Team Project | Documentation-Based Portfolio**

This repository documents my contribution to the Docker Compose infrastructure of the DTwear e-commerce project.

My responsibilities included configuring WordPress and MySQL services, managing service dependencies, and setting up persistent storage.

The original source code is not included in this repository. The project is presented through technical documentation and information from the academic project report.

## Available Evidence

- Academic project report (subject to publication permission)
- Docker Compose architecture explanation
- Documentation of my individual responsibilities

**Note:** This repository is intended to showcase my academic infrastructure experience, not to provide a reproducible application deployment.
