# update-grub for Fedora Linux

This is a bash script which helps you easily update grub on BIOS and UEFI systems.
It will automatically detect which one you are using and update the correct configuration.
It is equivalent to the 'update-grub' command found on Debian and Ubuntu.

## How to Install

```bash
git clone https://github.com/StanGenchev/update-grub-fedora.git
sudo cp update-grub-fedora/update-grub /usr/sbin/
sudo chmod +x /usr/sbin/update-grub
```
