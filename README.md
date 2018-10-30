nethesis_addrepos
=========

Role for add Nethesis Enterprise repositories

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: amygos.nethesis_addrepos

The repositories are not enable by default, can be enabled by setting the variable `repositories_enabled` to `true`

    - hosts: servers
      roles:
         - { role: amygos.nethesis_addrepos, repositories_enabled: true }

License
-------

MIT
