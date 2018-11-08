nethserver_vagrant_base_setup
=========

Role for Nethserver vagrant base setup steps

Role Variables
--------------

* `nethserver_hostname`: hostname of the nethserver instance, default `qa.sever.neth`
* `static_greens`: configure as static all green interfaces, default `false`

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: amygos.nethserver_vagrant_base_setup

License
-------

MIT
