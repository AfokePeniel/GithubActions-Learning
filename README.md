# GitHub Actions Learning Project

This project is designed to demonstrate various features and capabilities of GitHub Actions for learning purposes. It includes several example workflows that showcase different aspects of GitHub Actions functionality.

## Workflows Overview

### 1. Action Secrets (`action_secrets.yml`)
Demonstrates the use of secrets in GitHub Actions.

### 2. Artifacts (`artifacts.yml`)
Shows how to create and use artifacts between jobs.

### 3. Custom Environment Variables (`custom_env_variables.yml`)
Illustrates the use of custom environment variables at both the workflow and job levels.

### 4. Default Environment Variables (`default_env_variables.yml`)
Displays the default environment variables provided by GitHub Actions across different operating systems.

### 5. Environments (`environments.yml`)
Demonstrates the use of environments in deployments, including environment-specific secrets.

### 6. Basic Workflow (`main.yml`)
A simple workflow template showing basic GitHub Actions structure.

### 7. Self-Hosted Runner (`runnerfile.yml`)
An example of using a self-hosted runner with specific labels.

## Key Concepts Demonstrated

- **Secrets Management**: Secure handling of sensitive information.
- **Artifact Handling**: Creating and sharing artifacts between jobs.
- **Environment Variables**: Using both custom and predefined variables.
- **Cross-Platform Compatibility**: Running jobs on Ubuntu, Windows, and macOS.
- **Deployment Environments**: Setting up and using deployment environments.
- **Self-Hosted Runners**: Configuring jobs to run on custom, self-hosted runners.

## Usage

To explore these workflows:

1. Clone this repository.
2. Navigate to the `.github/workflows` directory to view the workflow files.
3. Each workflow file (`*.yml`) contains comments explaining its purpose and functionality.
4. To trigger workflows manually, use the "Actions" tab in the GitHub repository and select "Run workflow" for workflows with the `workflow_dispatch` event.

## Learning Objectives

- Understand the structure and syntax of GitHub Actions workflows.
- Learn how to use various GitHub Actions features like secrets, artifacts, and environments.
- Explore different types of runners (GitHub-hosted and self-hosted).
- Practice creating and managing environment variables in workflows.

