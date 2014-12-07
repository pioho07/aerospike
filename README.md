Role Name:Aerospike Role
=========

Aerospike Cluster build role. & Aerospike Management Console(AMC) Add

Requirements
------------

centos6 is been verified only in the system.
This role will be only available in RH system Linux.

Role Variables
--------------

The default variables are described in the aerospike / defaults / main.yml.
Contents of the default value and the default configuration parameters of Aerospike, you Yes put the latest version value at the time of playbook created.
Please be required value is described in variable aerospike / vars / main.yml overwritten.

Dependencies
------------

Unnecessary

Example Playbook
----------------

    - hosts: servers
      roles:
         - pioho07.aerospike

License
-------

BSD

Author Information
------------------

of infrastructure engineers cyberz Uehara
