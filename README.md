# Desktop git role

Ansible role to make sure git is installed. Does no more, no less.

## Requirements

None.

## Role Variables

None required.

### `git_packages`

Optionally the role default git package list can be overriden with this variable set in your inventory.

## Dependencies

None.

## Example Playbook

    - hosts: localhost
      vars:
      roles:
         - agoloncser.git

## License

BSD

## Author Information

https://github.com/agoloncser
