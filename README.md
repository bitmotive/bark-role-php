BARK: PHP
=========

Install PHP on a server and include required packages.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**PHP_REQUIRED_PACKAGES**:

A comma separated list of php packages to be installed with the OS package 
manager.

Dependencies
------------

Currently dependent on Debian/Ubuntu due to reliance on `apt`.


License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com
