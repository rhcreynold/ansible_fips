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
For RHEL 7:

rhel-7-server-rpms is need to install dracut-fips and dracut-fips-aesni

For RHEL 6:

rhel-6-server-optional-rpms and rhel-6-workstation-optional-rpms

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  become: yes
  roles:
    - ansible.fips
```

License
-------

BSD

Author Information
------------------

https://github.com/rhcreynold
