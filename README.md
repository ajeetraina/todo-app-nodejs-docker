# Todo App with Node.js and Docker

![CI/CD](https://github.com/ajeetraina/todo-app-nodejs-docker/workflows/CI/CD/badge.svg)
![Security Scan](https://github.com/ajeetraina/todo-app-nodejs-docker/workflows/Security%20Scan/badge.svg)
[![Backend Coverage](./backend/coverage/badge.svg)](./backend/coverage/lcov-report/index.html)
[![Frontend Coverage](./frontend/coverage/badge.svg)](./frontend/coverage/lcov-report/index.html)

A full-featured Todo List application built with Node.js, Express, and React, fully containerized with Docker.

## Security and Testing

### Security Scans

We regularly perform security scans using multiple tools:
- Snyk for dependency vulnerability scanning
- Azure Container Scan for Docker image scanning
- Trivy for filesystem scanning
- npm audit for package vulnerabilities

Security scan results are available in the GitHub Actions tab under the 'Security Scan' workflow.

### Test Results

Test results and coverage reports are automatically generated and published:
- Coverage reports: Available in GitHub Actions artifacts
- Test results: Published as workflow artifacts
- Coverage badges: Updated automatically in README

View detailed security information in our [Security Policy](SECURITY.md).

## Features

- Create, Read, Update, and Delete todos
- Mark todos as complete/incomplete
- Filter todos by status
- Containerized application with Docker
- Comprehensive test coverage with Jest
- OpenAPI documentation
- GitHub Actions CI/CD pipeline
- Automated security scanning

[Rest of the README content remains the same...]