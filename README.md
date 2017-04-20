[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-apt-cacher-ng.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-apt-cacher-ng)
andrewrothstein.apt-cacher-ng
=========

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
