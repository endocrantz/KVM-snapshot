# KVM-snapshot
Automated KVM snapshots for RHEL
This script will scan the host stystem for VMs with 'virsh list', dump the VM XML, and then attempt a snapshot, copy the image, and finally pivot back.
