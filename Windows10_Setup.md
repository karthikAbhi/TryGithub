# Setting up the Libusb driver for Windows Platform

1. Download Zadig tool

- Download Zadig-2.5 from the [here](https://zadig.akeo.ie/)
- Run the Zadig-2.5.exe.

2. Select the Nash Printer device

- Select **Options** -> *List All Devices*. This will list all the usb devices connected to the system.
- ![Image - List all Usb devices](/data/list_devices.png)

- From the drop down list. Select the device "**H-RPRT01-AXXX**".

3. Configure the libusb driver settings

- Select "**libusb-win32(v1.2.6.0)**" from the Driver selection spinner(Next to the Green pointing arrow).
- ![Image - Driver selection](/data/devices_selection.png)

4. Confirm the driver installation

- On completion of driver installation, Open the **device manager** as Administrator -> Under **libusb-win32 devices** -> "**H-RPRT01-AXXX**" device will be listed.
- ![Image - Driver Confirmation](/data/driver_confirmation.png)

*Congrats!* You have successfully completed the libusb driver installation for Windows platform.
