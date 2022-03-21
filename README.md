andrewrothstein.netdata
=========

![Build Status](https://github.com/andrewrothstein/ansible-netdata/actions/workflows/build.yml/badge.svg)

Installs [NetData](https://www.netdata.cloud/).

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
    - andrewrothstein.netdata
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
