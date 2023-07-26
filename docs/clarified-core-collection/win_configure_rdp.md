# win_configure_rdp

Role for enabling or disabling RDP on Windows hosts.

## Requirements

None

## Role Variables

Check the `defaults/main.yml` file for the full list of variables.

## Dependencies

None

## Example Playbook

```yaml
# Include the role in tasks
- name: Name of the task
  ansible.builtin.include_role:
    name: clarified.core.win_configure_rdp
```

```yaml
# Include the role in meta
---
- dependencies:
    - role: clarified.core.win_configure_rdp
```