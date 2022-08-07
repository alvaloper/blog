---
layout: post
title: How to Install Brave Browser on Debian 11 Bullseye
---

>Brave is a free and open-source web browser developed by Brave Software, Inc. based on the Chromium web browser. Brave is a privacy-focused browser, which automatically blocks online advertisements and website trackers in its default settings. [Wikipedia](https://en.wikipedia.org/wiki/Brave_(web_browser)).


You can do it in just 5 minutes. Let’s do it:

**Run your console and type the following as root superuser:**

Install dependencies

```code
sudo apt install apt-transport-https curl gnupg software-properties-common
```

Import the GPG key from the repository to install the Brave browser

```code
sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg
```

Add brave browser repository on Debian 11 bullseye

```code
echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list
```

Install Brave Browser on Debian 11

```code
sudo apt update
```

and

```code
sudo apt install brave-browser
```

Enjoy the Brave browser on your PC

{% include embed.html url="https://www.youtube.com/embed/bNTSAdLSXpY" %}

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)