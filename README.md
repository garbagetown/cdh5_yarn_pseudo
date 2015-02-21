garbagetown.cdh5_yarn_pseudo
=========

Install CDH 5 with YARN on a Single Linux Node in Pseudo-distributed mode.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

- [williamyeh.oracle-java](https://galaxy.ansible.com/list#/roles/2851)

Example Playbook
----------------

```
- hosts: 127.0.0.1
  connection: local

  roles:
    - garbagetown.cdh5_yarn_pseudo

  vars:
    - java_version: 7
```

License
-------

Licensed under the Apache License V2.0. See the [LICENSE file](LICENSE-2.0) for details.

Author Information
------------------

- https://twitter.com/garbagetown