USBTinyISP_1.2.6.0
==================

A windows 8.1 compatible Windows Driver

When I upgraded to WIndows 8.1 I found that the existing USBTinyISP 1.2.1.0 Drivers were throwing up errors when I attempted to install them.  The error I got was "attempt to load a program with incorrect format windows"

This is a quick set of drivers created the latest version of libusb-win32 (1.2.6.0) and used the included inf-wizard tool to create new drivers for the USBTinyISP.

I installed them with the Windows 8.1 with disable driver signature enforcement though as I understand it this should not be required to do this.  I used the update driver tool in Windows device manager to install the driver.  I have left the installation programs in place but they are untested.