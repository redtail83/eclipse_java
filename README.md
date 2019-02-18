Ansible Role: eclipse_java
=========

Install Eclipse for CentOS and Ubuntu linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
# Base URL of Eclipse download site.
site_url: http://ftp.jaist.ac.jp/pub/eclipse/technology/epp/downloads/release/2018-12/R/

# Archive file name.
file_name: eclipse-java-2018-12-R-linux-gtk-x86_64.tar.gz
```

Dependencies
------------

This role depends on:

* redtail83.java_gui

Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.eclipse_java }

License
-------

MIT
