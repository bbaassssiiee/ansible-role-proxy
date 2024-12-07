proxy
=========

A role to install a Squid proxy.

Requirements
------------

Linux.

Role Variables
--------------

```yml
# defaults
proxy_port: 3128
```

Dependencies
------------
Docker & Systemd.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: web
      roles:
         - role: bbaassssiiee.proxy
```
