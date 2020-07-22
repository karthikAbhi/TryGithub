# Setting up the Libusb driver for Windows Platform

Step 1: Download Zadig tool

- Download Zadig-2.5 from the [here](https://zadig.akeo.ie/)
- Run the Zadig-2.5.exe

Step 2: Select the Nash Printer device

- Select **Options** -> **_List All Devices_**. This will list all the usb devices connected to the system.
![Image - List all Usb devices](/data/list_devices.png)

- From the drop down list. Select the device "**H-RPRT01-AXXX**".

Step 3: Configure the libusb driver settings

- Select "**libusb-win32(v1.2.6.0)**" from the Driver selection spinner(Next to the Green pointing arrow).
![Image - Driver selection](/data/driver_selection.png)

Step 4: Install and confirm the driver installation

- Click on the **Replace Driver** button to replace the driver. 

- On completion of driver installation, Open the **device manager** with Administrator permissions(Run as Administrator) -> verify under **libusb-win32 devices** -> "**H-RPRT01-AXXX**" device will be listed.
![Image - Driver Confirmation](/data/driver_confirmation.png)

:clap: __*Congrats!*__ You have successfully completed the libusb driver installation for Windows platform.
