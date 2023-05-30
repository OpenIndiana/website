---
title: "Security Release 2023.05"
description: "Sometimes you release late and sometimes in quick succession. This time unfortunately because of a security issue. UPGRADE NOW!!!"
pubDate: "2023-05-04"
---

# Security Release 2023.05
We were made aware of a severe security Issue in illumos-gate, and as part of the fix for that Issue we are making a new release so people installing OpenIndiana without directly updating it
also get it. The Update to address this issue has been merged into illumos-gate already and is avalilable to download since a couple days as of this Announcement. Please upgrade your machines
NOW!!!

## Downloads
Here the new download links.
- x86 
  - Minimal [ISO](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-minimal-20230502.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-minimal-20230502.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-minimal-20230502.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-minimal-20230502.usb.sha256sum)
  - Server  [ISO](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-text-20230502.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-text-20230502.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-text-20230502.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-text-20230502.usb.sha256sum)
  - Desktop [ISO](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-gui-20230502.iso) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-gui-20230502.iso.sha256sum) / [USB](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-gui-20230502.usb) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-gui-20230502.usb.sha256sum)
  - Cloud Image [IMG](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-cloudimage.img.gz) [Sha256](https://dlc.openindiana.org/isos/hipster/20230502/OI-hipster-cloudimage.img.gz.sha256sum)
### Usage notes on the Downloads
- Please note the the USB image can **only** boot from an USB attached disk not from a HDD. Please use the ISO for Virtualmachine Installation. 
- The Cloud Image contains a metadata agent that allows limited Autoconfiguration by cloud-init configuration data. Only simple networking and SSH-keys are properly tested. Do other configurations after boot with your usual prefered method.

