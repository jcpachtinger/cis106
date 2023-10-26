---
Jerry Pachtinger
Fall '23
---

# Week Report 3

## Summary of Presentations

### Introduction to Linux

**What is an operating system?**

An os provides all the necessary software to run your computer. The kernel is the most basic element of the OS that runs to the low-level functionality and the additional software runs on top of the kernel.

**Aside from a kernel, what other parts make an operating system?**

The OS also comes with utility and productivity applications and ways for the user to interact with the computer such a GUI or Command line shell

**What is a Linux distribution?**

 A complete package that comes with the Linux kernel, UNIX tools, applications, startup scripts and an installer

**What is Ubuntu?**

A Linux distro that forked off of Debian. It is focused on freedom and customizability

**Define the following terms: Open Source, Closed source, free software**

Open source may be free or paid, it comes with a copy of the source code.
Closed source may be free or paid and does not provide the user with the source code
Free software comes with the source code and is governed by a GPL license that is more strict in requiring people modifying the source code to use the same license

**What are the 4 freedoms defined by the free software foundation?**

0: Use software for an purpose
1: Examine the source code and modify as you see fit
2: Redistribute the software
3: Redistribute your modified software

### The basics of Virtualization


**What is virtualization?**

Creating a virtual version of something.

**List 3 benefits of virtualization**

Run multiple OSs on a single computer without dual booting
Test applications before running on your host machine
Save a state and roll back at any time
Running legacy applications on new hardware

**What is a hypervisor?**

Software or hard ware that creates, manages, and runs a virtual machine

**What is virtualbox**

An open-source virtualization software

### Exploring Desktop Environments

**What is a desktop environment? (Provide 3 examples)**

Different graphical desktops that you can use to interact with a computer. Windows and Max lock you into one option, but Linux has many different options such as: GNOME, KDE, or XFCE

**List 4 common elements of desktop environments**

File manager
Menus
Window Manager
Icons

**What is Ubuntu’s default desktop environments?**

GNOME 3

**What are the official flavors of Ubuntu?**

Versions of the GNOME 3 desktop environment with different default applications and settings

### What is a Shell?

**What is Bash?**

Bash is a UNIX shell or command line language

**How do you access the Linux CLI?**

By going into the applications and searching for the terminal
By placing linux into text mode

**What is a console terminal?**

A command-line interface that allows you to interact with your computer via the keyboard

**What is a terminal emulator?**

A terminal emulator gives you access to the CLI usually while your in the GUI

**Provide 3 examples of Linux commands**
echo
date
uname
clear

### Managing Software

**Which command is used for updating ubuntu**

sudo apt-get update

**Which command is used for installing software. Provide an example.**

sudo apt install screenfetch

**Which command is used for removing software. Provide an example.**

sudo apt remove screenfetch

**Which command is used for searching for software. Provide an example.**

apt search "video player"

**Definition of the following terms:**
A package is a piece of software

A library is a collection of code that may be used by and required for the use of certain packages

A Repository is a collection of a lot of essential or popular packages