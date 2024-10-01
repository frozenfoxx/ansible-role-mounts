# ansible-role-mounts

Ansible role to manage filesystem mounts

# Requirements

- None

# Variables

- `mounts_bind_mount_paths`: permissions for bind mounts
- `mounts_bind_mounts`: paths and options for bind mounts
- `mounts_posix_mount_paths`: permissions for POSIX mounts
- `mounts_posix_mounts`: paths and options for POSIX mounts

# Usage

```
- hosts: servers
  roles:
    - { role: frozenfoxx.mounts }
```

# License

Apache-2.0
