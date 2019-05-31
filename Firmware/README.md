
This folder contains the source code for marlin2.0 and can be used on the MKS SGEN motherboard.

The compilation environment used is Atom+platformio;

Specific methods can refer to the following links:

http://marlinfw.org/docs/basics/install_platformio.html#installing-marlin-(platformio) 
http://docs.platformio.org/en/latest/ide/atom.html#installation

After compiling, there will be firmware.bin firmware in the folder(folder path: .pioenvs\LPC1769), then follow the steps below to update the firmware：

1.copy firmware.bin to SD card

2.insert SD card to MKS SGEN board

3.reboot MKS SGEN board

4.wait until firmware upgrade is completed
