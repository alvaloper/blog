---
layout: post
title: Check your hard drive, install gsmartcontrol an alternative to crystaldiskinfo on debian 11
---

>Smartmontools (S.M.A.R.T. Monitoring Tools) is a set of utility programs (smartctl and smartd) to control and monitor computer storage systems using the Self-Monitoring, Analysis and Reporting Technology (S.M.A.R.T.). [Wikipedia](https://en.wikipedia.org/wiki/Smartmontools).


You can do it in just 2 minutes. Let’s do it:

**First, run your console and type the following as root superuser:**

```code
sudo apt -y install gsmartcontrol
```

That is all, Enjoy!

To uninstall only the gsmartcontrol package we can use the following command:

```code
sudo apt-get remove gsmartcontrol
```

If you want to remove all dependencies of the program

```code
sudo apt-get -y autoremove gsmartcontrol
```

{% include embed.html url="https://www.youtube.com/embed/YfjxNJhuan8" %}

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)