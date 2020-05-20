Ansible role `perccli`
=========

An Ansible role for installing `perccli` - Dell PowerEdge PERC RAID controler management tool.
Playbook somehow follows [official page](https://www.dell.com/support/article/en-ba/sln283135/how-to-use-the-poweredge-raid-controller-perc-command-line-interface-cli-utility-to-manage-your-raid-controller?lang=en).

Requirements
------------

Role Variables
--------------

Dependencies
------------

None so far.

Example Playbook
----------------

```
- hosts: all
  roles:
    - role: pauliusm.perccli
```

Testing
-------

Use [run-docker-tests.sh](tests/run-docker-tests.sh) to test some things in docker.

License
-------

BSD

Contributors
------------

- [Paulius Mažeika](https://github.com/pauliusm)
