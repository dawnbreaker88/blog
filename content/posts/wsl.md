+++
title = "The Best Windows Feature Isn't Made by Microsoft"
date = "2025-08-15"


[taxonomies]
tags=["Linux","Beginners"]



[extra]
comment = true
+++


# **Introduction**

Before we get to the main feature, let's be real. If you're familiar with setting up compilers on Windows, you know what a hassle it is. You try to set up VS Code for a new language, install a bunch of packages, and still don't know whether it will work or not. It just ends in frustration. Sure, some may get it on the first try, but most of us don't. For me specifically, I prefer using the keyboard more than the mouse for everything.I observed something on my college PCs they all used Linux. 

At first, the majority of people didn't like it or felt it was weird using commands and all. For me, it was different. Instead of using a GUI application for everything, Linux aligned with my principles of minimalism. I also found it was actually quite easy to navigate the system once you got the hang of it.

# **The linux advantsge**

why bother with Linux? It started back in the 90s with a dude named Linus Torvalds who wanted to build his own OS for his custom PC components . He wrote the core of it the Linux kernel and from there, countless versions, or "distros," spun out, like Ubuntu, Arch, Fedora, Gentoo(This thing really sucks btw) and many others.

Fast forward to today, and Linux is the backbone for countless companies. Their internal systems, cloud servers, and development workflows often run on a Linux-based OS. The reason is simple: it’s free from the control of corporate giants like Microsoft and Apple, and its lightweight nature makes it faster for things like cloud and backend development which are so Heavy.

For students like us, learning Linux does two things. First, it improves our understanding of how a PC really works. Second, knowing it signals that you have some real, serious knowledge about computer systems.In short it’s everywhere you don’t see. Windows dominates the visible desktop, but Linux is the skeleton of modern computing and Development 

![Markdown Logo](https://miro.medium.com/v2/resize:fit:786/format:webp/0*Qqqd7UsfFDPL7WXh.jpeg)




# **How I discovered WSL - the best feature of windows**

So, I started digging deeper into the Linux rabbit hole. At first, I thought the only way I could actually use a Linux distro was to dual-boot, which wasn't a viable option for my laptop, so I almost gave up on the idea.

But I was still intrigued. I kept watching videos about the different distros like the OG, Arch Linux, and its famous quote, "I use Arch, btw." I was fascinated by how deeply you could customize the user experience until it felt like the system truly belonged to you.

Then one day, out of nowhere, I was scrolling through YouTube and found a video by a YouTuber called NetworkChuck titled "Linux on Windows." I thought, "Okay, fine, let's watch it."

BOOM. That’s when I discovered WSL, the Windows Subsystem for Linux.

# **Introducing WSL: The Feature That Changes Everything**

In simple terms, WSL (Windows Subsystem for Linux) is a feature that lets you run a real Linux kernel directly on your Windows system. It uses a built-in virtualization platform called Hyper-V to make this happen. The first version was announced in 2016 and after years of development, it officially launched, enabling developers to finally use a proper Linux environment inside Windows. This makes things way faster and easier, especially for power users.

After I watched a tutorial, I immediately set it up on my laptop. The process was surprisingly easy, but that was just the start. I began learning about package managers (like apt), using sudo, and even writing basic bash scripts. For the first time, I felt like I was discovering what it means to be a "power user."

The difference was incredible. I could do almost anything from the terminal. Instead of hunting for .exe files and clicking through setup wizards, I could just install software in seconds with a single command:

```bash
sudo apt install <package name>
```
I can set up compilers for new languages just with few lines for example for setting up for C compiler i can just do
```bash
sudo apt install build-essential
sudo apt install gcc
```
That was it. I could open a file in a terminal editor like nvim, write the code, and compile it right there. I remember the real "aha!" moment when I needed Jupyter Notebook for a project. I dreaded the heavy Anaconda installation, but in WSL, I had it up and running on my localhost with just a few commands. It just feels so fast, and you can even write simple functions to open websites like Netflix directly from your terminal. It’s a game-changer.

I spent many nights setting up my WSl and bash scripts now insted of opening and waiting for vscode load i can just have my terminal do everything for me with some lines 


![Markdown Logo](https://files.catbox.moe/ccvcq5.png)
My WSL setup


# **Conclusion**

So, my journey started with the familiar frustration of trying to set up a simple C compiler on Windows. It ended with me living in a terminal, feeling completely in control of my workflow, and building things faster than I ever thought possible. The bridge between those two worlds was WSL.

For years, it felt like you had to make a choice: the familiar desktop experience of Windows or the raw development power of Linux. WSL changes that. You get the best of both worlds, without the headache of dual-booting or buying a separate machine.If any part of my story resonated with you the frustration with setups, the curiosity about the command line, or the desire to feel more in command of your computer then my advice is simple: give WSL a try.

Feeling inspired to jump in? Stay tuned for my next article, where I’ll walk you through the exact steps to install WSL and set up some essential utilities to begin your own journey.

