# Gigabyte B450M-S2H Hackintosh with OpenCore 0.5.9

Hello, I share my OpenCore 0.5.9 EFI folder for Gigabyte B450M-S2H motherboard.
I am succesful running mac OS Catalina 10.15.6 with this configuration. 

##### My setup:
- Motherboard: Gigabyte B450M S2H Micro ATX AM4 F50 BIOS

- CPU: AMD Ryzen 5 2600 3.6 GHz 6-Core Processor

- GPU: Gigabyte RX570 GAMING 4G

- Memory: 2pcs * Samsung DDR4 8GB 3200

- Storage: WD GREEN SSD 240GB for mac OS

#### What's working: 
* sleep [(with additional configuration)](https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html#preparations "(with additional configuration)")
* audio
* all usb
* gpu
* ethernet

#### What's not working:
`Nothing`

# How to install:
1. Make a bootable usb drive with [GibMacOS](https://github.com/corpnewt/gibMacOS "GibMacOS") and [OpenCore](https://github.com/acidanthera/OpenCorePkghttp:// "OpenCore")
2. Extract my EFI folder to USB
3. **Remove all your additional  USB devices while installation, leave only USB mouse and keyboard to USB 2.0 back ports**
4. Boot from USB and start installation process
5. [Make Post-Install changes](https://dortania.github.io/OpenCore-Post-Install/#how-to-follow-this-guide "Make Post-Install changes")
6. Add your serial numbers by [GenSMBIOS](https://github.com/corpnewt/GenSMBIOShttp:// "GenSMBIOS") to `config.plist`
7. For additional information please follow this [guide](https://dortania.github.io/OpenCore-Install-Guide/ "guide")


**Thanks to all the developers who made this possible. And of course thanks to all hackintosh community.**

[AMD OS X](https://amd-osx.com/)

[AMD VANILLA](https://github.com/AMD-OSX/AMD_Vanilla)

[OpenCore Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[OpenCore Team](https://github.com/acidanthera/OpenCorePkg)

