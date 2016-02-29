# ansible-python

A Simple Ansible Role to Install Python in Remote Machines

1. Installation Steps : -

Default Python version : 2.7.10
Default Pip Version : 8.0.2

To Install with Default settings: -
  ansible-playbook -s main.yml
  
To Install specific python versions: -
  ansible-playbook -s main.yml --extra-vars "python_version=<python version> pip_version=<pip version>"
  
Other Packages Installed as part of this Role: -
  system_packages:
    - python-setuptools
    - python-dev
    - python-pip
    - libncurses-dev
    - git
    - make
    - gcc
    - build-essential
    - libreadline-gplv2-dev
    - libncursesw5-dev
    - libssl-dev
    - libsqlite3-dev
    - tk-dev
    - libgdbm-dev
    - libc6-dev
    - libbz2-dev
