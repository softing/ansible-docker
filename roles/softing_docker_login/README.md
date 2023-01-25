# Sofing • Ansible • Docker

**Different Ansible roles for for working in a Docker environment**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_docker_login

This role authorizes the current user in the Docker repository

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_docker_login
  vars:
    docker_login_registry_url: "registy.url.com"
    docker_login_username: "username"
    docker_login_password: "password"
```

## License

[GNU GPLv3](../../LICENSE)
