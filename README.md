# Ansible Role 

## Status

[![Build Status](https://travis-ci.org/lordoftheflies/ansible_role_docker.svg?branch=master)](https://travis-ci.org/lordoftheflies/ansible_role_docker)
[![Travis CI](http://img.shields.io/travis/lordoftheflies/ansible_role_docker/default.svg?style=flat)](http://travis-ci.org/lordoftheflies/ansible_role_docker/default)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)

## Description

ansible_role_docker is an Ansible role used to...

## Roadmap

* [ROADMAP.md](ROADMAP.md)

## References

* [docs.ansible.com](https://docs.ansible.com/)

## Requirements

### Production

* Ansible

### For Local Testing

* [Vagrant](https://www.vagrantup.com/) - (Tested using version 2.1.1)
* Vagrant plugins:
  * [vagrant-disksize (0.1.2)](https://github.com/sprotheroe/vagrant-disksize)
  * vagrant-vbguest (0.15.2) - Recommended [vagrant-vbguest](https://github.com/lordoftheflies/vagrant-vbguest)
  * vai (0.9.3) - For testing with multiple vms [vagrant-plugin-vai](https://github.com/lordoftheflies/vagrant-plugin-vai) 
* [Virtual Box](https://www.virtualbox.org/)
  * Tested using Version 5.2.14 r123301 (Qt5.6.1) 

## Variables

### defaults/main.yml

* [defaults/main.yml](defaults/main.yml) contains all of the required variables.

### project_name/site.yml example

* [example_ansible_role_docker.yml](files/example_site.yml) may contain an example entry.

## Testing

To test with all VM's defined in Vagrantfile run the following:

```shell
cd ansible-role-ansible_role_docker
vagrant up
```

To run on a specific VM's
```shell
vagrant up xenial
```

### VM's tested with Vagrant and Virtualbox

pass, fail, untested

| Distribution | Results  |
| ------------ | -------- |
| precise      | untested |
| trusty       | untested |
| xenial       | untested |
| bionic       | untested |
| CentOS 6     | untested |
| CentOS 7     | untested |

## Authors and License

* [László Hegedűs](mailto:laszlo.hegedus@cherubits.hu)

License: [Apache-2.0](Apache-2.0)

> **NOTE**: This skeleton generated using [galaxy-role-skeleton](https://github.com/cjsteel/galaxy-role-skeleton)

## Referencies

* [Docker Manual](https://docs.docker.com/get-started/)
* [Installation Guide](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* [Postinstall steps](https://docs.docker.com/install/linux/linux-postinstall/)
