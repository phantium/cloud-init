# cloud-init
Cloud init examples and usage

# Usage
Install package libguestfs-tools (Debian/Ubuntu)

Run update-guestfs-appliance

sudo guestfs --rw -a ubuntu-trusty.img

run

list-filesystems - to see which filesystems are available

mount /dev/sda1 /

edit /etc/cloud/cloud.cfg

after the changes are made be sure to use:

sync - to flush all changes to the disk image
