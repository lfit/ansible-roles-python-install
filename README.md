python-install
==============

A brief description of the role goes here.

Requirements
------------

None.

Role Variables
--------------

pyenv_version: Version of pyenv to install.
python34_version: Version of Python 3.4 to install.
python35_version: Version of Python 3.5 to install.
python36_version: Version of Python 3.6 to install.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lfit.python-install }

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering
