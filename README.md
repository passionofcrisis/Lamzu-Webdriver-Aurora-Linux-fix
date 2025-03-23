# Lamzu-Webdriver-Aurora-Linux-Fix
This is a fix to access the Lamzu Aurora/webdriver on chromium on Linux distro's



**Installation**

We will be adding a udev rule so the chromium based browser will be able to access the mouse.
Simply copy the Lamzu-Webdriver.rules file to /etc/udev/rules.d/ with admin permission and reboot.
After this the lamzu.net webdriver will find and connect to your mouse.



This code currently works for the Lamzu Maya X 8k and Lamzu Inca 8k mice.
With some adjustments to the code it might work for other mice using Aurora in the future, or even mice from other brands that utilize a webdriver.
Use the command "sudo dmesg" in the terminal and search for the mouse USB names. You might need to use the dongle and wired connections seperately to find all the info.



If you adjusted to code and made another mouse work, please let me know and i will add this to the code.



**Credits to Gunther and Stics on the Lamzu discord**

