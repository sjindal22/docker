# Docker

Container is a kind of VM (not exactly a VM though), waffed application
within a single host. Within the container it looks like a
real standalone Linux VM. Essentially packaging everything you need in your
environment for that application.

## A typical deployment infrastructure looks like below:

1. Infrastructure: This layer has racks and servers.
Hypervisor: Have vsphere, used to spin VMs.
VM is used for deploying applications.

It is cumbersome to deploy multiple applications on a single VM for following
reasons:
1. Binary conflicts.
2. Hitting CPU performance.
3. Loadbalancing.

## How does container deployment look like and why is it better?

Docker will be used for deploying multiple applications on a single VM.
Thus provides flexibility; containers are packaged as images.

