---
layout: post
title: Install the latest version of the google chrome web browser on debian 11 Bullseye
---

>Google Chrome is a cross-platform web browser developed by Google. It was first released in 2008 for Microsoft Windows, built with free software components from Apple WebKit and Mozilla Firefox.[14] It was later ported to Linux, macOS, iOS, and Android, where it is the default browser.[15] The browser is also the main component of ChromeOS, where it serves as the platform for web applications.  
[Wikipedia](https://en.wikipedia.org/wiki/Google_Chrome).


Let’s do it:

**Run your console and type the following as root superuser:**

**First step:**

```code
cat << EOF > /etc/apt/sources.list.d/google-chrome.list
deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main
EOF
```

**Second step:**

```code
wget -O- https://dl.google.com/linux/linux_signing_key.pub |gpg --dearmor > /etc/apt/trusted.gpg.d/google.gpg
```

**Third step:**

```code
apt update
```

**Fourth step:**

```code
apt install google-chrome-stable
```

That's all enjoy it!

{% include embed.html url="https://www.youtube.com/embed/7oYXMFs_vZo" %}

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)