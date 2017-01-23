dumb-init [![CircleCI](https://circleci.com/gh/spk83/ansible-dumb-init/tree/master.svg?style=shield)](https://circleci.com/gh/spk83/ansible-dumb-init/tree/master)
=======================

Installs dumb-init binary (https://github.com/Yelp/dumb-init)

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
    - spk83.dumb-init
```

License
-------

MIT

Author Information
------------------

Vishal Shah vishal.shah@nyu.edu