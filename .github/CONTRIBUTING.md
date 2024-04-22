# Contributing to eLTER-SO-costs-App

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the managers of this repository before making a change. This Discussion Forum is the perfect place to ask questions, propose features and discuss improvements.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Quick Links
- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Pull Request Process](#pull-request-process)
- [Branching Strategy](#branching-strategy)

## Code of Conduct

This project and everyone participating in it is governed by the eLTER-SO-costs-App Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to allan.souza@helsinki.fi.

## Getting Started

If you are new to contributing to open source on GitHub, [this guide](https://opensource.guide/how-to-contribute/) can help you get started. Please ensure you read our Code of Conduct.

Before you make your first contribution, you should familiarize yourself with how we do things:

- **Development Process**: We utilize GitHub Issues for tracking suggestions and work in progress.
- **Communications**: For more direct communication, you can also reach out to the developers (allan.souza@helsinki.fi)

### Setting Up Your Environment

Here's a quick rundown on how to set up eLTER-SO-costs-App for local development:

1. Fork the [repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).
2. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) your fork locally.
3. Create a [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) for local development.
4. Make your changes locally.
5. When you are done making changes, check that your changes pass any checks or tests.
6. Commit your changes and push your branch to GitHub.
7. Submit a pull request through the GitHub website using the template provided.

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations, and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Branching Strategy

To make the development process smooth and efficient, we follow a specific branching strategy. This ensures that the main branch always remains stable and release-ready.

- **Main Branch**: The `main` branch is the default branch and is considered stable at all times. It is the production branch.
- **Feature Branches**: For new features and non-emergency bug fixes, create a branch off `main`. Use a naming convention like `feature/<feature-name>` or `bugfix/<bug-name>`.
- **Hotfix Branches**: For critical bugs that need immediate attention, create a `hotfix/<hotfix-name>` branch off `main`.
- **Release Branches**: If there are several features or fixes that need to go together, consider creating a `release/<version>` branch off `main`, and merge features into this branch before merging back into `main`.

Please make sure to keep your branches up to date with the main branch to avoid merge conflicts.
