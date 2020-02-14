---
title: 'Ansible Role: Wildfly Application Server'
description: 'Guide to maintain Wildfly Application Server'
---

# Ansible Role: Wildfly Application Server

Role for configure Wildfly as a systemd service in Ubuntu 18.04 LTS.

## Requirements


Ansible sudoer user must exists on the remote machine and public ssh key needs to added to authorized hosts. 
Wildfly needs JDK8+.

## Role Variables

* Listening address
* Listening port

## Dependencies

Roles hosted in Galaxy:

* Wildfly needs JDK8+ (geerlingguy.java)

## Example Playbook

Including an example of how to use the role:

```yaml
    - hosts: sa
      roles:
         - role: lordoftheflies.ansible_role_wildfly
```

## License

Apache-2.0

Author Information
------------------

Name: László, Hegedűs\
Email: laszlo.hegedus@cherubits.hu\
Home: https://www.cherubits.hu

