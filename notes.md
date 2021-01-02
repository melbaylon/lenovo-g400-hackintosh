# 2021-01-02 first install pass

Trying to install macOS Mojave using 
- [UniBeast 9.3.0 - Mojave](https://www.tonymacx86.com/resources/unibeast-9-3-0-mojave.449/)
- [MultiBeast 11.3.0 - Mojave](https://www.tonymacx86.com/resources/multibeast-11-3-0-mojave.430/)

## Installation experience
### Booting into macOS Mojave USB installer
- trackpad doesn't work on boot to the installer
- internal keyboard also doesn't work
### Booting into installed macOS Mojave after install
[clover]: 'images/clover bootloader after install.jpg'
- macOS continues to the installation after reboot
  - pretty slow compared to when installing macOS on an MacBook Pro
  - reboots after this
  - continue setup (interl trackpad and keyboard not working)
  -  chose to not connect to the at this time
### Installing drivers
-  set up Multibeast
   -  NOTE: can't recall what options I choose, will need to revisit this
- Keyboard, trackpad and wifi doesn't work


## Steps taken
- Erase installation drive using Disk Utility
  - Format: APFS
  - Scheme: GUID Partition Map
- Change date to install Mojave in 2021 (make sure to not be connected to the Internet)
  - run 'date 1116211618' on Terminal
- Install macOS Mojave as you normally do
- Reboots a few times like a normal macOS Mojave installation
- And done!