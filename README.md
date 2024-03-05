<h1 align="center">
  <a href="https://github.com/topizdato/devopschallenge2">
    <!-- Please provide a path to your logo here -->
    <img src="docs/images/logo.png" alt="Logo" width="100" height="100">
  </a>
</h1>

<div align="center">
  DevOps Challenge 2
  <br />
  <a href="#about"><strong>Explore the docs »</strong></a>
  <br />
  <br />
  <a href="https://github.com/topizdato/devopschallenge2/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/topizdato/devopschallenge2/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  ·
  <a href="https://github.com/topizdato/devopschallenge2/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a>
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/topizdato/devopschallenge2.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/topizdato/devopschallenge2/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by topizdato](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-topizdato-ff1414.svg?style=flat-square)](https://github.com/topizdato)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Project assistance](#project-assistance)
- [Contributing](#contributing)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)

</details>

---

## About

DevOps Challenge 2 is a GitHub repository designed to integrate and deploy Chatwoot and Novu using Terraform on GCP, alongside developing a microservice for seamless integration. The repository follows a structured approach with specific epics and deadlines to enhance DevOps practices, including CI/CD pipelines using GitHub Actions, environment-based branching, and cost optimization strategies.

## Getting Started

Instructions to get your project up and running will be detailed here, specific to each part of the challenge including setup for Chatwoot, Novu, Terraform configurations, and microservice deployment.

## Usage

This section guides you through utilizing DevOps Challenge 2, focusing on the integration and deployment of Chatwoot and Novu on GCP using Terraform and managing their interactions through a microservice.

### Chatwoot and Novu Deployment

1. **Initial Setup**: Follow the setup instructions in your repository to configure both Chatwoot and Novu with necessary environment variables and dependencies.
2. **Terraform Deployment**: Use the Terraform scripts in the `/terraform` directory to deploy both Chatwoot and Novu on GCP. Ensure that you adjust the scripts according to the specific needs of each application.

### Microservice Integration

1. **Development**: In the `/microservice` directory, develop the microservice using the suggested tools and frameworks, ensuring it can facilitate communication between Chatwoot and Novu.
2. **Deployment**: Deploy this microservice within GCP, confirming that it integrates Chatwoot and Novu effectively for optimal notification and customer engagement management.

### Continuous Integration and Deployment

- Set up GitHub Actions workflows in your monorepo to handle CI/CD for both Chatwoot and Novu, ensuring automated testing, integration, and deployment based on your branch-based environment strategy.

### Infrastructure Management and Cleanup

- Implement and maintain the scheduled cleanup tasks in GitHub Actions to efficiently manage resources and reduce costs by tearing down non-critical infrastructure during specified off-hours.

## Roadmap

To structure a detailed agile roadmap for the DevOps Challenge 2 project over several sprints, we'll break down the tasks across two teams: Team Alpha and Team Beta. To enhance cross-team communication and knowledge sharing, Teams Alpha and Beta will interchange members every two sprints.

### Sprint 1: Initial Setup and Planning
- **Team Alpha**: Set up GCP and GitHub environments for Prod and NonProd. Begin the monorepo setup for both Chatwoot and Novu.
- **Team Beta**: Start on infrastructure definitions in Terraform for Chatwoot deployment.

### Sprint 2: Initial Deployments
- **Team Alpha**: Continue with the deployment configurations in Terraform for Novu.
- **Team Beta**: Initialize the Chatwoot deployment on GCP and ensure initial testing is successful.

### Sprint 3: Microservice Development and Deployment (Teams Mix)
- **Mixed Team Alpha**: Develop the skeleton and base functionality of the GCP-based microservice, ensuring basic communication between Chatwoot and Novu.
- **Mixed Team Beta**: Focus on setting up CI/CD pipelines in GitHub Actions for Chatwoot with an emphasis on automated testing.

### Sprint 4: Integration and Testing (Teams Mix)
- **Mixed Team Alpha**: Integrate the microservice with Chatwoot and Novu, ensuring data flows correctly and triggers notifications as expected.
- **Mixed Team Beta**: Refine the CI/CD pipelines, focusing on Novu and ensuring environment-specific configurations are correctly managed.

### Sprint 5: Security and Cleanup Scheduling
- **Team Alpha**: Implement security best practices within the deployments and the microservice. Start developing the cleanup scheduling in GitHub Actions.
- **Team Beta**: Perform thorough testing of the integrations, focusing on edge cases and potential failure points.

### Sprint 6: Optimization and Documentation
- **Team Alpha**: Optimize the infrastructure for cost and performance. Ensure all Terraform configurations are fine-tuned and documented.
- **Team Beta**: Finalize the documentation for the entire setup, including usage guides and operational procedures.

### Sprint 7: Final Testing and Adjustments (Teams Mix)
- **Mixed Team Alpha**: Conduct final testing across all components, focusing on resilience and performance under load.
- **Mixed Team Beta**: Make any necessary adjustments based on feedback from testing, ensuring that the system is robust and reliable.

### Sprint 8: Go-Live Preparation and Review (Teams Mix)
- **Mixed Team Alpha**: Prepare for the go-live, ensuring all monitoring and alerting are in place. Conduct a final review of the security implementations.
- **Mixed Team Beta**: Oversee a final round of user acceptance testing (UAT) and prepare deployment checklists for the go-live phase.


## Support

Reach out to the maintainer at one of the following places:

- [GitHub issues](https://github.com/topizdato/devopschallenge2/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+)

## Project assistance

If you want to say **thank you** or/and support active development:

- Add a [GitHub Star](https://github.com/topizdato/devopschallenge2) to the project.
- Tweet about it or write articles.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions are **greatly appreciated**.

## Authors & contributors

The initial setup of this repository is by [Your Name or Team].

## Security

Follows good practices of security. Use at your own risk.

## License

This project is licensed under the Apache License Version 2.0 - see the [LICENSE](LICENSE) file for details.
