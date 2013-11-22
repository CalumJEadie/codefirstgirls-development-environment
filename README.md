Code First: Girls Development Enviroment
========================================

(Work in progress!) Development environment to support Code First: Girls.

# What's this all about?

Software is really complex. Even a small application involves lots of different bits working together, a bit like an Orchestra, if one part is a bit out of place it can throw everything else off.

Setting up a development environment can be really fiddly and frustrating. To make this easier for can use this project to create a virtual computer inside your own, that has everything you need set up to get started.

# Usage

First up we need to install two programs; VirtualBox and Vagrant.

## Installing VirtualBox

- Head over to https://www.virtualbox.org/wiki/Downloads.
- Download the "platform package" for your operating system. E.g. if you have a MacBook, that would be the one for OS X hosts.
- Install.

## Installing Vagrant

- Head over to http://downloads.vagrantup.com/.
- Pick the latest version.
- Download the installer for your operating system. E.g. if you have a MacBook, that would be the '.dmg'.

## Creating your virtual computer

Open up terminal (cmd+space, type "terminal", hit enter).

In the terminal type the following. Each line is a command, type the line and hit enter afterwards.

```sh
cd ~
mkdir code-first-girls
cd code-first-girls
git clone https://github.com/CalumJEadie/codefirstgirls-development-environment.git
cd codefirstgirls-development-environment
vagrant up
```

# What have we set up?

![](https://github.com/CalumJEadie/codefirstgirls-development-environment/raw/master/docs/guest-within-host.png)

![](https://github.com/CalumJEadie/codefirstgirls-development-environment/raw/master/docs/ports-and-folders-mappings.png)

# Resources ( things that were helpful in putting this project together )

