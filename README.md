# OpenShift CI/CD Final Project

## Project Name

OpenShift CI/CD Pipeline with GitHub Actions and Tekton

## Project Description

This project demonstrates the implementation of a complete CI/CD pipeline for a sample application using GitHub Actions, Tekton, and OpenShift.

The project automates important stages of the software development lifecycle, including code validation, linting, unit testing, task execution, and application deployment on an OpenShift cluster.

## Technologies Used

- GitHub
- GitHub Actions
- OpenShift
- Tekton Pipelines
- Python
- flake8
- nose
- YAML
- CI/CD

## CI/CD Workflow

The project uses GitHub Actions to automate continuous integration activities.

The workflow includes:

1. Source code checkout
2. Dependency installation
3. Code linting using flake8
4. Running unit tests using nose
5. Reporting the workflow results

## Tekton Pipeline

Tekton is used to define and execute pipeline tasks on OpenShift.

The Tekton tasks include:

- Cleanup task
- Unit testing task
- Application build and deployment tasks

## OpenShift Deployment

The application is deployed on an OpenShift cluster using the configured CI/CD pipeline.

The project includes OpenShift resources such as:

- PersistentVolumeClaim
- Tekton Tasks
- Tekton Pipeline
- Application deployment

## Project Structure

```text
OpenShift-CI-CD-Final-Project/
│
├── README.md
│
├── .github/
│   └── workflows/
│       └── workflow.yml
│
└── .tekton/
    └── tasks.yml
