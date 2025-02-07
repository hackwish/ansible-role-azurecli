azure-cli Role
==============

Use this role to install azurecli on Ubuntu and MacOS.

Requirements
------------

- Linux Ubuntu based system
- MacOS based system
- Ansible
- Brew (for MacOS)

Example Playbook
----------------

    - hosts: azurecli
      roles:
         - { role: andrelohmann.azurecli }

License
-------

MIT

Author Information
------------------
 Based on https://github.com/andrelohmann

 Build ByDefault.

Test
----

``ansible-playbook tests/test.yml -i tests/inventory --syntax-check``

Solo Install
------------

``sudo ansible-playbook tests/test.yml -i tests/inventory``