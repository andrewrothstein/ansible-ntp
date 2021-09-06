andrewrothstein.ntp
===========================
![Build Status](https://github.com/andrewrothstein/ansible-ntp/actions/workflows/build.yml/badge.svg)

Installs an NTP daemon.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.ntp
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
