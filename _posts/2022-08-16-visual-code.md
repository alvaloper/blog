---
layout: post
title: How to install Visual Studio Code (VS Code) on Debian 11
---

>Visual Studio Code, also commonly referred to as VS Code,[9] is a source-code editor made by Microsoft for Windows, Linux and macOS.[10] Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. Users can change the theme, keyboard shortcuts, preferences, and install extensions that add additional functionality. In the Stack Overflow 2021 Developer Survey, Visual Studio Code was ranked the most popular developer environment tool, with 70% of 82,000 respondents reporting that they use it.  
[Wikipedia](https://en.wikipedia.org/wiki/Visual_Studio_Code).


Let’s do it:

**Run your console and type the following as root superuser:**

Add Microsoft Visual Studio Code GPG Key

```code
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo install -o root -g root -m 644 microsoft.gpg /usr/share/keyrings/microsoft-archive-keyring.gpg
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/usr/share/keyrings/microsoft-archive-keyring.gpg] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'
```

Install https transports

```code
sudo apt-get install apt-transport-https
```

Update

```code
sudo apt-get update
```

Install VS Code

```code
sudo apt-get install code # or code-insiders
```

How to remove Visual Studio Code

```code
sudo apt remove code
```

That's all enjoy it!

 {% include embed.html url="https://www.youtube.com/watch?v=kb68UMw0-Cs" %} 

**Thank you for your visit!**
*Contributions:*

+ Buy me a Coffee [Enter Here](https://www.buymeacoffee.com/alvaloper)
+ Paypal [Enter Here](https://www.paypal.com/paypalme/ingespinozalj)