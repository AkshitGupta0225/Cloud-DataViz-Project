VM Setup Guide (Cloud-DataViz-Project)

Objective
To create a separate Ubuntu environment using VirtualBox for experimenting with Tableau Server and Linux-based deployment setup.

VM Environment Details
Hypervisor: Oracle VirtualBox

Guest OS: Ubuntu 22.04.5 LTS (64-bit)

ISO Used: ubuntu-22.04.5-desktop-amd64.iso

RAM Allocated: 4 GB

CPU Cores: 2

Disk Size: 25 GB (VDI, dynamically allocated)

Network Mode: NAT

Steps Followed
Installed Oracle VirtualBox on Windows host.

Downloaded Ubuntu 22.04.5 ISO.

Created new virtual machine:

Type: Linux

Version: Ubuntu (64-bit)

Allocated RAM and processors.

Created new virtual hard disk (VDI format).

Attached Ubuntu ISO as startup disk.

Completed Ubuntu installation.

Skipped online account and Active Directory integration.

Performed system update after installation.

Purpose of VM in This Project
To simulate a cloud-like Linux environment.

To explore feasibility of Tableau Server installation on Linux.

To understand cross-platform deployment.

To isolate experimental environment from host system.

Observations
Tableau Desktop is not supported on Linux.

Tableau Desktop installed on Windows host.

VM primarily used for experimentation and environment setup practice.