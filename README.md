BARK: BASELINE
=========

BASELINE configuration of a Linux server with sane defaults.

Assumes you want to install a default package set, configure NTP, and setup 
initial firewall rules.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 


Role Variables
--------------

**BASELINE_REQUIRED_PACKAGES**:

A comma separated list of packages to be installed by the distribution's
package manager.



Dependencies
------------

Currently dependent on Debian/Ubuntu due to reliance on `apt` and `ufw`. 

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com
