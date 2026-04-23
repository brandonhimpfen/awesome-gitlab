# Awesome GitLab [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, features, integrations, workflows, and learning resources for **GitLab**, covering source control, CI/CD, DevSecOps, project management, and cloud-native software delivery.

## Contents

- [Official Resources](#official-resources)
- [Core Platform Features](#core-platform-features)
- [GitLab CI/CD](#gitlab-cicd)
- [Runners & Execution](#runners--execution)
- [DevSecOps & Security](#devsecops--security)
- [Infrastructure & Cloud](#infrastructure--cloud)
- [Containers & Kubernetes](#containers--kubernetes)
- [Automation & APIs](#automation--apis)
- [Integrations](#integrations)
- [Project & Product Management](#project--product-management)
- [Self-Hosting & Administration](#self-hosting--administration)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [GitLab](https://gitlab.com/) – Single application for the entire DevSecOps lifecycle.
- [GitLab Documentation](https://docs.gitlab.com/) – Official documentation for GitLab features and configuration.
- [GitLab Blog](https://about.gitlab.com/blog/) – Product updates, engineering posts, and DevOps insights.
- [GitLab Status](https://status.gitlab.com/) – Real-time availability and incident reporting.
- [GitLab Handbook](https://handbook.gitlab.com/) – Open company handbook detailing GitLab processes and culture.

## Core Platform Features

- [Source Code Management](https://docs.gitlab.com/ee/user/project/repository/) – Git-based repositories with branching, merging, and permissions.
- [Merge Requests](https://docs.gitlab.com/ee/user/project/merge_requests/) – Code review, approvals, and collaboration workflows.
- [Issues](https://docs.gitlab.com/ee/user/project/issues/) – Built-in issue tracking and planning.
- [Wiki](https://docs.gitlab.com/ee/user/project/wiki/) – Project documentation and knowledge bases.
- [Snippets](https://docs.gitlab.com/ee/user/snippets/) – Share and manage reusable code snippets.

## GitLab CI/CD

- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) – Integrated continuous integration and delivery system.
- [`.gitlab-ci.yml`](https://docs.gitlab.com/ee/ci/yaml/) – Declarative pipeline configuration file.
- [Pipelines](https://docs.gitlab.com/ee/ci/pipelines/) – Automated workflows triggered by code changes.
- [Pipeline Templates](https://gitlab.com/gitlab-org/gitlab/-/tree/master/lib/gitlab/ci/templates) – Predefined CI/CD templates for common stacks.
- [Multi-Project Pipelines](https://docs.gitlab.com/ee/ci/multi_project_pipelines.html) – Coordinate pipelines across repositories.

## Runners & Execution

- [GitLab Runner](https://docs.gitlab.com/runner/) – Agent that executes CI/CD jobs.
- [Docker Executor](https://docs.gitlab.com/runner/executors/docker.html) – Run jobs inside Docker containers.
- [Shell Executor](https://docs.gitlab.com/runner/executors/shell.html) – Execute jobs directly on host machines.
- [Kubernetes Executor](https://docs.gitlab.com/runner/executors/kubernetes.html) – Run CI jobs as Kubernetes pods.
- [Autoscaling Runners](https://docs.gitlab.com/runner/configuration/autoscale.html) – Automatically scale runners using cloud providers.

## DevSecOps & Security

- [SAST](https://docs.gitlab.com/ee/user/application_security/sast/) – Static application security testing in pipelines.
- [DAST](https://docs.gitlab.com/ee/user/application_security/dast/) – Dynamic security testing for running apps.
- [Dependency Scanning](https://docs.gitlab.com/ee/user/application_security/dependency_scanning/) – Identify vulnerable dependencies.
- [Container Scanning](https://docs.gitlab.com/ee/user/application_security/container_scanning/) – Scan container images for vulnerabilities.
- [License Compliance](https://docs.gitlab.com/ee/user/compliance/license_compliance/) – Track and enforce open-source licenses.
- [Secret Detection](https://docs.gitlab.com/ee/user/application_security/secret_detection/) – Detect leaked secrets in repositories.

## Infrastructure & Cloud

- [Infrastructure as Code](https://docs.gitlab.com/ee/user/infrastructure/) – Manage infrastructure directly from GitLab.
- [Terraform Integration](https://docs.gitlab.com/ee/user/infrastructure/iac/terraform.html) – Native Terraform workflows and state management.
- [AWS Integration](https://docs.gitlab.com/ee/user/integration/aws.html) – Deploy and manage workloads on AWS.
- [Google Cloud Integration](https://docs.gitlab.com/ee/user/integration/google_cloud.html) – CI/CD and deployment workflows for GCP.
- [Azure Integration](https://docs.gitlab.com/ee/user/integration/azure.html) – Azure DevOps and cloud deployment support.

## Containers & Kubernetes

- [GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/) – Built-in Docker image registry.
- [GitLab Kubernetes Integration](https://docs.gitlab.com/ee/user/project/clusters/) – Connect and deploy to Kubernetes clusters.
- [Auto DevOps](https://docs.gitlab.com/ee/topics/autodevops/) – Automated CI/CD pipelines with best-practice defaults.
- [Helm Charts](https://docs.gitlab.com/charts/) – Official Helm charts for deploying GitLab.
- [GitOps with GitLab](https://docs.gitlab.com/ee/topics/gitops/) – Declarative infrastructure and application delivery.

## Automation & APIs

- [GitLab REST API](https://docs.gitlab.com/ee/api/) – Programmatic access to GitLab resources.
- [GraphQL API](https://docs.gitlab.com/ee/api/graphql/) – Flexible querying of GitLab data.
- [Webhooks](https://docs.gitlab.com/ee/user/project/integrations/webhooks.html) – Trigger external systems from GitLab events.
- [GitLab CLI (glab)](https://gitlab.com/gitlab-org/cli) – Command-line interface for GitLab.
- [Terraform GitLab Provider](https://registry.terraform.io/providers/gitlabhq/gitlab/latest) – Manage GitLab resources as code.

## Integrations

- [Slack Integration](https://docs.gitlab.com/ee/user/project/integrations/slack.html) – Notifications and workflow updates in Slack.
- [Jira Integration](https://docs.gitlab.com/ee/user/project/integrations/jira.html) – Sync issues and development workflows.
- [Sentry Integration](https://docs.gitlab.com/ee/user/project/integrations/sentry.html) – Error tracking integration.
- [Datadog Integration](https://docs.gitlab.com/ee/user/project/integrations/datadog.html) – Monitoring and observability.
- [PagerDuty Integration](https://docs.gitlab.com/ee/user/project/integrations/pagerduty.html) – Incident response and alerting.
- [YAML Validator](https://yamlvalidator.dev) – Online YAML validator and [Chrome extension](https://chromewebstore.google.com/detail/yaml-validator/gjgbohnlhijomhfiflapnlnmcpckgigg) with JSON Schema support for GitLab CI, Kubernetes, Docker Compose, and other configuration formats.

## Project & Product Management

- [Epics](https://docs.gitlab.com/ee/user/group/epics/) – Plan and track large initiatives.
- [Roadmaps](https://docs.gitlab.com/ee/user/group/roadmaps/) – Visualize project timelines.
- [Milestones](https://docs.gitlab.com/ee/user/project/milestones/) – Organize work into deliverable phases.
- [Issue Boards](https://docs.gitlab.com/ee/user/project/issue_board.html) – Kanban-style workflow management.
- [Value Stream Analytics](https://docs.gitlab.com/ee/user/analytics/value_stream_analytics.html) – Measure DevOps efficiency and throughput.

## Self-Hosting & Administration

- [GitLab Omnibus](https://docs.gitlab.com/omnibus/) – Single-package installation for self-managed GitLab.
- [GitLab Runner Installation](https://docs.gitlab.com/runner/install/) – Setup and manage GitLab runners.
- [Backup & Restore](https://docs.gitlab.com/ee/raketasks/backup_restore.html) – Data protection and recovery procedures.
- [Scaling GitLab](https://docs.gitlab.com/ee/administration/reference_architectures/) – Reference architectures for large installations.
- [Security Hardening](https://docs.gitlab.com/ee/security/) – Best practices for securing GitLab instances.

## Learning Resources

### Tutorials
- [GitLab CI/CD Tutorials](https://docs.gitlab.com/ee/ci/examples/) – Practical pipeline examples.
- [GitLab University](https://about.gitlab.com/learn/) – Free and paid training courses.
- [Auto DevOps Guide](https://docs.gitlab.com/ee/topics/autodevops/) – End-to-end automated delivery workflows.

### Guides
- [DevSecOps with GitLab](https://about.gitlab.com/solutions/devsecops/) – Security-first software delivery practices.
- [CI/CD Best Practices](https://docs.gitlab.com/ee/ci/pipelines/best_practices.html) – Recommended pipeline design patterns.
- [GitOps Guide](https://docs.gitlab.com/ee/topics/gitops/) – Declarative infrastructure and application delivery.

### Courses
- *GitLab CI/CD Fundamentals* – Building and maintaining pipelines.
- *DevSecOps with GitLab* – Secure software delivery workflows.
- *Managing GitLab at Scale* – Administration and operations training.

## Related Awesome Lists

- [Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)
- [Awesome CI/CD](https://github.com/awesomelistsio/awesome-cicd)
- [Awesome Docker](https://github.com/awesomelistsio/awesome-docker)
- [Awesome Kubernetes](https://github.com/awesomelistsio/awesome-kubernetes)
- [Awesome Cloud](https://github.com/awesomelistsio/awesome-cloud)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
