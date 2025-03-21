# Lamzu-Maya-X-Webdriver-Aurora-Linux-Fix
This is a fix to access the Lamzu Aurora/webdriver on chromium on Linux distro's



**Installation**

We will be adding a udev rule so the chromium based browser will be able to access the mouse.
Simply copy the Lamzu-Maya-X.rules file to /etc/udev/rules.d/ with admin permission and reboot.
After this the lamzu.net webdriver will find and connect to your mouse.



Only works for the Lamzu Maya X mouse, but with some adjustments to the code it should work for other mice using Aurora or even mice from other brands.
Use the command "sudo dmesg" in the terminal and search for the mouse USB names. You might need to use the dongle and wired connections seperately to find all the info.


**Credits to Gunther on the Lamzu discord**
