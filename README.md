Ansible Role: Oracle MySQL Repository [![Build Status](https://travis-ci.org/ewypych/ansible-role-oracle-mysql-repo.png?branch=master)](https://travis-ci.org/ewypych/ansible-role-oracle-mysql-repo)
=========

This role can be used to install the Oracle MySQL Repository.

Requirements
------------

None.

Role Variables
--------------

Default variables from default/main.yml:

```
# default repository URL
repo_url: http://repo.mysql.com/{{ __distro_package  }}

# default MySQL version - you can choose one of the following versions:
# 5.5, 5.6, 5.7, 8.0
# type version WITHOUT the dot
# Works only with RedHat distributions
mysql_version: 57
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ewypych:oracle-mysql-repo }

License
-------

[MIT](https://tldrlegal.com/license/mit-license)

Author Information
------------------

[Emil Wypych](https://emilwypych.com) [@gmail](wypychemil@gmail.com)
