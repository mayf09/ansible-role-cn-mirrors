cn-mirrors
=========

An Ansible role that configure Chinese open source mirrors.

Role Variables
--------------

Available variables are listed below, along with default values:

    cm_user: {{ ansible_env.USER }}

    cm_apt_enable: true
    cm_apt_source: aliyun
    cm_apt_host:

    cm_pip_enable: false
    cm_pip_source: aliyun
    cm_pip_host:

    cm_npm_enable: false
    cm_npm_source: taobao
    cm_npm_host:

Configure `apt_host/pip_host` will make `apt_source/pip_source` disabled.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mayf09.cn-mirrors }

License
-------

MIT
