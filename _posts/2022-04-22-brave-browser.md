---
layout: post
title: How to Install Brave Browser on Debian 11 Bullseye
---

You can do it in just 5 minutes. Let’s do it:

Run your console and type the following as root superuser:

First step: install dependencies

sudo apt install apt-transport-https curl gnupg software-properties-common

Second step: import the GPG key from the repository to install the Brave browser

sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg

Third step: Add brave browser repository on Debian 11 bullseye

echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list

Fourth step: Install Brave Browser on Debian 11

sudo apt update

and

sudo apt install brave-browser

Enjoy the Brave browser on your PC

Thanks!

<!-- ![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub. -->

Contributions:

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)

Thank you for your visit! 