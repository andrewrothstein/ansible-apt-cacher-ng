Role Name
=========

Installs an apt-cacher-ng service.

Role Variables
--------------

See the [defaults](defaults/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: apt-cache-ng-servers
      roles:
         - role: andrewrothstein.apt-cacher-ng
	   apt_cache_ng_port: 8080

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
