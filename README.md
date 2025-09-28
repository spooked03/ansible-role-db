## Ansible Role: DB

### Role Variables

```yaml
# Default variables
db_root_password: root
db_name: testdb
```

## Example Playbook

```yaml
- hosts: db
    roles:
        - role: spooked03.db
            vars:
                db_root_password: strongpassword
                db_name: myapp
```

## License

GPLv3

