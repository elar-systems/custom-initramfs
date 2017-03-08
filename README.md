This uses Busybox static binary from Fedora's RPM to create a simple initramfs.

```bash
./create_initramfs.sh --help

Ex.:  ./create_initramfs.sh --arch arm --dir "${PWD}" --tty ttyS0
```
