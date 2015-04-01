# vmtools-w16
`vmtools-w16` is a set of tweaks and drivers for Windows 3.x running in VMware environments. It should assist customers running it in productive environments as VMware tools currently don’t support Windows 3.x.

![Example satprep maintenance report](https://raw.githubusercontent.com/stdevel/vmtools-w16/master/Screenshot.jpg "vmtools-w16 screenshot")

The software currently supports:
- time synchronization between ESXi host and VM
- **CPU idle** support
- FAT12 and FAT16 shrink support
- experimental 100 mbit/s network card support
- famous **Intel 8086 turbo button** emulation
- emulation of **5.25“ floppy drives** and their sound for a **better user-experience**

Additional features like **10 Gbit/s** network cards and **InfiniBand** are planned for the future. Don't hesitate to let me know if you have other useful ideas.

Simply put the EXE file into autorun to enable it after starting Windows 3.x. Feel free to alter the Visual Basic 3.0 source code.
