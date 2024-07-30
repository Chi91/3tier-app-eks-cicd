# Deployment of 3-Tier Application on Amazon EKS with CI/CD Pipeline

This project involves deploying a sample 3-tier web application on an Amazon Elastic Kubernetes Service (EKS) cluster using a CI/CD pipeline with GitHub Actions. The application consists of a backend built with .NET Core, a frontend built with HTML, CSS, and JavaScript, and a PostgreSQL database.

## Application Overview

The sample application includes the following components:

- **Backend Application**: Built with .NET Core.
- **Frontend Application**: Built with HTML, CSS, and JavaScript.
- **Database**: PostgreSQL.


## Prerequisites

- **Amazon EKS Cluster**: An EKS cluster set up and accessible.
- **kubectl**: Command-line tool installed and configured to interact with the Kubernetes cluster.
- **AWS CLI**: Installed and configured to interact with AWS services.
- **Docker**: Installed for building and pushing Docker images.
- **GitHub Actions**: Configured for CI/CD pipeline.
- **Source Code Repositories**: Access to the frontend and backend source code repositories.

## Set Up Docker Images

Build and push Docker images for the frontend and backend applications. Navigate to each repository and use Docker to build and push the images

## Configure GitHub Actions

Ensure that your GitHub Actions workflow is properly set up to build, test, and deploy the application. The workflow should include steps for:

- **Building Docker images**: Build the Docker images for both the frontend and backend applications.
- **Pushing Docker images to a container registry**: Push the built Docker images to a container registry.
- **Deploying the images to the EKS cluster using kubectl**: Deploy the Docker images to the Amazon EKS cluster using `kubectl`.



