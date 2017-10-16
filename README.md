Ansible Role: Prometheus ([lrk.flyway](https://galaxy.ansible.com/lrk/flyway/))
=========
[![Build Status](https://travis-ci.org/lrk/ansible-role-flyway.svg?branch=master)](https://travis-ci.org/lrk/ansible-role-flyway)

An Ansible Role that install [Flyway](https://flywaydb.org) Command-line Tool.


Supported OSes
--------------
- Centos 7

Requirements
------------

This role doesn't have any requirements, but flyway need JAVA to run.

Role Variables
--------------

Available variables along with default values are listed below (see `defaults/main.yml`)
```yml
---

```

Dependencies
------------

None

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - lrk.flyway
```

 License
 -------

 Apache License Version 2.0

 References
 ----------

- [Flyway](https://flywaydb.org)

Author Information
------------------
This role was created by [Lrk](https://github.com/lrk).
