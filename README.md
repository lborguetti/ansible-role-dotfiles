ansible-role-dotfiles
=========

[![Build Status](https://travis-ci.org/lborguetti/ansible-role-dotfiles.svg?branch=master)](https://travis-ci.org/lborguetti/ansible-role-dotfiles)

This role install my dotfiles.

Requirements
------------

None.

Role Variables
--------------

None.

Role Tags
--------------

- `dotfiles`: only run dotfiles tasks.
- `nvim`: only run nvim tasks.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-dotfiles }

License
-------

MIT

Author Information
------------------

Luciano Antonio Borguetti Faustino
