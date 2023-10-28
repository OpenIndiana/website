---
title: "Release 2023.10"
description: "The closing of this year brings with it our newest Release. We are happy to announce OpenIndiana 2023.10"
pubDate: "2023-10-28"
---

And again time has passed and things have happened. This release brings a lot of improvements and smaller or bigger changes.

To Download the Release checkout the links under [Downloads](/downloads)

## Highlights
- Openssl has been updated to the newest version of 3.1 which is now the default compiled against. We aim for the maximum compatibility since the newest API's might not be supported right away.
- Python packages are now imported into the package manager by script and usually very up to date. Generally if you need to install a python based app, then the package manager offers the latest versions.
  If you need specific versions try to use the C bindings from the openindiana.org repos and only install pure python software
  via pip and virtualenvs. There are plans to make this happen for ruby and perl as well.
- JDK support has been improved and the latest version now compiles regularly without problems. Thanks goes to Tribblix and others in the illumos community keeping the ball going and the packaging simple.
- Nvidia drivers are updated to the latest stable version. Any update blockages have been fixed.
- We finally managed to find and fix the underlying problem with Virtualbox. It turns out that C++ Exception handling gets used in interesting new ways. Only Gcc12 was able to compile these instructions correctly.
- Firefox 119 is available. We know how much all of the community love to Browse the web. As an alternative, the fork [Librewolf](https://librewolf.net/) is available for testing.

## Notable Software packages
- OpenSearch the Community based fork of Elasticsearch without the pesky Enterprise Licensing issues is available as `pkg://openindiana.org/database/opensearch`
- Inkscape Has been updated to 1.2.1
- Golang 1.21 is available for people wanting to run more Self Hosting focused applications
- Gcc 10, 12, 13 are available with 13 becoming the default in the next release
- Samba has been updated and offers a great Windows File Sharing solution
- Clang17 is available for people who need it.

## ARM status
Some people have heard about the ARM project within illumos and were wondering if there would be an ARM release. So far ARM has a base distro based on OmniOSCE and it will probably
only have that one distribution as a dedicated Channel. Linux Distributions are larger projects so it makes sense for them to have many different ARM distributions. illumos is smaller
and thus it does not make sense to have multiple channels competing for users. There will however be sharing of code updates. We hope somebody wants to look at libdrm as an example.

## Call for Maintainers
We would like to mention here that we are looking for maintainers. If you always wanted to participate in an OpenSource project we are always looking for people. There are a few dedicated maintainers
and we would love to see more people join in. There are many things to do in a distribution project and never enough hands. With the size of the project you can participate in places
you cannot in other projects.

We thank all contributors and regulars for their work and are looking forward to a fun 2024.

