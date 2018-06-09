sshd-config Role
=========


Role Variables
--------------

```
# Change to no to disable tunnelled clear text passwords
password_authentication: 'no'

# Authentication:
permit_root_login: prohibit-password
```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/sshd-config
#   version: master
#   name: sshd-config
```

License
-------

[MIT](LICENSE)