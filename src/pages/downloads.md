---
title: "Downloads"
layout: ../layouts/Page.astro
---

# Download

## Getting started
- [How to Install OpenIndiana](//docs.openindiana.org/handbook/getting-started/#installing-openindiana)
- [How to Upgrade OpenIndiana](//docs.openindiana.org/handbook/getting-started/#image-package-system-ips)

OpenIndiana works on most x86 PCs ([SPARC has Beta ISO's, support Welcome](//dlc.openindiana.aurora-opencloud.org/SPARC/)).

From 2017.04 onwards running on 32-bit systems is not supported anymore and the userland is being migrated progressively to 64-bit only. As usual 32-bit libraries and core applications are still delivered and maintained for the sake of backward compatibility (but only when running a 64-bit kernel).

To check if your hardware is supported, you can refer to the [illumos HCL](//illumos.org/hcl/) and the [OpenIndiana Community HCL](//docs.openindiana.org/community-hcl/components/); 
alternatively, you can boot a Live install media and run the Device Driver Utility (ddu).

For instructions regarding downloading, preparing and installing the images, 
please refer to the [OpenIndiana Handbook](//docs.openindiana.org/handbook/getting-started/).

If want to contribute to the project, [find out how you can help](/community#getting-involved).

<hr>

## Download the current Hipster snapshot of OpenIndiana.

| ISO | Size | Checksum| signature |
|-----|------|---------|-----------|
|[OpenIndiana Hipster 2023.04 Live DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.iso)|	1.80G|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.iso.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.iso.sig)|
|[OpenIndiana Hipster 2023.04 Live USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.usb)|	2.30G|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.usb.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-gui-20230421.usb.sig)|
|[OpenIndiana Hipster 2023.04 Text Install DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.iso)|	951M|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.iso.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.iso.sig)|
|[OpenIndiana Hipster 2023.04 Text Install USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.usb)|	1,20G|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.usb.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-text-20230421.usb.sig)|
|[OpenIndiana Hipster 2023.04 Minimal Install DVD (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.iso)|	391M|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.iso.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.iso.sig)|
|[OpenIndiana Hipster 2023.04 Minimal Install USB (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.usb)|	509M|	[sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.usb.sha256sum)|	[sig](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-minimal-20230421.usb.sig)|
|[OpenIndiana Hipster 2023.04 CloudImage (64-bit x86)](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-cloudimage.img.gz)| 737M | [sha256](//dlc.openindiana.org/isos/hipster/20230421/OI-hipster-cloudimage.img.gz.sha265sum) | no sig |

[Release Notes](/announcements/openindiana-hipster-2023-04-announcement/)

**Note: Due to technical problems there are no signatures at the moment.**

Please note that these links might be slower and it is recommended to visit a list with [mirror sites 
in your region](//dlc.openindiana.org/). For more mirrors our documentation has a list of 
[alternate download sites](//docs.openindiana.org/handbook/openindiana-download-mirrors/).

These installations can be updated regularly using the Hipster repository, and receive security fixes. 
Starting with 2017.04 release, every image is signed with 
OpenIndiana Release Engineering **GPG key** id **DBE31887**.