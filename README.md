# Self Hosted DevOps Platform

A fully self-hosted DevOps platform built using Docker.

## Tech Stack

- Gitea (Git Server)
- Drone CI (CI/CD pipelines)
- Docker
- Portainer (container management)

## Architecture

Developer → Gitea → Drone CI → Docker build pipeline

## Features

- Self hosted Git server
- OAuth integration with CI
- Automated build pipelines
- Containerized services with Docker

## Run Locally

Clone the repo:

git clone https://github.com/YOUR_USERNAME/self-hosted-devops-platform

Start the platform:

docker-compose up -d
