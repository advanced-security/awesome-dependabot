# awesome-dependabot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Dependabot (and related software supply chain) resources.

# Dependabot Tools
- [cli](https://github.com/dependabot/cli) - A tool for testing and debugging Dependabot update jobs.
- [fetch-metadata](https://github.com/dependabot/fetch-metadata) - Extract information about the dependencies being updated by a Dependabot-generated PR.

## Dependency Export
- [generate-dependencies-csv-action](https://github.com/thedave42/generate-dependencies-csv-action) - GitHub Action to generate a csv file listing the dependencies detected in a repository
- [gh-dependency-report](https://github.com/andyfeller/gh-dependency-report) - GitHub CLI extension for generating a report on repository dependencies.

## SBOM
- [sbom-generator](https://github.com/jhutchings1/sbom-generator) - Generates an sbom from a repository's dependency graph
- [gh-sbom](https://github.com/advanced-security/gh-sbom) - Generate SBOMs with gh CLI
- [spdx-to-dependency-graph-action](https://github.com/jhutchings1/spdx-to-dependency-graph-action) - A GitHub Action that takes SPDX SBOMs and uploads them to GitHub's dependency submission API to power Dependabot alerts


## Actions
- [package-policy](https://github.com/rob-derosa/package-policy) - A GitHub action to enforce that only approved packages are used within a project by providing an allow or prohibit list of packages.
- [dependabot-actions-workflow](https://github.com/dependabot/dependabot-actions-workflow) - Example workflow for updating Dependabot pull requests
- [dependabot-kev-action](https://github.com/felickz/dependabot-kev-action) - Action to detect if any open Dependabot alerts are in the list of CISA KEV CVEs and fail the workflow.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
