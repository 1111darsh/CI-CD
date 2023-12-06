#  CI/CD Pipeline using Jenkins

## Overview
This repository contains a basic Continuous Integration/Continuous Deployment (CI/CD) pipeline implemented using Jenkins. The pipeline automates the process of fetching code from a Git repository, building it, running tests, and deploying it.

## Jenkins Pipeline Configuration
The CI/CD pipeline is configured using a Jenkinsfile, which defines the stages and steps of the pipeline. The pipeline stages include:
- **Checkout**: Fetching code from the configured Git repository.
- **Build**: Compiling the application and generating build artifacts.
- **Test**: Executing automated tests to verify code functionality.
- **Deploy**: Deploying the application to the target environment.
