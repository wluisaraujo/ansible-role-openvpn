[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-OpenVPN-blue.svg)](https://galaxy.ansible.com/wluisaraujo/openvpn)[![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-openvpn.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-openvpn)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [OpenVPN](https://openvpn.net/)
------------

Description
------------

 * [Ansible](https://www.ansible.com) role for [OpenVPN](https://openvpn.net/)
 
Requirements
------------

 *

Installation
------------

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.openvpn
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.openvpn/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - openvpn
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
