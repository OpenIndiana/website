---
title: "OpenIndiana Hipster 2022.10 is here"
description: "OpenIndiana Hipster 2022.10 is here"
pubDate: "2022-12-04"
---

As you may already have noticed we have released new ISO and USB images for OpenIndiana Hipster some days ago. 
As usual we have received many updates via illumos-gate, eg. the latest Intel and AMD CPU microcode updates, 
the latest time zone changes and lots of enhancements for BHyVe and the internal SMB server.

We have merged more than 2500 PR’s with fixes, updates and new packages since our last release roughly one year ago. Some notable highlights are:

- Initial support to mount install media via NFS has been added. A fix to use NFSv3 instead NFSv4 is underway.
- We have updated the NVIDIA drivers to the latest production branch version and updated older versions.
- LibreOffice has been updated to 7.2.7 and is now a 64 bit application.
- Firefox and Thunderbird have been updated to the latest ESR releases.
- Mate desktop has been updated to the latest 1.26 version.
- We have removed our old Perl versions and replaced them with 5.34 and 5.36 which are 64 bit only. Version 5.36 is now our default.
- Our Python versions are undergoing a similar process which is not yet finished. We began to remove versions 2.7 and 3.5 and are updating (or removing if an update is not possible or the package is superfluous). IPS has been updated already to use Python 3.9 which increased its speed slitghtly.
- We have updated gcc-10 to its latest version and added gcc-11. We also added clang-13 and removed older versions.

More complete release notes will be published later.
