# Sofing • Ansible • Docker

**Different Ansible roles for for working in a Docker environment**

```
01010011 01001111 01000110 01010100 01001001 01001110 01000111 
```

## About

### softing_docker_user

This role creates a docker user, adds it to the docker group, and saves ssh keys for remote access with that user's permissions

### Examples

```yaml
- ansible.builtin.include_role:
    name: softing_docker_user
  vars:
    docker_user_hostname: "user.hostname.com"
    docker_user_pubkeys:
      - Key1
      - Key2
```

## License

[GNU GPLv3](../../LICENSE)
