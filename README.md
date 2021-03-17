# openbsd_kvm
This is for a guest OpenBSD VM on a Linux KVM host.
Using KVM and virt-manager I have discovered that the CPU usage of OpenBSD on the host is higher than the real CPU usage of the guest VM when it is an OpenBSD guest.
Playing with the XML configuration of it I have found how to correct the extra CPU load (about 10%) from the real usage.
