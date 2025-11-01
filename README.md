# Rôle Ansible: Template

[![CI](https://github.com/lacrif/ansible-role-temaplate/actions/workflows/ci.yml/badge.svg)](https://github.com/lacrif/ansible-role-template/actions/workflows/ci.yml)

An Ansible Role that installs ???

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
# List variable
```

## ## Exemple de Playbook

```yaml
- hosts: all
  roles:
    - lacrif.template
```

## Molecule

Lancer les tests

```bash
export MOLECULE_DISTRO_NAME=rockylinux && export MOLECULE_DISTRO_VERSION=9 && molecule test
export MOLECULE_DISTRO_NAME=ubuntu && export MOLECULE_DISTRO_VERSION=noble && molecule test
export MOLECULE_DISTRO_NAME=debian && export MOLECULE_DISTRO_VERSION=trixie && molecule test
```

## License

MIT / BSD

## Author Information

Lacrif
