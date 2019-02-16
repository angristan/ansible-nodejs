# Ansible role for Node.js

This is a simple role that will install Node.js on Debian/Ubuntu from [Nodesource](https://github.com/nodesource/distributions).

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
