# ansible-apps_docker

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_docker-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_docker)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_docker.svg)](https://github.com/lotusnoir/ansible-apps_docker/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_docker?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_docker)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_docker)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_docker)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Deploy [docker](https://docker.io) with proxy support using ansible. (forked from https://galaxy.ansible.com/geerlingguy/docker)

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_docker
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_docker


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

