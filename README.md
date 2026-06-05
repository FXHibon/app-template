# App Template

This is a template repository for creating future applications.

## Features

- **Default Branch**: Configured with `master` as the default branch.
- **Dependency Management**: Integrated with GitHub Dependabot to automatically keep GitHub Actions and other dependency ecosystems up-to-date.
- **IaC Pipeline Integration**: Included a GitHub Action workflow that calls the custom Infrastructure as Code (IaC) action from the [fxhibon/iac](https://github.com/fxhibon/iac) repository.

## Getting Started

1. Use this template to create a new repository on GitHub.
2. The GitHub Actions workflow will run automatically on pushes and pull requests to the `master` branch.
3. Dependabot will run checkups (weekly) for GitHub Actions.
