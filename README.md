# zerohacks.percona-mysql

[![Build Status](https://travis-ci.org/zerohacks/ansible-percona-mysql.svg?branch=master)](https://travis-ci.org/zerohacks/ansible-percona-mysql)
[![Ansible Role](https://img.shields.io/ansible/role/10650.svg?maxAge=2592000)](https://galaxy.ansible.com/zerohacks/percona-mysql/)

Install Percona Server for MySQL 5.7

## Requirements

This role requires Ansible 1.9 or higher and platform requirements are listed in the metadata file.

## Role Variables

- `mysql_root_password` (default: "reallylongpassword")

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
        - role: zerohacks.percona-mysql
          vars:
            - mysql_root_password: newpassword

## License

Licensed under the MIT license: http://www.opensource.org/licenses/mit-license.php
