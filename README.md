andrewrothstein.ntp
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ntp.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ntp)

Installs an NTP daemon

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
