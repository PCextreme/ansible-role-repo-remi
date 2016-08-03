# Ansible Role: Remi repository

Installs Remi repository

## Supported platforms

```
CentOS 6 & 7
```

## Requirements

None

## Role Variables

Enable remi-php55:

```
remi_enable_php55: true
```

Enable remi-php56:

```
remi_enable_php56: false
```

## Dependencies

None

## Example Playbook

```
- hosts: servers
  roles:
    - { role: pcextreme.repo-remi }
```

## Credits

- [Attila van der Velde](https://github.com/vdvm)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
