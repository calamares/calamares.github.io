---
layout: page
title: About
permalink: /about/
published: true
# Trailing whitespace is important in this file!
---

The idea of Calamares arose from a desire of several independent Linux distributions to come together and work on a shared system installer. Instead of everyone working on their own implementation and forking forks of forks, why not work together on something that can be used by many?

## What is Calamares

Calamares is an installer framework. By design it is very customizable, in order to satisfy a wide variety of needs and use cases.

Calamares aims to be easy, usable, beautiful, pragmatic, inclusive and distribution-agnostic.

Calamares includes an advanced partitioning feature, with support for both manual and automated partitioning operations. It is the first installer with an automated "Replace Partition" option, which makes it easy to reuse a partition over and over for distribution testing.

Got a Linux distribution but no system installer? [Grab Calamares](https://github.com/calamares/calamares), mix and match any number of [Calamares modules](https://github.com/calamares/calamares/tree/master/src/modules) (or write your own in Python or C++), throw together some [branding](https://github.com/calamares/calamares/tree/master/src/branding), package it up and you are ready to ship!

## What Calamares is not

Calamares is not a Manjaro Linux installer, or a KaOS installer, or a Maui installer, or even an installer for Arch Linux based distributions. Calamares is an independent product. The Calamares team works closely with Linux distributors to provide the very best experience to their users.

Calamares does not aim to be the ultimate "standard" installer of the Linux desktop. Many distributions already have more mature system installer solutions, but some don't, and that's where Calamares can be of use.

## What does Calamares look like

Since Calamares is designed to be customized, themed and branded by individual distributions,
it can look very different when used by specific distributions. There will be distinct
color schemes, welcome graphics, and while-you-wait slideshows.
It is very unlikely that you will encounter a "plain" version of Calamares.
The source code **does** have a default configuration, which looks like these
screenshots:

<div>
  <img src="/images/page-welcome.png" width="266" alt="Welcome page">
  <img src="/images/page-partition.png" width="266" alt="Partitioning page">
  <img src="/images/page-finished.png" width="266" alt="Partitioning page">
</div>

## Who develops Calamares

Calamares is maintained by [the Calamares team](/team/). Most of us are also [KDE](https://kde.org) developers, and we have received contributions from [BBQLinux](http://bbqlinux.org/), [Fedora](https://fedoraproject.org/), [KaOS](http://kaosx.us/), [Kubuntu](http://kubuntu.org), [Manjaro](http://manjaro.org/), [Maui](http://www.maui-project.org/), [Netrunner](http://www.netrunner.com/) and [OpenMandriva](https://www.openmandriva.org/) developers as well.

We gladly accept contributions from everyone, and we have no exclusive association with any Linux distribution. Calamares is not a KDE project, or a KaOS project, or a Manjaro project, we are just a bunch of people dumping some code on [GitHub](https://github.com/calamares).

## Who ships Calamares

Many Linux distributions are in varying stages of adopting Calamares as their primary system installer.

Operating systems that already ship Calamares:

- [AIMS Desktop](https://desktop.aims.ac.za/)
- [Apricity OS](http://www.apricityos.com/)
- [Archman Linux](https://archman.org/)
- [ArcoLinux](https://arcolinux.com/category/arcolinux/help/)
- [Argent Linux](https://rogentos.ro/#Portfolio)
- [BBQLinux](http://bbqlinux.org/)
- [BlackPanther OS](http://www.blackpantheros.eu/)
- [Bluestar Linux](http://bluestarlinux.sourceforge.net/)
- [Chakra](https://chakralinux.org/)
- [EndeavourOS](https://endeavouros.com/)
- [Feren OS](https://ferenos.weebly.com/)
- [GeckoLinux](http://geckolinux.github.io/)
- [Hamara Linux](https://www.hamaralinux.org/)
- [Kannolo](https://kannolo.sourceforge.io/) (Fedora Remix)
- [KaOS](http://kaosx.us/)
- [KDE Neon](https://neon.kde.org/)
- [Lubuntu](http://lubuntu.me/)
- [Manjaro](http://manjaro.org/)
- [Neptune](https://neptuneos.com/en/start-page.html)
- [Netrunner](http://www.netrunner.com/)
- [OpenMamba](http://openmamba.org/en/)
- [OpenMandriva](https://www.openmandriva.org/)
- [Parabola](https://www.parabola.nu/)
- [Parrot OS](https://parrotlinux.org/)
- [Pisi Linux](https://www.pisilinux.org/)
- [Redcore Linux](http://redcorelinux.org/)
- [Sabayon](https://www.sabayon.org/)
- [Salient OS](https://salientos.github.io/)
- [Siduction](https://siduction.org/)
- [SwagArch](https://swagarch.gitlab.io/)
- [Tanglu](http://tanglu.org/)

Operating systems that are evaluating Calamares in pre-release builds:

- [Frugalware](https://frugalware.org/)
- [Maui](http://www.maui-project.org/)
- [PCLinuxOS](http://www.pclinuxos.com/)

Operating systems that ship Calamares in their package repositories for third-party derivatives to use:

- [Debian](https://debian.org/)
- [Fedora](https://fedoraproject.org/)
- [Gentoo](https://gentoo.org/)
- [openSUSE](https://opensuse.org/) (from Leap 15)

## What is Calamares made of

Calamares is mostly written in C++11, with Qt 5 as general purpose library and UI toolkit.

Calamares is modular by design, and Python 3 was chosen as the main scripting language. The Python 3 interface is implemented with Boost.Python, and all Calamares configuration is done in YAML.

For a complete list of dependencies, see [the README file](https://github.com/calamares/calamares/blob/master/README.md).

## Contact us

IRC: #calamares on chat.freenode.net.  
<!-- Mailing list: [calamares-dev@googlegroups.com](mailto:calamares-dev@googlegroups.com)   -->
Bugs: [Calamares issues, bugs and feature requests](https://github.com/calamares/calamares/issues)
