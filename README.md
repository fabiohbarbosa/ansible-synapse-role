Ansible Synapse Role 
======

[![Build Status](https://travis-ci.org/fabiohbarbosa/ansible-synapse-role.svg?branch=master)](https://travis-ci.org/fabiohbarbosa/ansible-synapse-role)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-docker-blue.svg?style=flat-square)](https://galaxy.ansible.com/fabiohbarbosa/synapse/)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

Ansible role to synapse laucher in Ubuntu or Linux Mint.

Requirements
------------
- Ansible 2.0 or later

Supported Distributions
------------
- Linux Mint 17 Qiana
- Linux Mint 17.1 Rebecca
- Linux Mint 17.2 Rafaela
- Linux Mint 17.3 Rosa
- Linux Mint 18 Sarah
- Linux Mint 18.1 Serena
- Linux Mint 18.2 Sonya

- Ubuntu 14.04 Trusty
- Ubuntu 16.04 Xenial
- Ubuntu 16.10 Yakkety
- Ubuntu 17.04 Zesty

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: fabiohbarbosa.synapse }

License
-------

Test
-------
Use my [docker ansible runner image](https://hub.docker.com/r/fabiohbarbosa/ansible-runner/) to run this role. see all docker run commands in `.travis.yml` file.

MIT
