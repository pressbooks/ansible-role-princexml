PrinceXML
=========

[![Build Status](https://img.shields.io/travis/pressbooks/ansible-role-princexml.svg?style=flat-square)](https://travis-ci.org/pressbooks/ansible-role-princexml) [![GitHub release](https://img.shields.io/github/release/pressbooks/ansible-role-princexml.svg?style=flat-square)](https://github.com/pressbooks/ansible-role-princexml/releases/latest)

Installs [PrinceXML](https://princexml.com) on Ubuntu 16.04 or 18.04 or 20.04.

Requirements
------------

Optionally, a PrinceXML `license.dat` file.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    # PrinceXML package URI for Ubuntu 16.04 Xenial. Defaults to latest stable 64-bit.
    prince_package_uri_ubuntu_xenial: https://www.princexml.com/download/prince_13.5-1_ubuntu16.04_amd64.deb

    # PrinceXML package URI for Ubuntu 18.04 Bionic. Defaults to latest stable 64-bit.
    prince_package_uri_ubuntu_bionic: https://www.princexml.com/download/prince_13.5-1_ubuntu18.04_amd64.deb
    
    # PrinceXML package URI for Ubuntu 20.04 Focal. Defaults to latest stable 64-bit.
    prince_package_uri_ubuntu_focal: https://www.princexml.com/download/prince_13.5-1_ubuntu20.04_amd64.deb

    # The local path to your PrinceXML `license.dat` file (optional).
    prince_license: ""


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - pressbooks.princexml

License
-------

MIT

Author Information
------------------

This role was created in 2016 by [Ned Zimmerman](https://github.com/greatislander) for [Pressbooks](https://pressbooks.org).
