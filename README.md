# Load Balancing with NGINX and Docker

This repository demonstrates how to implement load balancing for a Golang application using NGINX and Docker.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup Instructions](#setup-instructions)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Build and Run the Docker Containers](#2-build-and-run-the-docker-containers)
  - [3. Access the Application](#3-access-the-application)
- [Testing the Load Balancer](#testing-the-load-balancer)
- [Conclusion](#conclusion)

## Introduction

This project sets up a simple Golang application with multiple instances, using NGINX as a load balancer to distribute incoming requests. Docker is used to containerize the application and manage the services.

## Prerequisites

Before running this project, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Setup Instructions

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/anamul94/load-balancing.git
cd load-balancing
```

### 2. Build and Run the Docker Containers

Use Docker Compose to build and run the Docker containers:

```bash
docker-compose up -build
```

The application will be accessible at http://localhost:8000.
