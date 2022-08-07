---
layout: post
title: Installing HP Printer Drivers on Debian 11 Bullseye in just 5 minutes!
---

The HPLIP (HP Linux Imaging and Printlng) project—initiated and led by HP Inc. (HP)—aims to ease Linux systems' ability to interact with HP's inkjet and laser printers with full printing, scanning, and faxing support. As of 2021 the supplied printer-drivers support a total of 3,088 HP printer models. (https://en.wikipedia.org/wiki/HP_Linux_Imaging_and_Printing).


You can do it in just 5 minutes. Let's do it:

**Make sure to log in as root user, and install the following**

```code
sudo apt-get install hplip
```

Then, to make everything easier, we install the graphical environment. (GUI)

```code
sudo apt-get install hplip-gui
``` 

Finally, we start the software configuration:

```code
hp-setup
``` 

Once these steps are done, we will have the application running in the background and the icon appears in the taskbar. Congratulations now enjoy your HP printer.


Contributions:

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)

Thank you for your visit! 