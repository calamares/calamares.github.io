---
layout: single
title: About
header:
  overlay_color: "#000"
  overlay_filter: "0.8"
  overlay_image: /images/banner.webp
toc: true
toc_label: "Content"
sidebar:
  nav: "links"
gallery:
  - url: /images/gallery/page-welcome.png
    image_path: /images/gallery/page-welcome-th.png
    alt: "Welcome Screen"
    title: "Welcome Screen"
  - url: /images/gallery/page-locale.png
    image_path: /images/gallery/page-locale-th.png
    alt: "Locale Screen"
    title: "Locale Screen"
  - url: /images/gallery/page-partition.png
    image_path: /images/gallery/page-partition-th.png
    alt: "Partitioning Screen"
    title: "Partitioning Screen"
permalink: /about/
published: true
# Trailing whitespace is important in this file!
---

The idea of Calamares arose from a desire of several independent Linux distributions to come together and work on a shared system installer. Instead of everyone working on their own implementation and forking forks of forks, why not work together on something that can be used by many?

## What is Calamares
{: .offset}

Calamares is an installer framework. By design it is very customizable, in order to satisfy a wide variety of needs and use cases.

Calamares aims to be easy, usable, beautiful, pragmatic, inclusive and distribution-agnostic.

Calamares includes an advanced partitioning feature, with support for both manual and automated partitioning operations. It is the first installer with an automated "Replace Partition" option, which makes it easy to reuse a partition over and over for distribution testing.

Got a Linux distribution but no system installer? [Grab Calamares](https://github.com/calamares/calamares){:target="_blank"}, mix and match any number of [Calamares modules](https://github.com/calamares/calamares/tree/calamares/src/modules){:target="_blank"} (or write your own in Python or C++), throw together some [branding](https://github.com/calamares/calamares/tree/calamares/src/branding){:target="_blank"}, package it up and you are ready to ship!
The [Calamares extensions](https://github.com/calamares/calamares-extensions){:target="_blank"}
repository holds more branding examples and specialized modules.

## What Calamares is not
{: .offset}

Calamares is not an installer for any specific Linux distribution.
It is **used** by Manjaro and KaOS and Maui and Netrunner Linux,
but it isn't "the Manjaro installer".
Calamares is an independent product.
The Calamares team works closely with Linux distributors to provide the
very best experience to their users.

Calamares does not aim to be the ultimate "standard" installer of the Linux
desktop. Many distributions already have more mature system installer
solutions, but some don't, and that's where Calamares can be of use.
A herd of Arch derivatives uses Calamares, as does a family of Debian and
Ubuntu spins, Fedora remixes and openSUSE flavors.


## What does Calamares look like
{: .offset}

Since Calamares is designed to be customized, themed and branded by individual distributions,
it [can look very different](/#gallery) when used by specific distributions. There will be distinct
color schemes, welcome graphics, and while-you-wait slideshows.
It is very unlikely that you will encounter a "plain" version of Calamares.
The source code **does** have a default configuration, which looks like these
screenshots:

<div class="">
  {% include gallery %}
</div>

## Who develops Calamares
{: .offset}

Calamares is maintained by [the Calamares team](/team/). Most of us are also [KDE](https://kde.org){:target="_blank"} developers, and we have received contributions from BBQLinux, [Fedora](https://fedoraproject.org/){:target="_blank"}, [KaOS](http://kaosx.us/){:target="_blank"}, [Kubuntu](http://kubuntu.org){:target="_blank"}, [Manjaro](http://manjaro.org/){:target="_blank"}, [Maui](http://www.maui-project.org/){:target="_blank"}, [Netrunner](http://www.netrunner.com/){:target="_blank"} and [OpenMandriva](https://www.openmandriva.org/){:target="_blank"} developers as well.

We gladly accept contributions from everyone, and we have no exclusive association with any Linux distribution. Calamares is not a KDE project, or a KaOS project, or a Manjaro project, we are just a bunch of people dumping some code on [GitHub](https://github.com/calamares){:target="_blank"}.

## Who ships Calamares
{: .offset}

Many Linux distributions are in varying stages of adopting Calamares as their primary system installer.

Operating systems that already ship Calamares:

- [AIMS Desktop](https://desktop.aims.ac.za/){:target="_blank"}
- [Archcraft](https://archcraft-os.github.io/){:target="_blank"}
- [Archman Linux](https://archman.org/){:target="_blank"}
- [ArcoLinux](https://arcolinux.info){:target="_blank"}
- [Argent Linux](https://argentlinux.io){:target="_blank"}
- [Athena OS](https://github.com/Athena-OS/athena-iso){:target="_blank"}
- [Bluestar Linux](https://sourceforge.net/projects/bluestarlinux/){:target="_blank"}
- [EndeavourOS](https://endeavouros.com/){:target="_blank"}
- [Feren OS](https://ferenos.weebly.com/){:target="_blank"}
- [Garuda Linux](https://garudalinux.org/){:target="_blank"}
- [GeckoLinux](http://geckolinux.github.io/){:target="_blank"}
- [Kannolo](https://kannolo.sourceforge.io/){:target="_blank"} (Fedora Remix)
- [KaOS](http://kaosx.us/){:target="_blank"}
- [KDE Neon](https://neon.kde.org/){:target="_blank"}
- [Lubuntu](http://lubuntu.me/){:target="_blank"}
- [Manjaro](http://manjaro.org/){:target="_blank"}
- [Neptune](https://neptuneos.com/en/start-page.html){:target="_blank"}
- [Netrunner](http://www.netrunner.com/){:target="_blank"}
- [NixOS](https://nixos.org/){:target="_blank"}
- [OpenMamba](http://openmamba.org/en/){:target="_blank"}
- [OpenMandriva](https://www.openmandriva.org/){:target="_blank"}
- [Parabola](https://www.parabola.nu/){:target="_blank"}
- [Parch Linux](https://parchlinux.com/){:target="_blank"}
- [Pisi Linux](https://www.pisilinux.org/){:target="_blank"}
- [Redcore Linux](http://redcorelinux.org/){:target="_blank"}
- [Salient OS](https://salientos.github.io/){:target="_blank"}
- [Siduction](https://siduction.org/){:target="_blank"}
- [TeLOS Linux](https://teloslinux.org){:target="_blank"}

Operating systems that are evaluating Calamares in pre-release builds:

- [Frugalware](https://frugalware.org/){:target="_blank"}
- [PCLinuxOS](http://www.pclinuxos.com/){:target="_blank"}

Operating systems that ship Calamares in their package repositories for third-party derivatives to use:

- [Debian](https://debian.org/){:target="_blank"}
- [Fedora](https://fedoraproject.org/){:target="_blank"}
- [Gentoo](https://gentoo.org/){:target="_blank"}
- [openSUSE](https://opensuse.org/){:target="_blank"} (from Leap 15)

## What is Calamares made of
{: .offset}

Calamares is mostly written in C++17, with Qt (6, but the code is still Qt5-compatible) as general
purpose library and UI toolkit.

Calamares is modular by design, and Python 3 was chosen as the main
scripting language. The Python 3 interface is implemented with pybind11 (Boost.Python is
available as an alternative),
and all Calamares configuration is done in YAML.

For a complete list of dependencies, see
[the README file](https://github.com/calamares/calamares/blob/calamares/README.md){:target="_blank"}.

## Contact us
{: .offset}

- [Matrix](https://webchat.kde.org/#/room/%23calamares:kde.org)
- Bugs: [Calamares issues, bugs and feature requests](https://github.com/calamares/calamares/issues){:target="_blank"}
- GPG: Calamares release tarballs are signed with a [GPG signing-subkey](pk-7FEA3DA6169C77D6.txt):
  - Calamares 3.2.3 - 3.2.25, E7C31EAE243D798415BCEF00128F00873E05AF1D
  - Calamares 3.2.26, 57E14BD1CD6C198BC11BF18D61A7D26277E4D0DB (one release only!)
  - Calamares 3.2.27 - 3.2.49.1, 86B8EDB6ED8E3F96A9BAECB5CFDDC96F12B1915C
  - Calamares 3.2.50 - 3.2.62, 4947400F3746A038900BB178328D742D8807A435 (with some exceptions)
  - Calamares 3.3.0 - 3.3.9, 3.3.11, 4947400F3746A038900BB178328D742D8807A435
  - Calamares 3.3.10, 3.3.12, 3.3.13, 6D98B995A1CA6CE4BB906518C7AA337DFA13881E (but release announcement says 4947..)
  - Calamares 3.3.14 - *current*, 6D98B995A1CA6CE4BB906518C7AA337DFA13881E
