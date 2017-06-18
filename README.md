# Archlinux builder

The collection of bash scripts I usually use to assemble a new archlinux-based system.

### General receipt:

1. Boot from your removable disk with live Archlinux.
2. Partition the disks.
3. Mount partitions in the correct order.
4. Install base system using `pacstrap`.
5. Generate `fstab` and change root into the new system. Now you can use scripts starting folder `2-conf`.
