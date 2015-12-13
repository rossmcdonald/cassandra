Cassandra
=========

An Ansible role for installing, configuring, and managing Apache Cassandra. This role attempts to give a 'packaged' feeling to the Cassandra installation, even though only binary tarballs from Apache are being used for the underlying installation (nothing from Datastax is used).

This is a work in progress, so please use with caution.

Requirements
------------

Prior experience with Cassandra is highly recommended.

Dependencies
------------

There are currently no dependencies required to use this playbook.

Example Playbook
----------------

An example playbook `test.yml` is included in the root directory for demonstration purposes. This playbook can be used with Vagrant for quick local testing. Alternatively, you can run the playbook against your local system using the command:

```
$ ansible-playbook -i dummy-inventory --become --ask-become-pass test.yml
```

License
-------

MIT

Author Information
------------------

Created by [Ross McDonald](https://github.com/rossmcdonald).
