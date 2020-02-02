# Continued support for phison kernel module.
## phison kernel module is for PCcard (PCIe) SSD's. They contain a IDE controller.

* Copy or symlink phison-0.1 to /usr/src
* Build and install with:
```
sudo dkms add -m phison -v 0.1
sudo dkms build -m phison -v 0.1
sudo dkms install -m phison -v 0.1
sudo update-initramfs -u
```
