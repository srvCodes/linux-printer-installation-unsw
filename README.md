# Instructions for installing UNSW network printers on Linux

Since the instructions on [taggi](https://taggi.cse.unsw.edu.au/FAQ/Managed_Print_Service_at_CSE/) do not work for Linux (at least on my Ubuntu OS), here is step-by-step guide to installing one. It should work for both your university desktop as well as personal laptops. No ApeosPort driver installation required.

1. Open Terminal and run (as a root user) the command: ```sudo apt install smbclient```
2. Open Settings -> Printers -> Additional Printer Settings. You should be able to see this on your screen:
![print0](https://github.com/srvCodes/linux-printer-installation-unsw/blob/main/images/print0.png)
3. Type in your zid and passwork. On the field ```smb://```, enter the printer URL. A valid URL for instance is: ADUNSW/mpspwpsxxx.ad.unsw.edu.au/STAFF-BLACK-PRINTER where xxx is a 3-digit code for your building/floor printer.
4. Click on Forward. You will be popped with the following where you should select 'Generic' -> Forward:
![print1](https://github.com/srvCodes/linux-printer-installation-unsw/blob/main/images/print1.png)
5. On the next pop-up, select 'Postscript' driver and choose 'Generic Postscript Printer Foomatic' option:
![print2](https://github.com/srvCodes/linux-printer-installation-unsw/blob/main/images/print2.png)
6. Click on Forward. And that's it. You should be able to see the following on your screen after submitting a test job:
![print3](https://github.com/srvCodes/linux-printer-installation-unsw/blob/main/images/print3.png)
7. The final setting should look like:
![print4](https://github.com/srvCodes/linux-printer-installation-unsw/blob/main/images/print4.png)

Thanks to Jean-Baptiste Cattley for helping me out with this!
  
