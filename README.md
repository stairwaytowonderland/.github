# stairwaytowonderland

The [**stairwaytowonderland**](https://github.com/stairwaytowonderland) org public doc.

## Shared Actions & Workflows Monorepo

For internal use.

### [**stairwaytowonderland / actions**](https://github.com/stairwaytowonderland/actions)

> Shared actions and workflows for use by the organization.

This **shared repository** contains actions and workflows to assist in:

- [**issue creation**](https://github.com/stairwaytowonderland/actions#import-csv-issues) *(workflow)*
- [**terraform deployments**](https://github.com/stairwaytowonderland/actions#terraform-deploy) *(workflow)*
- [**releasing new versions**](https://github.com/stairwaytowonderland/actions#release) *(workflow)*
- [**publishing releases**](https://github.com/stairwaytowonderland/actions#publish) *(workflow)*
- [**running pre-commit**](https://github.com/stairwaytowonderland/actions#pre-commit) *(workflow)*
- [**validating conventional commits**](https://github.com/stairwaytowonderland/actions#conventional-commit) *(workflow)*

## General Repository Creation

### [create-repository](https://github.com/stairwaytowonderland/create-repository/actions/workflows/create-repository.yaml)

> Automatically create a repository using the GitHub API

### [repository-template](https://github.com/stairwaytowonderland/repository-template) *(template)*

> A minimal starting point for a basic repository 🚀

## Python Projects

### [python-app-template](https://github.com/stairwaytowonderland/python-app-template) *(template)*

> A minimal starting point for a Python project wired up to the shared CI/CD workflows 🚀

### [python-reusable-workflows](https://github.com/stairwaytowonderland/python-reusable-workflows)

> Reuseable workflows to release a Python app using semantic versioning, create a wheel package artifact, and publish a release 🚀

## Marketplace Actions

### [node-semantic-release](https://github.com/stairwaytowonderland/node-semantic-release)

> Marketplace Action | Builds the project with npm, runs semantic-release, and base64-encodes the release notes for safe transport.

### [repository-create](https://github.com/stairwaytowonderland/repository-create)

> Marketplace Action | Creates a GitHub organization repository with overrideable pre-defined settings and branch rulesets.

### [simple-workflow-dispatch](https://github.com/stairwaytowonderland/simple-workflow-dispatch)

> Marketplace Action | Trigger a workflow_dispatch event on a target workflow file.

## Cloudflare

### [cloudflare-email-slack-worker](https://github.com/stairwaytowonderland/cloudflare-email-slack-worker)

> A Cloudflare Email Worker that receives incoming emails, parses them, and sends formatted notifications to Slack via webhooks 🚀

### [cloudflare-email-worker-iac](https://github.com/stairwaytowonderland/cloudflare-email-worker-iac) *(template)*

> A Cloudflare Email Worker Terraform Example 🚀
