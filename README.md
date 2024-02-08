# Desktop git role

[![Lint Code Base](https://github.com/agl4/ansible-role-git/actions/workflows/linter.yml/badge.svg)](https://github.com/agl4/ansible-role-git/actions/workflows/linter.yml)
[![Molecule testing](https://github.com/agl4/ansible-role-git/actions/workflows/ci.yml/badge.svg)](https://github.com/agl4/ansible-role-git/actions/workflows/ci.yml)

Ansible role to make sure git is installed. Does no more, no less.

## Requirements

None.

## Role Variables

None required.

### `git_packages`

Optionally the role default git package list can be overriden with
this variable set in your inventory.

## Dependencies

None.

## Example Playbook

```yaml
  - hosts: localhost
    vars:
    roles:
       - agl4.git
```

## License

BSD

## Author Information

[@agl4](https://github.com/agl4)
