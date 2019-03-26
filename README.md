# Ansible Role: Cumulus ONIE

This role can update the ONIE bootloader.

Naturalis uses this role together with a private inventory.

## Requirements

None.

## Role Variables

Available variables are listed below.
```bash
cl_oob_server: 192.168.144.5
```

## Dependencies

None.

## Example Playbook
```bash
    - hosts: switches
      roles:
        - ansible-cumulus-onie
```
## License

Apache2
