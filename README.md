# Awesome Dependabot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Dependabot (and related software supply chain) resources.

# Dependabot Tools

## CLI
- [cli](https://github.com/dependabot/cli) - A tool for testing and debugging Dependabot update jobs.

## Actions Automation
- [fetch-metadata](https://github.com/dependabot/fetch-metadata) - GitHub Action to extract information about the dependencies being updated by a Dependabot-generated PR.
- [dependabot-actions-workflow](https://github.com/dependabot/dependabot-actions-workflow) - Example workflow for updating Dependabot pull requests

## Policy Enforcement
- [package-policy](https://github.com/rob-derosa/package-policy) - A GitHub action to enforce that only approved packages are used within a project by providing an allow or prohibit list of packages.
- [dependabot-kev-action](https://github.com/advanced-security/dependabot-kev-action) - Action to detect if any open Dependabot alerts are in the CISA Known Exploited Vulnerabilities (KEV) Catalog of CVEs and fail the workflow.
- [policy-as-code](https://github.com/advanced-security/policy-as-code/blob/main/ghascompliance/defaults/policy.yml) - GitHub Advanced Security Policy as Code Action that supports Alerts and License compliance.

# Dependency Graph

## Dependency Export
- [generate-dependencies-csv-action](https://github.com/thedave42/generate-dependencies-csv-action) - GitHub Action to generate a csv file listing the dependencies detected in a repository
- [gh-dependency-report](https://github.com/andyfeller/gh-dependency-report) - GitHub CLI extension for generating a report on repository dependencies.

## SBOM
- [sbom-generator](https://github.com/jhutchings1/sbom-generator) - Generates an sbom from a repository's dependency graph
- [gh-sbom](https://github.com/advanced-security/gh-sbom) - Generate SBOMs with gh CLI
- [spdx-to-dependency-graph-action](https://github.com/jhutchings1/spdx-to-dependency-graph-action) - A GitHub Action that takes SPDX SBOMs and uploads them to GitHub's dependency submission API to power Dependabot alerts
- [generate-org-repos-sbom-action](https://github.com/joshjohanning/generate-org-repos-sbom-action) - An Action to wrap creating an SBOM for the entire organization via REST API
- [generate-sbom-action](https://github.com/advanced-security/generate-sbom-action) - An Action to wrap creating an SBOM via REST API

# Advisory Database
- [osv-schema](https://ossf.github.io/osv-schema/) OSSF OSV schema used by the [advisory-database](https://github.com/github/advisory-database/blob/main/CONTRIBUTING.md)
- [SecurityAdvisory](https://docs.github.com/en/graphql/reference/objects#securityadvisory) GitHub GraphQL object to query the advisory DB

# Attestation
- [generate-build-provenance](https://github.com/github-early-access/generate-build-provenance) - GitHub Action to create, sign and upload a build provenance attestation for artifacts built as part of a workflow.


## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
