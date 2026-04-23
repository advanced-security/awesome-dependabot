# awesome-dependabot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Dependabot / Dependency Graph (and related software supply chain) resources.

# Dependabot Tools
- [cli](https://github.com/dependabot/cli) - A tool for testing and debugging Dependabot update jobs.
- [fetch-metadata](https://github.com/dependabot/fetch-metadata) - Extract information about the dependencies being updated by a Dependabot-generated PR.

## Snapshot Submissions
- [spdx-to-dependency-graph-action](https://github.com/jhutchings1/spdx-to-dependency-graph-action) - A GitHub Action that takes SPDX SBOMs and uploads them to GitHub's dependency submission API to power Dependabot alerts
- [jessehouwing/actions-dependency-submission](https://github.com/jessehouwing/actions-dependency-submission) - Action to automatically report versions for pinned action dependencies
- [advanced-security/codeql-dependency-graph-action](https://github.com/advanced-security/codeql-dependency-graph-action) -  CodeQL <-> Dependency Graph Actions

## Dependency Export
- [generate-dependencies-csv-action](https://github.com/thedave42/generate-dependencies-csv-action) - GitHub Action to generate a csv file listing the dependencies detected in a repository
- [gh-dependency-report](https://github.com/andyfeller/gh-dependency-report) - GitHub CLI extension for generating a report on repository dependencies.

## SBOM
- [sbom-generator](https://github.com/jhutchings1/sbom-generator) - Generates an sbom from a repository's dependency graph
- [gh-sbom](https://github.com/advanced-security/gh-sbom) - Generate SBOMs with gh CLI
- [generate-org-repos-sbom-action](https://github.com/joshjohanning/generate-org-repos-sbom-action) - An Action to wrap creating an SBOM for the entire organization via REST API
- [generate-sbom-action](https://github.com/advanced-security/generate-sbom-action) - An Action to wrap creating an SBOM via REST API

## Dependency Review
- [blueoak-to-dependency-review](https://github.com/ctcampbell/blueoak-to-dependency-review) - A GitHub Dependency Review compatible YAML file for the Blue Oak Council license list

## Actions
- [package-policy](https://github.com/rob-derosa/package-policy) - A GitHub action to enforce that only approved packages are used within a project by providing an allow or prohibit list of packages.
- [dependabot-kev-action](https://github.com/advanced-security/dependabot-kev-action) - Action to detect if any open Dependabot alerts are in the CISA Known Exploited Vulnerabilities (KEV) Catalog of CVEs and fail the workflow.
- [policy-as-code](https://github.com/advanced-security/policy-as-code/blob/main/ghascompliance/defaults/policy.yml) - GitHub Advanced Security Policy as Code Action that supports Alerts and License compliance.
- [fetch-metadata](https://github.com/dependabot/fetch-metadata) - Extract information about the dependencies being updated by a Dependabot-generated PR.

## Advisory Database
- [osv-schema](https://ossf.github.io/osv-schema/) OSSF OSV schema used by the [advisory-database](https://github.com/github/advisory-database/blob/main/CONTRIBUTING.md)
- [SecurityAdvisory](https://docs.github.com/en/graphql/reference/objects#securityadvisory) GitHub GraphQL object to query the advisory DB

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
