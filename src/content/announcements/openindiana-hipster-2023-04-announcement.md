---
title: "Release of 2023.04"
description: "It is my great pleasure to announce the Release of OpenIndiana 2023.04. If you want to know what all has changed in the almost 2000 Commits since last release click here."
pubDate: "2023-04-21"
---


# Release of 2023.04
It is my great pleasure to announce the Release of the 2023.04 Snapshot of OpenIndiana Hipster. This Release marks the most active release since it's inception by commits and maintainers. 
While we had a great number of contributors over the years it has been a long time since we had a stable maintainership. This Release has been made possible through the hard work of these people 
and I would like to use the time to Thank them in this announcement. It is a great pleasure to work with you all. Also a thank you to the community that keeps supporting this projects.

This Release supports both x86 and SPARC. Arm is being worked on but there is no need for a OpenIndiana Release for it as of yet.

All Release notes are generated using `git-cliff` and some manual markings and adaptations.

## Downloads
- x86 
  - Minimal [ISO](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.usb.sha256sum)
  - Server  [ISO](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.usb.sha256sum)
  - Desktop [ISO](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.usb.sha256sum)
  - Cloud Image [IMG](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-cloudimage.img.gz) [Sha256](https://dlc.openindiana.org/isos/hipster/20230421/OI-hipster-cloudimage.img.gz.sha256sum)
### Usage notes on the Downloads
- Please note the the USB image can **only** boot from an USB attached disk not from a HDD. Please use the ISO for Virtualmachine Installation. 
- The Cloud Image contains a metadata agent that allows limited Autoconfiguration by cloud-init configuration data. Only simple networking and SSH-keys are properly tested. Do other configurations after boot with your usual prefered method.

## Highlights
- New Package [moosefs](https://moosefs.com/) a distributed filesystem for Kubernetes and other large applications. Including but not limited to the following features: "Trashbin" per filesystem, Data tiering, 
dynamic expansion, Atomic snapshots, Block storage, Storage Classes (making sure data is in the same Server room in a multi datacenter cluster or on SSD's/HDD's), Archive mode
- The Nvidia Package has been upgraded by default. We are aiming to 470 but as nvidia is
constantly removing cards from newer drivers and older ones have no support for newer cards,
users must start selecting the correct driver by themselves.
- Modern PHP 8.1 is available (it has been for a while but still worth highlighting)
- Thunderbird is now 102.10.0
- 32bit is being removed on an ongoing basis
- many upgrades to the tooling for packaging specifically to automate python and perl packaging
- Mail daemon upgrades
- Firefox is now 112.0

## Stats
To show the progress a bit better here the Git commits grouped by year:
                                                                                                                                                                                                                   
        year    sum
        2010    56      |
        2011    583     |██
        2012    456     |██
        2013    964     |████
        2014    748     |███
        2015    835     |████
        2016    1793    |█████████
        2017    1645    |████████
        2018    1363    |██████
        2019    1092    |█████
        2020    1140    |█████
        2021    1129    |█████
        2022    2885    |██████████████
        2023    1184    |█████

## Detailed log

### APR

- Distribute only 64 bit libraries and binaries

### Firefox

- Update to 112.0

### FreeImage

- Add patch for libraw 0.21 compatibility

### Gamin-0.1.10

- Obsolete library/python/gamin-27

### Mail

- :SpamAssassin - new perl package for mail spam detection

### MediaInfoLib

- Update to 22.12 and provide test results

### Net

- :LibIDN2 - new perl package (Provides bindings for GNU Libidn2)

### PHP

- Add initial SPARC support

### SDL2_mixer

- Update to 2.6.3

### Testing

- Update to 7.1 and switch to qt5

### Libgsasl

- Libgsasl-1.10.0 and enable MIT/GSSAPI

### Amp

- Switch to MariaDB 10.6 and PHP 8.1

### Ant

- Update to 1.10.13

### Apache2

- Update to 2.4.57
- Remove 32 bit dependencies apr/apr-util

### Apr

- Update to 1.7.2
- Update to 1.7.3

### Apr-util

- Update to 1.6.3
- Rebuild for 64bit no 32bit libs/binaries

### Arpack

- Update to 3.9.0

### Aspell

- Drop 32 bit

### Aspell-en

- Update to 2020.12.07-0 and switch to 64 bit

### Aspell-ru

- Update metadata and switch to 64 bit

### Asterisk

- Update to 20.2.1

### Atk

- Update to 2.38.0
- Add missing atk-autocleanups.h

### Autoconf-archive

- Update to 2023.02.20

### Autossh

- Switch to 64 bit and update meta data

### Awstats

- Update to 7.9

### Ayatana-ido

- Add package
- Update to 0.9.3

### Babeltrace

- Update to 1.5.11

### Babl

- Update to 0.1.98 and enable x86 optimisations up to sse2
- Update to 0.1.102

### Bacula

- Rebuild to update to dependencies on mariadb and postgresql
- Update to 13.0.2

### Barman

- Update to 3.3.0
- Update to 3.4.0
- Update to 3.5.0

### Bash

- Update to 5.2p12
- Update to 5.2p15

### Bind

- Update to 9.16.35
- Update to 9.16.36
- Update to 9.16.37
- Update to 9.16.38
- Update to 9.18.13

### Binutils

- Update to 2.40
- Create a fake 2.40 version because the real one is broken for us
- Re-enable real version 2.40 after illumos-gate update

### Bison-3.7

- Force to use illumos ranlib

### Bison-3.8

- Force to use illumos ranlib

### Bluefish

- Update to 2.2.13 and switch to default python

### Borgbackup

- Update to 1.2.3
- Update to 1.2.4

### Bvi

- Update to 1.4.2

### Ca-certificates

- Update to 2023.03.11

### Cabextract

- Update to 1.10
- Update to 1.11

### Chezmoi

- Update to 2.27.2
- Update to 2.27.3
- Update to 2.28.0
- Update to 2.29.1
- Update to 2.29.4
- Update to 2.30.0
- Update to 2.31.0
- Update to 2.31.1
- Update to 2.32.0
- Update to 2.33.0
- Update to 2.33.1

### Chmlib

- Drop 32 bit support

### Citus

- Update to 11.1.5 and switch to openssl-1.1

### Clamav

- Update to 1.0.1

### Cmake

- Update to 3.25.1
- Update to 3.25.2
- Update to 3.25.3
- Update to 3.26.0
- Update to 3.26.1
- Update to 3.26.2
- Update to 3.26.3

### Cmake.mk

- Fix CMAKE_LIBRARY_ARCHITECTURE $(MACH64)
- Cmake needs PATH

### Codeblocks

- Remove GCC10 setting is default now

### Cog-spur

- Support 7033 and 68533 image formats (SistaV1)
- Remove BitmapStreamTests update test master results
- Update to 5.0.3298
- Upgrade to 5.0.3307
- Add ClipboardExtendedPlugin

### Constype

- Update to 1.0.5

### Cracklib

- Update to 2.9.10
- Update to 2.9.11

### Crmsh

- Fix dependencies; remove man pages mangling

### Crypto/ca-certificates

- Update to 3.86

### Cunit

- Libtoolize needs PATH

### Cups-filters

- Update to 1.28.17

### Curl

- Update to 7.87.0
- Update to 7.88.0
- Fix dependencies
- Update to 7.88.1 and enable c-ares and websockets
- Update to 8.0.1
- Autoreconf needs PATH

### Daewoo-misc

- Update to 1.0.4

### Dash

- Update to 0.5.11.5
- Update to 0.5.12

### Database/sqlite

- Properly drop 32-bit support for tcl-sqlite

### Dav1d

- Update to 1.1.0

### Dbus-test-runner

- Add package

### Ddu

- Add PYVER to PKG_MACROS

### Diffutils

- Update to 3.9

### Dnspython

- Update to 2.3.0

### Double-conversion

- Add math support for SPARC

### Dovecot

- Update to 2.3.20

### Doxygen

- Update to 1.9.6

### Emacs

- Import one security patch from solaris-userland

### Enchant

- Update to 2.3.4

### Encodings

- Update to 1.0.7

### Environment.mk (oi-userland)

- Component-environment-prep should install USERLAND_REQUIRED_PACKAGES too

### Exiv2

- Update to 0.27.6
- Fix stack unwinding problems due to superfluous and outdated cmake module

### Expect

- Update metadata and drop 32 bit apps
- Drop 32bit + SPARC vis instruction option

### Extra-cmake-modules

- Update to 5.101.0
- Update to 5.102.0
- Update to 5.103.0
- Update to 5.104.0 and add documentation
- Update to 5.105.0

### Fbreader

- Switch to 64 bit

### Fcron

- Update to 3.3.1

### Fetchmail

- Update to 6.4.35
- Update to 6.4.36
- Update to 6.4.37

### Ffmpeg

- Update to 6.0

### Fftw-3

- Update to 3.3.10 and activate SSE2

### Filebench

- Rebuild for 64 bit

### Fio

- Update to 3.34

### Firefox

- Update to 102.6.0
- Update to 102.7.0 and update dependencies
- Update to 110.0
- Update to 110.0.1
- Update to 111

### Fish

- Update to 3.6.0 and provide test results
- Update to 3.6.1

### Font-util

- Update to 1.4.0

### Fontconfig

- Update to 2.14.2
- Work-around to fix firefox

### Freeciv

- Update to 3.0.5
- Update to 3.0.6
- Update to 3.0.7

### Freerdp

- Update to 2.9.0
- Update to 2.10.0

### Freetype

- Update to 2.13.0

### Gammu

- Switch to 64 bit and fix dependencies

### Gcc-10

- Import OmniOS patch to understand %h in the kernel and update
- Add convenience package with links into /usr/lib
- Solaris (and illumos) have no /proc/%d/task/

### Gcc-11

- Add convenience package with links into /usr/lib and update mpc and mpfr
- Solaris (and illumos) have no /proc/%d/task/

### Gcc-7

- Install-strip should install libobjc

### Gcc-component.mk (oi-userland)

- Packages required by tests should go to TEST_REQUIRED_PACKAGES
- Fix bootstrap detection
- Don't test target libraries twice

### Gdb

- Update  12.1
- Fix bugs in gen_syscall_table script

### Gdl

- Add missing patch

### Geeqie

- Update to 1.7.3

### Gegl

- Update to 0.4.40
- Disable documentation and vala support
- Update to 0.4.42
- Update to 0.4.44

### Gentium

- Update to 6.200

### Gettext

- Drop 32-bit binaries

### Gexiv2

- Update to 0.14.0

### Ggrep

- Packages required by tests should go to TEST_REQUIRED_PACKAGES

### Gi-docgen

- Add package

### Gimp

- Update to 2.10.34

### Git

- Update to 2.38.2
- Update to 2.39.0
- Update to 2.39.1
- Update to 2.39.2
- Update to 2.40.0
- Packages required by tests should go to TEST_REQUIRED_PACKAGES

### Glib

- Update to 2.74.6

### Glib-networking

- Drop 32 bit & provide test results

### Glib2

- Re-add 32 bit apps

### Gnome-commander

- Switch to 64 bit

### Gnome-connection-manager

- Rebuild for Python 3.9

### Gnome-keyring

- Update to 3.36.0 and add test results

### Gnu-coreutils

- Update to 9.2

### Gnu-grep

- Update to 3.9
- Update to 3.10

### Gnudatalanguage

- Update to 1.0.2 and provide test results

### Gnumeric

- Update to 1.12.54
- Update to 1.12.55

### Gnupg

- Update to 2.4.0

### Gnuplot

- Update to 5.4.6

### Gnutls

- Update to 3.8.0 and drop 32 bit tests

### Gobject-introspection

- Update to 1.72.0

### Goffice

- Update to 0.10.54
- Update to 0.10.55

### Golang-118

- Update to 1.18.9
- Update to 1.18.10

### Golang-119

- Update to 1.19.4
- Update to 1.19.8
- Update to 1.19.5
- Update to 1.19.6
- Update to 1.19.7

### Gpgme

- Update to 1.19.0

### Graphicsmagick

- Update to 1.3.40

### Graphviz

- Fix graphviz-perl-534 obsoletion and add graphviz-perl-536

### Gsl

- Update to 2.7.1 and drop 32 bit

### Gsoap

- Update to 2.8.124

### Gspell

- Update to 1.12.0

### Gst-devtools1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gst-editing-services1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2 and drop bash-completions

### Gst-libav1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Rebuild after FFmpeg update
- Update to 1.22.2

### Gst-plugins-bad1

- Update to 1.20.5
- Disable spandsp module because it breaks building on the server
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gst-plugins-base1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gst-plugins-good1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gst-plugins-python1

- Update to 1.22.0

### Gst-plugins-ugly1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gst-python

- Update to 1.20.5
- Update to 1.22.1
- Update to 1.22.2

### Gst-rtsp-server1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gstreamer1

- Update to 1.20.5
- Update to 1.22.0
- Update to 1.22.1
- Update to 1.22.2

### Gtk-doc

- Rebuild for Python 3.9
- Fix dependencies

### Gtkperf

- Rebuild for 64 bit

### Gtksourceview-3

- Fix manifest

### Haproxy

- Update to 2.7.2 and switch to openssl-1.1
- Update to 2.7.3
- Update to 2.7.4
- Add value ultrasparc to CPU variable
- Update to 2.7.5
- Update to 2.7.6

### Harfbuzz

- Update to 6.0.0
- Update to 7.0.0
- Update to 7.0.1
- Update to 7.1.0

### Hdf5

- Update to 1.14.0 and provide test results

### Help2man

- Update to 1.49.3

### Hplip

- Update to 3.22.10
- Add missing license file

### Htop

- Update to 3.2.2

### Hunspell

- Remove outdated patches (#10959)
- Enhance metadata

### Idzebra

- Update to 2.2.7 and drop 32 bit

### Imath

- Update to 3.1.7

### Indent

- Update to 2.2.13

### Install-types

- Replace nvidia-390 by nvidia

### Ipcalc

- Update to 0.51

### Iperf

- Rebuild for 64 bit

### Iperf3

- Update to 3.1.3, switch to 64 bit and drop static library

### Ips.mk (oi-userland)

- Remove gcc 4.9 remnants

### Irssi

- Update to 1.4.4

### Isas-misc

- Update to 1.0.4

### Iso-codes

- Update to 4.13.0

### Ixion

- Update to 0.18.1 and drop 32 bit

### Jenkins-core-lts

- Update to 2.375.3
- Update to 2.387.1
- Update to 2.387.2

### Jenkins-core-weekly

- Update to 2.379
- Update to 2.393
- Update to 2.394
- Update to 2.397
- Update to 2.399

### Jetbrains-mono

- Update to 2.304

### Jinja2

- TEST_STYLE=setup.py to be able to publish
- Add tests for python-37 and python-3.9

### Jis-misc

- Update to 1.0.4

### Json-glib

- Add 32 bit libs as they are needed by libgdata

### Kvm

- Fix dependencies

### Lasso

- Update to 2.8.1
- Update to 2.8.2

### Lcms2

- Update to 2.15

### LibSM

- Update to 1.2.4

### LibX11

- Don't use hardcoded arch. names in path

### LibXScrnSaver

- Update to 1.2.4

### LibXau

- Update to 1.0.11

### LibXaw

- Update to 1.0.15

### LibXcomposite

- Update to 0.4.6

### LibXdamage

- Update to 1.1.6

### LibXkbfile

- Update to 1.1.2

### LibXres

- Update to 1.2.2

### LibXv

- Update to 1.0.12

### Liba52

- Update to 0.8.0 and add test results

### Libarchive

- Import two patches from solaris-userland & switch to openssl-1.1
- Update to 3.6.2

### Libass

- Update to 0.17.0
- Update to 0.17.1

### Libayatana-appindicator

- Add package
- Update to 0.5.92

### Libayatana-indicator

- Add package

### Libbluray

- Update to 1.3.4

### Libcares

- Update to 1.19.0 and provide test results

### Libcompizconfig

- Fix build and metadata

### Libdbusmenu

- Add package

### Libdiscid

- Update to 0.6.4 and provide test results

### Libdvdnav

- Update to 6.1.1

### Libdvdread

- Update to 6.1.3

### Libfastjson

- Update to 0.99.9.1 and provide test results

### Libfontenc

- Update to 1.1.7

### Libgcrypt

- Update to 1.10.2

### Libgdata

- Update to 0.18.1

### Libgee

- Update to 0.20.6

### Libgnt

- Get rid of python2 - migrate to python3

### Libgpg-error

- Autoreconf needs PATH
- Update to 1.47

### Libgsf

- Update to 1.14.50

### Libhandy

- Update to 1.8.1
- Add missing build dependency
- Update to 1.8.2

### Libical

- Update to 3.0.16, drop 32 bit and add test results

### Libice

- Update to 1.1.1

### Libid3tag

- Update to 0.16.2

### Libidn

- Autoreconf needs PATH

### Libjpeg-turbo

- Update to 2.1.5
- Update to 2.1.5.1

### Libksba

- Update to 1.6.3

### Liblouis

- Update to 3.24.0
- Update to 3.25.0

### Libmad

- Cleanup and modernize the Makefile

### Libmagic/file

- Update to 5.44 and filter test results better
- Add lzlib dependency

### Libmediainfo

- Update to 23.03

### Libmemcached

- Update to 1.0.18 and add test results

### Libmicrohttpd

- Update to 0.9.76

### Libmms

- Cleanup the Makefile and fix URLs

### Libmodbus

- Update to 3.1.10 and provide test results

### Libmpeg2

- Cleanup, fix URLs and add test results

### Libmtp

- Update to 1.1.20

### Libnotify

- Update to 0.7.12

### Libpaper

- Update to 2.1.0

### Libpcap

- Update to 1.10.3
- Update to 1.10.4

### Libplist

- Update to 2.2.0, drop 32 bit and add test results

### Libpoppler

- Drop 32 bit

### Libpqxx

- Update to 7.7.5 and drop 32 bit

### Libpsl

- Add package

### Library/cairo

- Libtoolize needs PATH

### Libraw

- Update to 0.21.1

### Libreoffice

- Update to 7.5.1.2

### Librevenge

- Update to 0.0.5

### Librsync

- Update to 2.3.4 and provide test results

### Libsamplerate

- Re-add 32 bit

### Libsigsegv

- Update to 2.14

### Libsoup3

- Add package

### Libspectre

- Update to 0.2.10
- Update to 0.2.11
- Update to 0.2.12

### Libstatgrab

- Update to 0.92.1

### Libtiff

- Update to 4.5.0 and drop 32 bit apps

### Libtool

- Bootstrap needs PATH

### Libusb-1

- Update to 1.0.26 and add test results

### Libwebp

- Update to 1.3.0

### Libwps

- Update to 0.4.13 and drop 32 bit

### Libxfixes

- Update to 6.0.1

### Libxml2

- Autoreconf needs PATH

### Libxpm

- Update to 3.5.15

### Libxshmfence

- Update to 1.3.2

### Libxslt

- Properly obsolete library/python/libxsl-27
- Fix libxslt-39 FMRI
- Move python package into FMRI python sub-category

### Libyaml

- Bootstrap needs PATH; add test results

### Libzen

- Update to 0.4.40

### Lighttpd

- Update to 1.4.68
- Update to 1.4.69

### Lmdb

- Update to 0.9.30

### Lndir

- Update to 1.0.4

### Logrotate

- Update to 3.21.0

### Lsof

- Update to 4.96.5

### Mailutils

- Fix missing PKG_MACRO and manifest file

### Make-rules (oi-userland)

- Cleanup REQUIRED_PACKAGES
- Introduce USERLAND_TEST_REQUIRED_PACKAGES
- Sort order should not depend on locale
- Set PYVER/PYV/PERLVER/PLV for single Perl/Python version builds (ips.mk)
- Support for Post-releases (py-defaults.mk)

### Makedepend

- Update to 1.0.8

### Marco

- Prevent 1.26.1 from crashing related uninitialized pointer
- Add three commits to fix XRes related crashes from the project that haven't been released yet

### Mariadb-101

- Obsolete MariaDB 10.1 and switch default mediator to 10.6

### Mariadb-106

- Add back missing include files

### Mate-common

- Update to 1.27.0
- Fix typo
- Fix one more typo

### Mate-desktop

- Update to 1.26.1

### Maven

- Update to 3.8.7
- Update to 3.9.0
- Update to 3.9.1

### Mc

- Update to 4.8.29

### Mdds

- Update to 2.1.0

### Megasync

- Update to 4.9.0.0
- Rebuild after FFmpeg update

### Meson

- Update to 0.64.1
- Update to 1.0.0
- Update to 1.0.1
- Update to 1.1.0

### Minidlna

- Rebuild after FFmpeg update

### Misc-ethiopic

- Update to 1.0.5

### Misc-meltho

- Update to 1.0.4

### Mod_security2

- Update to 2.9.7

### Mpc

- Update to 1.3.0
- Update to 1.3.1

### Mpfr

- Update to 4.2.0

### Mpg123

- Update to 1.31.2
- Update to 1.31.3

### Mutt

- Update to 2.2.10

### Mysql_fdw

- Fix mariadb / postgress dependencies

### Nano

- Update to 7.1
- Update to 7.2

### Nasm

- Update to 2.16.01

### Ncurses

- Update to 6.4

### Net-snmp

- Fix build

### Netcdf

- Rename to netcdf-c, update to 4.9.0 and provide test results
- Update to 4.9.2

### Network/moosefs

- Added package

### Network/zabbix-agent

- Update to 6.2.7

### Nghttp2

- Update to 1.51.0
- Update to 1.52.0

### Nghttp3

- Update to 0.9.0
- Update to 0.10.0

### Nginx

- Update to 1.22.1

### Ngtcp2

- Update to 0.13.1
- Update to 0.14.0
- Update to 0.14.1

### Ninja

- Build and test needs PATH

### Nodejs-16

- Update to 16.19.0

### Nodejs-18

- Update to 18.13.0
- Update to 18.14.0
- Update to 18.14.2
- Update to 18.15.0
- Update to 18.16.0

### Nvidia

- Update to 525.60.11
- Update to 525.78.01
- Update to 525.85.05
- Update to 525.89.02
- Update to 525.105.17

### Nvidia-470

- Update to 470.182.03

### Olm

- Update to 3.2.14

### Openal-soft

- Update to 1.17.0

### Openblas

- Update to 0.3.22
- Update to 0.3.23

### Opencore-amr

- Update to 0.1.6

### Openexr

- Update to 3.1.6
- Make architecture independent
- Update to 3.1.7

### Openjdk-11

- Update to 11.0.18

### Openjdk-17

- Update to 17.0.6

### Openjdk-19

- Update to 19.0.2

### Openjdk-20

- Add package

### Openldap

- Update to 2.6.4 and add test results
- Force known perl version

### Openscenegraph

- Rebuild and disable FFmpeg support

### Openssh

- Update to 9.1p1
- Update to 9.2p1
- Update to 9.3p1

### Openssl

- Add patches for CVE-2023-0464

### Openssl-1.0.2

- Add patches for CVE-2023-0215 and CVE-2023-0286

### Openssl-1.1

- Update to 1.1.1t

### Pan

- Add system/library/math needed on SPARC

### Pango

- Update to 1.50.13
- Update to 1.50.14

### Pari

- Update to 2.15.2 and activate gmp
- Update to 2.15.3

### Pcre2

- Update to 10.42

### Pdns-recursor

- Fix dependencies

### Perl/Alien-Build

- Update to 2.74
- Update to 2.75
- Update to 2.76
- Update to 2.77
- Update to 2.78

### Perl/CGI

- Update to 4.55
- Update to 4.56

### Perl/CPAN-Meta-Check

- Update to 0.015
- Update to 0.017

### Perl/Class-Method-Modifiers

- Update to 2.14
- Update to 2.15

### Perl/Config-Tiny

- Update to 2.29

### Perl/Crypt-X509

- Update to 0.55

### Perl/DBD-Pg

- Update to 3.16.1
- Update to 3.16.3

### Perl/DBD-mysql

- Rebuild for MariaDB 10.6

### Perl/Data-OptList

- Update to 0.113

### Perl/Date-Manip

- Update to 6.90
- Update to 6.91

### Perl/DateTime-TimeZone

- Update to 2.57
- Update to 2.58
- Update to 2.59
- Update to 2.60

### Perl/Email-Address

- Update to 1.913

### Perl/Email-Date-Format

- Update to 1.007
- Update to 1.008

### Perl/Email-MIME

- Update to 1.953

### Perl/Email-MIME-ContentType

- Update to 1.028

### Perl/Email-MIME-Encodings

- Update to 1.317

### Perl/Email-MessageID

- Update to 1.408

### Perl/Email-Simple

- Update to 2.218

### Perl/Email-Stuffer

- Update to 0.019
- Update to 0.020

### Perl/Exporter-Tiny

- Update to 1.006001
- Update to 1.006002

### Perl/HTML-Parser

- Update to 3.81

### Perl/HTTP-Daemon

- Update to 6.15
- Update to 6.16

### Perl/IO-Socket-SSL

- Update to 2.078
- Update to 2.079
- Update to 2.080
- Update to 2.081

### Perl/MIME-Types

- Update to 2.23
- Update to 2.24

### Perl/Mail-AuthenticationResults

- Update to 2.20230112

### Perl/Mail-DKIM

- Update to 1.20230212

### Perl/Module-Build

- Update to 0.4232

### Perl/Mojolicious

- Update to 9.30
- Update to 9.31

### Perl/Moo

- Update to 2.005005

### Perl/Net-DNS

- Update to 1.36
- Update to 1.37

### Perl/Net-DNS-Resolver-Mock

- Update to 1.20230216

### Perl/Net-Server

- Update to 2.012
- Update to 2.013
- Update to 2.014

### Perl/Package-DeprecationManager

- Update to 0.18

### Perl/Params-ValidationCompiler

- Update to 0.31

### Perl/Path-Tiny

- Update to 0.144

### Perl/Sub-Exporter

- Update to 0.989

### Perl/Sub-Install

- Update to 0.929

### Perl/Sub-Quote

- Update to 2.006008

### Perl/Test-Deep

- Update to 1.202
- Update to 1.204

### Perl/Test-Fatal

- Update to 0.017

### Perl/Test-File

- Update to 1.993

### Perl/Test-Inter

- Update to 1.10

### Perl/Test-Needs

- Update to 0.002010

### Perl/Test-Without-Module

- Update to 0.21

### Perl/Test2-Suite

- Update to 0.000147
- Update to 0.000148
- Update to 0.000150

### Perl/Throwable

- Update to 1.001

### Perl/Type-Tiny

- Update to 2.002000
- Update to 2.002001
- Update to 2.004000

### Perl/Unicode-Normalize

- Remove - Unicode::Normalize is already provided by perl package

### Perl/YAML-LibYAML

- Update to 0.86

### Perl/YAML-Tiny

- Update to 1.74

### Perl/libwww-perl

- Update to 6.68

### Pgadmin3

- Update to 1.23 drop32 bit and wxwidgets2

### Pgbadger

- Update to 12.1

### Pgbouncer

- Update to 1.18.0

### Pgpool-II

- Update to 4.4.2 and use openssl-1.1 and PAM

### Pgtcl

- Drop 32bit add SPARC vis instruction option

### Php-81

- Update to 8.1.17

### Php-8_1-ext-memcache

- Add SPARC support

### Php-8_1-ext-memcached

- Add/correct build types

### Php-8_1-ext-mongodb

- Add/correct build types

### Php-8_1-ext-oauth

- Add/correct build types

### Php-8_1-ext-rrd

- Add/correct build types

### Pidgin

- Update to 2.14.12

### Pkgconf

- Update to 1.9.4

### Poppler-data

- Update metadata

### Postgresql-12

- Update to 12.14

### Postgresql-12-mysql_fdw

- Rebuild for MariaDB 10.6

### Postgresql-14

- Update to 14.7

### Postgresql-jdbc

- Update to 52.5.4
- Update to 42.6.0

### Privoxy

- Update to 3.0.34

### Proj

- Update to 9.2.0

### Pugixml

- Update to 1.13

### Pycurl

- Update 7.45.2 add ssl-1.1 obso. pycurl-35

### Pyproject.mk (oi-userland)

- Evaluate build dependencies
- Pyproject_installer should compile site-packages too
- Detect more build deps using get_requires_for_build_wheel hook

### Pystring

- Update to 1.1.4, fix CLASSIFICATION, and provide test results

### Python-dbus

- Update to version 1.3.2

### Python-xdg

- Rename to pyxdg, update to 0.28, add test results, add support for python 3.7

### Python/Automat

- Move from automat; update to 22.10.0; rebuild to get package for python 3.5 obsoleted

### Python/CherryPy

- Move from cherrypy; update to 18.8.0; rebuild to get package for python 3.5 obsoleted

### Python/Jinja2

- Move from jinja2; update to 3.1.2

### Python/Mako

- Move from mako; update to 1.2.4; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/MarkupSafe

- Move from markupsafe; update to 2.1.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/Pillow

- Move from pillow; update to 9.4.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/PyNaCl

- Move from pynacl; update to 1.5.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/PyYAML

- Move from pyyaml; update to 6.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/Pygments

- Move from pygments; update to 2.13.0; rebuild to get package for python 3.5 obsoleted

### Python/Pyro4

- Move from pyro4; update to 4.82; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/RBTools

- Move from rbtools; update to 4.0; rebuild for python 3.7 and 3.9 and to get package for python 3.5 obsoleted

### Python/Sphinx

- Update to 6.1.3

### Python/Twisted

- Move from twisted; rename package to normalize it; update to 22.10.0; obsolete package for python 3.5

### Python/ansible

- Update to 7.4.0

### Python/appdirs

- Add test results

### Python/argh

- Update dependencies, license and test results
- Update to 0.27.1
- Update to 0.27.2

### Python/astroid

- Update to 2.13.2; rebuild for python 3.7

### Python/attrs

- Update to 22.2.0

### Python/backports.entry_points_selectable

- Rename package to normalize it; update to 1.2.0
- Add test results

### Python/backports.functools_lru_cache

- Rename package to normalize it; update to 1.6.4
- Add test results

### Python/bcrypt

- Update to 3.2.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/bcrypt-legacy

- Remove obsoleted component

### Python/black

- Update to 23.1.0
- Update to 23.3.0

### Python/bleach

- Set PYTHON_TEST_BOOTSTRAP to break dependency loop
- Update to 6.0.0

### Python/build

- Update to 0.10.0

### Python/cachetools

- Update to 5.3.0

### Python/ccsm

- Rebuild for Python 3.9

### Python/certifi

- Move from python-certifi; update to 2022.12.7; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/cffi

- Update to 1.15.1; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/charset-normalizer

- Update to 3.0.1

### Python/cheroot

- Update to 9.0.0; rebuild to get package for python 3.5 obsoleted

### Python/compizconfig-python

- Rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted
- Do not incorporate recently obsoleted packages

### Python/configobj

- Update to 5.0.8

### Python/constantly

- Rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/contextlib2

- Update to 21.6.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/covdefaults

- Update to 2.2.2

### Python/coverage

- Update to 7.0.5; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 7.2.1

### Python/cryptography

- Update to 3.2.1; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Restore support for OpenSSL 1.0.2
- Remove warning for OpenSSL 1.0.2

### Python/cryptography_vectors

- Update to 39.0.1

### Python/decorator

- Update to 5.1.1; rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/distro

- Update to 1.8.0

### Python/dnspython

- Add test results

### Python/docutils

- Update to 0.19

### Python/elementpath

- Update to 4.0.1

### Python/exceptiongroup

- Update to 1.0.4
- Update to 1.1.0
- Update to 1.1.1

### Python/fastjsonschema

- Update to 2.16.3

### Python/filelock

- Update to 3.9.0
- Update to 3.10.7

### Python/flake8

- Support for pycodestyle 2.10; add test results
- Update to 6.0.0

### Python/flake8-noqa

- Update to 1.3.0
- Update to 1.3.1

### Python/flaky

- Rebuild to get package for python 3.5 obsoleted

### Python/flamegraph

- Rebuild for python 3.7 and 3.9 and to get package for python 2.7 obsoleted

### Python/flit_core

- Add test results

### Python/freezegun

- Update to 1.2.2

### Python/frozendict

- Update to 2.3.5; rebuild for python 3.7

### Python/ghp-import

- Add package dependencies

### Python/hatch_vcs

- Update to 0.3.0

### Python/hatchling

- Update to 1.12.2
- Update to 1.13.0

### Python/hyperlink

- Rebuild to get package for python 3.5 obsoleted

### Python/hypothesis

- Update to 6.60.0; rebuild to get package for python 3.5 obsoleted
- Update to 6.68.2

### Python/idna

- Update to 3.4; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/importlib_metadata

- Update to 5.2.0
- Update to 6.0.0
- Update to 6.1.0

### Python/importlib_resources

- Update to 5.12.0

### Python/incremental

- Update to 22.10.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/inflect

- Add test results
- Update to 6.0.4

### Python/iniconfig

- Add test results
- Update to 2.0.0

### Python/installer

- Update to 0.6.0
- Update to 0.7.0

### Python/ipython

- Update to 7.34.0; rebuild for python 3.7 and 3.9 and to get package for python 3.5 obsoleted

### Python/isort

- Update to 5.12.0

### Python/isort-37

- Add isort for Python 3.7

### Python/jaraco.collections

- Update to 4.0.0

### Python/jaraco.context

- Rename package to normalize it; update to 4.2.0

### Python/jaraco.envs

- Rename package to normalize it
- Add history to really rename the package
- Add test results

### Python/jaraco.functools

- Rename package to normalize it; update to 3.5.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/jaraco.text

- Add test results

### Python/jsonrpclib-pelix

- Move from jsonrpclib; rename package; update to 0.4.3.2; obsolete packages for python 2.7 and 3.5

### Python/jsonschema

- Update to 4.17.3; rebuild to get package for python 3.5 obsoleted

### Python/lazy_object_proxy

- Rename package to lazy-object-proxy

### Python/lxml

- Move from pylxml; update to 4.9.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/markdown

- Update to 3.4.1; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/mkdocs

- Update to 1.4.2
- Add babel to REQUIRED_PACKAGES

### Python/mock

- Update to 4.0.3; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 5.0.0

### Python/more-itertools

- Update to 9.0.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/msgpack

- Update to 1.0.4

### Python/mypy

- Update to 1.0.1
- Update to 1.1.1

### Python/mypy_extensions

- Update to 1.0.0

### Python/nbformat

- Update to 5.7.2

### Python/notify2

- Rebuild for python 3.7 and 3.9 and to get package for python 3.5 obsoleted

### Python/packaging

- Update to 22.0
- Update to 23.0

### Python/paramiko

- Update to 2.12.0; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 3.0.0

### Python/path

- Update to 16.6.0

### Python/pathlib2

- Update to 2.3.7.post1; rebuild for python 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/pathspec

- Update to 0.10.3
- Update to 0.11.0
- Update to 0.11.1

### Python/pexpect

- Rebuild to get package for python 3.5 obsoleted

### Python/pickleshare

- Update to 0.7.5; rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/pip

- Update to 22.3.1; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 23.0
- Update to 23.0.1

### Python/pip-run

- Update to 10.0.5

### Python/pipdeptree

- Update to 2.3.3; rebuild to get package for python 3.5 obsoleted

### Python/pkgconfig

- Fix component summary

### Python/platformdirs

- Update to 2.6.0
- Update to 2.6.2
- Update to 3.0.0
- Update to 3.2.0

### Python/ply

- Rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/poetry_core

- Move from poetry-core; update to 1.5.0

### Python/portend

- Update to 3.1.0; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Add test results

### Python/pretend

- Rebuild to get package for python 3.5 obsoleted

### Python/prettytable

- Update to 3.6.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/prompt_toolkit

- Move from prompt-toolkit; update to 3.0.36; rebuild for python 3.7 and 3.9 and to get packages fothon 2.7 and 3.5 obsoleted (#10245)

### Python/psycopg2

- Update to 2.9.5

### Python/ptyprocess

- Rebuild to get package for python 3.5 obsoleted

### Python/py

- Disable testing

### Python/py-cpuinfo

- Update to 9.0.0; rebuild to get package for python 3.5 obsoleted

### Python/py3c

- Move from library/py3c; rename package to normalize it; update to 1.4

### Python/pyOpenSSL

- Move from pyopenssl; rebuild to get package for python 3.5 obsoleted

### Python/pyasn1

- Rebuild to get package for python 3.5 obsoleted

### Python/pybonjour

- Rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/pycairo

- Update to 1.23.0; rebuild to get package for python 3.5 obsoleted

### Python/pycodestyle

- Update to 2.10.0

### Python/pycparser

- Rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/pycups

- Update to 2.0.1; rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/pyfakefs

- Fix tests

### Python/pyflakes

- Update to 3.0.1

### Python/pyhamcrest

- Move from hamcrest; rename package to normalize it; update to 2.0.4; obsolete package for python 3.5

### Python/pylint

- Normalize package dependencies

### Python/pyproject_api

- Update to 1.5.0
- Update to 1.5.1

### Python/pyproject_installer

- Update to 0.4.0

### Python/pyrsistent

- Update to 0.19.3; rebuild to get package for python 3.5 obsoleted

### Python/pytest

- Update to 7.2.1
- Update to 7.2.2

### Python/pytest-asyncio

- Update to 0.20.3

### Python/pytest-benchmark

- Update to 4.0.0; rebuild to get package for python 3.5 obsoleted

### Python/pytest-cov

- Update to 4.0.0

### Python/pytest-forked

- Update to 1.6.0

### Python/pytest-freezegun

- Fix DeprecationWarning

### Python/pytest-randomly

- Update to 3.12.0

### Python/pytest-reporter

- Update to 0.5.2; rebuild to get package for python 3.5 obsoleted

### Python/pytest-travis-fold

- Drop dependency on py
- @pytest.mark.trylast is deprecated

### Python/pytest_socket

- Move from pytest-socket; update to 0.6.0

### Python/python-dateutil

- Update to 2.8.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/python-rapidjson

- Rename package to normalize it; update to 1.9

### Python/python-xlib

- Update to 0.33; rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/pytz

- Update to 2022.7.1; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/pyzmq

- Update to 25.0.0; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/readme_renderer

- Add test results

### Python/requests

- Update to 2.28.1; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 2.28.2

### Python/resolvelib

- Update to 1.0.1

### Python/serpent

- Update to 1.41; rebuild to get package for python 3.5 obsoleted

### Python/setuptools

- Update to 65.6.3
- Fix C compiler executables
- Update to 65.7.0
- Update to 67.0.0
- Update to 67.1.0
- Update to 67.2.0
- Update to 67.3.2
- Update to 67.4.0
- Update to 67.6.1

### Python/setuptools_scm

- Update to 7.1.0

### Python/simplegeneric

- Rebuild for python 3.7 and 3.9 and to get packages for python 2.7 and 3.5 obsoleted

### Python/simplejson

- Update to 3.18.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/singledispatch

- Update to 4.0.0; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Add test results

### Python/sortedcontainers

- Rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/stevedore

- Update to 5.0.0

### Python/stevedore-37

- Downgrade to 3.5.2

### Python/tempora

- Update to 5.2.0; rebuild to get packages for python 2.7 and 3.5 obsoleted
- Update to 5.2.1
- Add test results

### Python/texttable

- Update to 1.6.7; rebuild to get package for python 3.5 obsoleted

### Python/toml

- Rebuild to get package for python 3.5 obsoleted

### Python/tomli

- Update REQUIRED_PACKAGES

### Python/tornado

- Update to 6.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/tox

- Update to 3.28.0
- Update to 4.2.8
- Update to 4.3.5
- Update to 4.4.4
- Update to 4.4.5
- Update to 4.4.6
- Update to 4.4.8
- Update to 4.4.11

### Python/tox-current-env

- Update to 0.0.10
- Update to 0.0.11

### Python/tqdm

- Update to 4.64.1

### Python/typeguard

- Update to 3.0.2

### Python/types-setuptools

- Update to 65.7.0.3

### Python/typing_extensions

- Add test results
- Update to 4.5.0

### Python/urllib3

- Update to 1.26.14; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/virtualenv

- Update to 20.17.1
- Update to 20.19.0
- Update to 20.20.0
- Update to 20.21.0

### Python/watchdog

- Update to 2.2.1
- Update to 2.3.1
- Update to 3.0.0

### Python/wcwidth

- Update to 0.2.6; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/webencodings

- Fix license

### Python/wheel

- Add test results
- Update to 0.40.0

### Python/wrapt

- Update to 1.14.1
- Update to 1.15.0

### Python/xmlschema

- Update to 2.2.2

### Python/zc.lockfile

- Rename package to normalize it; obsolete packages for python 2.7 and 3.5
- Add test results

### Python/zipp

- Update to 3.11.0
- Update to 3.12.0
- Update to 3.13.0
- Add test results
- Update to 3.14.0
- Update to 3.15.0

### Python/zope.interface

- Move from zope-interface; rename package to normalize it; update to 5.5.2; rebuild to get packages for python 2.7 and 3.5 obsoleted

### Python/zope.testrunner

- Update to 5.6

### Python27

- Update dependencies

### Python37

- Update to 3.7.16

### Python39

- Update to 3.9.16

### Qhull

- Update to 8.0.2 and provide test results

### Qpdf

- Update to 11.2.0
- Update to 11.3.0

### Qt5

- Drop 32 bit and use default mariadb, postgresql

### Qt6

- Switch to clang-15 and update dependencies

### Qtcreator

- Fix build by adding yaml-cpp dependency

### Quilt

- Update to 0.67

### Raptor2

- Update to 2.0.16 and provide test results

### Redis

- Update to 6.2.10

### Remmina

- Update to 1.4.29

### Ruby-23

- Rebuild after libgdbm update and fix dependencies

### Rustc

- Update to 1.67.1

### Samba

- Comment out archive signature url as it fails verification

### Sbcl

- Update to 2.2.11
- Update to 2.3.0
- Update to 2.3.1
- Update to 2.3.2
- Update to 2.3.3

### Scfdot

- Convert to 64 bit - add optimization

### Scientific/gdl

- Rebuild to fix metadata

### Scons

- Update to 4.4.0

### Sdl2

- Update to 2.26.3

### Setup.py.mk (oi-userland)

- Make coverage report removal more generic
- Make sure pytest is called indirectly to properly support tox-current-env
- Indirect pytest for another tox.ini syntax
- Mangle only the 'commands' keys in tox.ini
- Add unittest test style
- Call coverage and zope.testrunner inderictly by tox
- Remove timing from zope.testrunner test results
- Conversion to lowercase is needed too for full normalization of tox test dependencies
- Fix typo TOX_CALL_INIDIRECTLY -> TOX_CALL_INDIRECTLY
- Evaluate tox deps
- Add py.test to TOX_CALL_INDIRECTLY
- Allow PYTEST_ADDOPTS customization
- Set PATH for tox to workaround a bug
- Do not fail tox pre-test if there is no tox.ini
- 'tox --print-deps-to' failure is fatal
- Remove timing for tox 4 test results
- Recognize versioned binaries without hyphen
- TOX_CALL_INDIRECTLY should work with tabs too
- Normalize timing for single setup.py test too
- Add sphinx-build to TOX_CALL_INDIRECTLY
- Sort list of Sphinx doctest results
- Do not match TOX_CALL_INDIRECTLY entries as substrings
- Support for nose (via tox)
- TOX_TESTENV_PASSENV and --recreate are no longer needed for tox>=4 and recent tox-current-env
- Add --recreate back to tox to get consistent test results
- 'tox --print-extras-to' failure is fatal; tox always needs --no-provision
- Allow components to specify extra args for tox

### Sg3_utils

- Drop gcc-10 setting is the default now

### Shared-macros.mk (oi-userland)

- Add OPENSSL_LIBDIR and OPENSSL_PKG_CONFIG_PATH definitions
- Normalize PROTO_DIR and BUILD_DIR in test results
- Add more defines for Postgresql and Mysql
- Provide JPEG_IMPLEM_PKG definition
- Add definitions for clang
- PYTHON_SCRIPTS are in PROTO_DIR; make shebang fix more generic
- Openssl should default to 1.1
- PATH should be always set for build, install, and test
- Always prepend PATH with openssl bin dir

### Smartypants

- Add package

### Spdlog

- Drop 32 bit support

### Sqlcipher

- Update to 4.5.3 and switch to openssl-1.1

### Sqlite

- Update to 3.40.1
- Update to 3.41.0
- Remove mapfile
- Update to 3.41.1
- Update to 3.41.2

### Squeak

- Update to 4.20.3

### Sshpass

- Update to 1.10

### Stack-spur

- Support 7033 and 68533 image formats (SistaV1)
- Remove BitmapStreamTests update test master results
- Update to 5.0.3297
- Add ClipboardExtendedPlugin

### Subversion

- Rebuild for perl 5.36
- Rebuild 64bit drop 32bit dependencies

### Sudo

- Update to 1.9.12p2
- Update to 1.9.13p1
- Update to 1.9.13p2
- Update to 1.9.13p3

### Swipl

- Update to 9.0.0
- Update to 9.0.2
- Update to 9.0.4

### System-config-printer

- Update to 1.5.18
- Fix mode for applet and normalize test results

### Tcl

- Drop 32 bit add SPARC vis instruction option

### Tcl-8

- Update to 8.6.13

### Tcl-sqlite

- Drop 32 bit support, fix pkgIndex.tcl

### Tcllib

- Drop 32 bit support
- Fix name clash (page)

### Tcltls

- Provide test results
- Drop 32bit add SPARC vis instuction option

### Tcpdump

- Update to 4.99.3 (#11247)

### Tcsh

- Update to 6.24.02, switch to gcc-10 and drop locale patch
- Update to 6.24.05
- Update to 6.24.06
- Update to 6.24.07
- Mediate csh
- Update to 6.24.08
- Update to 6.24.10

### Tdb

- Update to 1.4.8

### Texinfo

- Update to 7.0.2
- Update to 7.0.3

### Thunderbird

- Update to 102.5.1
- Update to 102.6.0
- Update to 102.6.1 & update dependencies
- Update to 102.7.0
- Update to 102.7.1
- Update to 102.7.2
- Update to 102.8.0
- Update to 102.9.0
- Update to 102.9.1
- Update to 102.10.0

### Tig

- Update to 2.5.8

### Tk

- Drop 32 bit add SPARC vis instruction option

### Tk-8

- Update to 8.6.13

### Tklib

- Drop 32 bit support

### Tmux

- Add fix for CVE-2022-47016

### Toolame

- Update metadata

### Tools/cloney

- Copy mode should work with same set of files as other modes

### Tools/license-detector

- Normalize quotation marks for MIT
- Refactor to move filters to separate files and to support license headers
- Match full Apache-2.0 instead of two lines only
- Add Apache-2.0 license header
- Add ZPL-2.1
- Make BSD-2-Clause a bit more generic
- Recognize '-' as valid terms mark for BSD-3-Clause
- Make sure we do not match one license twice
- Support BSD-2-Clause without empty line after Copyright
- Add Unlicense
- Some BSD-2-Clause texts have terms without any marking
- Add BSD-3-Clause-Modification
- Add HPND
- Add MPL-2.0 license header
- Add GPL-3.0-only
- ISC filter should capture single copy of license only

### Tools/perl-integrate-module

- Do not re-run test if it failed earlier
- Warn if test results differ
- Failed fetch is fatal
- Get download_url for specified version, not always the latest

### Tools/perl-version-convert

- Fix special handling for Mail-DMARC

### Tools/python-integrate-project

- Warn if pytest is called directly by tox
- Support for testing bootstrapped projects
- Check and warn more direct pytest call cases
- Check only the 'commands' keys in tox.ini
- Warn if any TOX_CALL_INDIRECTLY tool is called directly
- Set HUMAN_VERSION instead of COMPONENT_VERSION
- Escape & in summary
- Support for tox 4
- Disable checkdocs pytest plugin
- Better support for missing download url
- Fix quoting
- Allow to specify target directory for integration
- Cleanup before we try to publish
- Support for SINGLE_PYTHON_VERSION

### Tools/python-requires

- Handle comments and invalid lines

### Tools/python-resolve-deps

- Handle tox extras dependencies specified in deps
- Handle DOS line ends

### Tor

- Update to version 0.4.7.12
- Update to version 0.4.7.13

### Transforms/generate-cleanup

- Replace Python version in *-nspkg.pth files
- Replace $(HUMAN_VERSION)
- Drop pyc/pyo files for Python 2.7
- Transform $(PYVER) for usr/bin files from Python packages only
- Fix syntax error when COMPONENT_FMRI is empty

### Transforms/python

- Fix tmp.fmri delete

### Transset

- Update to 1.0.3

### Twemoji

- Update to 14.0.2

### Uhttpmock

- Correct manifest and drop 32 bit

### Unrar

- Update to 6.2.5
- Update to 6.2.6

### Vala

- Update to 0.56.4
- Update to 0.56.5
- Update to 0.56.6

### Vim

- Update to 9.0.0950
- Update to 9.0.1000
- Update to 9.0.1100
- Update to 9.0.1199
- Update to 9.0.1250
- Update to 9.0.1300
- Update to 9.0.1350
- Update to 9.0.1400
- Update to 9.0.1430
- Update to 9.0.1440

### Vlc

- Update to 3.0.18
- Rebuild after various library updates

### Vobcopy

- Update to 1.2.1

### Wavpack

- Update to 5.6.0

### Weechat

- Update to 3.8

### Wqy-zenhei

- Update to 0.9.46

### Wxwidgets-3

- Drop 32 bit support
- Fix 64 bit metadata information

### X11/libX11

- Libtoolize needs PATH

### X11/libXext

- Libtoolize needs PATH

### X264

- Update to latest commit

### Xapian

- Update to 1.4.22 and drop 32 bit

### Xbitmaps

- Update to 1.1.3

### Xcb-util

- Update to 0.4.1

### Xcursogen

- Update to 1.0.8

### Xcursor-themes

- Update to 1.0.7
- Fix metadata

### Xdriinfo

- Update to 1.0.7

### Xfd

- Update to 1.1.4

### Xgamma

- Update to 1.0.7

### Xhost

- Update to 1.0.9

### Xinit

- Update to 1.4.2

### Xkbcomp

- Update to 1.4.6

### Xkeyboard-config

- Update to 2.38

### Xmlsec

- Update to 1.2.37

### Xmlto

- Try harder to use GNU variant of tools

### Xorg-video

- Update list of nvidia drivers

### Xorriso

- Update to 1.5.5

### Xprop

- Update to 1.2.6

### Xrandr

- Update to 1.5.2

### Xset

- Update to 1.2.5

### Xstdcmap

- Update to 1.0.5

### Xterm

- Update to 377
- Update to 378
- Update to 379

### Xvidtune

- Update to 1.0.4

### Xvinfo

- Update to 1.1.5

### Xwininfo

- Update to 1.1.6

### Xz

- Update to 5.2.9
- Update to 5.4.0
- Update to 5.4.1
- Update to 5.4.2

### Yara

- Update to 4.3.0

### Youtube-dl

- Rebuild for python 3.9

### Zenlib

- Fix typo

### Zstd

- Update to 1.5.4
- Update to 1.5.5

<!-- generated by git-cliff -->
