# Mini-cluster
-------------------------

## Objectives

The objectives are:
- to autoamte the creation of a set of virtual machines (VMs) to natively install Kubernettes (K8s) on top of them.
- to automate the provision of the VMs with basic services required to get the K8s up and running.
- to use K8s to deploy an orchestrated set of containers.



## Pre-requisites

### Hardware
Laptop with at least 8 Gb memory (recommended 16 Gb, ideally 32 Gb)

### Software
1. VirtualBox(v 6.0, or higher)
* Instructions to install here: https://www.virtualbox.org/wiki/Downloads 


2. Vagrant (v 2.2.5, or higher) 
* Instructions to install here: https://www.vagrantup.com/downloads.html
* (only if using Windows 10 or Windows 8 Pro) Disable Hyper-V, see instructions to disable here: https://www.poweronplatforms.com/enable-disable-hyper-v-windows-10-8/
* Check installation with the command `vagrant -v`'

