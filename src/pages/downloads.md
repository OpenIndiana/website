---
title: "Downloads"
layout: ../layouts/Page.astro
---

# Download

## Getting started
- [How to Install OpenIndiana](//docs.openindiana.org/handbook/getting-started/#installing-openindiana)
- [How to Upgrade OpenIndiana](//docs.openindiana.org/handbook/getting-started/#image-package-system-ips)

OpenIndiana works on most x86 PCs ([SPARC has Beta ISO's, support Welcome](//dlc.openindiana.aurora-opencloud.org/SPARC/)).

From 2017.04 onwards, running on 32-bit systems is not supported anymore and the userland is being migrated progressively to 64-bit only. As usual, 32-bit libraries and core applications are still delivered and maintained for the sake of backward compatibility (but only when running a 64-bit kernel).

To check if your hardware is supported, you can refer to the [illumos HCL](//illumos.org/hcl/) and the [OpenIndiana Community HCL](//docs.openindiana.org/community-hcl/components/); 
alternatively, you can boot a Live install media and run the Device Driver Utility (ddu).

For instructions regarding downloading, preparing and installing the images, 
please refer to the [OpenIndiana Handbook](//docs.openindiana.org/handbook/getting-started/).

If you want to contribute to the project, [find out how you can help](/community#getting-involved).

<hr>

## Download the current Hipster snapshot of OpenIndiana.

| Image                                                                                                                                        | Size    | Checksum                                                                                         |
|--------------------------------------------------------------------------------------------------------------------------------------------|---------|--------------------------------------------------------------------------------------------------|
| [OpenIndiana Hipster 2026.10 Live DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-gui-20261030.iso)               | 2.47 GiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-gui-20261030.iso.sha256sum)     |
| [OpenIndiana Hipster 2026.10 Live USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-gui-20261030.usb)               | 3.01 GiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-gui-20261030.usb.sha256sum)     |
| [OpenIndiana Hipster 2026.10 Text Install DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-text-20261030.iso)      | 593.8 MiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-text-20261030.iso.sha256sum)    |
| [OpenIndiana Hipster 2026.10 Text Install USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-text-20261030.usb)      | 752.6 MiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-text-20261030.usb.sha256sum)    |
| [OpenIndiana Hipster 2026.10 Minimal Install DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-minimal-20261030.iso) | 543.3 MiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-minimal-20261030.iso.sha256sum) |
| [OpenIndiana Hipster 2026.10 Minimal Install USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-minimal-20261030.usb) | 692.0 MiB | 	[sha256](//dlc.openindiana.org/isos/hipster/20261030/OI-hipster-minimal-20261030.usb.sha256sum) |
| [OpenIndiana Hipster cloud image, 7 November 2026 (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261107/OI-hipster-cloudimage-20261107.img.zst) | 883.3 MiB | [sha256](//dlc.openindiana.org/isos/hipster/20261107/OI-hipster-cloudimage-20261107.img.zst.sha256sum) |
| [OpenIndiana Hipster Vagrant box for libvirt, 7 November 2026 (64-bit x86)](//dlc.openindiana.org/isos/hipster/20261107/OI-hipster-vagrant-libvirt-20261107.box) | 1357.6 MiB | [sha256](//dlc.openindiana.org/isos/hipster/20261107/OI-hipster-vagrant-libvirt-20261107.box.sha256sum) |

The Live, Text and Minimal images are from 30 October 2026. The supplemental cloud image and libvirt Vagrant box were rebuilt on 7 November 2026 using pinned Hipster packages.

[Cloud and Vagrant instructions and validation details](https://dlc.openindiana.org/isos/hipster/20261107/README.txt) · [Package and build manifest](https://dlc.openindiana.org/isos/hipster/20261107/build-info.json) · [Vagrant catalog](https://dlc.openindiana.org/isos/hipster/20261107/vagrant.json)

Please note that these links might be slower, and it is recommended to visit a list with [mirror sites 
in your region](//dlc.openindiana.org/). For more mirrors, our documentation has a list of 
[alternate download sites](//docs.openindiana.org/handbook/openindiana-download-mirrors/).

These installations can be updated regularly using the Hipster repository, and receive security fixes. 
Starting with the 2017.04 release, the installation ISO and USB images are signed with
OpenIndiana Release Engineering **GPG key** id **DBE31887**.
