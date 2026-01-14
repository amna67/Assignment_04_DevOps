DevOps Assignment 04 – Continuous Deployment Pipeline
📌 Overview

This repository implements a Continuous Deployment (CD) pipeline for a Dockerized static website. The pipeline automatically deploys the latest application version to Render whenever changes are successfully merged into the develop branch.

The solution builds upon the Continuous Integration (CI) setup from Assignment 03 and ensures a fully automated deployment process without manual intervention.

🎯 Objectives

Implement a Continuous Deployment pipeline using GitHub Actions

Automate deployment of a containerized static website

Ensure deployments are triggered only after successful CI execution

Integrate cloud deployment using Render

📖 Scenario

This project extends the CI pipeline developed in Assignment 03 into a complete CI/CD workflow.
Any successful merge into the develop branch triggers an automated deployment to Render, ensuring that the live application always reflects the latest stable changes.

Manual deployment is not performed after the initial setup, maintaining consistency and reliability across deployments.

🔄 Continuous Deployment Pipeline

The Continuous Deployment pipeline is designed to automate the delivery process from source code to a live environment.

Pipeline Behavior

Triggered automatically on successful merge into the develop branch

Uses the Docker image generated during the CI process

Deploys the latest version of the application to Render

Ensures reliable and repeatable deployments without manual steps

This approach minimizes human error and follows modern DevOps best practices for automated software delivery.

Notes 

This project demonstrates practical usage of GitHub Actions for automated deployment.

The CD pipeline ensures faster release cycles and consistent application delivery.