---
title: "Release 2024.04"
description: "Our first regular release this year is out, this is mainly a update snapshot but it does add new hardware support."
pubDate: "2024-04-28"
---

We are pleased to announce the Release snapshot 2024.04 and accompanying images. Please be aware that we are a
rolling release distribution. All updates are already released and available to everybody who updates their system
regularly. This last half year focused mainly on updates to existing software but a couple of interesting additions
have made their way into the distribution. In Total there were roughly 1230 package updates additionally 900 python
package updates and 200 perl package updates.

To Download the Release go to the [Downloads](/downloads) page.

## Notable image changes
There are two notable changes to the images. First, we do not provide signatures for our images anymore as we cannot
update the public key on the keyservers and are generally not happy with the Usability of the signatures. Secondly, the
cloudimage is now compressed with zstd.

## Package Highlights
We have several packages which we know are of greater interest to our users.
- Firefox has been updated to 125
- Thunderbird is available in version 125
- Version 24.2 of LibreOffice is available
- MATE has been updated to 1.28 and several improvements from other systems have been added to base libraries to improve reliability
- The popular flood protection and brute force defense tool fail2ban is finally available on illumos based systems and packaged as `pkg:/network/fail2ban`
- An interesting experimental application named High-Performance SSH (HPN SSH) from Pittsburgh Supercomputing Center has been packaged with the same patches and options as OpenSSH. For more info on the Algorithms and changes visit https://www.psc.edu/hpn-ssh-home/hpn-ssh-faq/
- All packages still depending on libjpeg6 have been updated to libjpeg8-turbo. Which is the same as all popular Linux distributions. libjpeg8-turbo is also now the default jpeg for the distribution.
- nodejs is available in the freshly released version 22
- clang-18 is the default clang
- golang 1.22 is available and the new default
- Many packages are now compiled with GCC13. This process started a while ago but has now reached most packages.
- Postgres is available in version 16 including all packaged extensions
- Pulseaudio has been updated to version 17
- And as a niche newcomer alpine email is available in version 2.26

## Call for Maintainers/Contributors/Developers
If this project brings some value for you, we would love it if you could contribute some value to the project.
People who do not have a lot of time generally adopt one or two packages and update those. But we also have
space for people who want to work with many packages or a whole Desktop environment.

There are currently open spaces for people to manage the Wifi stack and port graphics drivers to our libdrm based framework.
If that work interests you connect with us on the Mailing lists.

We thank all contributors and regulars for their work and are looking forward to a fun 2024.