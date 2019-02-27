# entropy_rng

nsible role to install selinux auditing tools

## Installation

```yaml
   ansible-galaxy install zerodowntime.entropy_rng
```

## Requirements

This role requires Ansible 2.5 or higher.

Supported platforms:

```yaml
  platforms:
    - name: EL
      versions:
        - 7
```

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:

  - role: zerodowntime.entropy_rng
```

## License

[Apache License 2.0](LICENSE)

## Support

ansible@zerodowntime.pl
