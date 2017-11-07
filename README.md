Role Name
=========

An Ansible role based on https://access.redhat.com/solutions/137833

Requirements
------------

RHEL and a desire to run in FIPS mode

Role Variables
--------------

N/A

Dependencies
------------

rhel-7-server-rpms is need to install dracut-fips and dracut-fips-aesni

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: all \n
  become: yes \n
  roles: \n
    - ansible.fips


License
-------

BSD

Author Information
------------------

https://github.com/rhcreynold
# ansible_fips
