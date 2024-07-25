BARK: BASELINE
=========

BASELINE configuration of a Linux server with limited assumptions on purpose.

Assumes you want to install a default package set, configure NTP, and setup 
initial firewall rules.

Requirements
------------

Currently only supports Debian/Ubuntu machines running `apt` and `ufw`.

Role Variables
--------------

**BASELINE_REQUIRED_PACKAGES**:

A comma separated list of packages to be installed by the distribution's
package manager.



Dependencies
------------

All Ansible roles are configuration driven. Provide inventory specific 
variables in group_vars/, include them in the shell's environment, or 
provide them when prompted by the role at execution time.


License
-------

MIT

Author Information
------------------

A Bitmotive Project: Fueled by Caffeine, Written with Purpose
