# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] (beta, main branch content)

- Update documentation in README
- Update human-readable output format
  - Sort errors by flow
- New argument **--failon** (error/warning/note): Makes return code 1 in case --failon severity is reached
- Automate deployment of beta and release versions via Github Actions

## [1.1.0] - 2023-07-03

- Use [cosmiconfig](https://github.com/cosmiconfig/cosmiconfig) to load configuration
- Add a **--retrieve** argument in case user wants to retrieve flows from org before scanning
- Add a testing GitHub action Workflow 
- Add CHANGELOG.md file
- Code refactorization
  - let <=> const
  - Split main method into smaller methods
  - use fs-extra instead of sf plugin fs
  - Remove tslint (deprecated), replaced by eslint
  - Upgrade dependencies
  - Add VsCode local debugging configuration