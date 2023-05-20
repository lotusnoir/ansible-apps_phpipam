# ansible-apps_phpipam

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_phpipam-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_phpipam)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_phpipam.svg)](https://github.com/lotusnoir/ansible-apps_phpipam/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_phpipam?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_phpipam)
[![downloads](https://img.shields.io/ansible/role/d/52262)](https://galaxy.ansible.com/lotusnoir/apps_phpipam)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/52262)](https://galaxy.ansible.com/lotusnoir/apps_phpipam)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Deploy and install the ipam web tool [phpipam](https://github.com/momorientes/phpipam).
## Requirements

You need to install:
  - a mysql database - geerlingguy.mysql
  - a web server - geerlingguy.nginx


## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_phpipam
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_phpipam


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
