# [Ansible role lemp-stack](#ansible-role-lemp-stack)

Install LEMP Stack

|GitHub|Issues|Pull Requests|Version|Downloads|
|------|------|-------------|-------|---------|
|[![github](https://github.com/buluma/ansible-role-lemp-stack/actions/workflows/molecule.yml/badge.svg)](https://github.com/buluma/ansible-role-lemp-stack/actions/workflows/molecule.yml)|[![Issues](https://img.shields.io/github/issues/buluma/ansible-role-lemp-stack.svg)](https://github.com/buluma/ansible-role-lemp-stack/issues/)|[![PullRequests](https://img.shields.io/github/issues-pr-closed-raw/buluma/ansible-role-lemp-stack.svg)](https://github.com/buluma/ansible-role-lemp-stack/pulls/)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-lemp-stack.svg)](https://github.com/buluma/ansible-role-lemp-stack/releases/)|[![Ansible Role](https://img.shields.io/ansible/role/d/buluma/lemp-stack)](https://galaxy.ansible.com/ui/standalone/roles/buluma/lemp-stack/documentation)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-lemp-stack/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- become: true
  gather_facts: true
  hosts: all
  name: Converge
  roles:
    - ansible-role-lemp-stack
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.

## [Role Variables](#role-variables)

The default values for the variables are set in [`defaults/main.yml`](https://github.com/buluma/ansible-role-lemp-stack/blob/master/defaults/main.yml):

```yaml
---
php_version: 70
```

## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-lemp-stack/blob/master/requirements.txt).


## [Context](#context)

This role is part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:

![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-lemp-stack/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/robertdebock):

|container|tags|
|---------|----|
|[EL](https://hub.docker.com/r/robertdebock/enterpriselinux)|all|

The minimum version of Ansible required is 1.2, tests have been done on:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them on [GitHub](https://github.com/buluma/ansible-role-lemp-stack/issues).

## [License](#license)

[MIT](https://github.com/buluma/ansible-role-lemp-stack/blob/master/LICENSE).

## [Author Information](#author-information)

[mosufy](https://buluma.github.io/)

