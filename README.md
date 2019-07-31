# Ansible role for Node.js

[![CircleCI](https://circleci.com/gh/angristan/ansible-nodejs.svg?style=svg)](https://circleci.com/gh/angristan/ansible-nodejs)

This is a simple role that will install Node.js on Debian/Ubuntu from [Nodesource](https://github.com/nodesource/distributions).

## Installation

Add this to your `requirements.yml`:

```yml
- src: https://github.com/angristan/ansible-nodejs
```

## Sample playbook

```yaml
---

- hosts: myhost
  roles:
    - name: nodejs
      tags: nodejs
  vars:
    nodejs_version: 10
```
