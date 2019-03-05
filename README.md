# entropy_rng

Increase the entropy available in the system

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
