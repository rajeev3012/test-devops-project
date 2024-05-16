A simple devOps project



Project Overview
This project involves creating a simple web application using Python Flask, containerizing it with Docker, and deploying it through a Jenkins CI/CD pipeline. Git is used for version control, and Ansible can optionally be used for configuration management.

Steps
Flask Application

Set up a basic Flask web application with a simple "Hello, World!" endpoint.
Docker Containerization

Create a Dockerfile to containerize the Flask application.
Build and run the Docker container to ensure the application works inside the container.
Version Control with Git

Initialize a Git repository.
Commit the project files and push them to a GitHub repository.
CI/CD Pipeline with Jenkins

Set up Jenkins and create a pipeline job.
Configure the pipeline script to:
Clone the GitHub repository.
Build the Docker image.
Run the Docker container.
Optional: Configuration Management with Ansible

Create an Ansible playbook to ensure Docker is installed, pull the latest Docker image, and run the container on target servers.
