# CI/CD Tools and Practices – GitHub Action Workflows

This directory contains all **GitHub Actions workflows** created for the **CI/CD Tools and Practices Final Project**.

These workflows are responsible for automating the **Continuous Integration (CI)** part of the pipeline, including:

- ✅ Linting the source code
- 🧪 Running unit tests
- 🔁 Triggering actions on push, pull request or manual dispatch

Workflows are defined using YAML and are automatically executed by GitHub when specified conditions are met.

All workflows in this folder support the CI portion of the full CI/CD pipeline, which is later extended with **Tekton** and **OpenShift** for Continuous Delivery.