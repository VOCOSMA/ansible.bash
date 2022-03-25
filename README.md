# Ansible Bash Configuration Role

This role installs a simple bashrc for the `remote_user` based on
[sensible.bash](https://github.com/mrzool/bash-sensible) and a short aliases file.

## Example Playbook

```yml
---
- hosts: all
  roles:
    - bash
```

## License

This ansible role is licensed under the term of the GPLv3.  
For further information see the `COPYING` file or [https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html).
