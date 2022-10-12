## Errors and solutions

### GNS3
Could not access KVM kernel module: Permission denied
qemu-system-x86_64: failed to initialize KVM: Permission denied

<b>Solution</b>
Steps:
1. sudo chown root:{username} /dev/kvm
2. sudo systemctl restart libvirtd.service
(Repeat these every time you need to start a machine)

### Generate Network attacks
https://www.activestate.com/blog/python-for-cybersecurity-testing/
