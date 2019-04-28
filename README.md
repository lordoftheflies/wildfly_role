Role Name
=========

Role for configure Wildfly as a systemd service in Ubuntu 18.04 LTS.

Requirements
------------

Wildfly needs JDK8+ (geerlingguy.java)

Role Variables
--------------

* Listening address
* Listening port

Dependencies
------------

Roles hosted in Galaxy:

* Wildfly needs JDK8+ (geerlingguy.java)

Example Playbook
----------------

Including an example of how to use the role:

```yaml
    - hosts: sa
      roles:
         - role: lordoftheflies.ansible_role_wildfly
```

License
-------

BSD

Author Information
------------------

Name: László, Hegedűs\
Email: laszlo.hegedus@cherubits.hu\
Home: https://www.cherubits.hu

