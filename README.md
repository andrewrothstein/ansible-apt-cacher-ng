andrewrothstein.apt-cacher-ng
=========
![Build Status](https://github.com/andrewrothstein/ansible-apt-cacher-ng/actions/workflows/build.yml/badge.svg)

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
