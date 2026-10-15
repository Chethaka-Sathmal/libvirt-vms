# libvirt-vms

Spin up virtual machines on QEMU/KVM (Kernel-based Virtual Machine) using libvirt, configured on first boot with cloud-init.

## Structure

- `cloud-init/template.yaml` — base cloud-init config (users, SSH (Secure Shell) keys, packages) applied when a virtual machine first boots.
