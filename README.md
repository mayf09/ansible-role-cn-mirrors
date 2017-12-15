cn-mirrors
=========

An Ansible role that configure Chinese open source mirrors.

Role Variables
--------------

Available variables are listed below, along with default values:

    apt: true
    apt_source: aliyun
    apt_host:

    pip: false
    pip_source: aliyun
    pip_host:

Configure `apt_host/pip_host` will make `apt_source/pip_source` disabled.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mayf09.cn-mirrors }

License
-------

MIT
