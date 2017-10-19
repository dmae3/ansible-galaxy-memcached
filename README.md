Role of installing Memcached
=========

Memcached ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* memcached_version  
install Memcached version

* memcached_port  
run port

* memcached_user  
run user

* memcached_maxconn
max connection number

* memcached_cachesize  
cache size

* memcached_options  
options

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - role: { role: galaxy-memcached, memcached_version: 1.4.15 }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
