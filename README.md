## Abandoned project

As in my opinion cloud-init is no longer a proper system to use for modifying system images, I no longer have any plans to update this repository with examples.  
This repository will still serves as a good example as to what potential cloud-init has, which had been my purpose all along.  

Cloud-init should be used if you have a certain requirement where during startup you need to execute a certain call to a service/modify system settings on each bootup and possibly also provide meta-data for this as this is also possible together with OpenStack.

# cloud-init
Cloud init examples and usage

# Usage
Install package libguestfs-tools (Debian/Ubuntu)

sudo guestfish -i --rw imagename.qcow2

vi /etc/cloud/cloud.cfg

after the changes are made be sure to use:

sync - to flush all changes to the disk image

Full reference: https://cloudinit.readthedocs.org/
