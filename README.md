andrewrothstein.apt-cacher-ng
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-apt-cacher-ng.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-apt-cacher-ng)

Installs [apt-cacher-ng](https://www.unix-ag.uni-kl.de/~bloch/acng/)

Role Variables
--------------

See the [defaults](defaults/main.yml)

Example Playbook
----------------

```yml
- hosts: apt-cache-ng-servers
  roles:
    - andrewrothstein.apt-cacher-ng
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
