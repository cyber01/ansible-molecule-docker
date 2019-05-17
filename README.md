# Dockerfiles for ansible tests (molecule)

| System | Version | Docker Pulls  |
| ------ | ------- | ------------- |
| Fedora | 29 & latest  | [![Docker Pulls](https://img.shields.io/docker/pulls/cyber01/ansible-molecule-fedora.svg)](https://hub.docker.com/r/cyber01/ansible-molecule-fedora) |
| CentOS | 7 | [![Docker Pulls](https://img.shields.io/docker/pulls/cyber01/ansible-molecule-centos.svg)](https://hub.docker.com/r/cyber01/ansible-molecule-centos) |

Also contains docker images for [molecule](https://github.com/metacloud/molecule) testing framework. Those images only for CI ansible tests.
Every image comes with packages:
- systemd
- python
- bash
- iproute
- net-tools
- sudo
- deltarpm (only centos 7 and fedora)
- epel-release (only centos 7)
- initscripts (only centos 7 and fedora)
- ansible 
- which
- git
- selinux-policy (only centos 7 and fedora)
- libselinux-python (only centos 7 and fedora)
- policycoreutils-python (only centos 7 and fedora)
