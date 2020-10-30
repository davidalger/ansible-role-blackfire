# Ansible Role: Blackfire

[![Build Status](https://travis-ci.com/davidalger/ansible-role-blackfire.svg?branch=master)](https://travis-ci.com/davidalger/ansible-role-blackfire)

Installs the [Blackfire](https://blackfire.io/) agent for application performance profiling.

## Requirements

None.

## Role Variables

See `defaults/main.yml` for details.

## Dependencies

None.

## Example Playbook

    - hosts: web-servers
      roles:
        - { role: davidalger.blackfire, tags: blackfire }

## License

This work is licensed under the MIT license. See LICENSE file for details.

## Author Information

This role was created in 2018 by [David Alger](http://davidalger.com/).
