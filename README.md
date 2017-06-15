andrewrothstein.dumb-init
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-dumb-init.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-dumb-init)

Installs [dumb-init](https://github.com/Yelp/dumb-init).


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
    - andrewrothstein.dumb-init
```

License
-------

MIT

Author Information
------------------
* Vishal Shah <vishal.shah@nyu.edu>
* Andrew Rothstein <andrew.rothstein@gmail.com>
