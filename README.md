andrewrothstein.perforce
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-perforce.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-perforce)

A brief description of the andrewrothstein.perforce goes here.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbooks
----------------

```yml
- hosts: developer_desktop
  roles:
    - andrewrothstein.perforce
```

```yml
- hosts: headless_servers
  roles:
    - role: andrewrothstein.perforce
      vars:
        perforce_p4v_install: false
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
