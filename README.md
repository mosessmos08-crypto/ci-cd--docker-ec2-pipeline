# CI/CD Pipeline with Docker & AWS EC2

## Overview
End-to-end CI/CD pipeline for a Python application using Docker, GitHub Actions, and AWS EC2.

## Tech Stack
Python | Docker | GitHub Actions | AWS EC2

## Workflow
Code Push → GitHub Actions → Build Docker Image → Push to Docker Hub → Deploy on EC2 → Run Container

## Run Locally
docker build -t myapp .  
docker run -d -p 8000:8000 myapp  

## Access
http://<EC2-PUBLIC-IP>:8000  

## Features
- Dockerized Python application  
- Automated CI/CD pipeline  
- Docker image push to Docker Hub  
- Deployment on AWS EC2  

## Repository
https://github.com/mosessmos08-crypto/ci-cd-docker-ec2-pipeline
