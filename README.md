Ansible Role: sudo
=========

[![Build Status](https://travis-ci.org/jrgoldfinemiddleton/ansible-role-sudo.svg?branch=master)](https://travis-ci.org/jrgoldfinemiddleton/ansible-role-sudo)

This role simply gives a list of users passwordless sudo rights.

Requirements
------------

`sudo` must be installed.

Role Variables
--------------

```yaml
sudo_passwordless_users: []
```

List of users to be granted passwordless sudo rights.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - jrgoldfinemiddleton.sudo
```

License
-------

BSD

Author Information
------------------

Created in 2018 by [Jason Goldfine-Middleton](https://github.com/jrgoldfinemiddleton).
