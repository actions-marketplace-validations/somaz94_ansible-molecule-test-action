# Changelog

All notable changes to this project will be documented in this file.

## Unreleased (2026-07-21)

### Continuous Integration

- remove DCO workflow ([259d4ba](https://github.com/somaz94/ansible-molecule-test-action/commit/259d4bac7479a4e1447630ece6dbc2c55b1d1a52))
- adopt semantic-pr, labels, lock-threads, PR size, and auto-assign reusables ([ff8832b](https://github.com/somaz94/ansible-molecule-test-action/commit/ff8832b958f0b3dd2fa2969a81c40891961efd98))
- use reusable stale-issues workflow ([18dbe53](https://github.com/somaz94/ansible-molecule-test-action/commit/18dbe535404df5f7943cde1a30c605a384db20f3))
- use reusable issue-greeting workflow ([9373508](https://github.com/somaz94/ansible-molecule-test-action/commit/9373508674d02210c855b185a9d7740e55d00ef7))
- use reusable dependabot-auto-merge workflow ([7b424d0](https://github.com/somaz94/ansible-molecule-test-action/commit/7b424d04c45d44b8746b6a58e86ebd30bce11f74))
- use reusable contributors workflow ([90bc204](https://github.com/somaz94/ansible-molecule-test-action/commit/90bc2040915ae2749de16ad35759e88aa2c30b28))
- add ok-to-test workflow stub ([b7e340f](https://github.com/somaz94/ansible-molecule-test-action/commit/b7e340ffc26bbba55fb916d15c4b195ce559de38))
- add PR welcome workflow stub ([4fb1ee2](https://github.com/somaz94/ansible-molecule-test-action/commit/4fb1ee2e39df64b7127d82b9e9750260338ade25))
- add DCO check via shared reusable workflow ([68d154a](https://github.com/somaz94/ansible-molecule-test-action/commit/68d154a26ae1e577e540f3811c70042d422103ab))

### Chores

- **deps:** bump actions/setup-python from 6 to 7 (#3) ([#3](https://github.com/somaz94/ansible-molecule-test-action/pull/3)) ([e5955e8](https://github.com/somaz94/ansible-molecule-test-action/commit/e5955e8fb5127d7b1ae0930e054099be97df2357))
- **deps:** bump actions/checkout from 6 to 7 (#2) ([#2](https://github.com/somaz94/ansible-molecule-test-action/pull/2)) ([bdb150e](https://github.com/somaz94/ansible-molecule-test-action/commit/bdb150e9967f35fe4f0fb983cacb942f66182225))

### Contributors

- somaz

<br/>

## [v1.0.3](https://github.com/somaz94/ansible-molecule-test-action/compare/v1.0.2...v1.0.3) (2026-05-27)

### Code Refactoring

- align Run Molecule test step with set -euo pipefail ([2806b77](https://github.com/somaz94/ansible-molecule-test-action/commit/2806b77243df5ab386a4368a110de3de50c469f5))

### Continuous Integration

- add concurrency guards to recurring workflows ([f32b33b](https://github.com/somaz94/ansible-molecule-test-action/commit/f32b33bdf9e2289d07e04a3ce147210b3732732e))

### Chores

- drop unused docker dependabot ecosystem (composite action, no Dockerfile) ([90af70c](https://github.com/somaz94/ansible-molecule-test-action/commit/90af70ca1d5f9edfb5a1f69663ec22f5e86e959a))
- set CODEOWNERS to @somaz94 ([fd82c50](https://github.com/somaz94/ansible-molecule-test-action/commit/fd82c502e5f71ba2fc1d29493b61c5fe2a6942cc))

### Contributors

- somaz

<br/>

## [v1.0.2](https://github.com/somaz94/ansible-molecule-test-action/compare/v1.0.1...v1.0.2) (2026-04-21)

### Documentation

- add Known Compatibility section for ansible-core 2.19 issue ([4ad2f4e](https://github.com/somaz94/ansible-molecule-test-action/commit/4ad2f4e6defe0ac0bf2ee59780bc723e245a365c))

### Continuous Integration

- bump softprops/action-gh-release v2 to v3 for sibling-repo alignment ([8429e50](https://github.com/somaz94/ansible-molecule-test-action/commit/8429e503cae94b585ccac75312cad5777d08891d))

### Contributors

- somaz

<br/>

## [v1.0.1](https://github.com/somaz94/ansible-molecule-test-action/compare/v1.0.0...v1.0.1) (2026-04-21)

### Documentation

- add Requirements and Supported Distros sections to README ([cdb3b5c](https://github.com/somaz94/ansible-molecule-test-action/commit/cdb3b5ccdd25cad623d29808b7f57193749d2ce9))

### Chores

- rename action to 'Ansible Molecule Test Action' for marketplace ([dd172da](https://github.com/somaz94/ansible-molecule-test-action/commit/dd172dabd84479cebc9424380839b52e445446e5))

### Contributors

- somaz

<br/>

## [v1.0.0](https://github.com/somaz94/ansible-molecule-test-action/releases/tag/v1.0.0) (2026-04-21)

### Features

- implement ansible-molecule-test-action ([7a8099f](https://github.com/somaz94/ansible-molecule-test-action/commit/7a8099f1acfb422b1d48fdd699b878a8b0dd4ce6))

### Bug Fixes

- drop become/root ownership in fixture role for rockylinux9 compat ([673db85](https://github.com/somaz94/ansible-molecule-test-action/commit/673db85daec0f8981cadfc101ac4e01ad8e2a63f))
- set ANSIBLE_ROLES_PATH so molecule can find the fixture role ([493eed8](https://github.com/somaz94/ansible-molecule-test-action/commit/493eed838db5131cec7b22dfeb4ba7d35868d3f6))
- remove pip cache to avoid missing requirements.txt error ([870bc15](https://github.com/somaz94/ansible-molecule-test-action/commit/870bc15305d64c98e53d78abb21f3ff84ced27db))

### Continuous Integration

- add release, mirror, and changelog workflows ([8bc626e](https://github.com/somaz94/ansible-molecule-test-action/commit/8bc626eddd72946e0f82ee33bd3490cc86a562c1))

### Chores

- add baseline repo files and license ([b348de8](https://github.com/somaz94/ansible-molecule-test-action/commit/b348de837f89f93f1a47b6cb3f9e5a1365fee559))

### Contributors

- somaz

<br/>

