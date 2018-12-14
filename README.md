# Ansible Role: Moosh
Installs Moosh for Moodle.

## Requirements
None.

## Role Variables
None.

## Dependencies
None.

## Example Playbook
```yaml
- hosts: server
  become: yes

  tasks:
  - import_role:
      name: damianlewis.moosh
```
