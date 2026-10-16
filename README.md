# OpsNext AI Platform

A learning-focused, production-style self-hosted AI platform
built with Ollama, Open WebUI, Docker, AWS, and DevSecOps practices.

## Objectives

- Deploy and operate a self-hosted LLM.
- Build a GitHub-based CI/CD pipeline.
- Apply DevSecOps controls to the software delivery lifecycle.
- Automate AWS infrastructure with Terraform.
- Implement monitoring, alerting, backup, and recovery procedures.
- Measure AI inference performance and infrastructure utilization.

## Architecture

Ollama provides local model inference.
Open WebUI provides the web interface.
Docker Compose manages application services.
Nginx provides the HTTPS reverse proxy.
AWS hosts the deployment.

## Environments

- Development: local development and validation.
- Staging: integration tests and deployment verification.
- Production: approved and validated releases.

## Security Principles

- Do not commit credentials or production secrets.
- Do not expose the Ollama API directly to the internet.
- Restrict administrative access using least privilege.
- Validate changes before production deployment.
- Test backup restoration and deployment rollback.

## Project Status

Phase 0: repository foundation.
Subsequent phases will add deployment, CI/CD, security,
infrastructure automation, and observability.

## Learning Approach

Every implementation phase includes its purpose, commands,
validation steps, failure scenarios, and documentation.
