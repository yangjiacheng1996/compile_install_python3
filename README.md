Role Name
=========

download Python.tgz from www.python.org and compile it,make install and soft link.

Requirements
------------

can only run on all Debian+Ubuntu series and RHEL7+CentOS7

Role Variables
--------------

python_version=3.8.3 , detailed version
python_major_version=3.8  , major version

Dependencies
------------

No dependency

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

      - name: install python 3 on Debian series and EL7
        hosts: Python3
        become: True
        gather_facts: True
        roles:
          - role: compile_install_python3_from_local

License
-------

Apache 2

Author Information
------------------

github : yangjiacheng1996
