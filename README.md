# USBwave12
This repo is an attemps to give a support of the USBwave12 function generator from Elan Digital Systems to Windows 10, Linux and MacOS. 

## Driver instalation
The interface of the USBwave12 to the computer is based on the chip [CP2102](https://www.silabs.com/documents/public/data-sheets/CP2102-9.pdf) from Silicon Labs. This chip interface USB to an UART communication at a baudrate of XXX. The drivers has to be installed for Windows and MacOs (Linux users are blessed of a native integration into the kernels): [https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers). 
