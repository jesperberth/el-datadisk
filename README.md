el-datadisk
=========

Add data disk to Enterprise Linux using LVM

Requirements
------------


Role Variables
--------------

*  device
*  storagename
*  storagepath

´´´bash

---

device: "/dev/sdb"
storagename: "datadisk"
storagepath: "/mnt/datadisk"

´´´´

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - jesperberth.el_datadisk

License
-------

BSD

Author Information
------------------

Jesper Berth
