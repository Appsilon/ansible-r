Ansile Role: R
=========

An Ansible role that sets up multiple R versions.


[![CI](https://github.com/Appsilon/ansible-r/workflows/CI/badge.svg)](https://github.com/Appsilon/ansible-r/actions/workflows/ci.yml)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-appsilon.r_language-blue.svg)](https://galaxy.ansible.com/appsilon/r_language)

Requirements
------------

None.

Role Variables
--------------

* `downloads_path` [default: `/var/lib/ansible/downloads`]: Directory name where
  artefacts will be downloaded (will be created)
* `r_versions` [default: `4.1.0, 4.0.0, 3.6.3, 3.5.3, 3.5.0`]: R versions to install

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
     - appsilon.r_language
```

License
-------

MIT

Author Information
------------------

[`Appsilon`](https://appsilon.com/)
