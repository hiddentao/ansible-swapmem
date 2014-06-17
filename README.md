Ansible role: Swapmem
========

This sets up Swap space on a server if not already available. The setup 
swap space size will be twice the total system RAM size.

Dependencies
------------

None.


Example Playbook
-------------------------

This role requires Ansible facts, so ensure `gather_facts` is turned on:

```
- hosts: servers
  gather_facts: yes
  roles:
     - hiddentao.swapmem
```

License
-------

MIT

Author Information
------------------

By [Ramesh Nair](http://hiddentao.com)
