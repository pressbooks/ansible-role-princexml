PrinceXML
=========

Installs [PrinceXML](https://princexml.com) on Ubuntu 16.04.

Requirements
------------

Optionally, a PrinceXML `license.dat` file.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    prince_package_uri: https://www.princexml.com/download/prince_10r7-1_ubuntu16.04_amd64.deb

The URI of the desired PrinceXML package. Defaults to the latest stable version for Ubuntu 16.04/64-bit.

    prince_license: ''

The local path to your PrinceXML `license.dat` file (optional).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - greatislander.princexml

License
-------

MIT

Author Information
------------------

This role was created in 2016 by [Ned Zimmerman](https://github.com/greatislander) for [Pressbooks](https://pressbooks.org).
