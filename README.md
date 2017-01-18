nofloppy
========

[![Build Status](https://travis-ci.org/cognifloyd/ansible-role-nofloppy.svg?branch=master)](https://travis-ci.org/cognifloyd/ansible-role-nofloppy)

Blacklist the floppy module and omit it in dracut

Requirements
------------

Only tested on CentOS 7

Role Variables
--------------

Dracut gets a couple variables from the nofloppy dict (see defaults/main.yml).

Dependencies
------------

This depends on jtyr.ansible-dracut.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: cognfiloyd.nofloppy

License
-------

MIT

Author Information
------------------

By Jacob Floyd (@cognifloyd) while working for Theatro Labs, Inc. (theatro.com). Adapted from [centos7.ks](https://github.com/CentOS/sig-cloud-instance-build/blob/5162d86c/vagrant/centos7.ks)
