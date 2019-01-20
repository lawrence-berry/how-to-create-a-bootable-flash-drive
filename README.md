# How to create a bootable flash drive

First find the device name of the disk to make bootable:

Linux:

`sudo fdisk -l`

## MacOS

First find the device name of the disk to make bootable:

`sudo diskutil list`

then install unetbootin:

```
brew cask install unetbootin
```

Launch Unetbootin and write the image to your flash disk.

Then reboot and hold alt to initiate the boot menu.

