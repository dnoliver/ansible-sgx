# Ansible SGX

> Configure a system with the Intel SGX Development Environment

This playbook install the required dependencies to run SGX Examples on a given host.

## Install

```shell
# Install ansible
dnf install -y ansible
# Install ansible.posix collection
ansible-galaxy collection install ansible.posix
# Install ansible-lint
dnf install -y python3-ansible-lint
```

## Run

```shell
ansible-playbook ansible-playbook.yml
```

## Lint

```shell
ansible-lint ansible-playbook.yml
```
