# Docker Vagrant Setup

## Introduction
This project contains example `Vagrantfile`s for bringing up a Linux VM with Docker installed. There are 2 examples:
1. `docker/`: This brings up a single Linux VM with Docker installed
2. `docker-swarm/`: This brings up several VMs to form a Docker Swarm cluster

## Assumptions
Following is installed on the host machine:
* `Vagrant` (tested: 2.2.10)
* `Ansible` (tested: 2.10.1)

## Running
```console
cd docker
vagrant up
```

OR

```console
cd docker-swarm
vagrant up
```
