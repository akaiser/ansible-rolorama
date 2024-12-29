# allow_tcp

```yaml
# Example use
- name: Include checkout role
  ansible.builtin.include_role:
    name: __checkout
  vars:
    __checkout_repo: 'https://git_user:git_token@github.com/github_repo'
    __checkout_dest: '/some/path'
```
