# sbog/cadvisor

[![Build Status](https://travis-ci.com/sorrowless/ansible_cadvisor.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_cadvisor)
[![Ansible Role](https://img.shields.io/ansible/role/54493)](https://galaxy.ansible.com/sorrowless/cadvisor)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/54493)](https://galaxy.ansible.com/sorrowless/cadvisor)
[![Ansible Role](https://img.shields.io/ansible/role/d/54493)](https://galaxy.ansible.com/sorrowless/cadvisor)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_cadvisor)](https://github.com/sorrowless/ansible_cadvisor/blob/master/LICENSE)

An Ansible role which installs and configures [cadvisor](https://github.com/google/cadvisor) on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure cadvisor
  hosts: cadvisors
  remote_user: root

  roles:
    - cadvisor
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru) and
[one-mINd](https://github.com/one-mINd)
