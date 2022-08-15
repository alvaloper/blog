---
layout: post
title: How to install Sublime Text on Debian 11
---

>Sublime Text is a shareware cross-platform source code editor. It natively supports many programming languages and markup languages. Users can expand its functionality with plugins, typically community-built and maintained under free-software licenses. To facilitate plugins, Sublime Text features a Python API. .  
[Wikipedia](https://en.wikipedia.org/wiki/Sublime_Text).


Let’s do it:

**Run your console and type the following as root superuser:**

**First step:**

```code
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```

**Second step:**

```code
sudo apt install apt-transport-https
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

**Third step:**

```code
sudo apt update
```

**Fourth step:**

```code
sudo apt install sublime-text
```

That's all enjoy it!

{% include embed.html url="https://www.youtube.com/embed/Q9rNrJHAUMk" %}

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)