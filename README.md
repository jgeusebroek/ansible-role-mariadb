# Ansible role: mariadb-galera

An Ansible Role that installs and configures MariaDB-Galera RedHat/CentOS or Debian/Ubuntu.

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
       - { role: jgeusebroek.mariadb-galera, tags: ["mariadb-galera"] }

## Example Variables

    TODO

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Jeroen Geusebroek](http://jeroengeusebroek.nl/).