Arch Pro
========

Arch Pro is an mbed enabled development board for rapid prototyping. It is a variant of mbed LPC1768 with built-in Ethernet, USB Host/Device, Grove connectors and Arduino form factor. With a variety of Shield and Grove modules and lots of software libraries for Arch Pro, you can implement Ethernet, USB Host/Device and NFC applications rapidly and easily.

![](https://raw.githubusercontent.com/SeeedDocument/Arch_Pro/master/img/Arch_pro_v1_pinout.png)



### Upgrade firmware
If you can't use the drag-n-drop programming feature on windows or macos, try to upgrade the firmware.
New firmware can be found at this repository or https://github.com/mbedmicro/DAPLink/releases

1. Enter on-chip bootloader mode

   Pull down the test point named `boot` at the bottom of the board, and then power on the board.

   ![](https://statics3.seeedstudio.com/product/arch%20pro_03.jpg)

2. Replace `firmware.bin` with a new firmware

   A drive named `CRP DISABLD` will show up on your computer. `firmware.bin` will be in the drive. On macOS, use `sudo dd if=/path/to/new_firmware.bin of=/path/to/firmware.bin conv=notrunc`



