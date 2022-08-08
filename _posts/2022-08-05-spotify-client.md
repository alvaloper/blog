---
layout: post
title: How to Install Spotify Client on Debian 11 Bullseye
---

>It is one of the largest music streaming service providers, with over 433 million monthly active users, including 188 million paying subscribers, as of June 2022. 
[Wikipedia](https://en.wikipedia.org/wiki/Spotify).

You can do it in just 8 minutes. Let’s do it:

**Run your console and type the following as root superuser:**

**First step:**

```code
sudo apt install curl libcanberra-gtk-module -y
```

**Second step:**

```code
curl -sS https://download.spotify.com/debian/pubkey_0D811D58.gpg | sudo apt-key add -
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 5E3C45D7B312C643
```

**Third step:**

```code
echo deb http://repository.spotify.com stable non-free | sudo tee /etc/apt/sources.list.d/spotify.list
deb http://repository.spotify.com stable non-free
```

**Fourth step:**

```code
sudo apt update
```

**Fifth step:**

```code
sudo apt install spotify-client
```

That's all enjoy it!

{% include embed.html url="https://www.youtube.com/embed/wVTJOawyxEg" %}

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)