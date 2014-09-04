Hostname
=========

Very simply sets the host name.

Requirements
------------

Only tested on Ubuntu 14.04.

Role Variables
--------------

```
# The host name
hostname_hostname:
# The domain name to make it a FQDN
hostname_domain:
```
Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

```
---
- hosts: servers
  vars:
    hostname_hostname: server1
    hostname_domain: example.com
  roles:
     - remailednet.hostname
```

License
-------

MIT