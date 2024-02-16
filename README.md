# Ansible Role: `gcoop-libre.ansible_tools`

This role, install and configure useful scripts for _Ansible_ from `ansible_tools` git repository.

## Tags Summary


| _date_     | _tag_      | _description_                                                                    |
|------------|------------|----------------------------------------------------------------------------------|
| 2024-02-16 | `  v0.1.0` | add playbooks for Install and Configure Ansible Tools and Generate CMDB from AWX |

## Requirements

`ansible_tools` from git repository:

- https://gitlab.com/gcoop-libre/ansible_tools
- https://gitlab.com/osiux/ansible_tools
- https://github.com/gcoop-libre/ansible_tools
- https://github.com/osiris/ansible_tools
- https://codeberg.org/osiux/ansible_tools

## Role Variables

Available variables with default values in `defaults/main/*.yml`.

## Dependencies

- `ansible`
- `ansible-cmdb`
- `awx-cli`
- `coreutils`
- `git`
- `gpg`
- `jq`
- `moreutils`
- `pass`
- `tree`
- `yq`

## Example Playbook

```yaml

---

- name: Install Ansible Tools
  hosts: [all]

  roles:
    - role: gcoop-libre.ansible_tools

```

## Useful Playbooks

| _playbook_                      | _description_                         |
|---------------------------------|---------------------------------------|
| [`cmdb.yml`](../tests/cmdb.yml) | Generate _CMDB_ from _AWX_            |
| [`test.yml`](../tests/test.yml) | Install and configure _Ansible Tools_ |

## License

GNU General Public License, GPLv3.

## Author Information

This role was created in 2024 by
 [Osiris Alejandro Gomez](https://osiux.com/), worker cooperative of
 [gcoop Cooperativa de Software Libre](https://www.gcoop.coop/).
