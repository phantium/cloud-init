# cloud-init
Cloud init examples and usage

# Usage
Install package libguestfs-tools (Debian/Ubuntu)

sudo guestfish -i --rw imagename.qcow2

vi /etc/cloud/cloud.cfg

after the changes are made be sure to use:

sync - to flush all changes to the disk image

Full reference: https://cloudinit.readthedocs.org/
