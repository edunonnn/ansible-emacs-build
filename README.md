andrewrothstein.emacs-build
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-emacs-build.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-emacs-build)

A role to build [Emacs](https://www.gnu.org/software/emacs/)

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
    - andrewrothstein.emacs-builder
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
