[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-wannier-tools.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-wannier-tools)

# Ansible Role: marvel-nccr.wannier_tools

An Ansible role that installs [WannierTools](https://github.com/quanshengwu/wannier_tools) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.wannier_tools`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: marvel-nccr.wannier_tools
```

## Development and testing

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and [Docker](https://www.docker.com/) for tests.

After installing [Docker](https://www.docker.com/):
```bash
git clone https://github.com/marvel-nccr/ansible-role-wannier-tools marvel-nccr.wannier_tools
# Note: folder name marvel-nccr.wannier_tools is required for running tests
cd marvel-nccr.wannier_tools
pip install -r requirements.txt  # Installs molecule
molecule test  # runs tests
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
