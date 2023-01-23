# Ansible Collection - softing.docker

## Available roles

### softing/docker/login

Authorization in the Docker Registry

```yaml
- ansible.builtin.include_role:
    name: softing/docker/login
  vars:
    docker_login_registry_url: "registy.url.com"
    docker_login_username: "username"
    docker_login_password: "password"
```

### softing/docker/user

Create a docker user

```yaml
- ansible.builtin.include_role:
    name: softing/docker/user
  vars:
    docker_user_hostname: "user.hostname.com"
    docker_user_pubkeys:
      - Key1
      - Key2
```
