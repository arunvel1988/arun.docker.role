
## Example Playbook

```yaml
- hosts: all
  become: yes
  roles:
    - unxnn.docker
```
ansible-playbook 1.yaml -K
