# Backend project template

## Overview

Project template to quickly start development on new projects. 

## Tech stack

* PHP 7.4
* Symfony 5.0.5
* Docker
* Github Actions

## Quickstart

* Install Docker: `curl -sSL https://get.docker.com/ | sh`. If you are on Windows, make sure you shared the working drive with Docker.
* Install Docker Compose: `curl -L "https://github.com/docker/compose/releases/download/1.17.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose`. If you are on Windows, docker-compose comes with the msi package.
* Start containers: `docker-compose up -d --build`

## Notes

* The API runs on port `<your-port>` by default.
* Documentation is available on `http://localhost:<your-port>/api/documentation`.
