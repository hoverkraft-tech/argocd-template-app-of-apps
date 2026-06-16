# ArgoCD App-of-Apps Repository

<div align="center">
  <img src=".github/logo.svg" width="60px" align="center" alt="Logo for ArgoCD template app-of-apps" />
</div>

---

![GitHub Verified Creator](https://img.shields.io/badge/GitHub-Verified%20Creator-4493F8?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJyZ2IoNjgsIDE0NywgMjQ4KSI+CiAgPHBhdGggZD0ibTkuNTg1LjUyLjkyOS42OGMuMTUzLjExMi4zMzEuMTg2LjUxOC4yMTVsMS4xMzguMTc1YTIuNjc4IDIuNjc4IDAgMCAxIDIuMjQgMi4yNGwuMTc0IDEuMTM5Yy4wMjkuMTg3LjEwMy4zNjUuMjE1LjUxOGwuNjguOTI4YTIuNjc3IDIuNjc3IDAgMCAxIDAgMy4xN2wtLjY4LjkyOGExLjE3NCAxLjE3NCAwIDAgMC0uMjE1LjUxOGwtLjE3NSAxLjEzOGEyLjY3OCAyLjY3OCAwIDAgMS0yLjI0MSAyLjI0MWwtMS4xMzguMTc1YTEuMTcgMS4xNyAwIDAgMC0uNTE4LjIxNWwtLjkyOC42OGEyLjY3NyAyLjY3NyAwIDAgMS0zLjE3IDBsLS45MjgtLjY4YTEuMTc0IDEuMTc0IDAgMCAwLS41MTgtLjIxNUwzLjgzIDE0LjQxYTIuNjc4IDIuNjc4IDAgMCAxLTIuMjQtMi4yNGwtLjE3NS0xLjEzOGExLjE3IDEuMTcgMCAwIDAtLjIxNS0uNTE4bC0uNjgtLjkyOGEyLjY3NyAyLjY3NyAwIDAgMSAwLTMuMTdsLjY4LS45MjhjLjExMi0uMTUzLjE4Ni0uMzMxLjIxNS0uNTE4bC4xNzUtMS4xNGEyLjY3OCAyLjY3OCAwIDAgMSAyLjI0LTIuMjRsMS4xMzktLjE3NWMuMTg3LS4wMjkuMzY1LS4xMDMuNTE4LS4yMTVsLjkyOC0uNjhhMi42NzcgMi42NzcgMCAwIDEgMy4xNyAwWk03LjMwMyAxLjcyOGwtLjkyNy42OGEyLjY3IDIuNjcgMCAwIDEtMS4xOC40ODlsLTEuMTM3LjE3NGExLjE3OSAxLjE3OSAwIDAgMC0uOTg3Ljk4N2wtLjE3NCAxLjEzNmEyLjY3NyAyLjY3NyAwIDAgMS0uNDg5IDEuMThsLS42OC45MjhhMS4xOCAxLjE4IDAgMCAwIDAgMS4zOTRsLjY4LjkyN2MuMjU2LjM0OC40MjQuNzUzLjQ4OSAxLjE4bC4xNzQgMS4xMzdjLjA3OC41MDkuNDc4LjkwOS45ODcuOTg3bDEuMTM2LjE3NGEyLjY3IDIuNjcgMCAwIDEgMS4xOC40ODlsLjkyOC42OGMuNDE0LjMwNS45NzkuMzA1IDEuMzk0IDBsLjkyNy0uNjhhMi42NyAyLjY3IDAgMCAxIDEuMTgtLjQ4OWwxLjEzNy0uMTc0YTEuMTggMS4xOCAwIDAgMCAuOTg3LS45ODdsLjE3NC0xLjEzNmEyLjY3IDIuNjcgMCAwIDEgLjQ4OS0xLjE4bC42OC0uOTI4YTEuMTc2IDEuMTc2IDAgMCAwIDAtMS4zOTRsLS42OC0uOTI3YTIuNjg2IDIuNjg2IDAgMCAxLS40ODktMS4xOGwtLjE3NC0xLjEzN2ExLjE3OSAxLjE3OSAwIDAgMC0uOTg3LS45ODdsLTEuMTM2LS4xNzRhMi42NzcgMi42NzcgMCAwIDEtMS4xOC0uNDg5bC0uOTI4LS42OGExLjE3NiAxLjE3NiAwIDAgMC0xLjM5NCAwWk0xMS4yOCA2Ljc4bC0zLjc1IDMuNzVhLjc1Ljc1IDAgMCAxLTEuMDYgMEw0LjcyIDguNzhhLjc1MS43NTEgMCAwIDEgLjAxOC0xLjA0Mi43NTEuNzUxIDAgMCAxIDEuMDQyLS4wMThMNyA4Ljk0bDMuMjItMy4yMmEuNzUxLjc1MSAwIDAgMSAxLjA0Mi4wMTguNzUxLjc1MSAwIDAgMSAuMDE4IDEuMDQyWiI+PC9wYXRoPgo8L3N2Zz4K)
[![Continuous Integration](https://github.com/hoverkraft-tech/argocd-template-app-of-apps/actions/workflows/__main-ci.yml/badge.svg)](https://github.com/hoverkraft-tech/argocd-template-app-of-apps/actions/workflows/__main-ci.yml)
[![GitHub tag](https://img.shields.io/github/tag/hoverkraft-tech/argocd-template-app-of-apps?include_prereleases=&sort=semver&color=blue)](https://github.com/hoverkraft-tech/argocd-template-app-of-apps/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

This repository serves as the **Single Source of Truth** for all applications and infrastructure components deployed via ArgoCD. It implements the "App-of-Apps" pattern, enabling a scalable and standardized approach to managing Kubernetes deployments across various environments (Review, Development, UAT, Production).

**Key Principles:**

*   **GitOps Driven:** All changes to the infrastructure and applications are made through Git, reviewed, and then automatically synchronized by ArgoCD.
*   **Immutable Deployments:** Configuration and application manifests are versioned and treated as immutable artifacts.
*   **Environment Parity:** Strives for consistency across all environments to minimize discrepancies and facilitate smooth promotions.
*   **Convention over Configuration:** Standardized folder structures and naming conventions simplify management and reduce errors.

---

## Table of Contents

- [ArgoCD App-of-Apps Repository](#argocd-app-of-apps-repository)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Project Structure](#project-structure)
  - [Deployment Workflow](#deployment-workflow)
  - [Adding a New Application](#adding-a-new-application)
    - [1. Prepare Application Helm Chart](#1-prepare-application-helm-chart)
    - [2. Create Application Manifests](#2-create-application-manifests)
  - [Contributing](#contributing)
  - [License](#license)

---

## Overview

This repository uses the ArgoCD App-of-Apps pattern to manage the deployment of all services. Instead of having a single `Application` resource for each deployed component, we have a hierarchy where a root `Application` (or `ApplicationSet`) manages other `Application` resources. This structure provides:

*   **Centralized Control:** All deployments are managed from a single Git repository.
*   **Scalability:** Easily add new applications and environments without modifying the core ArgoCD setup.
*   **Standardization:** Enforce consistent deployment practices across all applications.

Changes to this repository are **not** supposed to be modified by hand, but instead triggered by external CI workflows (e.g., GitHub Actions `workflow_dispatch` events) to maintain the GitOps principle.

## Project Structure

The repository is organized to clearly separate application definitions, environment-specific configurations, and shared components.

*   ### `appsets/`
    Contains ArgoCD `ApplicationSet` resources. These define how groups of applications are deployed across different environments.
    *   `01_commons.yaml`: Defines `Application` resources for common infrastructure components.
    *   `02_envs.yaml`: Defines `Application` resources for environment-specific deployments (dev, uat, prod).

*   ### `commons/`
    Houses common Kubernetes manifests and Helm chart values that are shared across multiple applications or environments. This promotes reusability and reduces duplication.

*   ### `dev/`
    Dedicated to the development environment.
    *   `1_manifests.yaml`: ArgoCD `Application` definitions for base infrastructure manifests specific to `dev`.
    *   `2_apps.yaml`: ArgoCD `Application` definitions for deploying applications in the `dev` environment.
    *   `apps/`: Contains ArgoCD `Application` resources for individual applications deployed in `dev`.
        *   `review-apps/`: Specific manifests for review applications, typically deployed for pull requests.
            *   `landing-page/template.yml.tpl`: Example template for a review application.
    *   `manifests/`: Raw Kubernetes manifests specific to the `dev` environment.
        *   `echo-server.yaml`: Example manifest for an `echo-server`.
        *   `review-apps/`: Raw manifests for review applications.
            *   `landing-page/template.yml.tpl`: Example raw manifest template for a review application.

*   ### `prod/`
    Contains configurations and application definitions for the User Acceptance Testing (UAT) and Production environments.
    *   `1_manifests.yaml`: ArgoCD `Application` definitions for base infrastructure manifests specific to `prod`.
    *   `2_apps.yaml`: ArgoCD `Application` definitions for deploying applications in `prod` (UAT and Production).
    *   `apps/`: Contains ArgoCD `Application` resources for individual applications deployed in `prod`.
        *   `production/`: Production environment specific application definitions.
            *   `landing-page/landing-page.yml`: Example production application definition.
        *   `uat/`: UAT environment specific application definitions.
            *   `landing-page/landing-page.yml`: Example UAT application definition.
    *   `manifests/`: Raw Kubernetes manifests specific to the `prod` environment.
        *   `production/`: Raw manifests for the production environment.
            *   `landing-page/landing-page.yml`: Example raw production manifest.
        *   `uat/`: Raw manifests for the UAT environment.
            *   `landing-page/landing-page.yml`: Example raw UAT manifest.

*   ### `tools/`
    Scripts or utilities used for managing the repository or interacting with the ArgoCD setup.

*   ### `values/`
    Helm value files used by applications deployed in various environments. These files override default chart values and contain environment-specific configurations.

## Deployment Workflow

The deployment process is entirely automated and follows the GitOps principles:

1.  **Code Change:** A developer commits changes to an application's source code repository.
2.  **CI Pipeline:** The application's CI pipeline builds a new Docker image and publishes a new Helm chart (e.g., to `ghcr.io`).
3.  **GitOps Update:** The CI pipeline then triggers an update to this `argocd-app-of-apps` repository, typically by updating an image tag or Helm chart version in the relevant `*.yml` or `*.tpl` files.
4.  **Pull Request (Optional but Recommended):** For critical changes, a pull request is opened against this repository, allowing for review and approval.
5.  **Merge:** Once the changes are merged into `main`, ArgoCD detects the divergence between the desired state (Git) and the actual state (Kubernetes cluster).
6.  **Synchronization:** ArgoCD automatically synchronizes the cluster to match the desired state defined in this repository, deploying the new application version or configuration.

## Adding a New Application

To add a new application to the ArgoCD App-of-Apps setup, follow these steps. Replace `[app-name]` with the kebab-cased name of your application (e.g., `my-new-service`).

### 1. Prepare Application Helm Chart

Ensure your application has a published Helm chart. If using OCI registries (e.g., `ghcr.io`), you might need to register it with ArgoCD.

```sh
argocd repo add ghcr.io/[your-org]/[app-name]/charts/application --type helm --name [app-name] --enable-oci --username 'username' --password 'token' --upsert
```

> **Note:** This `argocd repo add` command is typically run once by an administrator to configure ArgoCD.

### 2. Create Application Manifests

For each environment you wish to deploy your application to, you need to create the corresponding ArgoCD `Application` resource (and potentially raw Kubernetes manifests if not using Helm exclusively).

*   **Review App (Development Environment):**
    These files are typically templated to create temporary deployments for each pull request.
    *   `./dev/apps/review-apps/[app-name]/template.yml.tpl`
    *   `./dev/manifests/review-apps/[app-name]/template.yml.tpl`

*   **UAT Environment:**
    *   `./prod/apps/uat/[app-name]/[app-name].yml`
    *   `./prod/manifests/uat/[app-name]/[app-name].yaml`

*   **Production Environment:**
    *   `./prod/apps/production/[app-name]/[app-name].yml`
    *   `./prod/manifests/production/[app-name]/[app-name].yaml`

**Example Content for `prod/apps/uat/[app-name]/[app-name].yml` (Helm Application):**

```yaml
apiVersion: argoproj.io/v1alpha1
kind: Application
metadata:
  name: [app-name]-uat
  namespace: argocd
  finalizers:
    - resources-finalizer.argocd.argoproj.io
spec:
  project: default
  source:
    repoURL: ghcr.io/[your-org]/[app-name]/charts/application
    targetRevision: 1.0.0 # Or use a dynamic tag from CI
    chart: [app-name]
    helm:
      valuesObject:
        image:
          tag: "latest" # Replace with actual image tag
        replicaCount: 1
        ingress:
          enabled: true
          host: [app-name].uat.example.com
  destination:
    server: https://kubernetes.default.svc
    namespace: [app-name]-uat
  syncPolicy:
    automated:
      prune: true
      selfHeal: true
    syncOptions:
      - CreateNamespace=true
```

## Contributing

We welcome contributions to this repository! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to submit pull requests, report bugs, and suggest features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
