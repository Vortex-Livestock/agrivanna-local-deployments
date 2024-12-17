# Agrivanna Local Deployments

## Table of Contents

- [Contributors](#contributors)
- [Description](#description)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Quick Start](#quick-start)

## Contributors

- [Axel Sanchez](https://github.com/Axeloooo)

## Description

Agrivanna Local Deployments is a service that provides a platform for farmers to manage their farms, generate reports, and share data with other farmers.

## Tech Stack

![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)

## Setup

The following programs should be installed:

- [Docker](https://docs.docker.com/get-docker/)

## Quick Start

1. Clone the repository

```bash
$ git clone git@github.com:Vortex-Livestock/agrivanna-local-deployments.git
```

2. Change directory to the project folder

```bash
$ cd agrivanna-local-deployments
```

3. Run the application

```bash
$ docker compose -f docker-compose.dev.yaml up -d
```
