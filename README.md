# Panhandler Packer 


An automated build tool for VM images containing the latest Panhandler. This currently builds 
images using VMWare Fusion or Workstation using Packer and Ansible.

## What is Panhandler?

https://panhandler.readthedocs.io/en/master/ 

Panhandler is a GUI tool used to manage and deploy PAN-OS and Panorama Skillets. For more information about 
Skillets, check out the [Skillet District](https://live.paloaltonetworks.com/t5/Skillet-District/ct-p/Skillets) on 
Live.


## Pre-reqs

* Packer - https://packer.io/
* VMWare - https://www.vmware.com/products/fusion.html



## Quick Start

To build the VM using VMWare Fusion or Workstation:

```bash

packer build -on-error=abort panhandler-vmware.json

```

