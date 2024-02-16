# [_ANSIBLE_ROLE_ANSIBLE_TOOLS CHANGELOG_](https://gitlab.com/gcoop-libre/ansible_role_ansible_tools)

 - this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

## [`Unreleased - 2024-02-16`](https://gitlab.com/gcoop-libre/ansible_role_ansible_tools/-/compare/v0.1.0...develop)

### `README`

- add summary for release v0.1.0
- add .readme-footer to use with git-tag-readme
- add .readme-header to use with git-tag-readme

## [`v0.1.0 - 2024-02-16`](https://gitlab.com/gcoop-libre/ansible_role_ansible_tools/-/compare/8e4d4d4...v0.1.0) _tests/cmdb: add playbook for Generate CMDB from AWX_

### `defaults/cmdb`

- define CMDB ansible_tools variables

### `defaults/config`

- define config variables for awx-cli and ansible_tools variables

### `defaults/git`

- define git variables for ansible_tools

### `defaults/main`

- define common ansible_tools variables

### `defaults/pip`

- define pip variables for ansible_tools

### `defaults/proxy`

- define proxy variables for ansible_tools

### `defaults/user`

- define ansible user variables for ansible_tools

### `general`

- set description project as This role, install and configure useful scripts for Ansible from ansible_tools git repository

### `.gitignore`

- ignore tests/inventory and tests/roles/*

### `gitlab-ci`

- add awx-config.sh to configure the environment for AWX in GitLab CI
- add ansible-lint, ansible-syntax-check and ansible-awx stages

### `handlers/main`

- add empty handlers file

### `LICENSE`

- add GPLv3 GNU GENERAL PUBLIC LICENSE

### `Makefile`

- add common rules for test and deploy ansible role

### `meta/main`

- add metadata for ansible galaxy

### `pre-commit`

- add ansible-lint, end-of-file-fixer, trailing-whitespace hooks

### `tasks/cmdb`

- add ansibe_tools cmdb tasks

### `tasks/config`

- add ansibe_tools config tasks

### `tasks/git`

- add ansibe_tools git tasks

### `tasks/main`

- add ansibe_tools main tasks

### `tasks/packages`

- add ansibe_tools system packages tasks

### `tasks/permissions`

- add ansibe_tools permissions tasks

### `tasks/pip`

- add ansibe_tools pip packages tasks

### `tasks/proxy`

- add ansibe_tools proxy tasks

### `tasks/user`

- add ansibe system user tasks

### `templates/tower_cli.cfg`

- add template for generate tower_cli.cfg

### `tests/ansible-lint`

- skip 204, 301, 302, 303 and 305

### `tests/cmdb`

- add playbook for Generate CMDB from AWX

### `tests/gcoop-libre`

- add symbolic link to role gcoop-libre.ansible_tools

### `tests/osiux`

- add symbolic link to role osiux.ansible_tools

### `tests/test`

- add playbook for Install and Configure Ansible Tools

### `vars/Debian_11`

- define ansible_tools_packages and ansible_tools_pip_packages
