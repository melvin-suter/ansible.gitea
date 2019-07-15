Gitea Setup with Ansible
===========================

This Ansible Role installs, configures and updates a Linux Gitea server. The following tasks will be configured:
* `Install and configure MariaDB`
* `Install and configure Gitea`
* `Install and configure Nginx`
* `Install and configure fail2ban`
* `Install and configure Let's Encrypt`

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`

Dependencies
------------

This Ansilbe Role has dependencies to these Ansilbe Roles:
* uniqconsulting.mariadb

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/playbook_graylog.yml`
