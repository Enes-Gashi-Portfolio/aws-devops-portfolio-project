# AWS DevOps Portfolio Project

## Overview

This project demonstrates a production-style DevOps workflow using AWS, Terraform, Docker, GitHub Actions, Linux, and GitHub.

The goal is to showcase how infrastructure and application deployments can be automated through Infrastructure as Code (IaC) and CI/CD pipelines.

## Technologies Used

- AWS
- Terraform
- Docker
- GitHub Actions
- Git & GitHub
- Linux
- IAM

## Architecture

The deployment workflow follows:

```text
Developer Push
      |
GitHub Actions
      |
Terraform
      |
AWS Infrastructure
      |
Docker Deployment
      |
Running Application
```

## Project Goals

- Provision AWS infrastructure using Terraform
- Containerize applications with Docker
- Automate deployments with GitHub Actions
- Demonstrate Linux administration and troubleshooting
- Follow Infrastructure as Code best practices

## Repository Structure

.
├── docs/
├── terraform/
├── .github/
│   └── workflows/
└── README.md
```
