---
layout: post
title: How to install Arduino IDE on Debian 11
---

>If we talk about Arduino we need to differentiate between the Company Arduino CC that is selling single-board microcontrollers and microcontroller kits for building digital devices and the Arduino IDE which is written in the programming language Java. You are here mostly for the latter, Debian is providing packages for Arduino IDE.The Arduino IDE interacts very nicely with the micocontroller boards from Arduino CC but also to the widely available clones of these. The IDE can be used on various not only Atmel based boards. This wiki page is mainly about the Arduino IDE packaged within Debian. 
[Debian Wiki](https://wiki.debian.org/Arduino).


Let’s do it:>

**Run your console and type the following as root superuser:**

Installing Arduino IDE from the Official Debian 11 Repository

```code
apt install arduino -y
```

Run the following command to confirm that the card has been detected correctly

```code
dmesg | tail
```

To add your Debian 11 login user to the dialout group, run the following command:

```code
sudo usermod -aG dialout $(whoami)
```

Now, restart your Debian 11 machine with the following command:

```code
sudo reboot
```

How to remove Arduino IDE

```code
sudo apt autoremove arduino --purge -y
```

That's all enjoy it!

<!-- {% include embed.html url="https://www.youtube.com/embed/kb68UMw0-Cs" %} --> 

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)