---
title: "Snapshot 2026.04 Available"
description: "Regular snapshots have been updated. As always visit the Downloads page to get them or simply update. For Notable changes..."
pubDate: "2026-05-05"
---

Regular snapshots have been updated. As always visit the [Downloads](/downloads) page to get them or simply update.

## Notable Changes
In the last half year the following notable Changes have been made:
  - OpenSSH 10.3p1 and CVE patches for openssl-1.1 (CVE-2026-28387/28388/28389/28390, imported from OmniOS).
  - CVE fixes for libsoup3 (CVE-2025-12105, CVE-2025-11021) and jq (CVE-2025-9403).
  - Firefox 150 and Thunderbird 150.
  - LibreOffice 26.2 series.
  - Rust 1.95 and the default Clang flipped to version 21.
  - Go 1.26 added as the new default; golang-122, 123 and 124 obsoleted.
  - Python 3.14.4 and 3.13.13 alongside the existing 3.12 and 3.9 lines.
  - Qemu 11.0 and VirtualBox 7.2.8 and the latest bHyve from upstream illumos with new SCSI backend features.
  - 7zip 26.x.
  - Several new packages this cycle: rofi, muon, R 4.5.2, WordNet, wsdd, libxcvt, solvespace 3.2, gradle 9.4.0 and the lark Python project.
  - New Xorg driver `xf86-video-illumosfb` for UEFI framebuffer on illumos.
  - New install-time drivers picked up from illumos: the `igc` 2.5G NIC driver and a fresh batch of virtio and storage drivers updates, so more hardware comes up out of the box.
  - SPARC support continues to grow: vlc, sbcl, swi-prolog, netbeans and qt 6.10.2 are now buildable on SPARC; xorg-server SPARC manifests fixed.
  - Mate desktop 1.28 refresh across panel, terminal, menus, notification daemon and libmateweather.
  - timescaledb keeps pace with PostgreSQL 16.
  - A huge number of automated Python and Perl package updates (omitted from the changelog below to keep it readable).

## Full Changelog

[0df7ea7](https://github.com/OpenIndiana/oi-userland/commit/0df7ea760fd12599d94b2050425b1d2eb64e1f5c)...[5923c50](https://github.com/OpenIndiana/oi-userland/commit/5923c505f5)



### 7zip

- add 25.01 ([eb70486](https://github.com/OpenIndiana/oi-userland/commit/eb704862dc709e0a7b647fdc9c757df03cbaa8f2))
- update to 26.00 ([7b5b142](https://github.com/OpenIndiana/oi-userland/commit/7b5b142050db13f3e73c2b6ee1524c1424b4b500))
- update to 26.01 ([d496267](https://github.com/OpenIndiana/oi-userland/commit/d496267fcb24128108ae5cc20595c0daaeaada75))

### Other

- add WordNet package ([8b9debe](https://github.com/OpenIndiana/oi-userland/commit/8b9debec1eb56cd4a0e060df718aede6909e469f))
- add rofi package ([44d8f60](https://github.com/OpenIndiana/oi-userland/commit/44d8f6081b1773abdd8343a9e12c8fbd8aa42d10))
- Don't disable all optional features for emacs-nox ([ce0ca9f](https://github.com/OpenIndiana/oi-userland/commit/ce0ca9f34fc2b9423a48653b6181c6a1fa2e8381))
- disable luanti ([6c98201](https://github.com/OpenIndiana/oi-userland/commit/6c98201f35f4a7ad1eaf8678022635858fdfe34f))
- Obsolete SUNWlibevent ([7c0fc69](https://github.com/OpenIndiana/oi-userland/commit/7c0fc69184ce95f607c8a88f34b6c932f575e36c))
- opensmalltalk stack-spur: update to VMMaker.oscog-eem.3682 ([efdb805](https://github.com/OpenIndiana/oi-userland/commit/efdb80500bd12e208be97050d9c0e6fdab2bb661))
- opensmalltalk cog-spur: update to VMMaker.oscog-eem.3681 ([2dd8220](https://github.com/OpenIndiana/oi-userland/commit/2dd8220a7238068c84946e1db6993a1bea61bef2))
- add muon 0.5.0 ([57dcdf5](https://github.com/OpenIndiana/oi-userland/commit/57dcdf50b8cf5b7ad0249485ce492a31fef66571))
- Switch default clang version to 21 ([f1dcf04](https://github.com/OpenIndiana/oi-userland/commit/f1dcf0491af8903981469c3c7d9d14000dc3a560))
- Obsolete golang-122 ([eff55b8](https://github.com/OpenIndiana/oi-userland/commit/eff55b8f80e9329eed03e989e44429f189ddf844))
- Obsolete golang-123 ([f57c0a0](https://github.com/OpenIndiana/oi-userland/commit/f57c0a0c7cd1b84d525e1bac50e7e76c0dff68f5))
- add R 4.5.2 ([8ab2e88](https://github.com/OpenIndiana/oi-userland/commit/8ab2e882e45b1823fc253798fac7457248a21385))
- opensmalltalk stack-spur: update to VMMaker.oscog-eem.3704 ([8693222](https://github.com/OpenIndiana/oi-userland/commit/86932229bd17c69b961b81268b594e0f483587e2))
- opensmalltalk cog-spur: update to VMMaker.oscog-eem.3705 ([ab108c1](https://github.com/OpenIndiana/oi-userland/commit/ab108c132a6a0519cf775bbc8a7f72ee71cc1a4d))
- advance to 2026 ([d738de9](https://github.com/OpenIndiana/oi-userland/commit/d738de90e02ba3515578bd17c886491b94bbfb55))
- opensmalltalk stack-spur: add PseudoTTYPlugin from VMMaker.oscog-eem.3719 ([7428ced](https://github.com/OpenIndiana/oi-userland/commit/7428cedcfc2b5ad939fb2f764d7baf57c2fde83b))
- opensmalltalk cog-spur: add PseudoTTYPlugin from VMMaker.oscog-eem.3719 ([7536a7c](https://github.com/OpenIndiana/oi-userland/commit/7536a7cec2de4047e14b6cbf84f076319fdd9044))
- opensmalltalk stack-spur: update to VMMaker.oscog-eem.3732 ([9fb0e6c](https://github.com/OpenIndiana/oi-userland/commit/9fb0e6c6212f4978afa7ca4d7a84ff7ab6eb1c8a))
- opensmalltalk cog-spur: update to VMMaker.oscog-eem.3732 ([097774a](https://github.com/OpenIndiana/oi-userland/commit/097774a42fc0a388e529bb1b99fd5081261adefb))
- disable thunderbird ([f672d6e](https://github.com/OpenIndiana/oi-userland/commit/f672d6ea7cd8b2b7ca8a33cd3a5249c7f46b12f5))
- python312-3.12.13 ([dfb6d4b](https://github.com/OpenIndiana/oi-userland/commit/dfb6d4b2d1c46a049deeee7e4ed528d6cca4b498))
- disable openindiana/nvidia ([3452514](https://github.com/OpenIndiana/oi-userland/commit/3452514dd79567f273b8b3e82cd0234c561ae9ab))
- reenable openindiana/nvidia ([37c1601](https://github.com/OpenIndiana/oi-userland/commit/37c16011687f12d09dfe2dc95192f47f31eb7c62))
- php84 -update to version 8.4.19 ([2db7c6f](https://github.com/OpenIndiana/oi-userland/commit/2db7c6f474948e396c0d81b2e9863d237236a1f3))
- disable zarith ([1c2af58](https://github.com/OpenIndiana/oi-userland/commit/1c2af589fe46bae9cdcd3c5c19940592986c4244))
- Add Sun-Solaris-Privilege Perl distribution ([4811af4](https://github.com/OpenIndiana/oi-userland/commit/4811af47e54c25a6c15ea7fb4ad18e8cd230d24d))
- re-enable thunderbird ([ab0b0e1](https://github.com/OpenIndiana/oi-userland/commit/ab0b0e183f497e1002838995d780f4c978668f72))
- disable failing thunderbird ([9c9e5db](https://github.com/OpenIndiana/oi-userland/commit/9c9e5db05dcf0f142c5f3ce5d4a56f1c7dc7d621))
- libmagic (file): update to 5.47 ([1b052d0](https://github.com/OpenIndiana/oi-userland/commit/1b052d0ac73abe7703ebf50fc3baed83de5a80fd))
- add libxcvt ([c7bbf03](https://github.com/OpenIndiana/oi-userland/commit/c7bbf037ce210db2ccd1dab6e284077f172289d2))
- Revert "libxml2 - update to version 2.15.2" ([16c8a13](https://github.com/OpenIndiana/oi-userland/commit/16c8a13f2fb58639d0234dc36f3fcbbc8e20fe45))
- re-enable luanti ([7def62d](https://github.com/OpenIndiana/oi-userland/commit/7def62da255d05cd4d57efb9485bf85b8ec07cdc))
- opensmalltalk cog-spur: add optional dependencies ([a52507d](https://github.com/OpenIndiana/oi-userland/commit/a52507d478f8fe50212fcc17f34e81a399c15030))
- opensmalltalk stack-spur: add optional dependencies ([c76951d](https://github.com/OpenIndiana/oi-userland/commit/c76951d8e21b4427309cdfa12b5547b12c9a2083))
- opensmalltalk cog-spur: change download URL to opensmalltalk ([fe2ac28](https://github.com/OpenIndiana/oi-userland/commit/fe2ac28586c84b984362855bf1bb9aecdf19bb6b))
- opensmalltalk stack-spur: change download URL to opensmalltalk ([74d2108](https://github.com/OpenIndiana/oi-userland/commit/74d210882a79fcdb6b9e4ef674a418d2f2320f24))
- Obsolete golang-124 ([3c8d025](https://github.com/OpenIndiana/oi-userland/commit/3c8d025044cc1bee409599b537c0466d6aafff0c))
- Add xf86-video-illumosfb: Xorg driver for UEFI framebuffer on illumos ([5e28c60](https://github.com/OpenIndiana/oi-userland/commit/5e28c60e3968e37df30f4215e8784e8b51220b50))
- disable x11/xf86-video-illumosfb ([1d0e338](https://github.com/OpenIndiana/oi-userland/commit/1d0e3382448cefe70b9ee1f6e6cfa0ec007c0837))
- re-enable thunderbird ([1d929e7](https://github.com/OpenIndiana/oi-userland/commit/1d929e7535b8778ffdf5892c11de0cb502221813))
- libexif; update to 0.6.26 ([a93d157](https://github.com/OpenIndiana/oi-userland/commit/a93d157da332346eaf4f7f660ad0eeefcaea1891))
- prepare 2026.04 release ([5923c50](https://github.com/OpenIndiana/oi-userland/commit/5923c505f515ae2443565fc1994a9d74ab82476f))

### QT

- update 6.9.3 ([96dc0d7](https://github.com/OpenIndiana/oi-userland/commit/96dc0d7ffd204d801a73fe25e6e5b6f322689507))

### Rebuilds

- rebuild openexr after openjph update ([ffb54e9](https://github.com/OpenIndiana/oi-userland/commit/ffb54e97768865a76f87e20a0b25caffb5173ac3))
- rebuild keepassxc after botan update ([5cf63d0](https://github.com/OpenIndiana/oi-userland/commit/5cf63d08318493ec8ebf07c51094854aa033c21d))
- rebuild gmime3 after gpgme update ([2ffb133](https://github.com/OpenIndiana/oi-userland/commit/2ffb13308391a20ec52b840f78ef17033045ffe2))
- rebuild samba after gpgme update ([0c3dd6e](https://github.com/OpenIndiana/oi-userland/commit/0c3dd6ee98d327fa77f2a80447ca0240c7b2bb3a))
- rebuild wget2 after gpgme update; add patch from omnios ([64af86c](https://github.com/OpenIndiana/oi-userland/commit/64af86cbb2fad850da17211f35b5641306d6881b))
- rebuild claws-mail after gpgme update ([0dadb9d](https://github.com/OpenIndiana/oi-userland/commit/0dadb9d5ad8b8f7d8323e00d8e3aea385ee1ad58))
- rebuild geany-plugins after gpgme update ([33a0b2b](https://github.com/OpenIndiana/oi-userland/commit/33a0b2bc934dbd99e7d162fcbbc64b532e90dcc3))
- rebuild seahorse after gpgme update; add a patch from opensuse ([1acceca](https://github.com/OpenIndiana/oi-userland/commit/1acceca512b6345f90afe3967ac9b786428918df))
- rebuild libwebp after giflib update ([1f90de3](https://github.com/OpenIndiana/oi-userland/commit/1f90de308e6458aa4fde789e6c225e6c025eb54b))
- rebuild imlib2 after giflib update ([0206500](https://github.com/OpenIndiana/oi-userland/commit/02065002f1e9c4214ec29eca742927f8104df6a5))
- rebuild libgdiplus after giflib update ([2407d0c](https://github.com/OpenIndiana/oi-userland/commit/2407d0cca912d766c15514bb4626607d93c85479))
- rebuild tracker after giflib update ([e8f08ff](https://github.com/OpenIndiana/oi-userland/commit/e8f08ff16a1f59e6b921f5018b9c342e9a6d225c))
- rebuild wmaker after giflib upate ([7068f87](https://github.com/OpenIndiana/oi-userland/commit/7068f87a6cfd3a91201ec3b23eab5c6d56b67724))
- rebuild openjdk11 after giflib update ([daec85c](https://github.com/OpenIndiana/oi-userland/commit/daec85ced595443b13875d56b96f6a89a0fd0f55))
- rebuild openscenegraph after giflib update ([099835e](https://github.com/OpenIndiana/oi-userland/commit/099835e95ca3eb6e896393990b77251f2b7cf2c1))
- rebuild emacs after giflib update ([fbbc212](https://github.com/OpenIndiana/oi-userland/commit/fbbc212cceaab3bb194880591c311e9f1a361bf0))
- rebuild openjdk-17 after giflib update ([ad5d906](https://github.com/OpenIndiana/oi-userland/commit/ad5d906c8105a10560b6c6870c68e2739ca752cd))
- rebuild openjdk-21 after giflib update ([dad5b84](https://github.com/OpenIndiana/oi-userland/commit/dad5b84c9ebb40f0d065ed4e72383bb6f038495e))
- rebuild openjdk23 after giflib update ([852f738](https://github.com/OpenIndiana/oi-userland/commit/852f7383ea9de0ceed1ae165e1cd4541c3f31b7d))
- rebuild openjdk-24 after giflib update ([8c448b2](https://github.com/OpenIndiana/oi-userland/commit/8c448b21cd3dc64f399367b6e624eff99befee4d))
- rebuild openjdk-25 after giflib update ([129ec0b](https://github.com/OpenIndiana/oi-userland/commit/129ec0b43150d3856e821e0db71b3decf93210d9))
- rebuild openexr after openjph update ([6852c41](https://github.com/OpenIndiana/oi-userland/commit/6852c4149edb9e1525ecb5ebdb9aee978d5f21c6))
- rebuild keepassxc after botan update ([e5004da](https://github.com/OpenIndiana/oi-userland/commit/e5004da62cc70b2a8322aeb76a966e13a41bfde7))
- rebuild xorg-server after xtrans update ([8d531fa](https://github.com/OpenIndiana/oi-userland/commit/8d531fac9fe9a2da4329e4b35bed4df2e4552e3f))
- rebuild yelp after groff-core obsoletion ([b37d000](https://github.com/OpenIndiana/oi-userland/commit/b37d000f8e020362d539fec12ac04ef29cde7a09))
- rebuild gst-plugins-good after libvpx update ([1e05722](https://github.com/OpenIndiana/oi-userland/commit/1e0572299032ce52f74c37d3cdbca2122b763ac0))
- rebuild ffmpeg-7 after libvpx update ([ece24a5](https://github.com/OpenIndiana/oi-userland/commit/ece24a556aae100c5f239f971725a69de57b9592))
- rebuild ffmpeg after libvpx update ([f4dff21](https://github.com/OpenIndiana/oi-userland/commit/f4dff21e7533e7eaa47dee3e0175d611fe54fd8e))
- rebuild ffmpeg-6 after libvpx update ([246bb88](https://github.com/OpenIndiana/oi-userland/commit/246bb88d7750e7fdad335b2c12cab7897f0fd084))
- rebuild vlc after libvpx update ([7faa1b9](https://github.com/OpenIndiana/oi-userland/commit/7faa1b9bd3fae0dd05584d2e288d09ce2a0896c2))
- rebuild opal after libvpx update ([7309278](https://github.com/OpenIndiana/oi-userland/commit/7309278e90bf412b2b2014f7cab1051184079db5))
- rebuild toxcore after libvpx update ([ca2c8bc](https://github.com/OpenIndiana/oi-userland/commit/ca2c8bcd40569d30659c4f07e76d36c95b652b77))

### SDL3

- update to 3.2.26 ([20f8a3f](https://github.com/OpenIndiana/oi-userland/commit/20f8a3fb23279d9991e2eb7d979c43043a1bac02))
- update to 3.4.0 ([f294e8e](https://github.com/OpenIndiana/oi-userland/commit/f294e8ee68d8327504ef07b04634816edaafc3c0))

### Zarith

- update to 1.14 ([6d13b9a](https://github.com/OpenIndiana/oi-userland/commit/6d13b9a2a557e273217d2124e0a69cd4a9f76303))

### a2ps

- update to 4.15.8 ([78b6a9e](https://github.com/OpenIndiana/oi-userland/commit/78b6a9e7174e814fa784bf8032f82666a1b4aae9))

### abseil-cpp

- update to 20250127.2 ([a4d412e](https://github.com/OpenIndiana/oi-userland/commit/a4d412ed003a47b4cc1a90122488cd3c8c9ed645))

### adwaita-icon-theme

- update to 49.0 ([34a23a7](https://github.com/OpenIndiana/oi-userland/commit/34a23a7ea1442a4f4d1838ecc834052ee33f2537))
- update to 50.0 ([b7fcf34](https://github.com/OpenIndiana/oi-userland/commit/b7fcf34632453960e356bcd56fb9df9fe4359e47))

### ant

- update to 1.10.16 ([a94d2ff](https://github.com/OpenIndiana/oi-userland/commit/a94d2ffcb1a85e753794871ad078ca206cdbb1de))
- update to 1.10.17 ([a8e950c](https://github.com/OpenIndiana/oi-userland/commit/a8e950c943b53e841b3478ea0394518e6092d3e5))

### apache-2.4

- update to 2.4.66 ([ef785d2](https://github.com/OpenIndiana/oi-userland/commit/ef785d2f5729f3939bba524c4d15270a40b6fd72))

### appstream

- update to 1.1.2 ([0de2d90](https://github.com/OpenIndiana/oi-userland/commit/0de2d90814181bf264f7d835bf36412456b40d4e))

### aspell

- update to 0.60.8.2 ([2bd47b9](https://github.com/OpenIndiana/oi-userland/commit/2bd47b929ea6e0078264f2834864e22aa3df9515))

### asterisk

- update to version 22.6.0 ([05b35b9](https://github.com/OpenIndiana/oi-userland/commit/05b35b96038b84bee242f451fca9fd9fcdb58e8c))
- add SPARC support ([c67ae6c](https://github.com/OpenIndiana/oi-userland/commit/c67ae6cc280042e9ac517bec10a8feb2840d689e))
- update to version 22.7.0 ([ff09bc0](https://github.com/OpenIndiana/oi-userland/commit/ff09bc0c6d4e3810d2069edcc5f6a73fbbb162ce))
- update to version 22.8.0 ([11e1bc7](https://github.com/OpenIndiana/oi-userland/commit/11e1bc73b1d6805a5fbd0677620168353ee93023))
- update to version 22.8.2 ([cc9b3dd](https://github.com/OpenIndiana/oi-userland/commit/cc9b3dde2de9f6d51f10a10d3a1d14110c0b14f8))

### at-spi2-core

- update to 2.58.3 ([1703e82](https://github.com/OpenIndiana/oi-userland/commit/1703e82b8a00c45b24e592fff787b0175b74fb95))
- update to 2.60.0; drop 32 bit ([d2289dc](https://github.com/OpenIndiana/oi-userland/commit/d2289dc3e833f4b2ec3239eb30e3eccbbac51a20))
- update to 2.60.1 ([f5745ef](https://github.com/OpenIndiana/oi-userland/commit/f5745efeaecdded8d74b8d500a8a15e38e90de9a))
- update to 2.60.2 ([972b689](https://github.com/OpenIndiana/oi-userland/commit/972b68983a1f5e6580e5b104b479fa4cf4bdfd2f))
- update to 2.60.3 ([2ec509e](https://github.com/OpenIndiana/oi-userland/commit/2ec509e8ae7e6e33948f70e251b87e06e3b27c17))

### atril

- rebuild after poppler upgrade ([870c3c2](https://github.com/OpenIndiana/oi-userland/commit/870c3c2e8888900cdb7568888c998687de8fbdc0))
- update to 1.28.3 ([a930f2f](https://github.com/OpenIndiana/oi-userland/commit/a930f2f1000c1de9a2fda5cd38431c4131429d8f))

### avahi

- remove configure options: --disable-gdbm --enable-dbm ([3b7f053](https://github.com/OpenIndiana/oi-userland/commit/3b7f053d890f21d8a3466a689919cec1a1690e3e))

### awstats

- update to 8.0 ([4a34025](https://github.com/OpenIndiana/oi-userland/commit/4a34025b5391f949a73cb0b6b4304ec918c76f4f))

### babl

- update to 0.1.118 ([f7096d7](https://github.com/OpenIndiana/oi-userland/commit/f7096d776b6ae47adc59958174d4bba4e5365061))
- update to 0.1.120 ([8930375](https://github.com/OpenIndiana/oi-userland/commit/893037576fa4416009393c39312e716652608a53))
- update to 0.1.122 ([f24cd51](https://github.com/OpenIndiana/oi-userland/commit/f24cd51a1b07f4a138365bed27a8a8e49f191de9))
- update to 0.1.124 ([6163543](https://github.com/OpenIndiana/oi-userland/commit/6163543d05712e9922a29ed82da3072817cf0f18))
- update to 0.1.126 ([8ddc6bd](https://github.com/OpenIndiana/oi-userland/commit/8ddc6bd04615ef248ff4577fe2de334ffab794f4))

### bash

- update to 5.3p9 ([ab156a0](https://github.com/OpenIndiana/oi-userland/commit/ab156a0c33c78caff4c3df8fae5bee7c112d8eb9))

### bind

- update to 9.18.42 ([f44b4c2](https://github.com/OpenIndiana/oi-userland/commit/f44b4c2bb8c22d03c1631cf2cc21c87d9b4978ae))
- update to 9.18.45 ([33159c5](https://github.com/OpenIndiana/oi-userland/commit/33159c5cd62e30aba20deb39857145866d06f522))
- update to 9.18.48 ([22f2b36](https://github.com/OpenIndiana/oi-userland/commit/22f2b36ef07d272b123e13d64919c1f6c3049cfc))
- update to version 9.20.22 ([2adf4d3](https://github.com/OpenIndiana/oi-userland/commit/2adf4d3c13bb20710d15442cd5c54e35fe63b146))

### binutils

- update to 2.45.1 ([101de56](https://github.com/OpenIndiana/oi-userland/commit/101de561a736404aac76913c0e97bd64d6c5379a))
- upadte to 2.46.0 ([6ebfcd7](https://github.com/OpenIndiana/oi-userland/commit/6ebfcd789b90fef091ebc6f2ef351be9aa1f0ea9))
- add missing patches ([959b27f](https://github.com/OpenIndiana/oi-userland/commit/959b27ffc893968f9bb7597e9324107d1c5e1bfa))

### bitmap

- update to 1.1.2 ([87b016e](https://github.com/OpenIndiana/oi-userland/commit/87b016e6148c5d7f1d31cc2bc7a6d4294cb01950))

### bluefish

- update to 2.2.18 ([11c8c2b](https://github.com/OpenIndiana/oi-userland/commit/11c8c2b71898941d980635e7762e7262ef9992e7))
- update to 2.2.19 ([4ad2710](https://github.com/OpenIndiana/oi-userland/commit/4ad2710a75c9e4e6d6a497b4c6e4d1eff3bd9aaf))
- update to 2.4.0 ([3df896b](https://github.com/OpenIndiana/oi-userland/commit/3df896b5b6b3f8d277cc7cec93a306bba0fc8b86))
- update to 2.4.1 ([82b44ed](https://github.com/OpenIndiana/oi-userland/commit/82b44edbf294f3d5f23f7824ed7c8acdf39fe94a))

### botan

- update to 3.10.0 ([9bf8afb](https://github.com/OpenIndiana/oi-userland/commit/9bf8afb57a6e58fcc23b5b26276043de132c628e))
- update to 3.11.0 ([0ab0571](https://github.com/OpenIndiana/oi-userland/commit/0ab0571a846cfe975e01f5028897c26a8c88153b))
- update to 3.11.1 ([b13e5ff](https://github.com/OpenIndiana/oi-userland/commit/b13e5ff82fdcc28b3400e056255df8d759c8851a))

### brotli

- update to 1.2.0 ([4550a59](https://github.com/OpenIndiana/oi-userland/commit/4550a59e0885e3170747ab3f33ce2197e71d5402))

### build-essential

- do not depend on readline ([f19377d](https://github.com/OpenIndiana/oi-userland/commit/f19377d0cfb7c0657becc011041296088afa1730))

### c_icap

- rebuild after lmdb upgrade ([c81234a](https://github.com/OpenIndiana/oi-userland/commit/c81234ae3b7c02d31cf8e31a8cf6fed2a6de4e15))

### ca-certificates

- update to 2025.11.04 ([5c357f0](https://github.com/OpenIndiana/oi-userland/commit/5c357f0e30c4836f465cb2b7ce60eda4eabde20c))
- update to 20251202 ([1bf2c06](https://github.com/OpenIndiana/oi-userland/commit/1bf2c06b1c7b5a9bc454dc15d21be8edc8a1fe91))
- update to 2026.03.19 ([6073665](https://github.com/OpenIndiana/oi-userland/commit/6073665508f02425fa29a45d184265ac5e145cf8))
- update to 20260413 ([d24eedf](https://github.com/OpenIndiana/oi-userland/commit/d24eedf250331e040c7daf806679d93728cd3889))

### calcmysky

- update to 0.4.0 ([49bde8c](https://github.com/OpenIndiana/oi-userland/commit/49bde8c9761a6774ada802e19f70f22344b61990))

### cargo-vendor.mk

- allow Cargo.toml in subdir ([a9c772a](https://github.com/OpenIndiana/oi-userland/commit/a9c772aeb44ba967fa242e9878cb370049fe81cd))
- make sure fetched crates are readable ([a0b681c](https://github.com/OpenIndiana/oi-userland/commit/a0b681c8a345e59bf5a9dd090ae3df2c065c6113))

### cargo.mk

- remove doctests timing from test results ([c694cbd](https://github.com/OpenIndiana/oi-userland/commit/c694cbdd9f8a50c63b12123f8a5cc8cac609c132))

### ccache

- update to 4.12.3 ([4434f25](https://github.com/OpenIndiana/oi-userland/commit/4434f25e60ee2c0d0048b8cf6b662b07d7640555))
- update to 4.13 ([c1247e8](https://github.com/OpenIndiana/oi-userland/commit/c1247e8dc7046fa514c4e56f58d199b220d6911a))
- update to 4.13.1 ([0fb5eb4](https://github.com/OpenIndiana/oi-userland/commit/0fb5eb41a8bec25db5f5f4f7ee1ba15c416b0f0f))
- update to 4.13.2 ([f930859](https://github.com/OpenIndiana/oi-userland/commit/f9308594acd9056829de02ba5cb22141251df6de))
- update to 4.13.3 ([30e9eb8](https://github.com/OpenIndiana/oi-userland/commit/30e9eb8230bafd254ae505e37aa0b1604ee6dd2a))
- update to 4.13.4 ([9cccb31](https://github.com/OpenIndiana/oi-userland/commit/9cccb31fe533e420fdc7d1637efd0a736889054f))
- update to 4.13.5 ([9d9efc7](https://github.com/OpenIndiana/oi-userland/commit/9d9efc796128269b50e0ea849f016062ebbce524))

### clamav

- update to 1.5.1 ([3f26bfe](https://github.com/OpenIndiana/oi-userland/commit/3f26bfe29d5081db4d3f869084d6f9993c0137ca))
- update to version 1.5.2 ([43b0584](https://github.com/OpenIndiana/oi-userland/commit/43b0584ee8c44b5727dac3612656d31fd7ef37ff))

### clang-21

- add 21.1.5 ([f1e50bb](https://github.com/OpenIndiana/oi-userland/commit/f1e50bb646bbf61d016303239ae092f7826bc942))
- update to 21.1.6 ([baa5f0c](https://github.com/OpenIndiana/oi-userland/commit/baa5f0c04362921434fc39c3ec01813c08f67d21))
- update to 21.7 ([3862dee](https://github.com/OpenIndiana/oi-userland/commit/3862deeeec9ff83c3076ad5bacbe4098ae4a949d))
- update to 21.1.8 ([c56c614](https://github.com/OpenIndiana/oi-userland/commit/c56c61415eef03ea622240473caac267a79fd54c))

### claws-mail

- rebuild after poppler upgrade ([c03958b](https://github.com/OpenIndiana/oi-userland/commit/c03958b3895a55f1f890aa6be1dfda440c1d26d9))
- update to 4.4.0 ([901c077](https://github.com/OpenIndiana/oi-userland/commit/901c0776c709681095939cfac30c86d54fdab1a5))

### cmake

- update to 4.2.0 ([25bddc1](https://github.com/OpenIndiana/oi-userland/commit/25bddc1af5134e47f522691caa97b2b352d3a3eb))
- update to 4.2.1 ([a1e430b](https://github.com/OpenIndiana/oi-userland/commit/a1e430b306be93639e214112777670497f580da8))
- update to 4.2.2 ([04e3ec0](https://github.com/OpenIndiana/oi-userland/commit/04e3ec0b44f1b05448f4c2b9b785f487928ea462))
- update to 4.2.3 ([5705471](https://github.com/OpenIndiana/oi-userland/commit/570547167b627eeb0d22d35bd62260f624717c3f))
- update to 4.3.0 ([c21bc8e](https://github.com/OpenIndiana/oi-userland/commit/c21bc8e3e0f83be7ee577b3a17d2dc518aa6a677))
- update to 4.3.1 ([547ddb1](https://github.com/OpenIndiana/oi-userland/commit/547ddb12dd1794074f3728e508b7e3c4d06fb07c))
- update to 4.3.2 ([9793617](https://github.com/OpenIndiana/oi-userland/commit/97936172296b163f0245ce8b7aac44b59013fe35))

### cmake3

- update to 3.31.10 ([f81d794](https://github.com/OpenIndiana/oi-userland/commit/f81d7947f99b1dfa15a43a2e29d077ff467acbc9))
- update to 3.31.11 ([d202ba6](https://github.com/OpenIndiana/oi-userland/commit/d202ba6459cd6fa1f5fbd200299278d46e777042))

### cmark

- update to 0.31.2 ([34d9a1e](https://github.com/OpenIndiana/oi-userland/commit/34d9a1ec687b4547f9128227394e9c95b66c11e7))

### coeurl

- update to 0.3.2 ([4816bef](https://github.com/OpenIndiana/oi-userland/commit/4816befc3322eff697465b57c8dc29ae66634ae4))

### coreutils

- update to 9.10 ([be80baa](https://github.com/OpenIndiana/oi-userland/commit/be80baa8560eda7af75a6b931da933c5a836245b))

### cups

- update to 2.4.15 ([ab14d79](https://github.com/OpenIndiana/oi-userland/commit/ab14d79930e7bfd1c5a63e1135812f934f19d329))
- update to 2.4.16 ([10e69dd](https://github.com/OpenIndiana/oi-userland/commit/10e69dddb9779ebe386b0f66035c84341e6562d7))
- update to 2.4.17 ([b0c04c4](https://github.com/OpenIndiana/oi-userland/commit/b0c04c4c2dc6a68cdbbe2944a982a6607dbcc2dc))
- update to 2.4.18 ([1cc8719](https://github.com/OpenIndiana/oi-userland/commit/1cc8719df01e54769656f9895b004dacfa9ceb89))
- update to 2.4.19 ([c25e7bd](https://github.com/OpenIndiana/oi-userland/commit/c25e7bd302fdde3bc704d68c27c9d6b4a6a00bc6))

### cups-filters

- rebuild after poppler upgrade ([dd182bf](https://github.com/OpenIndiana/oi-userland/commit/dd182bf8d4260f80cebe19cb5f6ce05bf039ffaf))

### curl

- update to 8.17.0 ([9db91e5](https://github.com/OpenIndiana/oi-userland/commit/9db91e5f69d3d1f4f2ac77567ac76ade1a6d37ed))
- update to 8.18.0 ([53317ce](https://github.com/OpenIndiana/oi-userland/commit/53317cedb508f086cd9e53ea233da4931b0ef4ec))
- update to 8.19.0 ([a3142f7](https://github.com/OpenIndiana/oi-userland/commit/a3142f7d9d841a54d2f152a213fda0d94d755d31))
- update to 8.20.0 ([d1dc6da](https://github.com/OpenIndiana/oi-userland/commit/d1dc6dabbe1f40744669c28dd681b65216a85e07))

### dash

- update to 0.5.13.1 ([d6fd123](https://github.com/OpenIndiana/oi-userland/commit/d6fd123062e92729050caab3ee74f83786a20ec9))

### dav1d

- update to 1.5.2 ([5b93e40](https://github.com/OpenIndiana/oi-userland/commit/5b93e40150d9030de62d9f52681d513cccab0f50))
- update to 1.5.3 ([5ee41eb](https://github.com/OpenIndiana/oi-userland/commit/5ee41ebbd603155b205539976015f149137130bf))

### developer/mergiraf

- update to 0.16.1 ([cd38b46](https://github.com/OpenIndiana/oi-userland/commit/cd38b461bbb4a35ec14a5179b1579fe19250f501))

### developer/scons

- update to 4.10.1 ([3ef118e](https://github.com/OpenIndiana/oi-userland/commit/3ef118e09533eeec2633fe089ab82c5eb77ead86))

### double-conversion

- update to 3.4.0 ([ec7aae0](https://github.com/OpenIndiana/oi-userland/commit/ec7aae0ea2b243c8e2d125ca435bcb5459d3fc70))

### dovecot

- update to version 2.4.3 ([8a11da3](https://github.com/OpenIndiana/oi-userland/commit/8a11da328859c1b459df10290996599c1a385f69))
- fix permissions in Usr/lib/dovecot ([6353d8a](https://github.com/OpenIndiana/oi-userland/commit/6353d8adfd1cb07c58cde236afc7827f466cd10b))
- fix serveral issues with plugins ([d621a68](https://github.com/OpenIndiana/oi-userland/commit/d621a68c5c204b94968550a579a37e941db7d028))

### dovecot-pigeonhole

- update to version 2.4.3 ([0577828](https://github.com/OpenIndiana/oi-userland/commit/057782855a9594d80e0e38a2f4aaaaaa083e5ec1))

### doxygen

- update to 1.16.0 ([8e9daaa](https://github.com/OpenIndiana/oi-userland/commit/8e9daaab4aa4222d47c0d58a16f25b3c6a68db94))
- update to 1.16.1 ([0505139](https://github.com/OpenIndiana/oi-userland/commit/05051397e2d7626aeb1ac05dfd82aa47eda64e67))

### easy-rsa

- update to 3.2.6 ([69f99cc](https://github.com/OpenIndiana/oi-userland/commit/69f99ccee3298227f3369d362de22e0a8a1dc126))

### editres

- update to 1.1.0 ([9465c61](https://github.com/OpenIndiana/oi-userland/commit/9465c616c356798f60d80180c2ec9e2cf61321ef))
- update to 1.1.1 ([e08b32a](https://github.com/OpenIndiana/oi-userland/commit/e08b32afb9d3da54e2d0060005a03cd3ac433859))

### efl

- rebuild after poppler upgrade ([df453b9](https://github.com/OpenIndiana/oi-userland/commit/df453b975055b7253cef29e435abcf1a47e47b21))
- rebuild after libraw upgrade ([87bcc27](https://github.com/OpenIndiana/oi-userland/commit/87bcc271bc25699e200fa4af9349915a34c7c268))

### elinks

- update to 0.19.0 ([fb0d5bb](https://github.com/OpenIndiana/oi-userland/commit/fb0d5bb2c8786275d1579459e32930fa573d0495))
- update to 0.19.1 ([a4c13a7](https://github.com/OpenIndiana/oi-userland/commit/a4c13a742360556c97192c082623b89988c2b3f6))

### elixir

- update to 1.19.2 ([01be9aa](https://github.com/OpenIndiana/oi-userland/commit/01be9aa66b7598a2404483ce4c90eafe433879ad))
- update to 1.19.3 ([3d9270c](https://github.com/OpenIndiana/oi-userland/commit/3d9270c7cb007c0cb17e8438455aab754ffaf068))
- update to 1.19.4 ([8152961](https://github.com/OpenIndiana/oi-userland/commit/81529618ecc2021fd5e782f7c07640a100255d90))
- update to 1.19.5 ([1f54cef](https://github.com/OpenIndiana/oi-userland/commit/1f54cefe2653afe044ec81f24d0024b4947859ab))

### enchant

- update to 2.8.14 ([cef1e03](https://github.com/OpenIndiana/oi-userland/commit/cef1e03afa1a589ab6bd050ad17a6a62566952e6))
- update to 2.8.15 ([b91473a](https://github.com/OpenIndiana/oi-userland/commit/b91473ada58312100f9147333ea6fa9ab1e103a7))

### eom

- update to 1.28.1 ([16795ff](https://github.com/OpenIndiana/oi-userland/commit/16795ff4284e01860d89a239608006b4bad87392))

### erlang

- don't substitue i386 header files ([7b55cbb](https://github.com/OpenIndiana/oi-userland/commit/7b55cbb0a16e438e6e1857f77107b16b9e5a9d24))
- update to 28.2 ([3211fce](https://github.com/OpenIndiana/oi-userland/commit/3211fced8b51fc9f8f0a69dadd120430ca3ec9d1))
- fix mainfest for none x86_64 architectures ([3cafb84](https://github.com/OpenIndiana/oi-userland/commit/3cafb845e9506dfb19976a0d368b9b63b0d557e9))
- update to 28.3 ([81af481](https://github.com/OpenIndiana/oi-userland/commit/81af4814206c2cf13e555ba9b66ee8d927dbef1f))
- fix collision with file from zlib ([655424a](https://github.com/OpenIndiana/oi-userland/commit/655424a19e99528d9b9d69be9c9e8930553cefc6))
- update to 28.3.1 ([9ca5f37](https://github.com/OpenIndiana/oi-userland/commit/9ca5f3788fead85e305e85a2a7287c2405c735ae))
- update to 28.3.2 ([b09126f](https://github.com/OpenIndiana/oi-userland/commit/b09126f1f31749ed2dc9d757af6ffc7371b499d0))
- update to 28.3.3 ([b770e99](https://github.com/OpenIndiana/oi-userland/commit/b770e99070870eb2477044f7afdfae67a5211de1))
- update to 28.4 ([752bb6d](https://github.com/OpenIndiana/oi-userland/commit/752bb6d9e143a1b931900ec761e76167ac685c43))
- update to 28.4.1 ([e9798e4](https://github.com/OpenIndiana/oi-userland/commit/e9798e4b7468d3f52cf85442151790d0d81c9d2e))
- update to 28.4.2 ([70adfdf](https://github.com/OpenIndiana/oi-userland/commit/70adfdf6e3260b7e8014d2e1a8f3b51e9e34c486))
- update to 28.5 ([e5360b7](https://github.com/OpenIndiana/oi-userland/commit/e5360b797663a1c875088c2798cc775afbfdae2c))

### exiv2

- update to 0.28.8 ([4b39004](https://github.com/OpenIndiana/oi-userland/commit/4b39004a76fe6772465309c7066a1bcf2a328678))

### expat

- update to 2.7.4 ([16698df](https://github.com/OpenIndiana/oi-userland/commit/16698df5eb62ad25304fb2b08ead70d5537df690))
- update to 2.7.5 ([699441e](https://github.com/OpenIndiana/oi-userland/commit/699441e61946d10b06b58ab9238170ed14ffd203))

### fast_float

- update to 8.2.0 ([656256f](https://github.com/OpenIndiana/oi-userland/commit/656256f9782d0872ba0971fec530d1c76737922f))
- update to 8.2.2 ([40f17ad](https://github.com/OpenIndiana/oi-userland/commit/40f17addaa600dbe33ecf7693cff2706fc1fceeb))
- update to 8.2.3 ([382d4bf](https://github.com/OpenIndiana/oi-userland/commit/382d4bf109c5547945549164dd49c810bbe65497))
- update to 8.2.4 ([34563d3](https://github.com/OpenIndiana/oi-userland/commit/34563d3a31aa3ffe8c3dd1a8391982102cc5cdf4))
- update to 8.2.5 ([6a81884](https://github.com/OpenIndiana/oi-userland/commit/6a8188400d9ebb93170ebcace0d89edfcb099851))

### fastfetch

- update to 2.55.0 ([8479043](https://github.com/OpenIndiana/oi-userland/commit/84790439206c2b232f2325798d4f1f437be5b72f))
- update to 2.55.1 ([8c93c38](https://github.com/OpenIndiana/oi-userland/commit/8c93c3808ee8c0c5a79d7d20de1d94c8d7691659))
- update to 2.56.0 ([44919e8](https://github.com/OpenIndiana/oi-userland/commit/44919e850ba3a1cce8cba536699d24ac57f74342))
- update to 2.56.1 ([b3d9721](https://github.com/OpenIndiana/oi-userland/commit/b3d9721cfb6ea6d0b8242b9a0b04c1aa312deb68))
- update to 2.57.1 ([aeca790](https://github.com/OpenIndiana/oi-userland/commit/aeca790c41b4bfec79efa09fb2b42d019873b456))
- update to 2.58.0 ([12718b3](https://github.com/OpenIndiana/oi-userland/commit/12718b3aa8742865fb6704a1c81f38324855a5fb))
- update to 2.59.0 ([bcb34a9](https://github.com/OpenIndiana/oi-userland/commit/bcb34a947b09f5ce0afad4315a470e49ae7f108c))
- update to 2.60.0 ([52523ca](https://github.com/OpenIndiana/oi-userland/commit/52523ca05cea2b7161d23468cd55dcfebf8485c1))
- update to 2.61.0 ([667ebcc](https://github.com/OpenIndiana/oi-userland/commit/667ebccf8f489920c4f69fa2d6c31b3a7cffa568))
- update to 2.62.0 ([fe1205f](https://github.com/OpenIndiana/oi-userland/commit/fe1205f0a461685f00e72f1dec69bd8e46f70214))
- update to 2.62.1 ([e75bb83](https://github.com/OpenIndiana/oi-userland/commit/e75bb8327d5121a9ad51642e70f4c86aee8003f2))

### fd-find

- update to 10.4.2 ([c05bcde](https://github.com/OpenIndiana/oi-userland/commit/c05bcde32b39aefd38599867dad8f0fd32da5a20))

### fetchmail

- update to 6.6.0 ([012da88](https://github.com/OpenIndiana/oi-userland/commit/012da88bd641ffeaf38e7b09c428b63cb75bdae2))
- update to 6.6.1 ([c325a9f](https://github.com/OpenIndiana/oi-userland/commit/c325a9f51b622b8f1e838a51d0990fdd2b6b27ce))
- update to 6.6.2 ([8fc0200](https://github.com/OpenIndiana/oi-userland/commit/8fc0200eacd63add1a9b9ad7f69b70ea50e631b3))
- update to 6.6.3 ([5969bf0](https://github.com/OpenIndiana/oi-userland/commit/5969bf0db9d5cd3c29d890abe58d3ffcce25e635))

### ffmpeg

- update to 7.1.3 ([0626bb8](https://github.com/OpenIndiana/oi-userland/commit/0626bb859d7fb2a397e7faa65858f80b9fcfb69d))
- update to 8.0.1; keep support for FFmpeg 7 ([e8373fc](https://github.com/OpenIndiana/oi-userland/commit/e8373fc54ecfbe590d16d468cd4dee5ca973485a))
- update to 8.1 ([16623ba](https://github.com/OpenIndiana/oi-userland/commit/16623ba44ed8407e560156b52310335699a8def2))

### ffmpeg-6

- update to 6.1.4 ([8657cfe](https://github.com/OpenIndiana/oi-userland/commit/8657cfe8f484a272e5926ae98f020d120a91d0ed))

### ffmpeg-7

- rename library symlinks ([8209d32](https://github.com/OpenIndiana/oi-userland/commit/8209d32a68c949022e900cf8c72953ba15fa6eab))

### fio

- update to 3.42 ([6aefe8a](https://github.com/OpenIndiana/oi-userland/commit/6aefe8a2ae0d0913f63f7450daa07f1a6127d4c7))

### firefox

- update to 144.0.2 ([04a0415](https://github.com/OpenIndiana/oi-userland/commit/04a04153485188647f52ecef3f03e10e047f6bd2))
- update to 145.0 ([a972dbb](https://github.com/OpenIndiana/oi-userland/commit/a972dbbd362e34cae2ed319fcd6990a9419f9477))
- update to 145.0.1 ([9767294](https://github.com/OpenIndiana/oi-userland/commit/97672949bec75af1ea5c32d689fb5e5e08b21882))
- update to 145.0.2 ([da4c854](https://github.com/OpenIndiana/oi-userland/commit/da4c8546fa07e250f5aec0f31deb3e0311861605))
- update to 146.0 ([674df73](https://github.com/OpenIndiana/oi-userland/commit/674df7384f58db3a57f1b87ed9e4decb1823a0c9))
- update to 146.0.1 ([5544330](https://github.com/OpenIndiana/oi-userland/commit/554433036d69c45a3c390fd0f28af659ded2e991))
- update to 147.0 ([1efda78](https://github.com/OpenIndiana/oi-userland/commit/1efda78150afde4e406e3fbe04ee6f692c43bed3))
- update to 147.0.1 ([53df462](https://github.com/OpenIndiana/oi-userland/commit/53df462a0238a2f780c373572acc0b424c69bc00))
- update to 147.0.2 ([4c066d2](https://github.com/OpenIndiana/oi-userland/commit/4c066d2f9497853ec3b8c1dac47d15516a4815d8))
- update to 147.0.3 ([ce9f68c](https://github.com/OpenIndiana/oi-userland/commit/ce9f68ce9916e8760d367bea6fb3b26b2c6d68b3))
- update to 147.0.4 ([343d4ec](https://github.com/OpenIndiana/oi-userland/commit/343d4ecf47a914cfd0ddbc136dc65c7f2a9c3494))
- update to 148.0 ([f7b46c2](https://github.com/OpenIndiana/oi-userland/commit/f7b46c273329d1c33f15af830c7a673e63f5e403))
- update to 148.0.2 ([6b9cbb3](https://github.com/OpenIndiana/oi-userland/commit/6b9cbb39aac42ef1419121d06063563c168116e9))
- update to 149.0 ([95f596e](https://github.com/OpenIndiana/oi-userland/commit/95f596e978c8ed7e1aa75869c7b0f2124f5ba182))
- update to 149.0.2 ([8474bfc](https://github.com/OpenIndiana/oi-userland/commit/8474bfcbb2cda329039914ca04b420589897fbd7))
- update to 150.0 ([03f06cc](https://github.com/OpenIndiana/oi-userland/commit/03f06ccbea1ad8cbe94ee5e7e1800ecfd72df88e))
- update to 150.0.1 ([b0633da](https://github.com/OpenIndiana/oi-userland/commit/b0633da2f71a505109d45cb448d806776d4cc76d))

### fish

- update to 4.0.9 ([4de1fa7](https://github.com/OpenIndiana/oi-userland/commit/4de1fa77cd28aa82777d3e87a3f94b56acacb337))
- update to 4.2.0 ([51258d0](https://github.com/OpenIndiana/oi-userland/commit/51258d04c28cd5e1eb8e4e6d1446be06a88383df))
- update to 4.2.1 ([c241e89](https://github.com/OpenIndiana/oi-userland/commit/c241e8961a246894179023944ee4cd211424a36c))
- update to 4.3.1 ([abaeb5c](https://github.com/OpenIndiana/oi-userland/commit/abaeb5c14da8a09ab4d58d025c186ad29e45b4b8))
- update to 4.3.2 ([1ca8ecf](https://github.com/OpenIndiana/oi-userland/commit/1ca8ecf78ea89297dca6f54450f11b79f44c6816))
- update to 4.3.3 ([3ee3e74](https://github.com/OpenIndiana/oi-userland/commit/3ee3e748874d1e13d72b349c7e353152e7854d29))
- update to 4.5.0 ([03d766e](https://github.com/OpenIndiana/oi-userland/commit/03d766eb041d474fad7d0d427845fd5d2e550c1c))

### fmt

- update to 12.1.0 ([2f19eed](https://github.com/OpenIndiana/oi-userland/commit/2f19eed62414ae56e06953f334f5958d1608d380))

### font-util

- update to 1.4.2 ([4ae2d70](https://github.com/OpenIndiana/oi-userland/commit/4ae2d707fce3ddc49c74c4f439c4209c04321ef2))

### fonts/iosevka

- update to 34.3.0 ([072ac5e](https://github.com/OpenIndiana/oi-userland/commit/072ac5e542e6d213576f22a591dc17c5d7a60871))
- update to 34.4.0 ([a7d0791](https://github.com/OpenIndiana/oi-userland/commit/a7d0791d5f7b5e029cfaffaf24a52083e7180166))

### fonttosfnt

- update to 1.2.5 ([4fa6dcc](https://github.com/OpenIndiana/oi-userland/commit/4fa6dcc7daa418a85e89a90465ebaa1b6fd3da88))

### fossil

- update to 2.28 ([a87960f](https://github.com/OpenIndiana/oi-userland/commit/a87960f0229e388c652553651bcf33197a12dabc))

### freeciv

- update to 3.2.2 ([7dc547b](https://github.com/OpenIndiana/oi-userland/commit/7dc547b4e530eed399769934bfc53d11a34ec0fb))
- update to 3.2.3 ([016447e](https://github.com/OpenIndiana/oi-userland/commit/016447e7f493b86d420ab574b27e204ba9ff6f52))
- update to 3.2.4 ([2814707](https://github.com/OpenIndiana/oi-userland/commit/28147075cd1e4a58e5a7a52c4e9561740111803c))

### freeipmi

- update to 1.6.17 ([6bf4091](https://github.com/OpenIndiana/oi-userland/commit/6bf40915415884bf8ee80a90524a6e96cffc7b7b))

### freeradius

- update to version 3.2.8 and removal of rlm_python (python2 module) ([08b5b6f](https://github.com/OpenIndiana/oi-userland/commit/08b5b6fecde169b0e78efca7504674cec2d44385))

### freerdp

- update to 3.22.0 ([718035b](https://github.com/OpenIndiana/oi-userland/commit/718035bcdc631c5ae603b185cf4fc197d2b81105))
- update to 3.23.0 ([09d4676](https://github.com/OpenIndiana/oi-userland/commit/09d46761acb3484d8705096e067423f69bf5aca8))
- update to 3.24.0 ([8b866ad](https://github.com/OpenIndiana/oi-userland/commit/8b866ad355ce822a8d2ca14b288c6332d9688b60))
- update to 3.24.1 ([d99d2f7](https://github.com/OpenIndiana/oi-userland/commit/d99d2f79303d9c6dd4f48edf4f733d1eb65f39a3))
- update to 3.24.2 ([f00bb2e](https://github.com/OpenIndiana/oi-userland/commit/f00bb2ee83a4f86a6e432946a8bacff71953564f))
- update to 3.25.0 ([0bf6780](https://github.com/OpenIndiana/oi-userland/commit/0bf67800503b6ac0fc8a1425911831161ebbeebc))

### freetds

- update to 1.5.7 ([9985480](https://github.com/OpenIndiana/oi-userland/commit/9985480d03010a24f3150bb3912377c6eb212a41))
- update to 1.5.8 ([17a1be7](https://github.com/OpenIndiana/oi-userland/commit/17a1be7d179cdae2826bb5c6fe9eaa9ef33488e8))
- update to 1.5.9 ([994f7e1](https://github.com/OpenIndiana/oi-userland/commit/994f7e15cbfa6d8b4aac07f50f6587c75eb173a7))
- update to 1.5.10 ([d791f3a](https://github.com/OpenIndiana/oi-userland/commit/d791f3ac981efb29b8ce3f26aad2ca6d7b86f9ed))
- update to 1.5.12 ([e459df3](https://github.com/OpenIndiana/oi-userland/commit/e459df3282e1b2ed956a86a2161afea50f38ab4a))
- update to 1.5.13 ([567a27d](https://github.com/OpenIndiana/oi-userland/commit/567a27d25a9fe3729e9170f43ac2ea9b70255f3f))
- update to 1.5.14 ([9e8c9b9](https://github.com/OpenIndiana/oi-userland/commit/9e8c9b958405e3f1a5eff44efeef102b3d836fc4))
- update to 1.5.16 ([e2fef33](https://github.com/OpenIndiana/oi-userland/commit/e2fef33dc762efc44d3dc70030b7691fc175c618))

### freetype

- update to 2.14.2 ([cfb36bd](https://github.com/OpenIndiana/oi-userland/commit/cfb36bdd15d0fedd88851fae0145d82fdec464c7))
- update to 2.14.3 ([8bf6527](https://github.com/OpenIndiana/oi-userland/commit/8bf6527d2b0cb2afe01d4ec8118913279e40fcf2))

### garage

- update to 2.2.0 ([00a5a92](https://github.com/OpenIndiana/oi-userland/commit/00a5a92face1f0703d850e5e843aaa4e7ca2a843))
- update to 2.3.0 ([9817dd7](https://github.com/OpenIndiana/oi-userland/commit/9817dd708c3f17a852000eb969d8491ab4816f97))

### gc

- bump to 8.2.12 ([933037a](https://github.com/OpenIndiana/oi-userland/commit/933037aa92ab35b7ec6cc804ea263824d896751b))

### gcc-14

- Add patches to allow nontrivial use of the C++ <locale> API ([89cab59](https://github.com/OpenIndiana/oi-userland/commit/89cab5989d6fe1f1c05d3628c98176ef7e227c0d))

### gdk-pixbuf

- update 2.44.5 ([5ef3b2f](https://github.com/OpenIndiana/oi-userland/commit/5ef3b2f9b68d037ba96c81597c28efc7e75b5ce2))
- update to 2.44.6 ([8a959d7](https://github.com/OpenIndiana/oi-userland/commit/8a959d700098b729a58fbbdff8e0a39c9e723635))

### geeqie

- rebuild after poppler upgrade ([9a18c21](https://github.com/OpenIndiana/oi-userland/commit/9a18c211b5444fde3b08dce1926d12a39ff00491))
- rebuild after libraw upgrade ([771aa41](https://github.com/OpenIndiana/oi-userland/commit/771aa413532ddc2c2331af116f0116dc8f0df99e))
- update to 2.7 ([6e1df60](https://github.com/OpenIndiana/oi-userland/commit/6e1df60ce026dbd977d23e5339cf804527f47c3a))

### gegl

- update to 0.4.66 ([8f870b0](https://github.com/OpenIndiana/oi-userland/commit/8f870b097157eb64517a1612665bb7ba0f257777))
- rebuild after poppler upgrade ([f830057](https://github.com/OpenIndiana/oi-userland/commit/f83005756a53f3dc8311aea2c1fd4ef3ae0171aa))
- rebuild after libraw upgrade ([a860643](https://github.com/OpenIndiana/oi-userland/commit/a8606439af43b97f5aab248cfbe6614cafa082ac))
- update to 0.4.68 ([1076180](https://github.com/OpenIndiana/oi-userland/commit/10761808fbffa194c912bfc39e47402b1e6900de))
- update to 0.4.70 ([9ebd0c7](https://github.com/OpenIndiana/oi-userland/commit/9ebd0c71b1aee3a8358c429ccff99e0a2fd110f6))

### geoip-database

- update to 20260329 ([958c2c8](https://github.com/OpenIndiana/oi-userland/commit/958c2c83a37985722d260cfcae66f2694fa7e8a4))

### ghostscript

- update to 10.06.0; import patches from solaris-userland ([4ea2f69](https://github.com/OpenIndiana/oi-userland/commit/4ea2f6901216a84949db2fc784998887880fbe46))

### giflib

- update to 5.2.2 - drop 32bit libs/binaries ([a9e7c6b](https://github.com/OpenIndiana/oi-userland/commit/a9e7c6baab43f9784f086967616757d15e1ac7eb))

### gimp

- update to 3.0.8 ([844f37e](https://github.com/OpenIndiana/oi-userland/commit/844f37e64229f2de58b6d705d3aa518580dc72a2))
- rebuild after poppler upgrade ([561a855](https://github.com/OpenIndiana/oi-userland/commit/561a855ebe4ee83e6e222d4ff9afb5f42ea03380))
- update to 3.2.0 ([72d51fe](https://github.com/OpenIndiana/oi-userland/commit/72d51fec8b5428c7750a2958ff0a96886cec9536))
- update to 3.2.2 ([b39a238](https://github.com/OpenIndiana/oi-userland/commit/b39a2387565499289efdc7f446b6a87720f4e080))
- update to 3.2.4 ([8dfe543](https://github.com/OpenIndiana/oi-userland/commit/8dfe5433c05cd2d71f8c8b29fb76ea6e349f74b8))

### git

- update to 2.51.2 ([6ca4698](https://github.com/OpenIndiana/oi-userland/commit/6ca469818df119277c8652688bc671f130f36613))
- update to 2.52.0 ([3663734](https://github.com/OpenIndiana/oi-userland/commit/366373452f135c949733f1f4067b1036784164cd))
- update to 2.53.0 ([2e1f3d3](https://github.com/OpenIndiana/oi-userland/commit/2e1f3d3a25fb22221b3a5340f6140df1ecc68580))
- update to 2.54.0 ([d562abe](https://github.com/OpenIndiana/oi-userland/commit/d562abe16d539f6be67ad59c0e58b37a78093408))

### glib

- update to 2.86.2 ([5883166](https://github.com/OpenIndiana/oi-userland/commit/5883166133b59878481402d46bcacf96d5485726))
- make 32-bit build variable ([dfbae0a](https://github.com/OpenIndiana/oi-userland/commit/dfbae0af841f468d1a3c35f9f50f419895aff6a6))
- update to 2.86.3 ([c292b5a](https://github.com/OpenIndiana/oi-userland/commit/c292b5a718ef25de7f02463b26621518e9a7fdc4))
- update to 2.86.4 ([a13c9ff](https://github.com/OpenIndiana/oi-userland/commit/a13c9fff20590cf2c6a9c9cd2a58b8387f7b6d03))
- update to 2.86.5 ([62dbca8](https://github.com/OpenIndiana/oi-userland/commit/62dbca84b766b7fcfb538fb9b70f340961670c33))

### glibmm-268

- update to 2.86.0 ([6f00040](https://github.com/OpenIndiana/oi-userland/commit/6f00040afe9ce56913741ee2ac3f11b12eb9541a))

### glm

- update to 1.0.2 ([68e3b9f](https://github.com/OpenIndiana/oi-userland/commit/68e3b9f237d1f89b7d52653e3719d71add641f69))
- update to 1.0.3 ([0e7440b](https://github.com/OpenIndiana/oi-userland/commit/0e7440bc7929604cebeecc7254da50bdb5af2e3a))

### gmp

- fix packaging ([f5bce55](https://github.com/OpenIndiana/oi-userland/commit/f5bce551f890427dd94b03928c5de47e8a1e3dfd))

### gnome-commander

- update to 1.18.5 ([ce68173](https://github.com/OpenIndiana/oi-userland/commit/ce681739b4775a41fac71fa34624f2afd81ed904))
- rebuild after poppler upgrade ([bfcc945](https://github.com/OpenIndiana/oi-userland/commit/bfcc945c5bf7e7a00ccadef97923593944562c8f))
- update to 1.18.6 ([cc3a115](https://github.com/OpenIndiana/oi-userland/commit/cc3a1157175087a78128783a0b626976955671ce))

### gnu-gettext

- update to 1.0 ([b0470f3](https://github.com/OpenIndiana/oi-userland/commit/b0470f37d29bd3de2eb2320b5e7f714f25e540ea))

### gnupg

- update to 2.5.16 ([b3dc71b](https://github.com/OpenIndiana/oi-userland/commit/b3dc71bfa71557c7452fba525ec0baf646a75211))
- update to 2.5.17 ([e6a4bca](https://github.com/OpenIndiana/oi-userland/commit/e6a4bcad598288f155a22158344187bc545245d1))
- update to 2.5.18 ([5ae82e0](https://github.com/OpenIndiana/oi-userland/commit/5ae82e01f9776eae4133416357daf0662fa41602))
- update to 2.5.19 ([b50f78b](https://github.com/OpenIndiana/oi-userland/commit/b50f78be78a151034ebab0bd2ba53e5c0f0f3040))

### gnutls

- update to 3.8.11 ([08bccf9](https://github.com/OpenIndiana/oi-userland/commit/08bccf95fa13e404d8fc69ce6e48e88675978fa4))
- update to 3.8.12 ([610c96b](https://github.com/OpenIndiana/oi-userland/commit/610c96b1ece037bd633aee8cfad93134962df44b))

### goffice

- update to 0.10.60 ([f5fdd4a](https://github.com/OpenIndiana/oi-userland/commit/f5fdd4a524812b8945020aefe4c5497efef23ff6))

### golang-1.24

- update to 1.24.11 ([62d7a81](https://github.com/OpenIndiana/oi-userland/commit/62d7a81dcc487deaccd01d9089cac26570b45062))
- update to 1.24.12 ([0d9047d](https://github.com/OpenIndiana/oi-userland/commit/0d9047d48bdc3aded8fa7854a1e64c0d3e2397e8))
- update to 1.24.13 ([c41b4d1](https://github.com/OpenIndiana/oi-userland/commit/c41b4d14b5ef7e67c0c755a5f77b16de3e2f9e5a))

### golang-1.25

- update to 1.25.5 ([1e0321e](https://github.com/OpenIndiana/oi-userland/commit/1e0321efff268bd0178e452dc38a5eef80d82bfa))
- update to 1.25.7 ([bca6f3d](https://github.com/OpenIndiana/oi-userland/commit/bca6f3d268535b818f89e60862e2fd704817da70))
- update to 1.25.8 ([54f8e25](https://github.com/OpenIndiana/oi-userland/commit/54f8e2556b5c9115c721cb3dcfd08d54c31ebd9d))

### golang-124

- update to 1.24.10 ([109a9e5](https://github.com/OpenIndiana/oi-userland/commit/109a9e59dbaff3e675b2969bacbd5fa2f053f080))

### golang-125

- update to 1.25.4 ([0744836](https://github.com/OpenIndiana/oi-userland/commit/074483699b406f4e2a1627ec0ae7e31d6f56f800))
- update to 1.25.6 ([494fe17](https://github.com/OpenIndiana/oi-userland/commit/494fe179a75ceab4732c2502def78969b69f7140))
- update to 1.25.9 ([306f81e](https://github.com/OpenIndiana/oi-userland/commit/306f81e7676198f015126d1dc1bec5511e5f0450))

### golang-126

- add 1.26.1 ([4e24c16](https://github.com/OpenIndiana/oi-userland/commit/4e24c1605bb88be82f292b438832b7caca7f8f2e))
- update to 1.26.2 ([ca28039](https://github.com/OpenIndiana/oi-userland/commit/ca280394485924c291b3af731ee47347a3b7f65e))

### gom

- update to 0.5.5 ([8bedebb](https://github.com/OpenIndiana/oi-userland/commit/8bedebbcf700dd4ade8b5505f955c6a04460f050))

### gpgme

- update to 2.0.1 ([7c3e804](https://github.com/OpenIndiana/oi-userland/commit/7c3e804540b1cfe9f71b83f87629cb8157e91472))

### gradle

- update to 9.4.1 ([d306fea](https://github.com/OpenIndiana/oi-userland/commit/d306fea8af62710d8f15dfa20c481c30352e69a8))

### gradlle

- add 9.4.0 ([171ed09](https://github.com/OpenIndiana/oi-userland/commit/171ed0932042bd6efa53947f946892fd6323ac84))

### graphicsmagick

- update to 1.3.46 ([837b8bb](https://github.com/OpenIndiana/oi-userland/commit/837b8bb21e8f9e4191757dbe50fdd452e7786a61))

### graphviz

- rebuild after poppler upgrade ([a5561e7](https://github.com/OpenIndiana/oi-userland/commit/a5561e760e124e01e30f2f9fa1e3dfc3f6068edc))

### groff

- update to 1.24.1 and integrate groff-core into groff ([6eeb1eb](https://github.com/OpenIndiana/oi-userland/commit/6eeb1ebffd1796ddbee608f58f8ee7f230593997))

### groovy-40

- update to 4.0.30 ([ea122f1](https://github.com/OpenIndiana/oi-userland/commit/ea122f18dd9cc63faa98abb23a9e0b2e76a358b8))
- update to 4.0.31 ([e89e401](https://github.com/OpenIndiana/oi-userland/commit/e89e401746cf5f575fdc79fa97787faa86ffc100))

### groovy-50

- update to 5.0.3 ([7d420a9](https://github.com/OpenIndiana/oi-userland/commit/7d420a9c30401babdc074c353255be142802cc6c))
- update to 5.0.4 ([5e4b0d1](https://github.com/OpenIndiana/oi-userland/commit/5e4b0d1faf3f440280cde006ae2fbaa0314d9be5))
- update to groovy-50-5.0.5 ([3f783de](https://github.com/OpenIndiana/oi-userland/commit/3f783de15da1cbdf109832a2b59703b1607f662f))

### gsettings-desktop-schemas

- update to 50.0 ([385ce98](https://github.com/OpenIndiana/oi-userland/commit/385ce98f7b72e9343d758c7ae81aeb86b78fe62c))
- update to 50.1 ([9db69da](https://github.com/OpenIndiana/oi-userland/commit/9db69da54d5a789717dbc05cffabef2bb443d30e))

### gsm

- update to 1.0.24 ([9cda0cd](https://github.com/OpenIndiana/oi-userland/commit/9cda0cdaf63dbc781ef3bcd6c6992c486eab9433))

### gsoap

- update to 2.8.140 ([669f56e](https://github.com/OpenIndiana/oi-userland/commit/669f56e99d9601b05f518a4b5a994fce468f38a8))
- update to 2.8.141 ([0afc85d](https://github.com/OpenIndiana/oi-userland/commit/0afc85d5031b59b8537ca4add645ff05beddc955))

### gspell

- update to 1.14.2 ([3601e31](https://github.com/OpenIndiana/oi-userland/commit/3601e319b984667e811cfd4dfd6ce941007c4eb5))

### gst-devtools

- update to 1.26.8 ([98ae2ea](https://github.com/OpenIndiana/oi-userland/commit/98ae2ea1bc7a57ce7269f1867381f820d33c2b23))
- update to 1.26.10 ([bc8b1b1](https://github.com/OpenIndiana/oi-userland/commit/bc8b1b1db99ebd4cfbdf0f25fa29959b1e54cdc6))
- update to 1.28.1 ([15a3d30](https://github.com/OpenIndiana/oi-userland/commit/15a3d30969544a632f6983a43b3bac1467594b56))
- update to 1.28.2 ([636753d](https://github.com/OpenIndiana/oi-userland/commit/636753d9d6c5ae37b20ff1671c3c844ef4cd95c4))

### gst-editing-services

- update to 1.26.8 ([5852301](https://github.com/OpenIndiana/oi-userland/commit/58523016903bad42859da9dca9ebc6b24b2edd24))
- update to 1.26.10 ([85bf675](https://github.com/OpenIndiana/oi-userland/commit/85bf67513bae0e31d49fda916121ea2e69e1d8ba))
- update to 1.28.1 ([1b17a54](https://github.com/OpenIndiana/oi-userland/commit/1b17a540421872e23dee844dfc253d4468bdd146))
- update to 1.28.2 ([81e918d](https://github.com/OpenIndiana/oi-userland/commit/81e918dedb45cbee8bc2ac15f21152d21b589e18))

### gst-libav

- update to 1.26.8 ([d2f3014](https://github.com/OpenIndiana/oi-userland/commit/d2f301408a645fcc104b78eeb5cab35609d2d01f))
- update to 1.26.9 ([9dcdec5](https://github.com/OpenIndiana/oi-userland/commit/9dcdec53e58129bf3fdee935d8a37cb5c2ef9a05))
- update to 1.26.10 ([ed20c31](https://github.com/OpenIndiana/oi-userland/commit/ed20c31a0cea320fb19d9ac0f61c1160ca92a786))
- update to 1.28.1 ([087a4a5](https://github.com/OpenIndiana/oi-userland/commit/087a4a5dc7e434a91e26f475e6c6a6517bc719e8))
- update to 1.28.2 ([04ccef2](https://github.com/OpenIndiana/oi-userland/commit/04ccef29ad9e3f9beb2f9f1cf96ce5e9ea6d938d))

### gst-plugins-bad

- update to 1.26.8 ([7f32711](https://github.com/OpenIndiana/oi-userland/commit/7f32711031ad80ef338c3b3866eb6d14017f0d29))
- update to 1.26.9 ([7f0add1](https://github.com/OpenIndiana/oi-userland/commit/7f0add16837e7f9ae63865de3a3eb29d03a4fb9a))
- update to 1.26.10 ([00b7737](https://github.com/OpenIndiana/oi-userland/commit/00b7737ce4fa65a0ee5d914812ec3aa295a8b459))
- update to 1.28.1 ([e0503bd](https://github.com/OpenIndiana/oi-userland/commit/e0503bdec81c100aeef3dda12f3c511e51c3d36c))
- update to 1.28.2 ([acaecb7](https://github.com/OpenIndiana/oi-userland/commit/acaecb75b602a9655996baf4c9cce532446a94c0))

### gst-plugins-base

- update to 1.26.8 ([e40326f](https://github.com/OpenIndiana/oi-userland/commit/e40326f17ade2193bd7ea0f986896e5c530ed256))
- update to 1.26.9 ([defea74](https://github.com/OpenIndiana/oi-userland/commit/defea74081f43496b74be7cad0e7bf1e91db5771))
- update to 1.26.10 ([4159f74](https://github.com/OpenIndiana/oi-userland/commit/4159f74d7c82c06423cb28f269617e18f18546b7))
- update to 1.28.0 ([a68e114](https://github.com/OpenIndiana/oi-userland/commit/a68e11481c3a8f0fbcdb85c50dddf926debdc74c))
- update to 1.28.1 ([07017c2](https://github.com/OpenIndiana/oi-userland/commit/07017c2114f31d01b1fd90ffc190ce2faadf0034))
- update to 1.28.2 ([fed43cd](https://github.com/OpenIndiana/oi-userland/commit/fed43cdd302292c74d6a4ceb1797755db9b4007f))

### gst-plugins-good

- update to 1.26.8 ([12443ef](https://github.com/OpenIndiana/oi-userland/commit/12443ef24a378c8e44fe971b7dcf44dd820e1a4d))
- update to 1.26.9 ([f79606c](https://github.com/OpenIndiana/oi-userland/commit/f79606c8a7f05c2a8584f567edcfc571504ca664))
- update to 1.26.10 ([11bb5bb](https://github.com/OpenIndiana/oi-userland/commit/11bb5bb4efddcad3a39ab3455f8304b70ac2e820))
- update to 1.28.1 ([26afd44](https://github.com/OpenIndiana/oi-userland/commit/26afd44a641d396d9fdba02753da1ea613ce38f7))
- update to 1.28.2 ([cd68f4f](https://github.com/OpenIndiana/oi-userland/commit/cd68f4f52cf148eedc2c46866785be0dda7ae60a))

### gst-plugins-ugly

- update to 1.26.8 ([ae90c18](https://github.com/OpenIndiana/oi-userland/commit/ae90c18bbdcbe43ab40d6723e41fd9653cc37442))
- update to 1.26.9 ([f42c547](https://github.com/OpenIndiana/oi-userland/commit/f42c547cf3e868b015153a599c0169d56f9311c3))
- update to 1.26.10 ([b806f25](https://github.com/OpenIndiana/oi-userland/commit/b806f25a1d1057e29847d044478a6d4f650dd16e))
- update to 1.28.1 ([86f073d](https://github.com/OpenIndiana/oi-userland/commit/86f073d64d6e0095c3b016881838e58b85e9c243))
- update to 1.28.2 ([39245b0](https://github.com/OpenIndiana/oi-userland/commit/39245b0a12ac3812c0229ea63994bea1d731ad62))

### gst-rtsp-server

- update to 1.26.8 ([8b8cf3c](https://github.com/OpenIndiana/oi-userland/commit/8b8cf3cbd6e94b34f6575e5956dfec10b5170ea8))
- update to 1.26.10 ([e9de686](https://github.com/OpenIndiana/oi-userland/commit/e9de68622ff56d640df384b4d534066262837ffd))
- update to 1.28.1 ([071c592](https://github.com/OpenIndiana/oi-userland/commit/071c5927c73b10c3dd6ddf83e6ab5c027994f45e))
- update to 1.28.2 ([d8ccaf6](https://github.com/OpenIndiana/oi-userland/commit/d8ccaf6dfc7737e2d04178ab84a0a60a8f7a0f73))

### gstreamer

- update to 1.26.8 ([e29e8b4](https://github.com/OpenIndiana/oi-userland/commit/e29e8b44dd79aa10ce9c2edc7f26c13af1ba049f))
- update to 1.26.9 ([ee52cb1](https://github.com/OpenIndiana/oi-userland/commit/ee52cb13cb207106416a82a70c15dd193983bf4d))
- update to 1.26.10 ([b3cd6a6](https://github.com/OpenIndiana/oi-userland/commit/b3cd6a631e32183f79ea83f6e8b702b0fe8f20a4))
- update to 1.28.0 ([8826979](https://github.com/OpenIndiana/oi-userland/commit/8826979c57cd572cd4e3b81b8920fe6840f71f9f))
- update to 1.28.1 ([8fbd1cc](https://github.com/OpenIndiana/oi-userland/commit/8fbd1cc42fb5783164bde02efadef407c7f18a8e))
- update to 1.28.2 ([97b83ec](https://github.com/OpenIndiana/oi-userland/commit/97b83ecb8e5fac4d6c72b6783955a7a8624f4b47))

### gthumb

- rebuild after libraw upgrade ([6fd3ccf](https://github.com/OpenIndiana/oi-userland/commit/6fd3ccffad870f099eacdd01c059b51998725a37))

### gtk-doc

- update to 1.35.1 ([618c5c9](https://github.com/OpenIndiana/oi-userland/commit/618c5c942466dd06a503aac4f5290ac0db38a2f9))

### gtk3

- update to 3.24.52 ([23f2f2b](https://github.com/OpenIndiana/oi-userland/commit/23f2f2b3b5a82b330fbbc3a4a35929747a73b93e))

### gucharmap

- update to 17.0.1 ([1824261](https://github.com/OpenIndiana/oi-userland/commit/1824261a634886624d7f00410271e1f4077818f1))
- update to 17.0.2 ([adcbe62](https://github.com/OpenIndiana/oi-userland/commit/adcbe62b6f39330d2f0f4698ac24e502934bea4c))

### haproxy

- update to 3.2.14 ([e13c8f6](https://github.com/OpenIndiana/oi-userland/commit/e13c8f6cde697d2f063567a61004414f613f34be))
- update to 3.2.15 ([97bb609](https://github.com/OpenIndiana/oi-userland/commit/97bb6092ac3f64c9a2c49d70011005a5f648c30a))
- update to 3.2.16 ([0a13b3d](https://github.com/OpenIndiana/oi-userland/commit/0a13b3dd28bb460e263e468806d51ad3cd5ab78d))

### harfbuzz

- update to 12.2.0 ([c3b9b44](https://github.com/OpenIndiana/oi-userland/commit/c3b9b44a8baedc6557c335856e46719544f6c7c3))
- update to 12.3.0 ([43ce5d7](https://github.com/OpenIndiana/oi-userland/commit/43ce5d7e81d20be931cb7d91b1f4937d0546be04))
- update to 12.3.1 ([c4feb3a](https://github.com/OpenIndiana/oi-userland/commit/c4feb3a21cf409fe74dcd59dba8186acb291bdc4))
- update to 12.3.2 ([66b1e22](https://github.com/OpenIndiana/oi-userland/commit/66b1e22c4fc58be21fd7b164e78a70f773cecfa8))
- update to 13.0.0 ([888d237](https://github.com/OpenIndiana/oi-userland/commit/888d237d944415716fb3445ef95b5742770a3c8e))
- update to 13.0.1 ([5a70fd1](https://github.com/OpenIndiana/oi-userland/commit/5a70fd174a38df24a61ce865df35f51de70d35b0))
- update to 13.1.0 ([d32e01c](https://github.com/OpenIndiana/oi-userland/commit/d32e01ca737e8c44dd6c6f46e7a248e5df8f732c))
- update to 13.1.1 ([4cd0d08](https://github.com/OpenIndiana/oi-userland/commit/4cd0d080d31b6d0feaa0c5f5127bda3509cc6494))
- update to 13.2.0 ([7c5a3e3](https://github.com/OpenIndiana/oi-userland/commit/7c5a3e38cd5cc0d7be77e82512883c0e5f370b18))
- update to 13.2.1 ([d35dc41](https://github.com/OpenIndiana/oi-userland/commit/d35dc410f30994df37ace654ca106eead2d4bc63))
- update to 14.0.0 ([8f8b7b2](https://github.com/OpenIndiana/oi-userland/commit/8f8b7b2b0f49fd189569037eeb7672309352c3a7))
- update to 14.1.0 ([659d78b](https://github.com/OpenIndiana/oi-userland/commit/659d78b9236e99e876d50592967353f56e8fbc53))
- update to 14.2.0 ([4b5214e](https://github.com/OpenIndiana/oi-userland/commit/4b5214e52b19615b09401b6fccca1ad9c0e07714))

### hdf5

- update to 2.1.1 ([ba1be0c](https://github.com/OpenIndiana/oi-userland/commit/ba1be0cd382d714d434e5f05d5264bcf39ee3769))

### heimdal

- add 7.8.0 ([6741c1e](https://github.com/OpenIndiana/oi-userland/commit/6741c1ea6a6582c506a68df664de917a6b8a870b))
- move man pages to /usr/heimdal ([85e95a8](https://github.com/OpenIndiana/oi-userland/commit/85e95a84e883a1178974d33089c581b3a0f43a82))
- rebuild after lmdb upgrade ([561b808](https://github.com/OpenIndiana/oi-userland/commit/561b808eba93252c0c67fd2daacee87803da6f04))

### htop

- update to 3.5.0 ([62d120d](https://github.com/OpenIndiana/oi-userland/commit/62d120d289e9f7365ea53520d469bf6ed3a04509))
- update to 3.5.1 ([de23ad4](https://github.com/OpenIndiana/oi-userland/commit/de23ad455c7d9cb21f5f7ce776663a759d1cabf2))

### ibus-anthy

- fix ibus-anthy 1.5.17 ([085e772](https://github.com/OpenIndiana/oi-userland/commit/085e772583923c2fbf599dad2a8bb98536d25dea))
- update to 1.5.18 ([8aecd03](https://github.com/OpenIndiana/oi-userland/commit/8aecd0328e8d6d1b1e0fed4e08579dd2fc46e788))

### iceauth

- update to 1.0.11 ([78bec08](https://github.com/OpenIndiana/oi-userland/commit/78bec08ce434f5c4625306ddec93bc9bfd236f92))

### ico

- update to 1.0.7 ([7456020](https://github.com/OpenIndiana/oi-userland/commit/7456020113c52b3cca903ddf91f70e88d7060b16))

### icu

- update to 78.1; keep ICU 77 libraries; obsolete ICU 72 and ICU 74 ([660943c](https://github.com/OpenIndiana/oi-userland/commit/660943c63680361ff7b7d5163f9dadef212ffbb0))
- fix genccode assembly detection for 64-bit ([21426a7](https://github.com/OpenIndiana/oi-userland/commit/21426a737087f8a8c75f107187742e1de7b6eb4a))
- update to 78.2 ([b057457](https://github.com/OpenIndiana/oi-userland/commit/b0574572a3308119b54b52b8d69abb3755c012e2))
- update to 78.3; obsolete ICU 75 ([c16d4c0](https://github.com/OpenIndiana/oi-userland/commit/c16d4c084995e4565aed31e2675dc96f8820482c))

### illumos-closed

- need more drivers for SPARC debug builds ([f12273c](https://github.com/OpenIndiana/oi-userland/commit/f12273c5e5842cc8e543160a149ec2844c07c550))
- Updates for SPARC debug builds ([2629f00](https://github.com/OpenIndiana/oi-userland/commit/2629f00e826ec860f78f628c860bc65a9cf6c3ce))

### imagemagick

- rebuild after libraw upgrade ([ee9b488](https://github.com/OpenIndiana/oi-userland/commit/ee9b488dfdaa361d90d1dfe5ad1d75615044c583))

### imake

- update to 1.0.11 ([8cc4406](https://github.com/OpenIndiana/oi-userland/commit/8cc4406d561f51b9d7f18d5d08c4ad45d40cf18f))

### imlib2

- update to 1.12.6 ([36a30f2](https://github.com/OpenIndiana/oi-userland/commit/36a30f2cbe474d8b1c845c22e1d859b3c1e4e5ee))
- rebuild after libraw upgrade ([3332050](https://github.com/OpenIndiana/oi-userland/commit/3332050ce15a5ad6a6e40a61d2be7586443e574f))

### inkscape

- update to 1.4.3 ([dd5cbec](https://github.com/OpenIndiana/oi-userland/commit/dd5cbeca18c58d351ec5ed6a78b4ddcf717ee791))
- add poppler 26.02 support ([65d59db](https://github.com/OpenIndiana/oi-userland/commit/65d59db7bdce470a512d55ed23a5ab3fb152fbbd))

### install-types

- obsolete auto_install installation profile - the autoinstall slim_source part is long gone ([d6e9e8b](https://github.com/OpenIndiana/oi-userland/commit/d6e9e8b993a6c2678f8a113c107df7544fdbf283))
- add new storage drivers from illumos-2023 to OI distribution ([2f42ce7](https://github.com/OpenIndiana/oi-userland/commit/2f42ce7783ee09536d8ae7af713cb64a8adf9309))
- add igc network driver and virtual io drivers ([f3ff58e](https://github.com/OpenIndiana/oi-userland/commit/f3ff58e40222de19c6d93382f554d20985e4a979))

### iosevka

- update to 34.2.1 ([fd699d6](https://github.com/OpenIndiana/oi-userland/commit/fd699d6f8f126fd9c6fc94ee915e8bfc1fa3220f))

### ipmitool

- rebuild to use openssl-3 ([438eea4](https://github.com/OpenIndiana/oi-userland/commit/438eea41c457ff8b60b07590b2e0b5f09928d34f))

### iso-codes

- update to 4.19.0 ([4f70125](https://github.com/OpenIndiana/oi-userland/commit/4f7012584a2b34582dc9c9f0d28516083fbbc7d7))
- update to 4.20.1 & add test results ([186c8bf](https://github.com/OpenIndiana/oi-userland/commit/186c8bff1a3de9acd48055d5d5a5ad7709c60d48))

### janet

- update to 1.40.0 ([f1144b7](https://github.com/OpenIndiana/oi-userland/commit/f1144b76cd928667e7e469a3e0954a73829d4a21))
- update to 1.40.1 ([2f01d61](https://github.com/OpenIndiana/oi-userland/commit/2f01d61aa75559bb71d5dc9c6313a1db279a6f17))
- update to 1.41.2 ([fc06edf](https://github.com/OpenIndiana/oi-userland/commit/fc06edf39b77578465920bb13e480b08de7ee18d))

### jansson

- update to 2.15.0 & drop 32 bit ([4e62251](https://github.com/OpenIndiana/oi-userland/commit/4e6225191368cfbec5c8a1432d6b094b2122ef6a))

### jasper

- update to 4.2.9 ([31c56fb](https://github.com/OpenIndiana/oi-userland/commit/31c56fbe92deb04ff184005d182ac06cb2424017))

### jenkins-core-lts

- update to 2.518.2 ([7fe0152](https://github.com/OpenIndiana/oi-userland/commit/7fe0152076f0b17cd0caf068a84e614864797b21))
- update to 2.528.3 ([dacb6bb](https://github.com/OpenIndiana/oi-userland/commit/dacb6bbc7d1020904eb5e0b49741b52ab35ecfe5))
- update to 2.541.1 ([daafd0e](https://github.com/OpenIndiana/oi-userland/commit/daafd0eab5039b04c104f9f959077d45357780fb))
- update to 2.541.2 ([078da91](https://github.com/OpenIndiana/oi-userland/commit/078da911cc193e736de6897d196b479425b1e52b))
- update to 2.541.3 ([f22f9c0](https://github.com/OpenIndiana/oi-userland/commit/f22f9c0d656e42bc59924287d3a8bebac5311a69))
- update to 2.555.1 ([a6ee176](https://github.com/OpenIndiana/oi-userland/commit/a6ee1761a8e8fbd45cbb83b9eb931fa496e731c2))

### jenkins-core-weekly

- update to 2.534 ([007c2fd](https://github.com/OpenIndiana/oi-userland/commit/007c2fd609fe72b8b5fcd522d3c3658c614ac9ec))
- update to 2.536 ([091f50a](https://github.com/OpenIndiana/oi-userland/commit/091f50a9e8440d4806ff8a5d0fae576aaacf5fdf))
- update to 2.538 ([8de6adf](https://github.com/OpenIndiana/oi-userland/commit/8de6adfc2e650562e1cdcb8ba4cf2e75e0785748))
- upate to 2.540 ([2af3945](https://github.com/OpenIndiana/oi-userland/commit/2af39457518822ba811e3fee7daa39fa0080601c))
- update to 2.541 ([1d7e127](https://github.com/OpenIndiana/oi-userland/commit/1d7e1278ed2eadbb0c0293066a4db2663a314db7))
- update to 2.545 ([6f88d53](https://github.com/OpenIndiana/oi-userland/commit/6f88d5378e9376f262e0f4756728c84102c9ca1c))
- update to 2.547 ([fdc819b](https://github.com/OpenIndiana/oi-userland/commit/fdc819bd15167b117351edaef5a1b47622dce809))
- update to 2.548 ([2cf3df6](https://github.com/OpenIndiana/oi-userland/commit/2cf3df65c997edcf4703f3ab22a6da849d53e1be))
- update to 2.551 ([e8e5baa](https://github.com/OpenIndiana/oi-userland/commit/e8e5baabe341d2d0ae05e7e27191e44dcd76ada4))
- upate to 2.554 ([18d0a26](https://github.com/OpenIndiana/oi-userland/commit/18d0a26cee3b6e264c069467c6b0501052451c96))
- update to 2.555 ([029dd80](https://github.com/OpenIndiana/oi-userland/commit/029dd8025e010f5c54eb4ddb291f06a2ae60febe))
- update to 2.557 ([8f81774](https://github.com/OpenIndiana/oi-userland/commit/8f8177493aeeae2172aca2f19249553a6d2e572c))
- update to 2.559 ([1070129](https://github.com/OpenIndiana/oi-userland/commit/1070129ebdd5c8c91a81631ee1c654493a0b2eb5))

### joe

- update to 4.7 ([1ee5331](https://github.com/OpenIndiana/oi-userland/commit/1ee5331e746e1dbb24fa9da8b59c2185a3dcdd25))

### jq

- add patch for CVE-2025-9403 ([98ff7dc](https://github.com/OpenIndiana/oi-userland/commit/98ff7dc1ba438cd54d7198e1a707d9d6c67b4e8e))

### keepassxc

- update to 2.7.11 ([51306f3](https://github.com/OpenIndiana/oi-userland/commit/51306f3533d68130c9ee010cd6079e517f7e00dc))
- update to 2.7.12 ([479bad3](https://github.com/OpenIndiana/oi-userland/commit/479bad3cc27c438b217257716f25a1e78db7d58a))

### lame

- fix gcc-14 build ([d9ead39](https://github.com/OpenIndiana/oi-userland/commit/d9ead390c0709d6eb5d0138ce7c57de40600d7f9))

### lcms2

- update to 2.18 ([12d1700](https://github.com/OpenIndiana/oi-userland/commit/12d17001c15cbc20ee62941c9d608b2fb06e3e3c))
- update to 2.19 ([3caef3f](https://github.com/OpenIndiana/oi-userland/commit/3caef3fc2ba88aa987bde4aa281e56f10ce055c4))

### libXcomposite

- update to 0.4.7 ([4f232e0](https://github.com/OpenIndiana/oi-userland/commit/4f232e089e05976406b6cc6693a4540d8c8ace1e))

### libXdamage

- update to 1.1.7 ([ce841ac](https://github.com/OpenIndiana/oi-userland/commit/ce841ac93a8463a35499f25106d33297726c2e44))

### libXinerama

- update to 1.1.6 ([2a7119d](https://github.com/OpenIndiana/oi-userland/commit/2a7119d1021e7d6e2bfd8d9a5c89e294eefcbaf5))

### libXpm

- update to 3.5.18 ([3fd5698](https://github.com/OpenIndiana/oi-userland/commit/3fd5698a13742ccce7bb07e396c54b61ee5add70))

### libXrandr

- update to 1.5.5 ([66b29a0](https://github.com/OpenIndiana/oi-userland/commit/66b29a08e0cdacdc54c98b19dbaf6f6ba61ddc13))

### libXvMC

- update to 1.0.15 ([2e128eb](https://github.com/OpenIndiana/oi-userland/commit/2e128eb423edb8ac302fb9005197d15ce9b23538))

### libarchive

- update to 3.8.3 ([3c0ecf3](https://github.com/OpenIndiana/oi-userland/commit/3c0ecf366e0f5f1c40fb46e8aa9217af3b8ef07d))
- update to 3.8.4 ([9b8e95d](https://github.com/OpenIndiana/oi-userland/commit/9b8e95da090b2f4c5b5ed198d33f68d385b04bb7))
- update to 3.8.5 ([b5afbed](https://github.com/OpenIndiana/oi-userland/commit/b5afbed9cf49842c6ca5e99c353c14668d4cc90c))
- update to 3.8.6 ([50de0bf](https://github.com/OpenIndiana/oi-userland/commit/50de0bf590ce11d1acc6adcb482aa526645096fb))
- update to 3.8.7 ([fee8e58](https://github.com/OpenIndiana/oi-userland/commit/fee8e58a553be8c9e758827926fda458089b6d4b))

### libass

- rebuild after libunibreak update ([97bdf90](https://github.com/OpenIndiana/oi-userland/commit/97bdf901ed03c650c2e01da207a364f0bc24d17d))

### libcares

- update to 1.34.6 ([a91aa2a](https://github.com/OpenIndiana/oi-userland/commit/a91aa2ae6ed418916de90e57298e0c88424469a8))

### libcdio

- update to 2.2.0 - add SPARC support ([ab6ab95](https://github.com/OpenIndiana/oi-userland/commit/ab6ab951b6e3c9ded69ee04b7f9e44f130932653))
- update to 2.3.0 ([ee0d2c6](https://github.com/OpenIndiana/oi-userland/commit/ee0d2c6788509c523a5239d0500a3a802873fae2))

### libcupsfilters

- rebuild after poppler upgrade ([4892e03](https://github.com/OpenIndiana/oi-userland/commit/4892e03a445556370a658a1f9eff9bb0782c5013))

### libdatrie

- update to 0.2.14 ([9da4f80](https://github.com/OpenIndiana/oi-userland/commit/9da4f808c1d0ef00513f7600af7aedd8ee5f7639))

### libde265

- update to 1.0.18 ([8bb8ae8](https://github.com/OpenIndiana/oi-userland/commit/8bb8ae854aa391c80f258ad0dfb24bfcbe621c3a))

### libexpat

- update to 2.8.0 ([231b18e](https://github.com/OpenIndiana/oi-userland/commit/231b18e531695e80ea25c6a55eb90595bf4d401b))

### libfontenc

- update to 1.1.9 ([c8788af](https://github.com/OpenIndiana/oi-userland/commit/c8788afa1539b20ad9b84b483f46742c573e320b))

### libfreeimage

- rebuild after libraw upgrade ([b3eeee7](https://github.com/OpenIndiana/oi-userland/commit/b3eeee77592e9006dd3cb991b81fcd9015eeb8aa))

### libgcrypt

- update to 1.12.1 ([b4d2ef8](https://github.com/OpenIndiana/oi-userland/commit/b4d2ef800ae22ef195f4739c86d17d76c52d2a6f))
- update to 1.12.2 ([efb852f](https://github.com/OpenIndiana/oi-userland/commit/efb852febb41c48e73307cb8a06d8a414ce2cc1f))

### libgit2

- update to 1.9.2 ([d476041](https://github.com/OpenIndiana/oi-userland/commit/d476041fdb00c2e04e867e494f29ff8602a492fb))

### libgpg-error

- update to 1.58 ([24a7697](https://github.com/OpenIndiana/oi-userland/commit/24a7697571419d74da75cf397bf0ab1290968b46))
- update to 1.59 ([e06fdf5](https://github.com/OpenIndiana/oi-userland/commit/e06fdf586779f5cd702cf7b5174449c8944e116b))
- update to 1.60 ([f376909](https://github.com/OpenIndiana/oi-userland/commit/f3769097b8f4cf24bc14e7ac7de3b6e23334cb2d))

### libgsf

- update to 1.14.54 ([ec2970d](https://github.com/OpenIndiana/oi-userland/commit/ec2970dc7b15987c8c5278eed6b440ec7886174e))
- update to 1.14.55 ([7082765](https://github.com/OpenIndiana/oi-userland/commit/7082765dfaad834f55376574b29a5ea49d556b78))
- update to 1.14.56 ([ddd8cc5](https://github.com/OpenIndiana/oi-userland/commit/ddd8cc5a9216066a328a182300ea3777a494c16c))
- rebuild after libxml2 update ([e53ceeb](https://github.com/OpenIndiana/oi-userland/commit/e53ceeb4b409a00f894f2282bad30395e0a1f3d8))

### libid3tag

- update to 0.16.4 ([d9152c2](https://github.com/OpenIndiana/oi-userland/commit/d9152c23e1fb7fefde9308b3f937c7826224d8e6))

### libjpeg-turbo

- update to 3.1.3 ([874ab31](https://github.com/OpenIndiana/oi-userland/commit/874ab3154db5d14de2db8800568bcc5ca587d999))
- update to 3.1.4 ([2e7b29c](https://github.com/OpenIndiana/oi-userland/commit/2e7b29cbd6d346fe708525dda34ad55550d07a29))
- update to 3.1.4.1 ([0e977cc](https://github.com/OpenIndiana/oi-userland/commit/0e977cc890c0919f8bf9f9b936b77d6faa778e6c))

### libksba

- update to 1.6.8 ([748e789](https://github.com/OpenIndiana/oi-userland/commit/748e78968885977b82255d1417b908a5fd08e32a))

### libmateweather

- update to 1.28.2 ([07dad0c](https://github.com/OpenIndiana/oi-userland/commit/07dad0ca44f5df039a81e9d1cb68e692a512cbae))

### libmodbus

- update to 3.1.12 ([9f525c1](https://github.com/OpenIndiana/oi-userland/commit/9f525c161b9c77f91ef753828f9e48c728878650))

### libmtp

- update to 1.1.23 ([f807fa5](https://github.com/OpenIndiana/oi-userland/commit/f807fa5e8d5be026f99f1650c976daf727259ca7))

### libnotify

- update to 0.8.8 ([03c6ad6](https://github.com/OpenIndiana/oi-userland/commit/03c6ad60159467c5af15169bb1795d34fb899782))

### libopenjph

- update to 0.26.0 ([3f3775d](https://github.com/OpenIndiana/oi-userland/commit/3f3775de6a018aa54b8fdcd038d5494d9d3f4629))

### libpaper

- update to 2.2.7 ([58a7579](https://github.com/OpenIndiana/oi-userland/commit/58a7579bb2244fe7d7e96ddadf3e682280526d63))

### libpcap

- update to 1.10.6 ([16f45b0](https://github.com/OpenIndiana/oi-userland/commit/16f45b0654338dbea000efc8bfe666b12c00a261))

### libpng-1.6

- update to 1.6.53 ([0df84e4](https://github.com/OpenIndiana/oi-userland/commit/0df84e444182b5df63a35c2393342ffbc7f884b1))
- update to 1.6.57 ([c1e49d0](https://github.com/OpenIndiana/oi-userland/commit/c1e49d0f2884cb51751cfadd575b91c9820e4a33))

### libpng16

- update to 1.6.51 ([74bd25f](https://github.com/OpenIndiana/oi-userland/commit/74bd25ff0e226ac8e67fb02d00914ed7b4f9effa))
- update to 1.6.54 ([22e3105](https://github.com/OpenIndiana/oi-userland/commit/22e310591ccefdd505e557603645c50925dfaa31))
- update to 1.6.55 ([49d3797](https://github.com/OpenIndiana/oi-userland/commit/49d3797166f89b733a39caaa0909cde98ddda54e))
- update to 1.6.56 ([6d8c03a](https://github.com/OpenIndiana/oi-userland/commit/6d8c03a41a649d359c92f9cdabc9a8bb1a1f859a))
- update to 1.6.58 ([05aa977](https://github.com/OpenIndiana/oi-userland/commit/05aa9779c6ff10ac885bc1c312db9d194c7b8cb8))

### libpqxx

- update to 7.10.3 ([04c2511](https://github.com/OpenIndiana/oi-userland/commit/04c2511b607a60b57980a7ff4fee353d43cf5aec))

### library/objfw

- update to 1.4.3 ([11efcc6](https://github.com/OpenIndiana/oi-userland/commit/11efcc6d4caec55c0e5250fc62139771969cee5b))
- update to 1.4.4 ([a5ecee4](https://github.com/OpenIndiana/oi-userland/commit/a5ecee4bb0b3642f17d24aa24b7f6c7b2dc5bcfe))
- update to 1.5.1 ([ff6525f](https://github.com/OpenIndiana/oi-userland/commit/ff6525f535e5d05d698f9e6a1ad292759fc7296b))

### libraw

- update to 0.21.5 ([0805c8a](https://github.com/OpenIndiana/oi-userland/commit/0805c8a25d0be4b9f1bf3cde1c7fe12e85e8fee5))
- update to 0.22.0 ([8a0fe87](https://github.com/OpenIndiana/oi-userland/commit/8a0fe87609f8588208627939313917ac0a02b5c5))
- update to 0.22.1 ([43157a8](https://github.com/OpenIndiana/oi-userland/commit/43157a8b3b95c0fc269365022059e82042f7217e))

### librecad

- update to 2.2.1.3 ([fd2cd3c](https://github.com/OpenIndiana/oi-userland/commit/fd2cd3c093bffc3185e57fd88e5c7c0d3bd34392))
- update to 2.2.1.4 ([367a4f4](https://github.com/OpenIndiana/oi-userland/commit/367a4f403ae5c228854726352ca014c6ed3d100e))

### libreoffice

- update to 25.8.3.1 ([3dbe2ad](https://github.com/OpenIndiana/oi-userland/commit/3dbe2ad3c4664a5b6f8a7c336d97ec78300da564))
- update to 25.8.3.2 ([399eb3a](https://github.com/OpenIndiana/oi-userland/commit/399eb3a48dc97e295a56bac8d18b347c8163c853))
- update to 25.8.4.1 ([ea5c366](https://github.com/OpenIndiana/oi-userland/commit/ea5c366b4f51ebf025bca29b82f79106c1abbbbc))
- update to 25.8.4.2 ([94aa23d](https://github.com/OpenIndiana/oi-userland/commit/94aa23dbed933a136fca5445498e0c3c84df6c53))
- update to 26.2.0.3 ([6de25d2](https://github.com/OpenIndiana/oi-userland/commit/6de25d21ee1cfefbce2787c82eda8dc8fc606d01))
- fix moc-qt6 check ([6380726](https://github.com/OpenIndiana/oi-userland/commit/638072695e460caffc03f0baaec1d9945f4d39bc))
- update to 26.2.1.1 ([30425f3](https://github.com/OpenIndiana/oi-userland/commit/30425f3529b35127850c2cb28440f38122fc56cc))
- rebuild after qt6 upgrade ([9d963e5](https://github.com/OpenIndiana/oi-userland/commit/9d963e5061b99a308fe68d4e8cbdf02f27a43d28))
- add poppler 26.02 support ([d0e9b33](https://github.com/OpenIndiana/oi-userland/commit/d0e9b33f4a8605ddbc1a202447e21a8e8c7ad67b))
- update to 26.2.1.2 ([324901d](https://github.com/OpenIndiana/oi-userland/commit/324901d0f3804e4d0e2c7170c201630a23fecc9e))
- update to 26.2.2.1 ([1442bc4](https://github.com/OpenIndiana/oi-userland/commit/1442bc4a28aba9b5b3f8535678c0774180b888db))
- update to 26.2.2.2 ([3d3e0e5](https://github.com/OpenIndiana/oi-userland/commit/3d3e0e5d8615901e604e134f6ad2c046f602beb4))
- update to libreoffice-26.2.3.1 ([83c83a5](https://github.com/OpenIndiana/oi-userland/commit/83c83a5bb24a8c83988d9f81fa3799bb6d37a480))
- update to 26.2.3.2 ([a62f4c9](https://github.com/OpenIndiana/oi-userland/commit/a62f4c91c3d9fb44a641e940e6ae0f41f51d2979))

### librewolf

- update to 146.0.1-1 ([faf717d](https://github.com/OpenIndiana/oi-userland/commit/faf717d09de1c0fd944bb3bb7309435a50fcdab3))
- update 147.0.4 ([d34195f](https://github.com/OpenIndiana/oi-userland/commit/d34195fefc79e8fd198da63d2b298793d5069c69))
- update to 149.0.2-2 ([59cb83e](https://github.com/OpenIndiana/oi-userland/commit/59cb83e22cb15a8319648775188ab5b16e31dfbb))

### librsvg

- update to version 2.61.3 ([e12ca37](https://github.com/OpenIndiana/oi-userland/commit/e12ca37edeccb2f4581a23e3ec2c4db0238c2df7))
- add librsvg-2.0.pc ([6ad8de4](https://github.com/OpenIndiana/oi-userland/commit/6ad8de47cd965e1be2ee3328e9cb0e87ab8a816f))
- readd gdk-pixbufloader, minor update 2.61.4 ([ee8dc53](https://github.com/OpenIndiana/oi-userland/commit/ee8dc53966d2b57d60be6fecb80e85ae4bf8f389))

### libsamplerate

- fix dependencies - recomile using gcc-14 ([2768a55](https://github.com/OpenIndiana/oi-userland/commit/2768a55dd9989d066469b2bfb460d5f4d9d45cea))

### libsmbclient

- update to version 4.23.3 ([3823c60](https://github.com/OpenIndiana/oi-userland/commit/3823c6049aae562864ec8810bf8f74dc28e94604))
- update to version 4.23.4 ([2045e89](https://github.com/OpenIndiana/oi-userland/commit/2045e89ce1ac6f41ca6685472982fb41ed4daefb))
- update to version 4.23.5 ([203cbbe](https://github.com/OpenIndiana/oi-userland/commit/203cbbedca0a72c47c19c2231771b2780fa2a640))
- fix modes for libexec files ([6e7bc45](https://github.com/OpenIndiana/oi-userland/commit/6e7bc45ec9772798b123859c266ad4df4711af6c))
- update to version 4.23.6 ([af9c302](https://github.com/OpenIndiana/oi-userland/commit/af9c3029574e43b2b0717dc4f8f759653b5288dc))
- update to version 4.24.0 ([2aadc5e](https://github.com/OpenIndiana/oi-userland/commit/2aadc5e14b134c6eea5efc96e7c2137153191d7e))

### libsodium

- update to 1.0.21 ([a0bd6ff](https://github.com/OpenIndiana/oi-userland/commit/a0bd6ff2b00f1bdd3cbe23526d986288fa6833fe))
- update to 1.0.22 ([79038e3](https://github.com/OpenIndiana/oi-userland/commit/79038e348aeabc4df24b62619587cf767b3f16fc))

### libsoup3

- fix CVE-2025-12105 ([2f414d2](https://github.com/OpenIndiana/oi-userland/commit/2f414d2412813e7e7161ab921f5286958c232fc9))
- fix CVE-2025-11021 ([9cc39ca](https://github.com/OpenIndiana/oi-userland/commit/9cc39cab59d7a46a819a66c6ea2cdb51c4392221))
- Fix CVE-2025-14523 and CVE-2026-0719 ([23791dd](https://github.com/OpenIndiana/oi-userland/commit/23791dd6298d7054d0af6366d494c14881df01e6))

### libtasn1

- update to 4.21.0 ([866f2a7](https://github.com/OpenIndiana/oi-userland/commit/866f2a76ab3b9ddee23c85e1448dc66e0ce93483))

### libunibreak

- update to 7.0 ([70bd6e8](https://github.com/OpenIndiana/oi-userland/commit/70bd6e8528b1fb9d1948f31e2e710717d3bdf0a4))

### libunistring

- update to 1.4.2 ([1fbc76c](https://github.com/OpenIndiana/oi-userland/commit/1fbc76c525bf63e0f133e3e9450f75a9e5f7783a))

### libupnp

- update to 1.4.30 ([5799373](https://github.com/OpenIndiana/oi-userland/commit/5799373e4417e7c1851a46e841a2daf0ca1feeff))

### liburcu

- new package (prerequisite for latest bind version) ([e382261](https://github.com/OpenIndiana/oi-userland/commit/e382261c8d86e7586f229e9ac8188f9447268377))

### libvpx

- update to 1.16.0 ([9808538](https://github.com/OpenIndiana/oi-userland/commit/980853852667c7067df4ae4d33888ff0737dd78d))

### libx11

- update to 1.8.13 ([d8fd582](https://github.com/OpenIndiana/oi-userland/commit/d8fd58292119eb3d4f96e805109cf255200f9c8d))

### libxext

- update to 1.3.7 ([ef1d7dd](https://github.com/OpenIndiana/oi-userland/commit/ef1d7dd69d8a041f0d6a8e41de4040322c54f05e))

### libxkbcommon

- update to 1.13.1 ([14545b6](https://github.com/OpenIndiana/oi-userland/commit/14545b62a8d3b8ae91522525a8cae5b720c8cf15))

### libxkbfile

- update to 1.2.0 ([450db8c](https://github.com/OpenIndiana/oi-userland/commit/450db8ced8f4b0981a14d325aa723b4768dd9ec4))

### libxml2

- update to version 2.15.2 ([ecd924d](https://github.com/OpenIndiana/oi-userland/commit/ecd924dd9603365771b3325958f542637ea6cb45))
- update to version 2.15.2 (incl. fix) ([f9522ef](https://github.com/OpenIndiana/oi-userland/commit/f9522ef94fc733126472ad1a1172308c51ae4ea5))
- added missing libxml2.la file ([77e7020](https://github.com/OpenIndiana/oi-userland/commit/77e7020b9cd56529ab3016f20f5ccb01e9a72f3b))
- update to version 2.15.3 ([e141785](https://github.com/OpenIndiana/oi-userland/commit/e141785712c6c75a4be47bedfefb105e43bacf76))

### libxmlb

- update to 0.3.25 ([db68401](https://github.com/OpenIndiana/oi-userland/commit/db6840163d1fb308a685f125549c0501e1000ab0))
- update to 0.3.26 ([995f235](https://github.com/OpenIndiana/oi-userland/commit/995f2358cd0cb6a3abe75d77af4a4cb08a358faf))

### libxmu

- update to 1.3.1 ([63ccaf3](https://github.com/OpenIndiana/oi-userland/commit/63ccaf3f10751067ba322328f3a8800b94e28105))

### libxpm

- update to 3.5.19 ([23a5adc](https://github.com/OpenIndiana/oi-userland/commit/23a5adc7d36612e5bd07248b064bef723e80f047))

### libxslt

- update to 1.1.45 ([1428118](https://github.com/OpenIndiana/oi-userland/commit/1428118c16da9e5b879059f7afc46ee1afcf68e5))

### libxxf86vm

- update to 1.1.7 ([7d19c77](https://github.com/OpenIndiana/oi-userland/commit/7d19c77aff3a2d2d4f18ccc2325ebc9e8e99eab5))

### listres

- update to 1.0.7 ([6298eb6](https://github.com/OpenIndiana/oi-userland/commit/6298eb63fdb4e7043fb069cffa26b65b4e727788))

### lldpd

- update to 1.0.18 ([a2415ad](https://github.com/OpenIndiana/oi-userland/commit/a2415ad37a622acba03d5349bfceb53b055fdedc))

### lmdb

- update to 0.9.35 ([349735b](https://github.com/OpenIndiana/oi-userland/commit/349735bf0351616faeeea54f9580646df618fcbb))

### lmdbxx

- rebuild after lmdb upgrade ([0d29760](https://github.com/OpenIndiana/oi-userland/commit/0d29760f91e46217b6e2ec3a1b64c4b6e4641e0f))

### luanti

- update to 5.14.0 ([493b196](https://github.com/OpenIndiana/oi-userland/commit/493b196ab4da8db890afc35c907e01a1e035d720))
- update to 5.15.1 ([26924fe](https://github.com/OpenIndiana/oi-userland/commit/26924fee8ad1d51261cf5d06b9acabb4b1fb982c))
- update to 5.15.2 ([7a5c0bc](https://github.com/OpenIndiana/oi-userland/commit/7a5c0bce4b232681ccc9fd065aeddb1dafeb76f7))

### lzip

- update to 1.26 ([015d88c](https://github.com/OpenIndiana/oi-userland/commit/015d88c444a3de4b44653866364b98eebd1cc6cf))

### lzlib

- update to 1.16 ([a5c8cbb](https://github.com/OpenIndiana/oi-userland/commit/a5c8cbb05e46dbe738821e12162aff69ee0c17ed))

### m17n-db

- update to 1.8.11 ([3288b10](https://github.com/OpenIndiana/oi-userland/commit/3288b10675fa20a1ee39d6bddc965176dd14e03c))

### m4

- update to 1.4.21 ([93d052b](https://github.com/OpenIndiana/oi-userland/commit/93d052bec22bc9c903a8deccd488ab6ccf9204a7))

### mailutils

- update to 3.21 ([27731b9](https://github.com/OpenIndiana/oi-userland/commit/27731b9f4333a6e253090d93b1ae46c9b60fb318))

### make-rules

- support for patching Cargo vendored sources ([25f1752](https://github.com/OpenIndiana/oi-userland/commit/25f17529f7aa118c390d6b59186418e73ca40dba))
- convert pkg build style to use common-rules.mk ([823c796](https://github.com/OpenIndiana/oi-userland/commit/823c796d486991a6d9a83cd6fbc345967b46ad09))
- python-requires should consult proto dir while evaluating stdin ([dff157c](https://github.com/OpenIndiana/oi-userland/commit/dff157cf61a235e97aa96a9aa1ab8ace3189cfa0))
- remove duplicate -f from $(RM) calls ([c1348e4](https://github.com/OpenIndiana/oi-userland/commit/c1348e4cb60323a9b8e2f3af5af55c3f618d64d9))

### marco

- update to 1.28.2 ([2fb9cfd](https://github.com/OpenIndiana/oi-userland/commit/2fb9cfdbcd251dba78b9f544c138d3ab0ca8a7a2))

### mariadb114

- update to version 11.4.9 ([7182a89](https://github.com/OpenIndiana/oi-userland/commit/7182a8901a085fd45f2b784886ed1914d946348f))
- update to version 11.4.10 ([3391434](https://github.com/OpenIndiana/oi-userland/commit/33914340318aa10cd89fd79f2f776a9a004c448a))

### mate-menus

- update to 1.28.1 ([f722dbf](https://github.com/OpenIndiana/oi-userland/commit/f722dbfd525f1f1a4ef8a41dd21c1256cd5d3395))

### mate-notification-daemon

- update to 1.28.5 ([c21043c](https://github.com/OpenIndiana/oi-userland/commit/c21043c5d930b47d69b8696e239edf256b1ea369))

### mate-panel

- update to 1.28.7 ([873a551](https://github.com/OpenIndiana/oi-userland/commit/873a551de670a8c3bc4614198ff5dc57bc3029f9))

### mate-terminal

- update to 1.28.3 ([b0cf87f](https://github.com/OpenIndiana/oi-userland/commit/b0cf87fe2676f9c588b970a3565e4d0916e5d75f))

### mate.mk

- update archive url ([1f5bf83](https://github.com/OpenIndiana/oi-userland/commit/1f5bf8379d55e07b68e43ec20d476177684c5181))

### maven

- update to 3.9.12 ([c96c23f](https://github.com/OpenIndiana/oi-userland/commit/c96c23f1285f316a7607a1db6990cf53ec54068d))
- update to 3.9.13 ([65eb7e7](https://github.com/OpenIndiana/oi-userland/commit/65eb7e711f9c5e5b1b5706027c6497825f4a27d2))
- update to 3.9.14 ([1fde871](https://github.com/OpenIndiana/oi-userland/commit/1fde871fe71aced5d9528cca33e55acba2f04b43))

### maxima

- update to 5.49.0 ([1047cc2](https://github.com/OpenIndiana/oi-userland/commit/1047cc230ce21463e77a19a64e41e1c7ade422b9))

### meson

- rebuild to provide 3.14 version ([98fae1c](https://github.com/OpenIndiana/oi-userland/commit/98fae1c455a4f4f08f0ec914e0ebedd0f3789371))

### meson.mk

- do not depend on python mediator ([73a42a3](https://github.com/OpenIndiana/oi-userland/commit/73a42a33a5622eb680e649dcc99b832729924dbb))

### mona-sans

- update to 2.0.8 ([ba08557](https://github.com/OpenIndiana/oi-userland/commit/ba0855708d2ffd970a333d82f244dd6580ca1fe9))

### mozilla-nspr

- update to 4.38.2 ([6ac0bd6](https://github.com/OpenIndiana/oi-userland/commit/6ac0bd68f3e0a772ec88deac34bd089500b15e9a))

### mpg123

- update to 1.33.4 ([f8a53bd](https://github.com/OpenIndiana/oi-userland/commit/f8a53bd306b9fc5f6c56d186e35cba379cecd6ac))
- update to 1.33.5 ([d46fd1a](https://github.com/OpenIndiana/oi-userland/commit/d46fd1a5251cab9dd9cf600867685f06f4e83c1d))

### mutt

- update to 2.2.16 ([26d2a47](https://github.com/OpenIndiana/oi-userland/commit/26d2a47e7d6048e2c8f739e885b2844d1525534d))
- update to 2.3.0 ([6ed0da9](https://github.com/OpenIndiana/oi-userland/commit/6ed0da911901939bf1f68142e31e24e235bc02ff))
- update to 2.3.1 ([9c7ae2b](https://github.com/OpenIndiana/oi-userland/commit/9c7ae2b234b574a8de335fd36b8a5e00bae78c28))
- update to 2.3.2 ([ff1770e](https://github.com/OpenIndiana/oi-userland/commit/ff1770e812582dbee0c6b29858f82be59de16c76))

### mypaint-brushes

- update to 2.0.2 ([6437afd](https://github.com/OpenIndiana/oi-userland/commit/6437afdb2dc7e9395285bac8f263f516e50416d5))

### nano

- update to 8.7 ([62f0340](https://github.com/OpenIndiana/oi-userland/commit/62f0340ec664c5a6e045581e52f62d36f97a1529))
- update to 8.7.1 ([7b4a15b](https://github.com/OpenIndiana/oi-userland/commit/7b4a15b77563ffd411524c425e4188317215f9e8))
- update to 9.0 ([1bfa686](https://github.com/OpenIndiana/oi-userland/commit/1bfa6868d4b608af90ad0aa1a97d1edb3de8adbe))

### netbeans

- update to 28 ([a61b5f0](https://github.com/OpenIndiana/oi-userland/commit/a61b5f051fb6e693da166179502f8e6d1f60230e))
- add SPARC support ([858f669](https://github.com/OpenIndiana/oi-userland/commit/858f669cce87d12fcbfd92eafc878112c718c2c4))
- update to 29 ([17846b9](https://github.com/OpenIndiana/oi-userland/commit/17846b95231f1465df68fc565d6d4d357a8c218d))
- re-add SPARC support ([b9c0a2a](https://github.com/OpenIndiana/oi-userland/commit/b9c0a2a28a13b0eba30405e6da00a50dff0a814f))
- fix arch support; re-add missing x86 binaries ([eaedf69](https://github.com/OpenIndiana/oi-userland/commit/eaedf698a63926c49b4094adc299d45991ab0ccf))

### nghttp2

- update to 1.68.1 ([06f0c7d](https://github.com/OpenIndiana/oi-userland/commit/06f0c7dd61035ed049c6ec996267deaf67ba9ed3))
- update to 1.69.0 ([7ce5f84](https://github.com/OpenIndiana/oi-userland/commit/7ce5f847520a1f35865fca2856007b3d9e21b0b2))

### nghttp3

- update to 1.13.0 ([ff9f401](https://github.com/OpenIndiana/oi-userland/commit/ff9f401163b2ebcac4cda055861572db0efe7034))
- update to 1.13.1 ([764dd1b](https://github.com/OpenIndiana/oi-userland/commit/764dd1ba983e57f822ada924009d458c7c1ba063))
- update to 1.14.0 ([6639c1f](https://github.com/OpenIndiana/oi-userland/commit/6639c1f5218842cd9a231353fba879d8bd0052c3))
- update to 1.15.0 ([9bf6bdd](https://github.com/OpenIndiana/oi-userland/commit/9bf6bdd7ca42127bb5e488cb20ab5de474e72737))

### ngtcp2

- update to 1.18.0 ([dc86a50](https://github.com/OpenIndiana/oi-userland/commit/dc86a50624d9330b59330211f13b33a3dc13b878))
- update to 1.19.0 ([af1909d](https://github.com/OpenIndiana/oi-userland/commit/af1909dcaaa227f8fd0bef19c76917467a6a1da6))
- update to 1.20.0 ([96eb830](https://github.com/OpenIndiana/oi-userland/commit/96eb8304950bb7dce0627f0970f9f748812afd7e))
- update to 1.21.0 ([3582de3](https://github.com/OpenIndiana/oi-userland/commit/3582de3ce234735b1ad333c888d51b2a8077e148))
- update to 1.22.0 ([05d6225](https://github.com/OpenIndiana/oi-userland/commit/05d62254b5f961ffe0a54a3011183b37ed2ab356))
- update to 1.22.1 ([163db42](https://github.com/OpenIndiana/oi-userland/commit/163db428c132dc53d661aeccb98b33c8737852e5))

### ninja

- update to 1.13.2 ([0ed6211](https://github.com/OpenIndiana/oi-userland/commit/0ed6211a23838a55792019766d897e4d266f20ca))

### nodejs-20

- update to 20.19.6 ([05dffa2](https://github.com/OpenIndiana/oi-userland/commit/05dffa21710a4d83900a4c127268f821d62b3c0c))
- update to 20.20.0 ([1a0e4f2](https://github.com/OpenIndiana/oi-userland/commit/1a0e4f20ef508a95a63f65c4ae6c445999a312cd))

### nodejs-22

- update to 22.21.0 ([1ec3b0f](https://github.com/OpenIndiana/oi-userland/commit/1ec3b0feb5f7b960d9516a978cc6018c86616a37))
- update to 22.21.1 ([3c47674](https://github.com/OpenIndiana/oi-userland/commit/3c47674cfb5d3722001bb4c465e70b3ff3103f80))
- update to 22.22.0 ([1e1d6b3](https://github.com/OpenIndiana/oi-userland/commit/1e1d6b3857c95c8765f7877c44e9ed8470c4f556))
- update to 22.22.2 ([438c708](https://github.com/OpenIndiana/oi-userland/commit/438c708a39370b0cc29c617bd7a751851b492336))

### nodejs-24

- update to 24.11.0 ([77ad059](https://github.com/OpenIndiana/oi-userland/commit/77ad059dc29bd4e588c7c96d7fab1275d493bd6e))
- update to 24.11.1 ([296bab4](https://github.com/OpenIndiana/oi-userland/commit/296bab40cb77b98fc4c0137a3e471535a416df29))
- update to 24.12.0 ([cc51dcf](https://github.com/OpenIndiana/oi-userland/commit/cc51dcf53decd0e6ec0200d6ca29416040467b62))
- update to 24.13.0 ([aa24f7d](https://github.com/OpenIndiana/oi-userland/commit/aa24f7d331de226ec6a420ca1be57e9fc4eb6738))
- update to 24.13.1 ([5485656](https://github.com/OpenIndiana/oi-userland/commit/5485656fccb43e58593892c4930b72af4caa15be))
- update to 24.14.0 ([4a74e3a](https://github.com/OpenIndiana/oi-userland/commit/4a74e3a3aaff9650756f448e1de83544ed017795))
- update to 24.14.1 ([febba9e](https://github.com/OpenIndiana/oi-userland/commit/febba9e066494c4fea635c234565942a5523482c))
- update to 24.15.0 ([2b41b13](https://github.com/OpenIndiana/oi-userland/commit/2b41b13444188ae4746643242747422f0863742e))

### nspr

- update to 4.38 ([b84d8a0](https://github.com/OpenIndiana/oi-userland/commit/b84d8a0f6eecc9ddc5ef600144cdedf2e2a821dc))

### ntp

- re-add SPARC support ([09f8c5c](https://github.com/OpenIndiana/oi-userland/commit/09f8c5cf22c1ae9990c1bd857b75b86fa1a8ef31))

### nvidia

- update to 580.105.08 ([a374acc](https://github.com/OpenIndiana/oi-userland/commit/a374acc525005a617ae37c810c8a150b2cdf8843))
- update to 580.119.02 ([be713a0](https://github.com/OpenIndiana/oi-userland/commit/be713a0c32d2b09dde31af776e5422d108239674))
- update to 580.126.09 ([040ff77](https://github.com/OpenIndiana/oi-userland/commit/040ff773b13310ca39a38cc44a40845add57b611))
- update to 580.126.18 ([e661bc8](https://github.com/OpenIndiana/oi-userland/commit/e661bc8a6558319f6e6ccc04979c9a6491c8ac7d))
- update to 580.142 ([4ea6635](https://github.com/OpenIndiana/oi-userland/commit/4ea6635dd0dbede7b056ce065b9227866112978f))
- update to 595.58.03, drop 32 bit libraries; keep R580 as nvidia-580 ([760f0f0](https://github.com/OpenIndiana/oi-userland/commit/760f0f0bfb0cb8bb76d5ce0fcee42b5781b57862))
- update to 595.71.05 ([7b4edec](https://github.com/OpenIndiana/oi-userland/commit/7b4edec140cb45afc8ca7df62f8f943e4503ce1c))

### nvidia-535

- update to 535.274.02 ([14dcc8a](https://github.com/OpenIndiana/oi-userland/commit/14dcc8a1f73c7184b7c9d2ce886fe264c9498bc5))
- update to 535.288.01 ([8cb898f](https://github.com/OpenIndiana/oi-userland/commit/8cb898f601fd0a022b542716d4cd831cc96257ae))
- update to 535.309.01 ([7f05f2b](https://github.com/OpenIndiana/oi-userland/commit/7f05f2b7098fe29b862d2e879316b755e78c1271))

### nvidia-580

- update to 580.159.03 ([aa017b4](https://github.com/OpenIndiana/oi-userland/commit/aa017b44138344662823b1682a34e7b885577966))

### ocaml

- update to 5.4.1 ([8ba405f](https://github.com/OpenIndiana/oi-userland/commit/8ba405fffbcb65e019ca36be313f3511a2094a7e))

### ogl-select

- drop 32 bit support ([17a5d2a](https://github.com/OpenIndiana/oi-userland/commit/17a5d2aa62039530b44865c18a60a1e2d881c176))

### openblas

- add SPARC support ([fba9722](https://github.com/OpenIndiana/oi-userland/commit/fba9722a3db6305808a553f52b88496e05fe8117))
- fix tests dblat1 and xdcblat1 on SPARC ([89a5098](https://github.com/OpenIndiana/oi-userland/commit/89a5098eb33696e882bb11fc35196a85015f19a0))
- update to 0.3.31 ([2d54070](https://github.com/OpenIndiana/oi-userland/commit/2d54070ce58d74df44d59140049b43900da5c37e))
- update to 0.3.32 ([db2e98a](https://github.com/OpenIndiana/oi-userland/commit/db2e98a288e0a008fd1bb2d07ddba6189baa54a4))

### opencolorio

- update to 2.5.1 ([9a92e0c](https://github.com/OpenIndiana/oi-userland/commit/9a92e0c23d399a0c1a7ec7684d4df9850733c729))

### opendkim

- rebuild after lmdb upgrade ([050bfc2](https://github.com/OpenIndiana/oi-userland/commit/050bfc2c4e266e38cf0bfb29dbee6f1568571812))

### openexr

- update to 3.4.3 ([1295c73](https://github.com/OpenIndiana/oi-userland/commit/1295c7386e33c179d104bc3c27f49aa536405f2d))
- update to 3.4.4 ([6a209d2](https://github.com/OpenIndiana/oi-userland/commit/6a209d2f376ce4181ea1c5ccf8b4011d68f3ce57))
- update to 3.4.5 ([b635679](https://github.com/OpenIndiana/oi-userland/commit/b63567964f33056a5398342baa25ad5931b47616))
- update to 3.4.6 ([d8afa7a](https://github.com/OpenIndiana/oi-userland/commit/d8afa7a20d377c306786f1158269c6aefea788e9))
- update to 3.4.7 ([61efd72](https://github.com/OpenIndiana/oi-userland/commit/61efd729d3a1dfcf5cfbfcef9befbdbbc374aef9))
- update to 3.4.8 ([470afdd](https://github.com/OpenIndiana/oi-userland/commit/470afdd4f3a55d4361d55eaa86cdd7a84ab75f83))
- update to 3.4.9 ([63588b6](https://github.com/OpenIndiana/oi-userland/commit/63588b66ce557419ec24d84eda9933822dc40450))
- update to 3.4.10 ([20afa59](https://github.com/OpenIndiana/oi-userland/commit/20afa591459830477df407b1fa1febb2c7e0df72))
- update to 3.4.11 ([a23e5bc](https://github.com/OpenIndiana/oi-userland/commit/a23e5bc45e9d48001d14677568b5d4339f66136d))

### openjdk-17

- update to 17.0.17-ga, eliminate GNU linker usage, add SPARC support ([b579376](https://github.com/OpenIndiana/oi-userland/commit/b5793768664eafcd3fe8ae281a883cb3d7d79682))

### openjph

- update to 0.24.3 ([7020d4c](https://github.com/OpenIndiana/oi-userland/commit/7020d4cbf637bb9a2b1b7e15b15cf1a8035197b1))
- update to 0.24.4 ([b24ff91](https://github.com/OpenIndiana/oi-userland/commit/b24ff912cd31a3a6a630af3d1f93c37ef3079c2c))
- update to 0.25.0 ([90a37da](https://github.com/OpenIndiana/oi-userland/commit/90a37dac6091d71c27a4d5087d56b899bc6fb767))
- update to 0.25.2 ([0d41799](https://github.com/OpenIndiana/oi-userland/commit/0d417997950048d75062fb0648724afdff036ec1))
- update to 0.25.3 ([2a1bea1](https://github.com/OpenIndiana/oi-userland/commit/2a1bea1b4df900c5efeca7bf93abfdb9a8dc106d))
- update to 0.26.3 ([5afcf69](https://github.com/OpenIndiana/oi-userland/commit/5afcf698352abb70b0696aabfefee9dac5bbf847))
- update to 0.27.0 ([15473d5](https://github.com/OpenIndiana/oi-userland/commit/15473d5546cc8cf2781e120f07839c5f63961bfc))

### openldap

- multiple ldap server usability fixes ([eebcff1](https://github.com/OpenIndiana/oi-userland/commit/eebcff149772303862e311aa476bea8e178c7d37))
- update to 2.6.12 ([6375b9b](https://github.com/OpenIndiana/oi-userland/commit/6375b9bf34634427aafd359d69554a662f34620e))
- update to 2.6.13 ([87119f9](https://github.com/OpenIndiana/oi-userland/commit/87119f9b95a004cdd19fa45e2af65ac0a69947d3))

### openscenegraph

- rebuild after poppler upgrade ([c9cffe7](https://github.com/OpenIndiana/oi-userland/commit/c9cffe78f5d103efb5351b9d0359526899cf1291))

### opensmalltalk

- update to VMMaker.oscog-eem.3738 image 23641 ([238b45f](https://github.com/OpenIndiana/oi-userland/commit/238b45fa2bfb4512c1da0f3f1e3789446256a116))
- upgrade to VMMaker.oscog-eem.3738 image 23641 ([fe85e80](https://github.com/OpenIndiana/oi-userland/commit/fe85e80d48ac5151fc1f9533e0cc70c4a49611cd))

### openssh

- update to 10.2p1. See openssh release notes for ssh-agent path change ([3399fc6](https://github.com/OpenIndiana/oi-userland/commit/3399fc6de2ad229a954242cc4701743d2c417370))
- fix login auditing ([a00a0cd](https://github.com/OpenIndiana/oi-userland/commit/a00a0cd056d095d468e9e0a5fd7bac7b9ec3b62f))
- update to 10.3p1 ([4e099d1](https://github.com/OpenIndiana/oi-userland/commit/4e099d1fa097cd5495238e2d28bdadef24f0fa24))

### openssl-1.0.2

- add patches for CVE-2026-28388, 28389, and 28390 (imported from OmniOS) ([39b5e87](https://github.com/OpenIndiana/oi-userland/commit/39b5e8755e0efdc93bda61b2438dfa3721cd7277))

### openssl-1.1

- add patches for CVE-2026-28387, 28388, 28389, and 28390 (imported from OmniOS) ([03e04fa](https://github.com/OpenIndiana/oi-userland/commit/03e04fa00bd4a7501d15e2f7795d8f92ab8f259c))

### openssl-3

- update to 3.5.5 ([90717ff](https://github.com/OpenIndiana/oi-userland/commit/90717ff3206315fce8f35f3b0e6705ed82eabb47))
- update to 3.5.6 ([076365e](https://github.com/OpenIndiana/oi-userland/commit/076365ea2411b2412b9c2d94afb01ee34a42a1d9))

### openvpn

- update to 2.6.16 ([6b56a19](https://github.com/OpenIndiana/oi-userland/commit/6b56a1936bc821ded60ebd68eddaa95f7f71ff29))
- update to 2.6.17 ([0301572](https://github.com/OpenIndiana/oi-userland/commit/030157272244fe65655692be1c5ad884eb1e9368))
- update to 2.6.19 ([872e528](https://github.com/OpenIndiana/oi-userland/commit/872e5282a4f2eb4231895df039e43b6570dd212e))

### opus

- update to 1.6 ([6a94983](https://github.com/OpenIndiana/oi-userland/commit/6a94983eebb8744ad440830cabcc9e45eb3fe119))
- update to 1.6.1 ([0fa573c](https://github.com/OpenIndiana/oi-userland/commit/0fa573c76717f84c4edb4495c949a38dace0919a))

### orc

- update to 0.4.42 ([9119f19](https://github.com/OpenIndiana/oi-userland/commit/9119f191f12e90a89fe6de93c378a1314a075894))

### p11-kit

- update to 0.26.1 ([442a2bc](https://github.com/OpenIndiana/oi-userland/commit/442a2bc6bf38fc521d2bc6881cf9e62a356a34f5))

### pango

- update to 1.57.1 ([86c7e15](https://github.com/OpenIndiana/oi-userland/commit/86c7e15edb7f2d3ffddb41b6325be3352ee61b96))

### pari

- update to 2.17.3 ([2f7874d](https://github.com/OpenIndiana/oi-userland/commit/2f7874d7d88fb076b434338ca3fd9edc60719a48))

### pari-elldata

- Fix COMPONENT_NAME to fix re-publishing ([bdf5e03](https://github.com/OpenIndiana/oi-userland/commit/bdf5e03ac1c03347c70c228dc1dd661af60d52d0))

### pcre2

- enable jit ([ee1909f](https://github.com/OpenIndiana/oi-userland/commit/ee1909f2e0f494e128e4d61475ff7ed7e30def71))
- enable jit option only for none SPARC systems ([6b91646](https://github.com/OpenIndiana/oi-userland/commit/6b916460d9c63d11b986e674c474db6f54cab98f))

### pgbadger

- update to 13.2 ([b4ac33c](https://github.com/OpenIndiana/oi-userland/commit/b4ac33ce8f923fb48905980e2391261c696a9f25))

### pgpool-II

- update to 4.6.4 ([dbaff13](https://github.com/OpenIndiana/oi-userland/commit/dbaff13eb6bbf0ba0de576aff8f1b7a15556a693))

### php-8_5

- add pkg5 file ([db75ab1](https://github.com/OpenIndiana/oi-userland/commit/db75ab1d4e466c0619e4fd67b8fac17e1f8d5171))
- update to 8.5.3 ([01c267b](https://github.com/OpenIndiana/oi-userland/commit/01c267bcdaf3652a02c3842fd47a13b25ad96a69))
- update to 8.5.4 ([2fe18c5](https://github.com/OpenIndiana/oi-userland/commit/2fe18c596f7af559c22bda9aa7ddf2ddfeadf6f7))
- update to 8.5.5 ([eb9b1d5](https://github.com/OpenIndiana/oi-userland/commit/eb9b1d56bfecc5ab1e4ee99ecd47b6bf0b7ae40b))

### php83

- update to version 8.3.28 ([0890b97](https://github.com/OpenIndiana/oi-userland/commit/0890b97d64e93ba95fff188ce2675cc14c406bee))
- update to version 8.3.29 ([6b17307](https://github.com/OpenIndiana/oi-userland/commit/6b17307c1676595af34cea4f3405e35c5dbdbe1e))
- mongodb update to version 2.1.4 ([a382f7c](https://github.com/OpenIndiana/oi-userland/commit/a382f7c21be2cf97ba07e690fafb0ef6f0ed8390))
- memcached update to version 3.4.0 ([6fb6a70](https://github.com/OpenIndiana/oi-userland/commit/6fb6a70896595727829d1500c438dcbe6a42e3aa))
- apcu update to version 5.1.28 ([10fd451](https://github.com/OpenIndiana/oi-userland/commit/10fd451ceb0eedaa45f803e6d071475256092995))
- imagick update to version 3.8.1 ([ed141d3](https://github.com/OpenIndiana/oi-userland/commit/ed141d36d1c8b59c84f57fa6ee233c26423e9223))
- oauth update to version 2.0.10 ([0d60a99](https://github.com/OpenIndiana/oi-userland/commit/0d60a993084f412241302ce4ece61f1684c3504f))
- redis update to version 6.3.0 ([baf12ad](https://github.com/OpenIndiana/oi-userland/commit/baf12ada78a7c3c571961d7a8ed33e61be80a160))
- xdebug update to version 3.5.0 ([d07206c](https://github.com/OpenIndiana/oi-userland/commit/d07206c11f790f447ed9c1335c22798e1b1b0a5e))
- yaml update to version 2.3.0 ([fc0f8d2](https://github.com/OpenIndiana/oi-userland/commit/fc0f8d2d0d1c20381ab352ec053ff0d47fe36a59))
- update to version 8.3.30 ([2f5d2de](https://github.com/OpenIndiana/oi-userland/commit/2f5d2deefec7a40c1e515ee5389b8b793060cb25))
- rebuild due to new libxml2 version ([6052932](https://github.com/OpenIndiana/oi-userland/commit/6052932747e7a40abdb51178654d7c183ca98771))

### php84

- update to version 8.4.15 ([9c0cf52](https://github.com/OpenIndiana/oi-userland/commit/9c0cf52a9deb5d10eee60daf779e33d2f09c21d2))
- update to version 8.4.16 ([686184e](https://github.com/OpenIndiana/oi-userland/commit/686184ede707f375fac9d54fc88f44e872d6f642))
- memcached update to version 3.4.0 ([be12421](https://github.com/OpenIndiana/oi-userland/commit/be12421ef903e6e0a171c65c3af83d10eae95f6e))
- apcu update to version 5.1.28 ([4cb1a83](https://github.com/OpenIndiana/oi-userland/commit/4cb1a83e04d8d48be85fd3a33a12dbf252345c4b))
- imagick update to version 3.8.1 ([fb58025](https://github.com/OpenIndiana/oi-userland/commit/fb5802523e45ba5507b83fb59ec0599889f7732a))
- mongodb update to version 2.1.4 ([a6fbb7e](https://github.com/OpenIndiana/oi-userland/commit/a6fbb7e9a0fc1fe1f0752a367f23a43b5f8ab107))
- redis update to version 6.3.0 ([a840b49](https://github.com/OpenIndiana/oi-userland/commit/a840b49122266ded103f4709bf37e8773a704b40))
- xdebug update to version 3.5.0 ([2fb86a6](https://github.com/OpenIndiana/oi-userland/commit/2fb86a63ed377a22cfdc3f16a8cef3aa9f7515aa))
- oauth update to version 2.0.10 ([801e055](https://github.com/OpenIndiana/oi-userland/commit/801e0559db00b5ac044271b683b2ad3703a8f8b0))
- yaml update to version 2.3.0 ([b108233](https://github.com/OpenIndiana/oi-userland/commit/b1082332bff5d43750659499e38c1029266939eb))
- update to version 8.4.17 ([4b212d2](https://github.com/OpenIndiana/oi-userland/commit/4b212d2da4b24ca62684cabb488e12adfb3b329e))
- update to version 8.4.20 ([35ad026](https://github.com/OpenIndiana/oi-userland/commit/35ad026012b56b5fe78e06c7066214b56c2b1b12))

### php85

- new php version 8.5.1 ([b61774f](https://github.com/OpenIndiana/oi-userland/commit/b61774ff94f8dec501f067ecb7289bfbd6aac9e6))
- update to version 8.5.2 ([8e2388a](https://github.com/OpenIndiana/oi-userland/commit/8e2388ae875ade6f08659ca347953ea9aa40e803))
- add back pecl/pear funtionality as pie currently not available for openindiana ([c88eba6](https://github.com/OpenIndiana/oi-userland/commit/c88eba6bb6d7944046a9d181c4b3dea70a30f081))
- rebuild due to new libxml2 version ([08f9d67](https://github.com/OpenIndiana/oi-userland/commit/08f9d67353c584b3cb855a3d427fcb63b5473a82))

### poppler

- update to 26.02 and switch to qt6 ([f36c360](https://github.com/OpenIndiana/oi-userland/commit/f36c360cfae88d6d7ff2014faeb4aca07b483f61))

### postfix

- update to 3.10.5 ([67bdccb](https://github.com/OpenIndiana/oi-userland/commit/67bdccbff981503d7f48331ce507c642fe40d442))
- update to 3.10.6 ([ffd4595](https://github.com/OpenIndiana/oi-userland/commit/ffd45953d46c4c6081bda3ea0731441da77c28df))
- update to 3.10.7 ([b3b7f0c](https://github.com/OpenIndiana/oi-userland/commit/b3b7f0c087812787bdfd0d151621c76b66cb4e9b))
- rebuild after lmdb upgrade ([597ca6a](https://github.com/OpenIndiana/oi-userland/commit/597ca6ad406b30fd80948d087260f85908f33fa3))
- update to 3.11.0 ([df6eb85](https://github.com/OpenIndiana/oi-userland/commit/df6eb8551789a36fce932d12e13195436b83e21d))
- update to 3.11.1 ([df4e3c9](https://github.com/OpenIndiana/oi-userland/commit/df4e3c96ba9d44bf423b15514d66fefda809b115))

### postgresql-14

- update to 14.19 ([01e5fd4](https://github.com/OpenIndiana/oi-userland/commit/01e5fd4931ee248f8e75a0de56cf6d34c13d06ed))
- update to 14.20 ([cfaa05c](https://github.com/OpenIndiana/oi-userland/commit/cfaa05c055f7423d59b481e9ffdd1cef9f6234c6))
- update to 14.21 ([9be8cc9](https://github.com/OpenIndiana/oi-userland/commit/9be8cc9f85d606e82bef43a373e1a2c3bc97f468))
- update to 14.22 ([e6825c9](https://github.com/OpenIndiana/oi-userland/commit/e6825c9104def5d260e05759d70033cbda5760e7))

### postgresql-15

- update to 15.15 ([4441376](https://github.com/OpenIndiana/oi-userland/commit/44413761a805be9b5bb1f81795fdfa9fbe832447))
- update to 15.16 ([f09e0af](https://github.com/OpenIndiana/oi-userland/commit/f09e0af44a75ebc9529ff759ba55320a32b5bc2a))
- update to 15.17 ([cfe6af5](https://github.com/OpenIndiana/oi-userland/commit/cfe6af5bb2995e2df2c3baa3fabe4887f11f7b26))

### postgresql-16

- update to 16.11 ([a34a7b2](https://github.com/OpenIndiana/oi-userland/commit/a34a7b20a707a22079c8b8ccb7c0125d196658f9))
- update to 16.12 ([cfb982a](https://github.com/OpenIndiana/oi-userland/commit/cfb982af10095aff6b50432f2e4b48cd50cc64eb))
- update to 16.13 ([c98a823](https://github.com/OpenIndiana/oi-userland/commit/c98a823b88e4aee58a6ed065680fb9f546092bf9))

### postgresql-16-citus

- update to 14.0.0 ([83aef4f](https://github.com/OpenIndiana/oi-userland/commit/83aef4f9f061c29ad70d12de05184e2dfbce9f48))

### postgresql-16-mysql_fdw

- update to 2.9.3 ([453006e](https://github.com/OpenIndiana/oi-userland/commit/453006e4261ac5ca6f0be3bec24128007295ef5b))

### postgresql-16-pg_repack

- update to 1.5.3 ([01a8868](https://github.com/OpenIndiana/oi-userland/commit/01a8868acbe0ebe5f72f8d91fc8fed61a1dafaa4))

### postgresql-16-timescaledb

- update to 2.23.0 ([93627f6](https://github.com/OpenIndiana/oi-userland/commit/93627f619de1e8f156219fed43657e58310aee4d))
- update to 2.23.1 ([662e35c](https://github.com/OpenIndiana/oi-userland/commit/662e35cdeebaf0dd94f771bf3354cb31bd41b806))
- update to 2.24.0 ([bc1939b](https://github.com/OpenIndiana/oi-userland/commit/bc1939b759d0622f7596c222d49de2b812925959))
- update to 2.25.1 ([79414d6](https://github.com/OpenIndiana/oi-userland/commit/79414d6a8b8ec50f72eac996c2c414bd2cdb0a47))
- update to 2.25.2 ([db4f33d](https://github.com/OpenIndiana/oi-userland/commit/db4f33d94d2e56ec7a4ceea70cb25d48c545a875))
- update to 2.26.1 ([6fb7ac6](https://github.com/OpenIndiana/oi-userland/commit/6fb7ac64596022095daa3eb848f66c26d9269f24))
- update to 2.26.2 ([ff206cb](https://github.com/OpenIndiana/oi-userland/commit/ff206cbe9a0e01a57728e18081991976ecbce018))
- update to 2.26.3 ([a589312](https://github.com/OpenIndiana/oi-userland/commit/a5893121273c2faddba1ee2c88436be96ffae5cc))
- update to 2.26.4 ([45e257b](https://github.com/OpenIndiana/oi-userland/commit/45e257baa7b904e4624b8fdbd0f35b1208eaae94))

### prep-patch.mk

- ADDITIONAL_PATCHES does not need a guard ([8bce856](https://github.com/OpenIndiana/oi-userland/commit/8bce8560adeeec91b0e4c97ce42979e2b69c9a34))
- keep list of all patches in ALL_PATCHES ([d2e19e0](https://github.com/OpenIndiana/oi-userland/commit/d2e19e0a32352874ef137cdccdbdd1ec8e9e1320))

### proj

- update to 9.7.1 ([00a37fb](https://github.com/OpenIndiana/oi-userland/commit/00a37fbf5c5e67831bdcf742d6eb9f91026a8800))
- update to 9.8.0 ([41f1011](https://github.com/OpenIndiana/oi-userland/commit/41f1011b872f8a13f645995744ee3cb4ede3f76c))

### protobuf

- update to 34.0; keep 30.2 libraries; obsolete 24.4 and 29.3 ([06b3c5c](https://github.com/OpenIndiana/oi-userland/commit/06b3c5c161135edec71d5f8d53c95bb438b262a3))
- update to 34.1; keep 34.0 libraries ([2607f2e](https://github.com/OpenIndiana/oi-userland/commit/2607f2ecd09787beaf8482313dedec5a4cc9c5f3))

### pyproject.mk

- use oldest supported Python for META.depend.res ([3d4c55b](https://github.com/OpenIndiana/oi-userland/commit/3d4c55b9605b0ac67265f7678eb5fec0bcd15e83))

### python-313

- update to 3.13.9 ([374428f](https://github.com/OpenIndiana/oi-userland/commit/374428f81de35204ab354db220ecf74600f2f525))
- update to 3.13.11 ([3eabdcd](https://github.com/OpenIndiana/oi-userland/commit/3eabdcd09c20b2ebe99276e3e680caa552192334))
- update to 3.13.12 ([e4176de](https://github.com/OpenIndiana/oi-userland/commit/e4176de8f5472f681655945754c8fe6641935d44))
- update to 3.13.13 ([eeb756a](https://github.com/OpenIndiana/oi-userland/commit/eeb756ad76d2367b92ac40955d908693766585e8))

### python-314

- fix tzdata handling ([e3105a4](https://github.com/OpenIndiana/oi-userland/commit/e3105a452e4f477abe0a44879679d5b31e9c4343))
- update to 3.14.2 ([1c2fcaa](https://github.com/OpenIndiana/oi-userland/commit/1c2fcaabddf81768ff41cc38c08f9358a5ae7ec3))
- backport threading.get_native_id support ([4e3b872](https://github.com/OpenIndiana/oi-userland/commit/4e3b872b2092b9243f5815aa777b6a836ac434f9))
- update to 3.14.3 ([dcdef5a](https://github.com/OpenIndiana/oi-userland/commit/dcdef5abecbaa8176fcc003f57f0156b9724017f))
- update to 3.14.4 ([f87f5ae](https://github.com/OpenIndiana/oi-userland/commit/f87f5ae335044c3adfdfc16c4ad4abb23ffd32ce))

### python-39

- update to 3.9.25 ([bbe9290](https://github.com/OpenIndiana/oi-userland/commit/bbe9290c58c200f79cd267996f35448961f98dc1))
- backport threading.get_native_id support ([1bc9bb3](https://github.com/OpenIndiana/oi-userland/commit/1bc9bb3e388cf63836edbf9f70c9cf6105dab75c))

### qemu

- update to 10.1.2 ([906c809](https://github.com/OpenIndiana/oi-userland/commit/906c8090736d3624bb4535bd437b67fb25448712))
- update to 10.1.3 ([ecb67b3](https://github.com/OpenIndiana/oi-userland/commit/ecb67b3219f15bc9fee1b90636eb7584e667d3da))
- add SPARC support ([c178852](https://github.com/OpenIndiana/oi-userland/commit/c1788524409f578f40923a9616eb181b91c56fd7))
- update to 10.2.0 ([8ff9d89](https://github.com/OpenIndiana/oi-userland/commit/8ff9d895284ae8ac3a96b2129d90065238198c9f))
- update to 10.2.1 ([ee1927e](https://github.com/OpenIndiana/oi-userland/commit/ee1927e945005f29b04a1057c6db836a9ab1e4ca))
- update to 10.2.2 ([724474c](https://github.com/OpenIndiana/oi-userland/commit/724474ce661e13907c4858f4df0b8f0933ade1ea))
- update to 11.0.0 ([c3e9aa9](https://github.com/OpenIndiana/oi-userland/commit/c3e9aa9a3238b7db28a443ea18734188824520ad))

### qt5

- update to 5.15.18 ([54edc99](https://github.com/OpenIndiana/oi-userland/commit/54edc99b095ecfee5e676a020d670a5a4c48fded))

### qt6

- fix dependencies ([f39e65f](https://github.com/OpenIndiana/oi-userland/commit/f39e65f5861a6c521a67d9005bfc7098e6cad5f2))
- add missing pulseaudio headers; explicitly disable gstreamer ([2f016b8](https://github.com/OpenIndiana/oi-userland/commit/2f016b8d6481cb97c534501dceda88d1d787b7c0))
- add SPARC support ([59e0aff](https://github.com/OpenIndiana/oi-userland/commit/59e0aff3d31fed83faf8795ce4c9d3bf5c903a28))
- update 6.10 ([42ece16](https://github.com/OpenIndiana/oi-userland/commit/42ece16970bd0c10a554b267451e599b88453f66))
- finish SPARC support for qt-6.10.2 ([815398f](https://github.com/OpenIndiana/oi-userland/commit/815398f69d60628887ef307c1034007e0937ce34))
- update to 6.10.3 ([e30b7c2](https://github.com/OpenIndiana/oi-userland/commit/e30b7c2f58cc2435c56db1c35ca8296d9a406382))

### quilt

- depend on the system/mta metapackage ([cafe9cb](https://github.com/OpenIndiana/oi-userland/commit/cafe9cbf1f2f580e78887be263e67dca3a6c76a2))
- fix license meta data ([df9dc46](https://github.com/OpenIndiana/oi-userland/commit/df9dc46edb28f493fcaee9bb86e77c46535ff0b2))

### re2

- update to 2025-11-05 ([bd47740](https://github.com/OpenIndiana/oi-userland/commit/bd47740f728f06dab215c71f1343b8a1567abd5c))

### re2c

- update to 4.3.1 ([cb242e2](https://github.com/OpenIndiana/oi-userland/commit/cb242e20bfeaa745018ce58d1b172813e2eb7e18))
- update to 4.4 ([71d539a](https://github.com/OpenIndiana/oi-userland/commit/71d539ad30c381ad9e0ec3de7d1d6db7f64b3b0e))
- update to 4.5 ([75610cd](https://github.com/OpenIndiana/oi-userland/commit/75610cdedeb6f10ca60b86b79898c5187fe644e7))
- update to 4.5.1 ([3074677](https://github.com/OpenIndiana/oi-userland/commit/307467727039787345d635dd57bc2f1d1b198534))

### readline

- update to 8.3p3 ([dfa1030](https://github.com/OpenIndiana/oi-userland/commit/dfa10309bfd5a916b6551998ce685ef361be03f0))
- switch to ncurses ([66d3171](https://github.com/OpenIndiana/oi-userland/commit/66d3171ed3f6ee964bb06f200679661c5e5cdac6))

### redis

- update 8.6.1 ([797168a](https://github.com/OpenIndiana/oi-userland/commit/797168a3fdaa80c56044d03713cd068b41836489))

### remmina

- update to 1.4.41 ([f44a2e4](https://github.com/OpenIndiana/oi-userland/commit/f44a2e44caf427e8d1db51feb6474ded395ecbf2))
- update to 1.4.43 ([6c0c5fb](https://github.com/OpenIndiana/oi-userland/commit/6c0c5fbaf6812805bcb0462f19fc722fa3a9061b))

### rgb

- update to 1.1.1 ([25e324f](https://github.com/OpenIndiana/oi-userland/commit/25e324f578fbd6977b05381b3adf1ab5da7fafa2))

### ripgrep

- update to 15.1.0 ([62f41ba](https://github.com/OpenIndiana/oi-userland/commit/62f41baef393a8bc521a9bb9411c29c1be166448))

### rlwrap

- update to 0.48 ([c26118e](https://github.com/OpenIndiana/oi-userland/commit/c26118e187d1617eba29b40de8ab26cb1ad4ea3e))

### rsync

- update to 3.4.2 ([a7c01f2](https://github.com/OpenIndiana/oi-userland/commit/a7c01f2b3685955869b1f548ec1a3060e429ed87))

### ruby-32

- update to 3.2.10 ([d2d61a3](https://github.com/OpenIndiana/oi-userland/commit/d2d61a3b53f96c2fd928b8820ed677398623de2c))
- update to 3.2.11 ([868c272](https://github.com/OpenIndiana/oi-userland/commit/868c272a89ee9a7be2d8c8f2f8b2778cdb1cba9e))

### ruby-34

- update to 3.4.8 ([f12de49](https://github.com/OpenIndiana/oi-userland/commit/f12de49d4c218c2c2fa903c801a0550992823a58))
- update to 3.4.9 ([3f0d25e](https://github.com/OpenIndiana/oi-userland/commit/3f0d25eebf27b1dd8428e56ce4951b9c13d3bca3))

### ruby-4.0

- update to 4.0.2 ([54aaa0f](https://github.com/OpenIndiana/oi-userland/commit/54aaa0f4dc3bf0e4d531ae05182ee2422a2280f7))

### ruby-40

- Add ruby 4.0.0 ([0a73bba](https://github.com/OpenIndiana/oi-userland/commit/0a73bba7d16af0b9053dbef81c7935dea2ecfd4b))
- update to 4.0.1 ([dcea30b](https://github.com/OpenIndiana/oi-userland/commit/dcea30bc00f113003349b9a4710d53d543a04189))
- update to 4.0.3 ([53f0de8](https://github.com/OpenIndiana/oi-userland/commit/53f0de85377ce24a2df81212ef4857b87d7520df))

### rust

- update to version 1.90.0 ([a5113d7](https://github.com/OpenIndiana/oi-userland/commit/a5113d722bc7dabc733d61888bf54199cc98fab0))

### rust/cargo-c

- update to 0.10.19+cargo-0.93.0 ([d1c45c1](https://github.com/OpenIndiana/oi-userland/commit/d1c45c16cb922df7694ef2a4db5c90410af27e74))

### rust/cbindgen

- update to 0.29.2 ([8540430](https://github.com/OpenIndiana/oi-userland/commit/85404308103610593e6dc9b8e4c8af84db52a71e))

### rustc

- update to version 1.91.1 ([740722f](https://github.com/OpenIndiana/oi-userland/commit/740722fa6e6d2effc0910f3fdb9817fbe4a40e84))
- update to version 1.92.0 ([f06093b](https://github.com/OpenIndiana/oi-userland/commit/f06093b271a1c8bdf30a54576936b35fa9eca685))
- update to version 1.93.0 ([5d35c8c](https://github.com/OpenIndiana/oi-userland/commit/5d35c8cc8880cbb41f0153a40624ee2cdc04cb98))
- update to version 1.94.0 ([4e78584](https://github.com/OpenIndiana/oi-userland/commit/4e78584398c1a5eb00f74c41c31a77a4506bd12b))
- update to version 1.94.1 ([2ca3878](https://github.com/OpenIndiana/oi-userland/commit/2ca3878dc3259316a50307f0dc2b56d01221fc0f))
- update to version 1.95.0 ([d92082e](https://github.com/OpenIndiana/oi-userland/commit/d92082e0d971a88f8599bf9de59c1567b92ebb18))

### samba

- update to version 4.23.3 ([cc917f4](https://github.com/OpenIndiana/oi-userland/commit/cc917f441fa4d6892c7c064fe6c8473964b7bb47))
- udate to version 4.23.4 ([0f3cd65](https://github.com/OpenIndiana/oi-userland/commit/0f3cd65348ccca5d6a68bd2e4ebb66dba4fe6880))
- update to version 4.23.5 ([449b943](https://github.com/OpenIndiana/oi-userland/commit/449b9438b0b87969b738b148cf7214f3a521ace3))
- rebuild after lmdb upgrade ([37f917e](https://github.com/OpenIndiana/oi-userland/commit/37f917e2c77d4fd929b9026eee5c61fb079f8540))
- update to version 4.23.6 ([808f0bd](https://github.com/OpenIndiana/oi-userland/commit/808f0bd9c4230e734ec6da4fc287236f39da4aac))
- update to version 4.24.0 ([d984109](https://github.com/OpenIndiana/oi-userland/commit/d984109a46c3028307214b2d4d7b82a7c363c61e))

### sane-frontend

- rebuild for remove unneeded dependency gimp2, update source package location and build recipe ([6122478](https://github.com/OpenIndiana/oi-userland/commit/61224780d0679dfa9483d61c6e291acfa09229d8))

### sbcl

- update to 2.5.10 ([5430647](https://github.com/OpenIndiana/oi-userland/commit/5430647e17461c9629532098958ab381e9c70346))
- update to 2.5.11 ([85c2f96](https://github.com/OpenIndiana/oi-userland/commit/85c2f96e34589cf6ce17f22575cdcf3152cb309f))
- update to 2.6.0 ([d54353f](https://github.com/OpenIndiana/oi-userland/commit/d54353fa34a45e3bdc0932cddf80b69048a153be))
- update to 2.6.1 ([13deb68](https://github.com/OpenIndiana/oi-userland/commit/13deb68d2ba8bb259748f60adcaac41e071ffe37))
- update to 2.6.2 ([b8cdce1](https://github.com/OpenIndiana/oi-userland/commit/b8cdce1b2baecb268801d0f9d967d66911b09caf))
- add SPARC support ([1f15013](https://github.com/OpenIndiana/oi-userland/commit/1f15013a88ce788842a9352f97d149255ccef288))
- update to 2.6.3 ([5ab09ba](https://github.com/OpenIndiana/oi-userland/commit/5ab09ba1878b864007837e48f9c918b6531b177e))

### scientific/R

- update to 4.5.3 ([b3af27c](https://github.com/OpenIndiana/oi-userland/commit/b3af27cf309567607733cb48f97322974122b10f))

### sdl2_image

- update to 2.8.10 ([5d4d30d](https://github.com/OpenIndiana/oi-userland/commit/5d4d30db5a78c5dd0344759c8df03aa38664c755))

### sdl3

- update to 3.2.28 ([802b171](https://github.com/OpenIndiana/oi-userland/commit/802b1710ec96eacb9e892429e9a33bc09c51822b))
- update to 3.4.2 ([e37f402](https://github.com/OpenIndiana/oi-userland/commit/e37f40264d7fd8ebe4de85931ad77b825bcfb3dd))
- update to 3.4.4 ([19fa7d5](https://github.com/OpenIndiana/oi-userland/commit/19fa7d5e09409a24a2ac6706668af9efeab3b950))

### sdl3-image

- update to 3.2.6 ([2b62803](https://github.com/OpenIndiana/oi-userland/commit/2b62803793d9bff96812034625ec0288059ab882))

### sdl3-ttf

- add 3.2.2 ([6d5ca1a](https://github.com/OpenIndiana/oi-userland/commit/6d5ca1a71ba350fdd8f2ac1100e4464b82ebed14))

### sdl3_image

- update to 3.4.0 ([7367e34](https://github.com/OpenIndiana/oi-userland/commit/7367e346621a3d7c7921aa901737142ac1b21b08))
- update to 3.4.2 ([069f1d2](https://github.com/OpenIndiana/oi-userland/commit/069f1d233ce55f46c8767a523b749106718dd8c0))

### seaweedfs

- update to 3.99 ([9e467fa](https://github.com/OpenIndiana/oi-userland/commit/9e467fa22202888d2deab0e608a51a82187d986a))
- update to 4.01 ([6c4ce13](https://github.com/OpenIndiana/oi-userland/commit/6c4ce13fd2bcca4a46b5517da495d37812aa2852))
- update to 4.05 ([66b2f88](https://github.com/OpenIndiana/oi-userland/commit/66b2f88fbb0ff3a79b4010da6483e1f6d9d23f69))
- update to 4.06 ([b445bee](https://github.com/OpenIndiana/oi-userland/commit/b445beec6d4783e5aa6547ce4f262a43bf8d5e43))
- update to 4.07 ([a1f0512](https://github.com/OpenIndiana/oi-userland/commit/a1f051223f87d78bce4af9a3379cbf317ae04127))

### sendmail

- update to version 8.18.2 ([c4ca592](https://github.com/OpenIndiana/oi-userland/commit/c4ca59227d11651cc76eded0aeda75580ed1ca1a))

### setup.py.mk

- use PROTOPYTHONVENDORDIR for COMPONENT_TEST_ENV ([3b3be28](https://github.com/OpenIndiana/oi-userland/commit/3b3be28f6e3b553a7862b31a4dae4b0781f0554b))
- set CLONEY_MODE directly ([0b6be5d](https://github.com/OpenIndiana/oi-userland/commit/0b6be5d97c43888e2d9807e71f5a17936a2285c6))
- detect test dependencies only when really needed ([62b4870](https://github.com/OpenIndiana/oi-userland/commit/62b48704a66e7a4e92ec4a33c68b2adf01d627f7))
- drop optional line from tox test results ([7e30c94](https://github.com/OpenIndiana/oi-userland/commit/7e30c94aed45c25324d5bf85e5a148567da519c2))
- set PYTHON_VERSION when detecting test dependencies ([3c09db6](https://github.com/OpenIndiana/oi-userland/commit/3c09db6e01e9d01f3ce8c382fc99b9f1b6b0b24f))
- test dependency detection does not need PROTOPYTHONSITEDIR in PYTHONPATH ([37f3d1b](https://github.com/OpenIndiana/oi-userland/commit/37f3d1b46ec540a677a64e94f22f0023e51f02b1))
- clear Pytest cache between test runs ([fecdb65](https://github.com/OpenIndiana/oi-userland/commit/fecdb65ead7dff477f8a4aa2b04f62982c65f56e))
- tox should call stestr indirectly ([093d0a0](https://github.com/OpenIndiana/oi-userland/commit/093d0a068c78a97939340af82b5b96ecd5625b08))
- add indirect pytest-regressions -> pytest-datadir dependency ([c2b6da0](https://github.com/OpenIndiana/oi-userland/commit/c2b6da067a41ca79f2c265273fdf040e0431fa6a))
- set PYTHONSAFEPATH for testing ([84a2c10](https://github.com/OpenIndiana/oi-userland/commit/84a2c10a7ac9c8ac48917a9db4f2afd42a241a22))

### setxkbmap

- update to 1.3.5 ([737f047](https://github.com/OpenIndiana/oi-userland/commit/737f047416e669819da937453deab0b23fe5a786))

### shared-macros.mk

- add macros for pkg-config directories ([496ba00](https://github.com/OpenIndiana/oi-userland/commit/496ba0017525d2fd590432cb0a84fde5cda14dc5))
- symlink suffix support for create-symlinks ([6df2b7d](https://github.com/OpenIndiana/oi-userland/commit/6df2b7d444c3b2655b902d876f22d8ac3b905972))
- add PKG_CONFIG_DIR and PROTOPKGCONFIGDIR ([9af0081](https://github.com/OpenIndiana/oi-userland/commit/9af008138a59ce7a921dcf053afd2a75961dc10b))

### socat

- update to 1.8.1.1 ([3e27476](https://github.com/OpenIndiana/oi-userland/commit/3e2747639f9549d3fc539861b8bc1b222dd4616d))

### solvespace

- add 3.2 ([fdc61df](https://github.com/OpenIndiana/oi-userland/commit/fdc61df1b9c514386b1c0a7c4eaabb71a42d3551))

### soundtouch

- update to 2.4.1 ([139a756](https://github.com/OpenIndiana/oi-userland/commit/139a756784d913454ae8b2eb22add402e49d4df9))

### sqlite

- update to 3.51.0 ([7d2a32e](https://github.com/OpenIndiana/oi-userland/commit/7d2a32eadb483e30726d4b2bb5f71cd6fb192150))
- update to 3.51.1 ([48d176e](https://github.com/OpenIndiana/oi-userland/commit/48d176ee1d4b4bec3d1117de0b6f281844fbcdc8))
- update to 3.51.2 ([f073398](https://github.com/OpenIndiana/oi-userland/commit/f073398c95d5ca2f90b46a6eeb27dba9b7d53c4c))
- update to 3.51.3 ([10f4eaa](https://github.com/OpenIndiana/oi-userland/commit/10f4eaa1cca7d202f44da243ca66a515e3d3121e))
- update to 3.53.0; add soname patch from OmniOS ([d14e1e4](https://github.com/OpenIndiana/oi-userland/commit/d14e1e4034bb1a7ed462cfa84d86bbd25af49d64))

### sqlitebrowser

- add to oi-userland ([e033200](https://github.com/OpenIndiana/oi-userland/commit/e0332001c55f8408e02486b6205b53a407b6309c))
- build with QT6 ([ead2d08](https://github.com/OpenIndiana/oi-userland/commit/ead2d08a03eeb257bfc655ee9198abf93c0ae970))

### squeak

- add icon and desktop files ([1165136](https://github.com/OpenIndiana/oi-userland/commit/11651366e2c63dad26cc495e43b7cfb6d52caacd))
- fix ckformat mediator link ([bcc34cb](https://github.com/OpenIndiana/oi-userland/commit/bcc34cba63e859aaf6d95b16a1e1d5217399eea9))
- add optional dependencies ([7ec1231](https://github.com/OpenIndiana/oi-userland/commit/7ec123104744e5b12954dccc9befa8d98bf9409f))
- remove KedamaPlugin2 from build ([0e6b5ce](https://github.com/OpenIndiana/oi-userland/commit/0e6b5cebdcf9fa1f3c3ad6f4801d69e1bb4206a1))

### squid

- add SPARC support ([ca05689](https://github.com/OpenIndiana/oi-userland/commit/ca0568943072fa0a3e655b9a2000121159988684))
- update to version 7.3 ([b25667c](https://github.com/OpenIndiana/oi-userland/commit/b25667cf682be2bdb84deac06a55a51017ef3cbe))
- update to version 7.4 ([3579a31](https://github.com/OpenIndiana/oi-userland/commit/3579a31cbb5e117d4c1d3df28f5e1e69adf0da0e))
- update to version 7.5 ([e499002](https://github.com/OpenIndiana/oi-userland/commit/e499002a63f4c334d605b747c4618db3bda75282))

### stellarium

- update to 25.4 ([9caa266](https://github.com/OpenIndiana/oi-userland/commit/9caa2665d8ab2d963e65f162f9dc9cdab9aa739a))

### swi-prolog

- add SPARC support ([eb7cba3](https://github.com/OpenIndiana/oi-userland/commit/eb7cba320e4342551dbcd081d6467605a388d474))

### swig

- update to 4.4.0 ([0d87965](https://github.com/OpenIndiana/oi-userland/commit/0d879652a563fe1b7cd4815eb3d9d11945618b74))

### sysding

- fix Makefile targets ([da0ed28](https://github.com/OpenIndiana/oi-userland/commit/da0ed28ac9326856ec4f331df47f77ec4e19b498))

### sysutils/bat

- update to 0.26.1 ([d25910b](https://github.com/OpenIndiana/oi-userland/commit/d25910beaeb07f08ff0c0a64aba09a40e3cef687))

### sysutils/borgbackup

- update to 1.4.2 ([f215207](https://github.com/OpenIndiana/oi-userland/commit/f2152072eee07e11c18792e3d9f91a351df82811))
- update to 1.4.3 ([073fbdf](https://github.com/OpenIndiana/oi-userland/commit/073fbdfb3fc5b332862dc51859071d10c3807ceb))

### talloc

- update to 2.4.4 ([344cfd1](https://github.com/OpenIndiana/oi-userland/commit/344cfd152d5190f18365c743f78f1784387e97f0))

### tcltls

- update to 2.0 ([2719f1d](https://github.com/OpenIndiana/oi-userland/commit/2719f1dbcbdb6e8da07ef3f7bf71bb729ac333e6))

### tcpdump

- update to 4.99.6 ([95fd18d](https://github.com/OpenIndiana/oi-userland/commit/95fd18dd20e1b82d3c817a8d85f9c97e1d55f0c3))

### tdb

- update to 1.4.15 ([aa39c6c](https://github.com/OpenIndiana/oi-userland/commit/aa39c6c8737aaf6c1af6473239ffe9acaa3c1322))

### texgyre

- enhance metadata ([05157f3](https://github.com/OpenIndiana/oi-userland/commit/05157f32f96e8c9e2a4dc9537499d4cea265a94b))

### texinfo

- update to 7.3 ([398268f](https://github.com/OpenIndiana/oi-userland/commit/398268f1cfdb5e05f6328641a62c1bd47fdceb9f))

### thunderbird

- update to 145.0 ([b8786a7](https://github.com/OpenIndiana/oi-userland/commit/b8786a75aa833a29a9eac25a6273319ab164e7a8))
- update to 146.0 ([7ca3f68](https://github.com/OpenIndiana/oi-userland/commit/7ca3f687aee91362f4946c9991cc23a46bf7a43a))
- update to 146.0.1 ([5453049](https://github.com/OpenIndiana/oi-userland/commit/5453049e36361cf70dd566f9e82d4a0aabb1b297))
- update to 147.0 ([986eeae](https://github.com/OpenIndiana/oi-userland/commit/986eeae65c963ba246b43fef4b5fd9059a76bbea))
- update to 147.0.1 ([7608d17](https://github.com/OpenIndiana/oi-userland/commit/7608d17fdb0c088ab4049a10c521a10665f66f1a))
- update to 147.0.2 ([daef3eb](https://github.com/OpenIndiana/oi-userland/commit/daef3eb9db9bae24a8eb852e3c99d569dbd71548))
- update to 148.0 ([0641226](https://github.com/OpenIndiana/oi-userland/commit/0641226265b14c25798ef8265c82387d64eaf922))
- update to 148.0.1 ([50ccee0](https://github.com/OpenIndiana/oi-userland/commit/50ccee0bc7aa8c7b8272ebd834897763488e3f86))
- update to 149.0 ([b87ff99](https://github.com/OpenIndiana/oi-userland/commit/b87ff994b6f5bb3898a11780e8b2f98db884487d))
- update to 149.0.1 ([e00aee8](https://github.com/OpenIndiana/oi-userland/commit/e00aee8559400ff96c57ce31235fab0a7c227f5b))
- update to 149.0.2 ([cf0da3b](https://github.com/OpenIndiana/oi-userland/commit/cf0da3b603b17ac84594d52709c2f59c0a3d8bae))
- update to 150.0 ([e66198a](https://github.com/OpenIndiana/oi-userland/commit/e66198a00bb721d48b9c51746aed859bf3ccfb99))
- update to 150.0.1 ([39a416d](https://github.com/OpenIndiana/oi-userland/commit/39a416d0ba63e6449e4ec4ea6b1e333a8b3e1d2f))

### tmux

- update to 3.6 ([6955cc2](https://github.com/OpenIndiana/oi-userland/commit/6955cc2dc15786c4024f6b88f2aff9a6ee78511b))
- update to 3.6a ([e6734df](https://github.com/OpenIndiana/oi-userland/commit/e6734df83151e995f898af7739f5b5348c5890b4))

### tomcat-11

- update to 11.0.14 ([c208870](https://github.com/OpenIndiana/oi-userland/commit/c2088700e1897995f8ae343f159b3173a0c2aa7c))
- update to 11.0.15 ([22647b5](https://github.com/OpenIndiana/oi-userland/commit/22647b59eb6c0884c1fbe817d09625734b6a5862))
- update to 11.0.18 ([ea873b9](https://github.com/OpenIndiana/oi-userland/commit/ea873b95f119e2730ecf93976a6be81fd0b692d8))
- update to 11.0.20 ([84f6f6a](https://github.com/OpenIndiana/oi-userland/commit/84f6f6a6a7fb942734bd33d0ad7fceb8f6dd63aa))
- update to 11.0.21 ([935e66b](https://github.com/OpenIndiana/oi-userland/commit/935e66bf36968d5089a1f85d3278c5472c65da6a))

### tools

- fix userland-fetch assigning user-agent ([c3757e6](https://github.com/OpenIndiana/oi-userland/commit/c3757e62ddb96b4c7414a6074f786cd9427a675b))
- set user-agent default curl/8.18.0 ([c25416c](https://github.com/OpenIndiana/oi-userland/commit/c25416ce049b402d46859b06cbb38dbe7cec8cf0))

### tools/perl-integrate-module

- take first hit only from metacpan query results ([2273c0f](https://github.com/OpenIndiana/oi-userland/commit/2273c0f7aab6669a5740c42ef6c6c9c22babd9dd))

### tools/python-integrate-project

- tox should not provision ([c0efd51](https://github.com/OpenIndiana/oi-userland/commit/c0efd512f81b5ff2a4956a46222f09c7b53bfabd))
- fix versioned python binary name ([811046a](https://github.com/OpenIndiana/oi-userland/commit/811046af107265e32bf23bff8da16c3e878c4b61))
- postpone CARGO_VENDOR setting ([fc61548](https://github.com/OpenIndiana/oi-userland/commit/fc615480731b1ce39b4dba9f6bd0bcb8f372ab46))
- drop support for setup.py test style ([ba3421d](https://github.com/OpenIndiana/oi-userland/commit/ba3421d7da6e01f1790f32cb96f0f6a4281373b8))
- improve tox provisioning detection ([05e6b3e](https://github.com/OpenIndiana/oi-userland/commit/05e6b3ec9a9b7f37e36731ef5b0883d11dce6e55))
- fix CARGO_VENDOR setting ([dd00c03](https://github.com/OpenIndiana/oi-userland/commit/dd00c03d22e3aa0453d5c134ed9666918f65ffb2))
- support for CARGO_TOML_SUBDIR ([54fb4e9](https://github.com/OpenIndiana/oi-userland/commit/54fb4e92dae319cd6b531702312daa8db23960f7))
- fix printf typo ([987a272](https://github.com/OpenIndiana/oi-userland/commit/987a2720aec2708b8390a6cd765408ae29d8a270))
- allow CARGO_TOML_SUBDIR override ([d6e16e7](https://github.com/OpenIndiana/oi-userland/commit/d6e16e7203e908990d9a3f5ef49461e0adfc65a8))
- support for cargo patches ([bcbbf32](https://github.com/OpenIndiana/oi-userland/commit/bcbbf3292e76d3fab5aa73198e655ad281ae8fd1))
- consider COMPONENT_SUBDIR when looking for Cargo.toml ([c7c8dd8](https://github.com/OpenIndiana/oi-userland/commit/c7c8dd80831eb58181bdfa21fe46b70612689b5c))
- check requires_python ([028bb46](https://github.com/OpenIndiana/oi-userland/commit/028bb46ba86ba7962f49c4fee84d2c1e644e3a96))
- requires_python is optional ([6fa2163](https://github.com/OpenIndiana/oi-userland/commit/6fa2163b918c70fa8653223dae18bb9cb469990a))
- allow to set CARGO_VENDOR in hook-begin ([a685f7e](https://github.com/OpenIndiana/oi-userland/commit/a685f7e3ba024e6eb183a488a7ef0b7a6daf3e08))
- evaluate full Python version for requires_python ([cf4a661](https://github.com/OpenIndiana/oi-userland/commit/cf4a661d23651e1e4f5064731f5d7274cf43d755))

### tor

- update to version 0.4.8.20 ([1caa55c](https://github.com/OpenIndiana/oi-userland/commit/1caa55ca3ee49c86a255d3e48079e79fdf5c36fe))
- update to version 0.4.8.21 ([44e681b](https://github.com/OpenIndiana/oi-userland/commit/44e681bb5286abf37ddfae1f2ece063f80898c9f))
- Update to 0.4.8.22 ([f4b68e8](https://github.com/OpenIndiana/oi-userland/commit/f4b68e867fea45bd673d2939628fe17be1f74fb2))
- update to 0.4.9.5 ([169ce94](https://github.com/OpenIndiana/oi-userland/commit/169ce94fd48eadde6acb1529347584ba246e4b86))
- update to tor.0.4.9.6 ([18558fe](https://github.com/OpenIndiana/oi-userland/commit/18558fe7dcd88d7c7daa60d7a377049e72cc069f))

### tracker

- rebuild after poppler upgrade ([72c49fe](https://github.com/OpenIndiana/oi-userland/commit/72c49fe186932b4cbeec6f201de29130136bbfe2))

### trealla

- update to 2.84.22 ([3dd77f4](https://github.com/OpenIndiana/oi-userland/commit/3dd77f436d547d4cfea4a6a88b7f37408ef179fa))
- update to 8.24.25 ([d50e03d](https://github.com/OpenIndiana/oi-userland/commit/d50e03d5c5e4b51285ec82824909c903617f2175))
- update to 8.24.29; fix license file ([3adfb54](https://github.com/OpenIndiana/oi-userland/commit/3adfb54a38cefd0564aa198de2942e939c92f33e))
- update to 2.85.5 ([40116b6](https://github.com/OpenIndiana/oi-userland/commit/40116b6270e82a89847429bf6b764b7522b4fdbb))
- update to 8.25.7 ([979a682](https://github.com/OpenIndiana/oi-userland/commit/979a68278ddd86923fb779fdfcc74ff63bd18ecc))
- update to 2.86.5 ([b6b61f4](https://github.com/OpenIndiana/oi-userland/commit/b6b61f460bb59b372fd74a57d4e8a1f7fb95f54d))
- add SPARC support ([87e1af2](https://github.com/OpenIndiana/oi-userland/commit/87e1af24f941d49652fedd6c4e5990aec00ca96e))
- re-add SPARC support ([b0da0b4](https://github.com/OpenIndiana/oi-userland/commit/b0da0b4a90b1d434d5af02f56ee432d0c4d0b926))
- update to 2.90.2 ([3521918](https://github.com/OpenIndiana/oi-userland/commit/352191813f8b3dc3ac8b293bb81cdf0b46c0fa60))
- update to 2.90.23 ([8201967](https://github.com/OpenIndiana/oi-userland/commit/820196700e6dc98faae7f4fdd4274266e290b896))
- update to 2.92.19 ([cf2079b](https://github.com/OpenIndiana/oi-userland/commit/cf2079bdec1238e3adce07ec0e56c24a7cfada9e))
- update to 2.93.0 ([9d22518](https://github.com/OpenIndiana/oi-userland/commit/9d2251834732149a2e117cd1c5acbe11f0d3d719))
- update to 2.94.3 ([0472b8b](https://github.com/OpenIndiana/oi-userland/commit/0472b8ba6ab6f48de3f85b058f1d9ce00fddc09a))

### trealla-prolog

- update to 2.84.3 ([44b3257](https://github.com/OpenIndiana/oi-userland/commit/44b32577a8dda06769795702abe9ecb050e5736b))
- update to 2.84.7 ([d5e19e1](https://github.com/OpenIndiana/oi-userland/commit/d5e19e1fd61e6476733cc89cb3e923b8a3ec9812))
- update to 2.84.9 ([adf3beb](https://github.com/OpenIndiana/oi-userland/commit/adf3beb02931c4834bb0763f0e9e178d4cce783d))
- update to 2.84.12 ([a5156d3](https://github.com/OpenIndiana/oi-userland/commit/a5156d36bc6c534a0a5d6578bd57f68a1dfaa6b2))
- update to 2.84.15 ([ed096bd](https://github.com/OpenIndiana/oi-userland/commit/ed096bd961a21479dfeba65f136cbd33a9f22aad))
- update to 2.84.16 ([9e20a0b](https://github.com/OpenIndiana/oi-userland/commit/9e20a0bf6b3a37424ce2c969b0e4bef7aa42336f))
- update to 2.85.9 ([342d474](https://github.com/OpenIndiana/oi-userland/commit/342d47455b58d4be2723d7d277bdad5d10fe9efd))
- update to 8.25.13 ([f4e1324](https://github.com/OpenIndiana/oi-userland/commit/f4e1324ac3e6bf6d9ec000afece4f8fd84c3a6c1))
- update to 8.25.18 ([0586fc4](https://github.com/OpenIndiana/oi-userland/commit/0586fc4cc1be9a21cf2119e570fba23a1203c509))
- update to 8.26.1 ([d58bacf](https://github.com/OpenIndiana/oi-userland/commit/d58bacf449075011408a36ae831b9f0c85b852cb))
- update to 2.86.7 ([17925a3](https://github.com/OpenIndiana/oi-userland/commit/17925a3eecb9dcedbeab919269c66a1ce1f295e4))
- update to 2.86.10 ([1836cc0](https://github.com/OpenIndiana/oi-userland/commit/1836cc01cabed126e7f3136d14ae3319e0707953))
- update to 2.86.12 ([dce10e6](https://github.com/OpenIndiana/oi-userland/commit/dce10e6f7568676e9898d9195ed229053a52d52f))
- update to 2.87.3 ([6191438](https://github.com/OpenIndiana/oi-userland/commit/619143844a4b40190a6ffb8598809d4ee2e23e0f))
- update to 2.87.5 ([65509a0](https://github.com/OpenIndiana/oi-userland/commit/65509a02ad9b105e9fd3455c8fc067a79fc95ba2))
- update to 2.87.7 ([3ba273f](https://github.com/OpenIndiana/oi-userland/commit/3ba273f4793dcf485ea27e358e365058b555e817))
- update to 2.88.0 ([c04da45](https://github.com/OpenIndiana/oi-userland/commit/c04da459efb2c1f00a9897e1063fda5743a54372))
- update to 2.88.1; rearrange files ([603470a](https://github.com/OpenIndiana/oi-userland/commit/603470a923c1da1c900038046c35132cac4764a2))
- update to 2.88.2; fix mode for binary ([9be2d0b](https://github.com/OpenIndiana/oi-userland/commit/9be2d0bb02fd574143006e51350739d1bb69d105))
- update to 2.88.3 ([2669e57](https://github.com/OpenIndiana/oi-userland/commit/2669e577d9b75c2b52bc38d857588a633767140e))
- update to 2.88.4 ([9fc2fce](https://github.com/OpenIndiana/oi-userland/commit/9fc2fce8d8055f31896017d36109dc36bd566496))
- update to 2.89.13 ([189538b](https://github.com/OpenIndiana/oi-userland/commit/189538bd126fc0f272fa667cb6416a743e78a2a1))
- update to 2.90.8 ([aed5e4e](https://github.com/OpenIndiana/oi-userland/commit/aed5e4e4adb4bbf5d6b1849123e1868e2c03b03d))
- update to 2.90.35 ([132709c](https://github.com/OpenIndiana/oi-userland/commit/132709c23a673e63f215093cd6d837bc7af45f20))
- update to 2.90.37 ([7c9bfaf](https://github.com/OpenIndiana/oi-userland/commit/7c9bfaf20afcfb2c0f03feeb8a73e7dc6473f80b))
- update to 2.90.39 ([63b69ab](https://github.com/OpenIndiana/oi-userland/commit/63b69ab21523c724926ca61349cc0991786c86eb))
- update to 2.90.41 ([841c3c0](https://github.com/OpenIndiana/oi-userland/commit/841c3c0e099a138df053799646623590cf749e60))
- update to 2.91.1 ([47ea286](https://github.com/OpenIndiana/oi-userland/commit/47ea286dc97b58b5877b1d7e510cc495a8a9413f))
- update to 2.91.3 ([8800d22](https://github.com/OpenIndiana/oi-userland/commit/8800d22aa3c1010979d04dc5dc56a481b39b1b8e))
- update to 2.91.5 ([e205b3a](https://github.com/OpenIndiana/oi-userland/commit/e205b3aad1be78638e47fc9e5ee9799a84ea17c6))
- update to 2.91.7 ([8f2e8b4](https://github.com/OpenIndiana/oi-userland/commit/8f2e8b4a8ac886ac800b265132cc7a063c85ff38))
- update to 2.92.3 ([82e58ea](https://github.com/OpenIndiana/oi-userland/commit/82e58eab737b2e97ab2186027e4b35e04a9c12c4))
- update to 2.92.7 ([623588b](https://github.com/OpenIndiana/oi-userland/commit/623588b61a3b6f049c6dedf2a761856d3d36c711))
- update to 2.92.11 ([50cd212](https://github.com/OpenIndiana/oi-userland/commit/50cd212b9b4e90191538b7763934d45567a9642e))
- update to 2.92.15 ([3601bc6](https://github.com/OpenIndiana/oi-userland/commit/3601bc6ce46b7447f56b345ec47e21fdbbc12b36))
- update to 2.92.25 ([10a6bcc](https://github.com/OpenIndiana/oi-userland/commit/10a6bcc9153ff3d16321b13feb01cddbe91992d0))
- update to 2.92.34 ([c4ebb89](https://github.com/OpenIndiana/oi-userland/commit/c4ebb89748ca9f6c3265fe8ebb3e0533165b5d42))

### trousers

- update to version 0.3.15 ([719c6d3](https://github.com/OpenIndiana/oi-userland/commit/719c6d3b3e050f1418e494fa77920264bd7c5dbd))

### unbound

- update to 1.24.2 ([6ded81c](https://github.com/OpenIndiana/oi-userland/commit/6ded81cc90288634d04d12afdb68ce377737a703))

### unicode-ucd

- update to 17.0.0 ([346b378](https://github.com/OpenIndiana/oi-userland/commit/346b378ef400ee780780406394398666a6bedd14))

### unicode-ucd-unihan

- update to 17.0.0 ([7dfd271](https://github.com/OpenIndiana/oi-userland/commit/7dfd271dcfb76c77dd8cac35560d3905c3661405))

### unrar

- update to 7.2.3 ([4bc6cef](https://github.com/OpenIndiana/oi-userland/commit/4bc6cef780f31064eab3303258c24ba2e4b1af63))
- update to 7.2.4 ([0f033fe](https://github.com/OpenIndiana/oi-userland/commit/0f033fe126ce9d963619ebd3d2e60873876a7a4f))
- update to 7.2.5 ([9c5cae4](https://github.com/OpenIndiana/oi-userland/commit/9c5cae40d7393d5972509daa18e1c841c48c1db2))

### userland-fetch

- fix downloads for codeberg (eg. librewolf) ([4848c5d](https://github.com/OpenIndiana/oi-userland/commit/4848c5d166e791b11367628debe41a0b85e1b987))
- revert last change as it breaks other downloads ([5c039e2](https://github.com/OpenIndiana/oi-userland/commit/5c039e28bf2679a57149a89ded90b756d447085c))

### vala

- update to 0.56.19 ([9df5333](https://github.com/OpenIndiana/oi-userland/commit/9df53331daa92cf62ce7641c7a23fc91731df2dd))

### valgrind

- update to 3.27.0 ([bd7c5a8](https://github.com/OpenIndiana/oi-userland/commit/bd7c5a83a86cd614b09b79cfadcac34ca0d598c7))

### vim

- update to 9.1.1879 ([54a9e10](https://github.com/OpenIndiana/oi-userland/commit/54a9e10a4042f8e4b183036d70c60b6d4b73373b))
- update to 9.1.1891 ([2d82e3f](https://github.com/OpenIndiana/oi-userland/commit/2d82e3f90541765ceac42ded68b2f66cb5414917))
- update to 9.1.1898 ([191c424](https://github.com/OpenIndiana/oi-userland/commit/191c424bcec9d154131f8c24859508226103b407))
- update to 9.1.1900 ([e01583e](https://github.com/OpenIndiana/oi-userland/commit/e01583e469d82ded812067d9f4b18d69c66b09c4))
- update to 9.1.1924 ([be33518](https://github.com/OpenIndiana/oi-userland/commit/be33518844ae4b82fb9aaa4dd06d00278138e843))
- update to 9.1.1934 ([81501ba](https://github.com/OpenIndiana/oi-userland/commit/81501ba14f4633b5e72a5c2124745e8904219bc1))
- update to 9.1.1952 ([858e256](https://github.com/OpenIndiana/oi-userland/commit/858e2565e3d68bf39da6a3f8a36f446ec6d39c36))
- update to 9.1.2000 ([a13b7e6](https://github.com/OpenIndiana/oi-userland/commit/a13b7e6df2889ce7150340495950dbf403fc8ecf))
- update to 9.1.20031 ([325ce8e](https://github.com/OpenIndiana/oi-userland/commit/325ce8ef8c7b6d157ff1a220bcf744deeb6d2635))
- update to 9.1.2050 ([30d3cbd](https://github.com/OpenIndiana/oi-userland/commit/30d3cbd26b3a003eb8a8592d284bd76e1031271d))
- update to 9.1.2100 ([1c0bd4b](https://github.com/OpenIndiana/oi-userland/commit/1c0bd4bb4f1699b7b42ccf19e0272e678f90aa5d))
- update to 9.2.0000 ([6dadecd](https://github.com/OpenIndiana/oi-userland/commit/6dadecdeec980f518d1caa53cf0e9d3e22d65bd7))
- update to 9.2.0100 ([9509a9d](https://github.com/OpenIndiana/oi-userland/commit/9509a9d2bd36441353284a8f5f7bc851f34660ad))
- delete removal of ko.po,zh_CN.po language files, they are fixed ([6842ff6](https://github.com/OpenIndiana/oi-userland/commit/6842ff6350978771ea0ff6260489b6f83ac32c70))
- update to 9.2.0150 ([1f4b6c5](https://github.com/OpenIndiana/oi-userland/commit/1f4b6c599294570e61e4d331530cdbc5e4e9f6ae))
- update to 9.2.0200 ([f0fcc70](https://github.com/OpenIndiana/oi-userland/commit/f0fcc7090232b9c5afb5b16c371d6a0d4f74576b))
- update to 9.2.0250 ([a62fc7c](https://github.com/OpenIndiana/oi-userland/commit/a62fc7cc46e00cc314f1d2b2e3bb018401ceac91))
- update to 9.2.0300 ([a760240](https://github.com/OpenIndiana/oi-userland/commit/a7602401a98f925b2e08e31dbd02f312bd974be4))
- update to 9.2.0350 ([c32d498](https://github.com/OpenIndiana/oi-userland/commit/c32d498c775d25cc425b69ca53d0add5aad7e652))
- update to 9.2.0400 ([e8295b0](https://github.com/OpenIndiana/oi-userland/commit/e8295b0db714afa000c10b6b2a3fbac80feca7d3))

### virtualbox

- update 7.2.4 ([aa36429](https://github.com/OpenIndiana/oi-userland/commit/aa3642966dbf9ae04f664f8d253f29f561e7cb27))
- update 7.2.6 ([f65d7c9](https://github.com/OpenIndiana/oi-userland/commit/f65d7c97fe783f5b4c23128d0533571cb6cc7a43))
- rebuild after qt6 upgrade ([ddb7bda](https://github.com/OpenIndiana/oi-userland/commit/ddb7bda88d7d95061a48f127a1d4387e4b53d440))
- update to 7.2.8 ([e5e6eb7](https://github.com/OpenIndiana/oi-userland/commit/e5e6eb79947b263e4030f9d208b5edb567f39834))

### vlc

- update to 3.0.23 ([f7d4fab](https://github.com/OpenIndiana/oi-userland/commit/f7d4fab4c2519a9aa755aafd708b5a291ccb1297))
- add SPARC support ([f952dad](https://github.com/OpenIndiana/oi-userland/commit/f952dad54e3e49920e5c2219235b62879e193a08))

### vte-291

- update to 0.82.2 ([3eaecd3](https://github.com/OpenIndiana/oi-userland/commit/3eaecd3b5b091fbde92537d505f66a7313841b70))
- update to 0.82.3 ([26a2e42](https://github.com/OpenIndiana/oi-userland/commit/26a2e42728ecbd89b28e388a8f6aa9a01d545ebe))
- update to 0.84.0 ([bb99d94](https://github.com/OpenIndiana/oi-userland/commit/bb99d94cefdf616e1c1ef0e05d08cefe103d3eee))

### w3m

- update to 0.5.6 ([b9bcd47](https://github.com/OpenIndiana/oi-userland/commit/b9bcd47e9e3adcf38e4e57f510f03bd76a18b5fe))

### wavpack

- update to 5.9.0 ([0cbd7d7](https://github.com/OpenIndiana/oi-userland/commit/0cbd7d7603560335a85590e759a869605ed7fbaf))

### webkitgtk

- update to 2.50.4 ([f47d8f1](https://github.com/OpenIndiana/oi-userland/commit/f47d8f12f0fd88dd163de0f712d715b3a96e0d84))
- re-add SPARC support ([fc3528f](https://github.com/OpenIndiana/oi-userland/commit/fc3528f6ed4a0dc52dcb5a01c9088d835c1e9a76))
- update to 2.50.5 ([d605d7c](https://github.com/OpenIndiana/oi-userland/commit/d605d7c393965710dd21243770baf90c07108387))
- update to 2.50.6 ([c94bf85](https://github.com/OpenIndiana/oi-userland/commit/c94bf85d6b4a9bc756ec30a8d7966bb2a4bb382e))
- update to 2.52.0 ([b8dbc1a](https://github.com/OpenIndiana/oi-userland/commit/b8dbc1a26f407f1611e2d0487e2c67f11b92ec93))
- update to 2.52.1 ([45c85ed](https://github.com/OpenIndiana/oi-userland/commit/45c85edcd9aae421098af089974662cb397dcf1d))
- update to 2.52.2 ([204ae4a](https://github.com/OpenIndiana/oi-userland/commit/204ae4a17f5c6dd6a841b5e8bec7538c9749cf6b))
- update to 2.52.3 ([048f0fc](https://github.com/OpenIndiana/oi-userland/commit/048f0fccc48195b9083c1575b33279e797930d1b))

### weechat

- update to 4.7.2 ([aa58a53](https://github.com/OpenIndiana/oi-userland/commit/aa58a53583abb806f63c56da0ac9c4276e6ded03))
- update to 4.8.1 ([7a9664b](https://github.com/OpenIndiana/oi-userland/commit/7a9664b8cabc0f344d42dc51d368debe67f1b2fb))
- update to 4.8.2 ([eefb98b](https://github.com/OpenIndiana/oi-userland/commit/eefb98b00981809c0cd43cbc5b1eb74ae36454ed))
- update to 4.9.0 ([18643c8](https://github.com/OpenIndiana/oi-userland/commit/18643c8a72a286a5a965f8a5d32bc089ffc79ce5))

### wget2

- update to 2.2.1 ([aaf72ec](https://github.com/OpenIndiana/oi-userland/commit/aaf72ec3b131c6a26227d0abe75c0f3fa0f97a2b))

### wireshark

- update to 4.6.1 ([eef1848](https://github.com/OpenIndiana/oi-userland/commit/eef184822e993bccfc1e1d258401fc437d3a81f3))
- update to 4.6.2 ([b764c0f](https://github.com/OpenIndiana/oi-userland/commit/b764c0fd0796a9105b803b2760451f0464477497))
- update to 4.6.3 ([6acec06](https://github.com/OpenIndiana/oi-userland/commit/6acec06781abbf5efbf80babcd00a71354197404))
- rebuild after qt6 upgrade ([e005dba](https://github.com/OpenIndiana/oi-userland/commit/e005dba66b4375728ad6b17e09e0f20a82e30a37))
- update to 4.6.4 ([e9331c4](https://github.com/OpenIndiana/oi-userland/commit/e9331c4905dfd133b94db1b5585fc7ffdfa85c9b))
- update to 4.6.5 ([1d79ab7](https://github.com/OpenIndiana/oi-userland/commit/1d79ab734f1e2a42f9d997cff36c2887da78239e))

### wsdd

- add to oi-userland ([3aebeb0](https://github.com/OpenIndiana/oi-userland/commit/3aebeb0506613628ecaef1329b98df14e3d50a5a))
- update SMF manifest ([36f1cf9](https://github.com/OpenIndiana/oi-userland/commit/36f1cf9cb96060bd918523a3c365c6496e322928))

### wxwidgets

- update to 3.2.10 ([ba7b913](https://github.com/OpenIndiana/oi-userland/commit/ba7b913839065e6ce2c3ab7e30fe9094bacb7f97))

### wxwidgets-3

- update to 3.2.9 ([8b3dd9d](https://github.com/OpenIndiana/oi-userland/commit/8b3dd9d1df956e2a63363eb63b3fde6c47a0be6c))

### x11-protocols

- update to 2025.1 ([4e396dd](https://github.com/OpenIndiana/oi-userland/commit/4e396ddc5d24963b25114fdce7768e5c6e5b9c2d))

### xapian

- update to 1.4.30 ([e75dc5f](https://github.com/OpenIndiana/oi-userland/commit/e75dc5f55109642b53dd2bf41858b158286cdcfb))
- update to 1.4.31 ([8b0411e](https://github.com/OpenIndiana/oi-userland/commit/8b0411eebe443e88c4db01c313256c0240358eb2))

### xauth

- update to 1.1.5 ([f77506a](https://github.com/OpenIndiana/oi-userland/commit/f77506a0e9b17080555b2a2c349ecd0de5dbad17))

### xbiff

- update to 1.0.6 ([c13eaf3](https://github.com/OpenIndiana/oi-userland/commit/c13eaf3d2063f926cdaf865f104e0dd4dd92c12a))

### xcalc

- update to 1.1.3 ([782cbbb](https://github.com/OpenIndiana/oi-userland/commit/782cbbb421b08e7f217ca72a84e765fd21ace374))

### xconsole

- update to 1.1.1 ([533840e](https://github.com/OpenIndiana/oi-userland/commit/533840efb7ae67b44c18ed539052420b823817f8))

### xfd

- update to 1.1.5 ([4b69cfc](https://github.com/OpenIndiana/oi-userland/commit/4b69cfcd1b07122a159870ca851c1a3e82dae17c))

### xkbcomp

- update to 1.5.0 ([27fbabf](https://github.com/OpenIndiana/oi-userland/commit/27fbabfe6e7478bffc05aff5faa6dc8c1ee18d3c))

### xkill

- update to 1.0.7 ([0bf3cdc](https://github.com/OpenIndiana/oi-userland/commit/0bf3cdc8883de050dabbc1fd1f71ca53edcf6458))

### xorg-cf-files

- update to 1.0.9 ([2beae0f](https://github.com/OpenIndiana/oi-userland/commit/2beae0f43dceef5ea537805d34ef3cf0841594fb))

### xorg-server

- fix SPARC manifest support ([a502d0c](https://github.com/OpenIndiana/oi-userland/commit/a502d0c75d82b3a5a781d18e3d4d010ea4ed5917))
- don't deliver files that are now in libxcvt ([da9f97a](https://github.com/OpenIndiana/oi-userland/commit/da9f97a7064283eed58a6ada22bca3f67ced608e))

### xorriso

- update to 1.5.8 ([a40324d](https://github.com/OpenIndiana/oi-userland/commit/a40324d2cd4f1d1fcffc4e7ea8e2cf71e6b525c4))
- update to 1.5.8.pl01 ([448529b](https://github.com/OpenIndiana/oi-userland/commit/448529b60ee89e6b8793fd5eeffed09769cbe0fe))

### xrandr

- update to 1.5.4 ([4481664](https://github.com/OpenIndiana/oi-userland/commit/44816641074bea422f958ae3a2cdef52f45965f5))

### xscreensaver

- update to version 6.10 ([9639a74](https://github.com/OpenIndiana/oi-userland/commit/9639a7483c1137aa25a2adcbda1d3fde0c94d5e6))

### xterm

- update to 404 ([57b5b69](https://github.com/OpenIndiana/oi-userland/commit/57b5b69b875aed303b927ae3ed53915668b3c20b))
- update to 405 ([cb896da](https://github.com/OpenIndiana/oi-userland/commit/cb896da8217eb0dcdb8aeec9b6627f0130e00265))
- update to 406 ([8a8ff12](https://github.com/OpenIndiana/oi-userland/commit/8a8ff12fc2816ffb5380c299d96530ddc798fc64))
- update to 407 ([881e1e9](https://github.com/OpenIndiana/oi-userland/commit/881e1e9f849430ed2662886a920157f6fbce1aa3))
- update to 409 ([991ba4e](https://github.com/OpenIndiana/oi-userland/commit/991ba4e69c5e5017069d3fd494d4bca5f6fc750d))

### xtrans

- update to 1.6.0 ([3909d9b](https://github.com/OpenIndiana/oi-userland/commit/3909d9bb14252013fa4bf2e5d3d255d9bce30551))

### xz

- update to 5.8.2 ([c0699b3](https://github.com/OpenIndiana/oi-userland/commit/c0699b38c02d0a0bbf043a3ceff5dd428df67d7e))
- update to 5.8.3 ([9cc8fff](https://github.com/OpenIndiana/oi-userland/commit/9cc8fffcf60c780dbdf4cda02c217bed2e1630bc))

### yara

- update to 4.5.5 ([bc99d25](https://github.com/OpenIndiana/oi-userland/commit/bc99d25640c67d7f0115957ea8537840cd81277b))

### zadm

- add dependency on library/perl-5/sun-solaris-privilege ([ee13b79](https://github.com/OpenIndiana/oi-userland/commit/ee13b792e58d96ed4ac19db5aabb1040439c0c43))

### zlib

- update to 1.3.2 ([a38dadb](https://github.com/OpenIndiana/oi-userland/commit/a38dadb601ef1ba815e1d18ef705b93937a9436c))
