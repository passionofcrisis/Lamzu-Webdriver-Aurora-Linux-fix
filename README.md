# Lamzu-Webdriver-Aurora-Linux-Fix
Fix to access the Lamzu Aurora/webdriver on chromium on Linux distro's



**Installation**

We will be adding a udev rule so the chromium based browser will be able to access the mouse.
Simply copy the Lamzu-Webdriver.rules file to /etc/udev/rules.d/ with admin permission and reboot.
After this the lamzu.net webdriver will connect to your mouse.
This will not allow firmware updates, device id apparently changes while in update state.
If this still does not work and you are using the snap version of chromium browser try using the flatpack or install through your distro's repo.



This code currently works for the Lamzu Maya X 8k, Lamzu Inca 8k and Lamzu Paro mice. 
With some adjustments to the code it might work for other mice using Aurora in the future, or even mice from other brands that utilize a webdriver.
Use the command "sudo dmesg" in the terminal and search for the mouse USB names. You might need to use the dongle and wired connections seperately to find all the info.



If you adjusted the code and made another mouse work, please let me know and I will add this.



**Credits to Gunther, Stics, and minn on the Lamzu discord, WingofaGriffin on github**

