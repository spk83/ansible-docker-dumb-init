[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-dumb-init.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-dumb-init)
andrewrothstein.dumb-init
===========================

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

Andrew Rothstein <andrew.rothstein@gmail.com>
