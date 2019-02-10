# machine-image-jessie

This creates a minimally bootable "machine image" rootfs for Debian Jessie using Docker multi-stage builds and debootstrap. The resulting rootfs can be used in an `initramfs` or by extracting to a partition and installing a bootloader - it's not designed to use as a base for Docker containers.
