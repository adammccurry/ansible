# perun-ansible-sendmail

Ansible galaxy role cesnet.sendmail that installs sendmail and add relays.

## Requirements


## Role variables
* sendmail_relays - List of relays

## Available tags
* install
* configuration

## Example playbook
```
- hosts: all
  remote_user: root
  vars:
    sendmail_relays: []
  roles:
    - cesnet.sendmail
```