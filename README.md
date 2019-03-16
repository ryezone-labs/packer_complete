ryezone_labs/packer_complete
=========

This role contains the common logic I use to finalize my vagrant boxes in packer.

Role Variables
--------------

| Variable Name | Type | Default Value | Description |
| ------------- | ---- | ------------- | ----------- |


Example Playbook
----------------

```yaml
---
- hosts: 127.0.0.1
  connection: local
  vars:
    packer_init_desktop: false
  roles:
    - rz.packer_init
    - rz.packer_complete
```

License
-------

BSD
