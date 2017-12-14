[![Build Status](https://travis-ci.org/jgeusebroek/ansible-role-mariadb.svg?branch=master)](https://travis-ci.org/jgeusebroek/ansible-role-mariadb)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-jgeusebroek.mariadb-blue.svg)](https://galaxy.ansible.com/jgeusebroek/mariadb)

# Ansible role: Mariadb

An Ansible Role that installs and configures Mariadb on RedHat/CentOS or Debian/Ubuntu.

## Requirements

Epel repository when using RedHat / CentOS. You could use [ansible-role-epel](https://galaxy.ansible.com/detail#/role/6522) for this.
Furthermore ensure that SELinux and the firewall are disabled or configured correctly.

## Dependencies

None

## Example Playbook

    ---
    - hosts: all
      become: true
      vars:

      roles:
       - { role: jgeusebroek.mariadb, tags: ["mariadb"] }

## Example Variables

    TODO

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Jeroen Geusebroek](http://jeroengeusebroek.nl/).
