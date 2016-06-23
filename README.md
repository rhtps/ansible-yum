rhtps.yum
=========

A brief description of the role goes here.

rhtps philosophy
----------------

The rhtps Ansible roles were designed for a few specific use cases. Details [here](https://github.com/rhtps/philosophy).

Requirements
------------

None, however this is typically used in conjunction with the [rhtps.aws](https://github.com/rhtps/ansible-aws) role.

Role Variables
--------------

```rhn_username``` and ```rhn_password``` need to be set in the executing shell's environment.

Either export these, or edit ```env.sh``` and source it.

Dependencies
------------

* Internet access
* Red Hat subscriptions, if syncing from the Content Delivery Network (CDN).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - rhtps.yum

License
-------

Apache 2.0

Author Information
------------------

[Jason Callaway](https://github.com/jason-callaway) <jcallawa@redhat.com> is a Solutions Architect at Red Hat. 
