Epel repo
=========

This role is used to setup the epel repository for centos

Requirements
------------

There are no requirements as of yet

Role Variables
--------------

The most important variable is:

```
# List of all the repos
epelCentosRepoList:
  - name: epel
    state: enable
  - name: epel-testing
```

This lets you enable or disable an repo.
The standard vallue is disable


Dependencies
------------

There are no requirements for this installation

Example Playbook
----------------

    - name: epel repo install
      hosts: all
      roles:
        - ggiinnoo.epel

Upcomming features:
-------

License
-------

BSD

Author Information
------------------

    Creator: Gino Jansen
    Website: www.ginojansen.nl