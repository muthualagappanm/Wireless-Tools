![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)

# Microchip PCAP Utility Release Notes
- Microchip PCAP Utility Tool connects the Wireshark Graphical User Interface (GUI) and the sniffer firmware running on the ZigBit® USB stick. The sniffer captures the packets based on the channel and channel page selection. Captured data is sent to Wireshark software to show the decoded packets on the GUI. The sniffer captures IEEE® 802.15.4, Zigbee® packets or custom protocol.

- This file contains release and version information for the Microchip PCAP Utility
- which is used to capture/sniff IEEE 802.15.4 Frames ( 2.4 GHZ & Sub Ghz)

## Microchip PCAP Utility (Windows) **v1.1.0** and Release Date **2024-9-20**

### System Requirements
- Wireshark Software installed 
- i.e, Wireshark-4.2.4 version (32bit or 64bit depending on the OS Installed) or later

### Supported Devices
- RZ600 with RF231 Radio
- RZ600 with RF212 Radio
- ZigBit_RF233_USB
- ZigBit_RF212B_USB
- SAMR30G18A With RF212B (SAMR30_ XPLAINED_PRO)

### Package Contents
- Microchip PCAP Utility Tool binary
- User Guide pdf
- Firmware hex files for RZ600(RF231 Radio), RZ600(RF212 Radio),ZigBit_RF233_USB,ZigBit_RF212B_USB
- Release Notes.txt

### Procedure : Steps to operate Microchip PCAP Utility Tool
- All Programs->Microchip PCAP Utility.
- Once the Tool is opened, Select setting and then configure the Baudrate, channel (Select the channel starting from 11 to 26 for 2.4 Ghz and 0-10 for Sub Ghz from the drop down box), data rate and then click OK.
- Click Start capture will automatically invoke wireshark instance for capture to begin.
- Select Stop capture to pause capture in wireshark display window.
- Select Start capture to display packets in wireshark.
- If user needs to change the channel then press Stop capture, then select the channel and press start capture again.
- Captured files are saved in the dafult location of C:\Users\UserID\AppData\Local\Temp.
- User can change the dafault file capture eventlog location using "Output Directory".

### New Features
- Added SAMR30 Sniffer support
- BLE Proximity Monitor and Receiver
- WBZ451 BLE and MAC Combo applications based on BLE Provision Service Harmony component.

### Bug fixes and Improvements
- None

### Known Issues
- None

### Limitations
- None

### Additional Notes
- None

### Support Contact
- www.microchip.com/support
--------------------------------------------------------------------------------------------------------------------
## Trademarks
The Microchip name and logo, the Microchip logo and MPLAB are registered trademarks of Microchip Technology Incorporated in the U.S.A. and other countries.
All other trademarks mentioned herein are property of their respective companies.