# Ansible

## Scripts

```shell
# Build Docker
./build-docker

# Run Docker
./run-docker
```

## Ansible-Playbook

```shell
ansible-playbook main.yml

# Run only tasks with tag "node"
ansible-playbook main.yml -t node
```

## Ansible-Vault

```shell
ansible-vault encrypt test.txt
ansible-vault decrypt test.txt
```

## Resources

- https://frontendmasters.com/courses/developer-productivity/
- https://theprimeagen.github.io/dev-productivity/
- https://github.com/ThePrimeagen/ansible
- https://github.com/ThePrimeagen/.dotfiles
- https://github.com/geerlingguy/mac-dev-playbook/blob/master/.github/workflows/ci.yml
- https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_tags.html
