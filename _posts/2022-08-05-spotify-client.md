---
layout: post
title: How to Install Spotify Client on Debian 11 Bullseye
---

You can do it in just 8 minutes. Let’s do it:

Run your console and type the following as root superuser:

First step: sudo apt install curl libcanberra-gtk-module -y

Second step: curl -sS https://download.spotify.com/debian/pubkey_0D811D58.gpg | sudo apt-key add -
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 5E3C45D7B312C643

Third step: echo deb http://repository.spotify.com stable non-free | sudo tee /etc/apt/sources.list.d/spotify.list
deb http://repository.spotify.com stable non-free

Fourth step: sudo apt update

Fifth step: sudo apt install spotify-client

That's all enjoy it! Thanks for your visit!

<!-- ![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub. -->

Contributions:

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)

Thank you for your visit! 