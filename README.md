# Contributing to Cosign

Thank you for considering contributing to Cosign! We welcome any contributions, whether it's bug fixes, new features, or improvements to the existing codebase.

## Your First Pull Request

Working on your first Pull Request? Start with [Sigstore's contribution guidelines](https://github.com/sigstore/community/blob/main/CONTRIBUTING.md) which includes some high level information on how to contribute to Sigstore projects.

To help you get familiar with our contribution process, we have a list of [good first issues](https://github.com/sigstore/cosign/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) which are relatively limited scope. This is a great place to get started!

Before working on an issue, please:

1. Check the comments to see if someone is already working on it.
1. If it's unassigned, comment that you're working on it to avoid duplication.

## Contribution Prerequisites

Before running Cosign, ensure that you have [Go](https://go.dev/doc/install) installed.

## Sending a Pull Request

You can find a step by step guide to submit your contribution on [Sigstore's contribution guidelines](https://github.com/sigstore/community/blob/main/CONTRIBUTING.md#pull-request-process).

The next instructions will usher you through the build, unit testing, linting, and documentation processes:

### Building Cosign

To build cosign locally, run this command:

```shell
make cosign
```

### Running Unit Tests

To run the unit tests, execute the following command:

```shell
make test
```

**Make sure all tests pass** without any failures or errors.

### Running Lint

To run the linting checks, use the following command:

```shell
make lint
```
Address any linting warnings or errors before submitting your PR.

## Document Generation

If your changes require updates to project documentation, generate or update the documentation by running:

```shell
make docgen
```

Ensure that the documentation is up-to-date and reflects your changes accurately.


**Now you are ready!** When you send the PR make sure to sign the [Developer Certificate of Origin](https://github.com/src-d/guide/blob/master/developer-community/fix-DCO.md) and that all the build checks are green.

We are looking forward for your PRs and working together!