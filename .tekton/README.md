# CI/CD Tools and Practices – Tekton Workflows

This directory contains all **Tekton workflow definitions** created for the **CI/CD Tools and Practices Final Project**.

These Tekton resources define the **Continuous Delivery (CD)** portion of the pipeline and include:

- 🧩 **Tasks** for:
  - Linting
  - Unit testing
  - Building container images

- 🔗 **Pipelines** that orchestrate the tasks in the correct order

- ⚙️ **PipelineRuns** to trigger and test the pipeline execution

All YAML manifests are designed to run in an **OpenShift** cluster and are deployed via the OpenShift Pipelines (Tekton) engine. These Tekton components work together with GitHub Actions (CI) to enable a complete CI/CD workflow.
