---
title: "Snapshot 2025.10 Available"
description: "Regular snapshots have been updated. As always visit the Downloads page to get them or simply update. For Notable changes..."
pubDate: "2025-10-28"
---

Regular snapshots have been updated. As always visit the [Downloads](/downloads) page to get them or simply update.

## Notable Changes
In the last half year the following notable Changes have been made:
  - Introduction of several Rust based utilities with the Packaged directly from crates.io
    - Utilities like lsd, mergiraf, ripgrep, fd and other fancy tools
    - Helix Editor and IDE. (Note: there may be issues in getting LSP servers but the rust one is available)
  - Multiple Prolog Interpreters/VM's.
  - SunRay Maintenance work and improvements. (It's still a popular way to run Desktops for Families)
  - CVE Fixes for OpenSSH and OpenSSL (people usually get those via updates but important to mention that we keep an eye out for them)
  - A huge number of automated Python and Perl package updates.
  - Availability of Python 3.14 3.13, 3.12 and also 3.9
  - Availability of Distributed storage offerings Seaweedfs, garage and minio
  - SPARC support for Zabbix-server
  - Librewolf 144
  - Firefox 144
  - Thunderbird 144
  - Fish 4.0 (the one rewritten in Rust)
  - Libreoffice 25.8.2
  - Librecad 2.2

## Full Changelog

[3d9404c](https://github.com/OpenIndiana/oi-userland/commit/3d9404cc8660ff14ef6bffcce1cfdbb9934250ad)...[0df7ea7](https://github.com/OpenIndiana/oi-userland/commit/0df7ea760fd12599d94b2050425b1d2eb64e1f5c)

### Bug Fixes

- Fix rpm2cpio dependencies ([f174680](https://github.com/OpenIndiana/oi-userland/commit/f174680d92547e7ddf30dd2e626977a07ce2d307))
- Fix pgagent build ([f9f4562](https://github.com/OpenIndiana/oi-userland/commit/f9f456223845162ca7ac590fc6cb857f89fc4b1d))
- Fix foomatic-db build ([48bb625](https://github.com/OpenIndiana/oi-userland/commit/48bb625eeea9eddad4aef3b0fe99b16349290d89))

### SDL3

- Update to 3.2.22 ([0929c0c](https://github.com/OpenIndiana/oi-userland/commit/0929c0cb87bdb7dce7f72d66a87c5be88fdd47bd))
- Static lib is really needed ([a85dfb4](https://github.com/OpenIndiana/oi-userland/commit/a85dfb48e713ec8f5718d91363dd4e2123417d3d))

### SUNWxwplt

- Fix build version ([28a91e9](https://github.com/OpenIndiana/oi-userland/commit/28a91e93c6f3d31be6197fc90df3a9664f3dc567))

### X-incorporation

- Readd empty package ([3f9efd6](https://github.com/OpenIndiana/oi-userland/commit/3f9efd6b08cfc74c2d6588833bc556df15a0ff72))

### A2ps

- Update to 4.15.7 ([62a0faf](https://github.com/OpenIndiana/oi-userland/commit/62a0faf1640a483d64fc597c586fedd4d970331e))

### Abiword

- Update to 3.0.7 ([9fc1b6c](https://github.com/OpenIndiana/oi-userland/commit/9fc1b6c112bc624344100938e510c6955095affe))

### Ant

- Update to 1.10.15 ([77b28fb](https://github.com/OpenIndiana/oi-userland/commit/77b28fbf47f51346535ee3b57942edcbd223873c))

### Antlr4

- Add 4.13.2 ([c78cff3](https://github.com/OpenIndiana/oi-userland/commit/c78cff39c53daa2c5963325c3d6a9a3ea15ab714))
- Fix download ([e2be82d](https://github.com/OpenIndiana/oi-userland/commit/e2be82d1a256a9d92adb3b6ac07642c3e6dcf846))

### Apache-24

- Update to 2.4.65 ([9cf0a1d](https://github.com/OpenIndiana/oi-userland/commit/9cf0a1dfd47441d509c632c112b93cc66361020d))

### Apache24

- Update to 2.4.64 ([b2ff4fd](https://github.com/OpenIndiana/oi-userland/commit/b2ff4fd413af7da057b94170b83c8effe7a5b422))

### Appstream

- Update to 1.0.6 ([7a04ece](https://github.com/OpenIndiana/oi-userland/commit/7a04ece1cf417bbc3a7153cbb83e22bdf373beb2))
- Update to 1.1.1 ([044c5a3](https://github.com/OpenIndiana/oi-userland/commit/044c5a3f03729d2de6e190e93d1d02df4355c8e9))

### Appstream-glib

- Add 0.8.3 ([be3d40f](https://github.com/OpenIndiana/oi-userland/commit/be3d40fe0002073fa673a676837a65906ba1e152))

### At-spi2-core

- Update to 2.56.3 ([94c5c00](https://github.com/OpenIndiana/oi-userland/commit/94c5c00ff9b141ad516475f77cd1779fff38b7a9))
- Update to 2.56.4 ([a2f62d6](https://github.com/OpenIndiana/oi-userland/commit/a2f62d6247f7e902daaaf2244e80a72a199c86bf))
- Update to 2.56.5 ([961b223](https://github.com/OpenIndiana/oi-userland/commit/961b2232307541be864d63f34f780661924b7652))
- Update to 2.58.0 ([4d14f87](https://github.com/OpenIndiana/oi-userland/commit/4d14f87f0334877b841786f13c4a0e99f4592d07))
- Update to 2.58.1 ([09c534e](https://github.com/OpenIndiana/oi-userland/commit/09c534e9819fed230a5a3a104f7d0118d3ac84ac))

### Automake-1.18

- Update to 1.18.1 ([f9fe4b7](https://github.com/OpenIndiana/oi-userland/commit/f9fe4b760eb6b4e6b439a1c080a1a0e758d9f071))

### Babl

- Update to 0.1.114 ([9e37ebb](https://github.com/OpenIndiana/oi-userland/commit/9e37ebba808413af1d76702fe833365a8ce2e718))
- Update to 0.1.116 ([5d28121](https://github.com/OpenIndiana/oi-userland/commit/5d281211c2113f091a80a14e5c3ba5e6f2ad5c61))

### Bind

- Update to 9.18.37 ([225a349](https://github.com/OpenIndiana/oi-userland/commit/225a349152c5c8e2a22edf5f950b440d2e9f3f9e))
- Update to 9.18.39 ([182da08](https://github.com/OpenIndiana/oi-userland/commit/182da080bc90f6bbc5a3915cd130a81cea2924c2))
- Update to 9.18.41 ([e48526c](https://github.com/OpenIndiana/oi-userland/commit/e48526c68e7aeb5789e498e76dccbf5b00544fa9))

### Binutils

- Update to 2.45 ([899be86](https://github.com/OpenIndiana/oi-userland/commit/899be868af6bc6a587b84837e0536236f80d8d82))

### Botan

- Update to 3.9.0 ([36fb7f8](https://github.com/OpenIndiana/oi-userland/commit/36fb7f8b4767f48d4772e62e72b3b028bfaea8e7))

### Bvi

- Update to 1.5.0 ([174260a](https://github.com/OpenIndiana/oi-userland/commit/174260a9f04acbc5b06e3c25a69ef382747f5a31))

### C_icap

- Update to 0.6.4 ([ec71d2e](https://github.com/OpenIndiana/oi-userland/commit/ec71d2efcbdbf7aeee18d7a94b02a25ba15048fa))

### Ca-certificates

- Update to 2025.07.15 ([b97cbdb](https://github.com/OpenIndiana/oi-userland/commit/b97cbdbf6f087073a62ac5b52d00987a43d2deee))
- Update to 20250909 ([ccb7cd1](https://github.com/OpenIndiana/oi-userland/commit/ccb7cd12dd2703679e16168c00dc8c21c0b8df68))

### Calcmysky

- Update to 0.3.5 ([0bac4cf](https://github.com/OpenIndiana/oi-userland/commit/0bac4cfe9e647b94bb0edb97cd012d84ce1cf86f))

### Cargo.mk

- Normalize variable hash in test results ([62596ad](https://github.com/OpenIndiana/oi-userland/commit/62596adf6bc6f65515ebb36728cd92da03c4ee75))

### Ccache

- Update to 4.12.1 ([3b2f9f2](https://github.com/OpenIndiana/oi-userland/commit/3b2f9f267fbf2a1b7dc5a1a51c41a5e690de2d75))

### Cde-runtime

- Add empty package to satisfy SunRay install requirements ([67a0854](https://github.com/OpenIndiana/oi-userland/commit/67a0854f88a2742f249bf7730c7d200735a3c9df))

### Clang-20

- Update to 20.1.7 ([7057046](https://github.com/OpenIndiana/oi-userland/commit/70570463398460b37a62b4082c4eefa4a41c2662))
- Update to 20.1.8 ([43f4259](https://github.com/OpenIndiana/oi-userland/commit/43f4259286cb6bb63239b1501a8afeab0ec7c167))

### Cmake

- Update to 4.0.3 ([90e1ae4](https://github.com/OpenIndiana/oi-userland/commit/90e1ae4ec16138d52454a89ea4406be646f2d02d))
- Update to 4.1.0 ([8e017b7](https://github.com/OpenIndiana/oi-userland/commit/8e017b7c2abab0307adc2c0d6e5e25cce6fab720))
- Update to 4.1.1 ([c9118fe](https://github.com/OpenIndiana/oi-userland/commit/c9118feb66dac2c49c738b0e07ea53b4ec827c3c))
- Update to 4.1.2 ([45ec733](https://github.com/OpenIndiana/oi-userland/commit/45ec7331e51feace851a9ae812d6a99bfcacde8a))

### Cmocka

- Update to 1.1.8 ([7bf7ea5](https://github.com/OpenIndiana/oi-userland/commit/7bf7ea5c74f1df2f53ed1f1c2eff006cc4e58cfd))

### Coeurl

- Rebuild for library/libevent2 ([e7c4223](https://github.com/OpenIndiana/oi-userland/commit/e7c4223027ccca6643bb94eaa1c3b1519ca29600))

### Cog-spur

- Update to VMMaker.oscog-eem.3581 ([287133e](https://github.com/OpenIndiana/oi-userland/commit/287133e015ae60efe272770672619af64ed28f66))
- Update to VMMaker.oscog-eem.3610 ([dacae18](https://github.com/OpenIndiana/oi-userland/commit/dacae1855dbe2c3213a806f21c302155963a0b80))

### Compiz-plugins-extra

- Fix build for gcc-14 ([47f5e5c](https://github.com/OpenIndiana/oi-userland/commit/47f5e5cc3b7d2d4a682ab43ec4261bb2f0a6c763))

### Compiz-plugins-main

- Fix build for gcc-14 ([b094c0e](https://github.com/OpenIndiana/oi-userland/commit/b094c0e422d1bb763aadeb09f23edeb72b933c8a))

### Cryptopp

- Fix pkgconfig file ([d30e8fc](https://github.com/OpenIndiana/oi-userland/commit/d30e8fccd7c147655e3aebecc03e44a78620f32d))

### Cscope

- Fix build ([d35d558](https://github.com/OpenIndiana/oi-userland/commit/d35d5586b9f86ce71febb112f86286b1794c2f25))

### Cups

- Update to 2.4.14 ([6ba1646](https://github.com/OpenIndiana/oi-userland/commit/6ba16466d271091635e2b05fae282cacc4fa5b77))

### Curl

- Update to 8.15.0 ([58ad347](https://github.com/OpenIndiana/oi-userland/commit/58ad3473b4dbd1a03b4be0424bff52b6aca7b5f5))
- Update to 8.16.0 ([e2675a3](https://github.com/OpenIndiana/oi-userland/commit/e2675a3ec4ff95a5110795e4aecf96cfa20b0679))
- Add latest test results with valgrind ([535f964](https://github.com/OpenIndiana/oi-userland/commit/535f964c89ee495611b168108be1409bb7ecee11))

### Dbus

- Move dbus-daemon to /usr/bin; move 32 bit support to separate package ([e0f696a](https://github.com/OpenIndiana/oi-userland/commit/e0f696add4a59129b5719f6cb48bae79b2fcf5f5))

### Dbus-test-runner

- Dbus-daemon moved to /usr/bin ([f4eeb3c](https://github.com/OpenIndiana/oi-userland/commit/f4eeb3c4cb4a06bba668f54cbb557c67191f0289))

### Desktop-cache

- Fix manifest, use /tmp cache files while installing ([cc963af](https://github.com/OpenIndiana/oi-userland/commit/cc963af6ee33151403f908942b0b0ae6ddc82cc1))
- Fix gio-module-cache method script ([efd1cb5](https://github.com/OpenIndiana/oi-userland/commit/efd1cb537e3627f3755189c860053a13c4a8ccee))
- Fix gio-module-cache.sh script again ([36440bc](https://github.com/OpenIndiana/oi-userland/commit/36440bcd26821ce58415af5c3eb2b766c320886b))
- Revert changes from pull #22334 #22413 and #22416 ([c5f9aca](https://github.com/OpenIndiana/oi-userland/commit/c5f9acab5be9b37a3d119f90748b7f196448d985))
- Fix sparcv7 pixbuf-installer ([073eb22](https://github.com/OpenIndiana/oi-userland/commit/073eb2263bd99b70c8dfa18cb3fa9a9e03d9994d))

### Developer/scons

- Update to 4.10.0 ([74d4a79](https://github.com/OpenIndiana/oi-userland/commit/74d4a79582fd18ba212e3d01b2b138ae8f799220))

### Dhcp

- Add empty package to satisfy SunRay install requirements ([35f6127](https://github.com/OpenIndiana/oi-userland/commit/35f612716a487049b3b250f236fe1edbcc79b3b6))

### Djvulibre

- Update to 3.5.29 ([a3d0de5](https://github.com/OpenIndiana/oi-userland/commit/a3d0de50a1f9d98b279f7bf4912d55620a7c2db0))

### Dmenu

- Fix build with gcc-14 ([9bbc87e](https://github.com/OpenIndiana/oi-userland/commit/9bbc87e79425c925df4fa11277f609cd096ee464))
- Update to 5.4 ([ea10db4](https://github.com/OpenIndiana/oi-userland/commit/ea10db479692fb424980258b8bbdc226402ec886))

### Dmz-cursor-theme

- Modernize Makefile; switch to 64 bit ([8a344f6](https://github.com/OpenIndiana/oi-userland/commit/8a344f6e1c08c55ab8f00717de3bbbbd936f31ea))

### Doxygen

- Update to 1.15.0 ([dd576bf](https://github.com/OpenIndiana/oi-userland/commit/dd576bf89273f371d778708ef5e078476cf7b8b6))

### Easy-rsa

- Update to 3.2.3 ([4e01646](https://github.com/OpenIndiana/oi-userland/commit/4e01646f1f64a3570e64e9f42fd4b26c504c7569))
- Update to 3.2.4 ([73ef8a7](https://github.com/OpenIndiana/oi-userland/commit/73ef8a792404be3996ccc6520283be9256236ec7))

### Ecl

- Fix download url ([cdd868f](https://github.com/OpenIndiana/oi-userland/commit/cdd868f07127c184bb8658af4df766489b42ad58))

### Elixir

- Update to 1.19.1 ([a5b4a0e](https://github.com/OpenIndiana/oi-userland/commit/a5b4a0e6f7689f2f28563210afb598fb3728b9cb))

### Emacs

- Update to 30.2 ([4b91d44](https://github.com/OpenIndiana/oi-userland/commit/4b91d44b572fd391c3f410ccc965f92a5047435f))

### Enchant

- Update to 2.8.8 ([b68e9e8](https://github.com/OpenIndiana/oi-userland/commit/b68e9e8fc51b0392ead4021b612409248fd04a74))
- Update to 2.8.9 ([0492581](https://github.com/OpenIndiana/oi-userland/commit/04925817aaa4ada260402bbd93f9ed2c67a0b310))
- Update to 2.8.10 ([4cafa30](https://github.com/OpenIndiana/oi-userland/commit/4cafa300482704c1569a359cb572ed78c05a2459))
- Update to 2.8.11 ([2761095](https://github.com/OpenIndiana/oi-userland/commit/2761095c888e107e8e2a57402b07c0142fa0f66d))
- Update to 2.8.12 ([b6dfe5f](https://github.com/OpenIndiana/oi-userland/commit/b6dfe5f30505b3c4cff006b7b8e0f6ab96f633e0))

### Engrampa

- Fix build with gcc-14 ([bc533ef](https://github.com/OpenIndiana/oi-userland/commit/bc533ef514df8ba5707024026dd210cbf93bf690))

### Ephoto

- Modernize Makefile ([d3bba69](https://github.com/OpenIndiana/oi-userland/commit/d3bba69352e54107b4757b8ad6cbc41d37d592e4))

### Erlang

- Update to 28.0 ([c165f88](https://github.com/OpenIndiana/oi-userland/commit/c165f886d690529b4124195d74d1403725a475e7))
- Add SPARC support ([f4af08a](https://github.com/OpenIndiana/oi-userland/commit/f4af08aa83dbc778a3ed513e4726c3a5fe3d7802))
- Fix manifest ([2cb38ca](https://github.com/OpenIndiana/oi-userland/commit/2cb38ca2d1dc7c9cae5af6187e0d8e7194822fcb))
- Update to 28.0.1 ([210ca14](https://github.com/OpenIndiana/oi-userland/commit/210ca1442ec8728c3f142315054ab9ae6f4d1958))
- Update to 28.0.2 ([bf987d4](https://github.com/OpenIndiana/oi-userland/commit/bf987d46810c2fd0840af190c0ec853f4db13c02))
- Update to 28.0.4 ([89bd765](https://github.com/OpenIndiana/oi-userland/commit/89bd765125635b44c53c2ce7fa5c403055304a40))
- Update to 28.1 ([2908ffb](https://github.com/OpenIndiana/oi-userland/commit/2908ffb91e621070530b6422b8594dc95237c352))
- Re-add SPARC support ([5ba5202](https://github.com/OpenIndiana/oi-userland/commit/5ba52021b71755ce9cd731950667f88ce5205bb3))
- Update to 28.1.1 ([bf55c27](https://github.com/OpenIndiana/oi-userland/commit/bf55c27f18c7a82bc6f17f0f509121cca408257e))

### Exiv2

- Update to 0.28.6 ([61ee42d](https://github.com/OpenIndiana/oi-userland/commit/61ee42dfd9fd5a66e21529f6b370d16f1241f2df))
- Update to 0.28.7 ([b17d1d4](https://github.com/OpenIndiana/oi-userland/commit/b17d1d4f5af350a4cd5840bc79297ddb1cd16a05))

### Expat

- Update to 2.7.2 ([41d109f](https://github.com/OpenIndiana/oi-userland/commit/41d109f9a6ecd818915659ab0b836209af703191))
- Update to 2.7.3 ([495d215](https://github.com/OpenIndiana/oi-userland/commit/495d215e188348699afac42c20ab2720041792c7))

### Fast_float

- Update to 8.1.0 ([116d309](https://github.com/OpenIndiana/oi-userland/commit/116d309de8a1b44d00375f5668afe97ff14d1825))

### Fastfetch

- Update to 2.46.0 ([a8ced15](https://github.com/OpenIndiana/oi-userland/commit/a8ced154949c95b0233bbdc2c2bf4ab69be5b3c4))
- Update to 2.47.0 ([c616c6c](https://github.com/OpenIndiana/oi-userland/commit/c616c6c5a6f3531c46b942f7cc3966ad8b978f6e))
- Update to 2.48.0 ([130d814](https://github.com/OpenIndiana/oi-userland/commit/130d8149a1c579b779b8d9a2d8b9df68ff5c34e1))
- Update to 2.48.1 ([90e0dd4](https://github.com/OpenIndiana/oi-userland/commit/90e0dd44623d1c5c90de30b9952dfe97d845c8a2))
- Update to 2.49.0 ([50291a7](https://github.com/OpenIndiana/oi-userland/commit/50291a7d25a9b2cf448235d6a79db31d9097caf9))
- Update to 2.50.1 ([b36da4e](https://github.com/OpenIndiana/oi-userland/commit/b36da4e457b47911ab262c94f6c0cf7a7a7d33f1))
- Update to 2.50.2 ([299573d](https://github.com/OpenIndiana/oi-userland/commit/299573d39700157e87354fa60a24ea989e0147c6))
- Update to 2.51.1 (#23636) ([a378f13](https://github.com/OpenIndiana/oi-userland/commit/a378f1391f78797adcb7dcd79c68ec746e08eac4))
- Update to 2.52.0 ([c319a7b](https://github.com/OpenIndiana/oi-userland/commit/c319a7b1aaa537a052962c51561c965244d7b569))
- Update to 2.53.0 ([0274327](https://github.com/OpenIndiana/oi-userland/commit/02743272f7096555b8f09e3e248b2c15d1ca970b))
- Update to 2.54.0 ([fe5827e](https://github.com/OpenIndiana/oi-userland/commit/fe5827e265cc4755339d3d7c5d6b2ab868b7fd76))

### Fetchmail

- Update to 6.5.3 ([fd9d7af](https://github.com/OpenIndiana/oi-userland/commit/fd9d7afca873ffe3c52c7855f75299dd15272705))
- Update to 6.5.4 ([98f0e9c](https://github.com/OpenIndiana/oi-userland/commit/98f0e9c2a90b1f57fd992c0d554be80ad3242b19))
- Update to 6.5.5 ([c612e1e](https://github.com/OpenIndiana/oi-userland/commit/c612e1e792f4f5360428948ea2202e2a2a7c4654))
- Update to 6.5.6 ([2c2d694](https://github.com/OpenIndiana/oi-userland/commit/2c2d69450280c080ac9302e8f4fc38318d046da8))
- Update to 6.5.7 ([1261ab4](https://github.com/OpenIndiana/oi-userland/commit/1261ab424ef0dae3a3160ff4a99cfef0f577ba76))

### Ffmpeg

- Update to 7.1.2 ([e6a3b61](https://github.com/OpenIndiana/oi-userland/commit/e6a3b619f48cd379369a1c1faa8aa80c5872c874))

### Fio

- Update to 3.41 ([491072c](https://github.com/OpenIndiana/oi-userland/commit/491072c8fa78ccc5edb1ffef921663e9bc1ab525))

### Firefox

- Update to 139.0.4 ([54a2ec3](https://github.com/OpenIndiana/oi-userland/commit/54a2ec37185e7bfea82cbd422a5e45e05b1bfee6))
- Update to 140.0 ([5f7cc0b](https://github.com/OpenIndiana/oi-userland/commit/5f7cc0bf27c1525d44d612fa71099b1e89ff73e2))
- Update to 140.0.1 ([05a7992](https://github.com/OpenIndiana/oi-userland/commit/05a7992b96cba52bed195c18fba41301f9f22353))
- Update to 140.0.2 ([a10028d](https://github.com/OpenIndiana/oi-userland/commit/a10028db9fb3b79b99b8d3f55007d58a3187dd91))
- Update to 140.0.4 ([9fce434](https://github.com/OpenIndiana/oi-userland/commit/9fce434cec76584236a03a658dc32bebd1682fd9))
- Update to 141.0 ([75ec882](https://github.com/OpenIndiana/oi-userland/commit/75ec8825a1ecaefd10d3a424885333047f815d05))
- Update to 141.0.2 ([c7d5e86](https://github.com/OpenIndiana/oi-userland/commit/c7d5e86cdd2b19a4af765a23221ad88d1dd0003d))
- Update to 141.0.3 ([a58fb25](https://github.com/OpenIndiana/oi-userland/commit/a58fb25613f9954a65a9ca1e10bc5ddb51ba67e3))
- Update to 142.0 ([dab476c](https://github.com/OpenIndiana/oi-userland/commit/dab476c827e6cfc9cade558059cfc8387cb9cad3))
- Update to 142.0.1 ([768ac2f](https://github.com/OpenIndiana/oi-userland/commit/768ac2f7f3e7fac387d4833c6e1ad1cd95454e81))
- Update to 143.0 ([bf2efd7](https://github.com/OpenIndiana/oi-userland/commit/bf2efd73c9db8024ca304ce3f42e43842c9641fa))
- Update to 143.0.1 ([140245d](https://github.com/OpenIndiana/oi-userland/commit/140245de89db27fbf1a3e7d52237bdfb405833c1))
- Update to 143.0.3 ([d0cd5ee](https://github.com/OpenIndiana/oi-userland/commit/d0cd5ee5b36893e55b712a608b96eed6d2af8f8f))
- Update to 143.0.4 ([09503df](https://github.com/OpenIndiana/oi-userland/commit/09503df310f66b490503e16cd5cb96918b16fe41))
- Update to 144.0 ([8bf9174](https://github.com/OpenIndiana/oi-userland/commit/8bf9174aa64f93d27c56e5c1dfeef4d2f76fdc17))
- Fix Bug 1990430 ([ccc02f7](https://github.com/OpenIndiana/oi-userland/commit/ccc02f754616d69a7de886714b6e666ef3eff285))

### Fish

- Update to 4.0.2 ([56858a7](https://github.com/OpenIndiana/oi-userland/commit/56858a7d31bce77156966b6de25b6f4d8af12de7))
- Do not build docs ([f66a678](https://github.com/OpenIndiana/oi-userland/commit/f66a6782f5a72667b8919ae64776b2497669f12d))
- Update to 4.0.6 ([1603c50](https://github.com/OpenIndiana/oi-userland/commit/1603c50471dfe9728600039855d412e9751fb768))

### Flatbuffers

- Update to 25.9.23 ([87bbfb6](https://github.com/OpenIndiana/oi-userland/commit/87bbfb66a96d6d5302f778f98d609d4975ff8bce))

### Fmt

- Update to 12.0.0 ([5d8f419](https://github.com/OpenIndiana/oi-userland/commit/5d8f4196d52293ef2d18eb3fc6bf644c67a733d4))

### Fontconfig

- Update to 2.17.1; import/update some files from solaris-userland ([cf2457e](https://github.com/OpenIndiana/oi-userland/commit/cf2457ef4bed57efec6a7cb858de866bb650ead9))

### Foomatic-filters

- Fix build ([778ca21](https://github.com/OpenIndiana/oi-userland/commit/778ca21b4db1aeeba135e4d8d75d098972abc2b6))

### Fossil

- Update to 2.27 ([7a71a3c](https://github.com/OpenIndiana/oi-userland/commit/7a71a3c5d2e2f5a361ae7088ade1e61628b46257))

### Freeciv

- Update to 3.2.0 ([07ab0c6](https://github.com/OpenIndiana/oi-userland/commit/07ab0c6e6c13e3b42de1bcff8062d5fa1d765ecc))
- Update to 3.2.1 ([90c274a](https://github.com/OpenIndiana/oi-userland/commit/90c274ac39c184bbdedd88519b2c5b7cc2b84e06))

### Freeipmi

- Update to 1.6.16 ([fcb9796](https://github.com/OpenIndiana/oi-userland/commit/fcb97962836f65c46caff0832a7ddac467de26f9))

### Freetds

- Update to 1.5.2 ([8f958e6](https://github.com/OpenIndiana/oi-userland/commit/8f958e66799f4250d1d22d0982d1fa7636991c04))
- Update to 1.5.3 ([6a75956](https://github.com/OpenIndiana/oi-userland/commit/6a75956a255587aee52bfb1b1f45dac837a7ef7c))
- Update to 1.5.4 ([a37ab90](https://github.com/OpenIndiana/oi-userland/commit/a37ab905b80262706cfcbb8574283d09175a8184))
- Update to 1.5.5 ([0504336](https://github.com/OpenIndiana/oi-userland/commit/0504336e526715689c6a5bfe0264c5cb042c776e))
- Update to 1.5.6 ([1a29789](https://github.com/OpenIndiana/oi-userland/commit/1a29789bf3515d8ecbf977f0e1cec2b53be90e9c))

### Freetype

- Update to 2.14.0 ([edad6b0](https://github.com/OpenIndiana/oi-userland/commit/edad6b0420f79ae56f2425328efe8cdaec9188c2))
- Update to 2.14.1 ([59f17c2](https://github.com/OpenIndiana/oi-userland/commit/59f17c288cf3efc8dcd1190612c6a24bff49ca8e))

### Gaa

- Fix build ([300e1b4](https://github.com/OpenIndiana/oi-userland/commit/300e1b4e33f0e3e984ffc99f459adc8b653a380e))

### Garage

- Add garage ([499488b](https://github.com/OpenIndiana/oi-userland/commit/499488b7aee047a18c4aa1f8dc5be81aae3b0ad7))

### Gc

- Bump to 8.2.10 ([a0c6551](https://github.com/OpenIndiana/oi-userland/commit/a0c6551ffee6d83824fee644c81da6f564b29887))

### Gcc-13

- Update to 13.4.0; add test results filter ([34b6bef](https://github.com/OpenIndiana/oi-userland/commit/34b6bef1024792dcfdb819779c2ebb520e29b432))

### Gdb

- Update version 16.3 ([5649a31](https://github.com/OpenIndiana/oi-userland/commit/5649a31f4366f8e5ad129a4fa3ee9ab4178fa8d9))

### Gdbm

- Update to 1.26 ([b526441](https://github.com/OpenIndiana/oi-userland/commit/b5264412d53ffcb5f51fb5093cacae771390fdc5))

### Gdk-pixbuf

- Update to 2.43.5 ([8f28eed](https://github.com/OpenIndiana/oi-userland/commit/8f28eed94347d46124c280e46c242d3211795ffc))

### Gdm

- Readd with new package name gdm-2 ([127fd4f](https://github.com/OpenIndiana/oi-userland/commit/127fd4fd6bbe1a6242f938a8bce6de2de9b84b43))

### Geany

- Update to 2.1 ([f65fe87](https://github.com/OpenIndiana/oi-userland/commit/f65fe87f2d4b0b651669cf2014321345ed4b95de))

### Geany-plugins

- Update to 2.1 ([f2005ab](https://github.com/OpenIndiana/oi-userland/commit/f2005ab39c6ab5d2d7df4ad8bec5b6dac5045ec3))
- Autoreconf needs PATH ([9711d40](https://github.com/OpenIndiana/oi-userland/commit/9711d408f8a07ea95716e0e11a88088c80e6476c))

### Gegl

- New babl rebuild ([cd8cb4e](https://github.com/OpenIndiana/oi-userland/commit/cd8cb4e4d60fc58f530930a2ca6c6ad28fbd3486))
- Update to 0.4.64 ([b4826cd](https://github.com/OpenIndiana/oi-userland/commit/b4826cd7ab8ed5cabd255574a276092aefab65a7))

### Gentium

- Update to 7.000 ([4dfb238](https://github.com/OpenIndiana/oi-userland/commit/4dfb2380ffa2c859c2bca8e776e486c0db8a3c86))

### Geoip-database

- Update to 20250914 ([5874635](https://github.com/OpenIndiana/oi-userland/commit/58746358a52b5c4d705881812fd9e46796a9bd5f))

### Gettext

- Update to 0.25.1 ([b8ba196](https://github.com/OpenIndiana/oi-userland/commit/b8ba196f8cf745c66f77159943827676b393a294))
- Update to 0.26 ([17356a2](https://github.com/OpenIndiana/oi-userland/commit/17356a2b81e50701e8c97d82486eb15b744dda7e))
- Disable nls to prevent libintl creation ([7ae2300](https://github.com/OpenIndiana/oi-userland/commit/7ae23007bab708b64994118fdfe61946b1101d61))

### Gexiv2

- Update to 0.14.6 ([b1c73cc](https://github.com/OpenIndiana/oi-userland/commit/b1c73cc3d30196110f1f58291b82cf9d936570ef))

### Ghex

- Update to 46.3 ([8951726](https://github.com/OpenIndiana/oi-userland/commit/89517266cf2803e384504a337303110dd94b9183))

### Gimp

- Update to 3.0.4 ([05198cc](https://github.com/OpenIndiana/oi-userland/commit/05198ccf9b3c39edd3d735f2a38b8e3c60c2c9d2))
- Update to 3.0.6 ([aab5ec8](https://github.com/OpenIndiana/oi-userland/commit/aab5ec8f4fee804f1c45ac0f48329e27e17477f0))

### Git

- Update to 2.50.0 ([a53706e](https://github.com/OpenIndiana/oi-userland/commit/a53706eb70abf95afcdb0259e86f27fcc0556b79))
- Update to 2.50.1 ([5e1a6d3](https://github.com/OpenIndiana/oi-userland/commit/5e1a6d39a9c113b753c1c881e72a7c2f490d4e97))
- Update to 2.51.0 ([0657e85](https://github.com/OpenIndiana/oi-userland/commit/0657e85adabd969b4fcafead2ad3bbe297117b2c))
- Update to 2.51.1 ([0766b8d](https://github.com/OpenIndiana/oi-userland/commit/0766b8db16bd7cdd4b8af128218efb4b29bbc437))

### Gnome-commander

- Update to 1.18.3 ([f563382](https://github.com/OpenIndiana/oi-userland/commit/f56338248445cb35e6932cdc06f35b3e8f06f4f7))
- Update to 1.18.4 ([bb5df5c](https://github.com/OpenIndiana/oi-userland/commit/bb5df5c7073773cf1fc1cffa7a060c3e0af915c4))

### Gnome-desktop

- Add with package name gnome-desktop-2 ([f0b2fef](https://github.com/OpenIndiana/oi-userland/commit/f0b2feff06da1a92518d6dea68b7f9c965c8d6fb))
- Update to 44.4 ([dc3880f](https://github.com/OpenIndiana/oi-userland/commit/dc3880fe3ce17bab4a2ea26cf03fcd1971b032a9))

### Gnome-session

- Build 64bit, update autoconf process ([15a2188](https://github.com/OpenIndiana/oi-userland/commit/15a2188f45dbe3ff3a77b625247a0824c1a9ef81))

### Gnome-settings-daemon

- Add renamed package gnome-settings-daemon-2 ([b5094b4](https://github.com/OpenIndiana/oi-userland/commit/b5094b4ece0cc5c2f4e56fbcb78384e93dc12ac1))

### Gnu-cobol

- Fix build ([767ef89](https://github.com/OpenIndiana/oi-userland/commit/767ef89ab26b7e724a1bbdd89e0297c35890cf63))

### Gnupg

- Make sure development_version is not set; import some settings from solaris-userland ([4738c52](https://github.com/OpenIndiana/oi-userland/commit/4738c52309ac218a2f46a71c2a175f2de317312e))

### Gnuplot

- Update to 6.0.3 ([ba42215](https://github.com/OpenIndiana/oi-userland/commit/ba42215ca0310207271f8c947a6387f7b06b16fd))
- Add patches from solaris-userland; add missing demo data files ([7bc17a6](https://github.com/OpenIndiana/oi-userland/commit/7bc17a647cd79ec260a37fdb407877f66c517677))

### Gnutls

- Update to 3.8.10 ([29276b2](https://github.com/OpenIndiana/oi-userland/commit/29276b2133f54239287e78591cd867f8b391fe72))
- Fix build of tests ([4b3e56a](https://github.com/OpenIndiana/oi-userland/commit/4b3e56a8d25811a018ffde3fcfe96e37c2c335f6))

### Gobject-introspection

- Update to 1.86.0 ([8d1f199](https://github.com/OpenIndiana/oi-userland/commit/8d1f19994498697fe89ce364079a55639fc8b783))

### Gocr

- Modernize Makefile ([b3b8752](https://github.com/OpenIndiana/oi-userland/commit/b3b8752406814e6cbf41d526ad4b0fd72965430f))

### Golang

- Switch to 1.25 ([64c40a1](https://github.com/OpenIndiana/oi-userland/commit/64c40a1848271df5a16bf7dd0ff0f9c7c8b2a198))

### Golang-1.23

- Update to 1.23.11 ([cd2028c](https://github.com/OpenIndiana/oi-userland/commit/cd2028caeb4d5e1ef3e6064532d964e1fcbd2bd6))

### Golang-1.24

- Update to 1.24.8 ([037383d](https://github.com/OpenIndiana/oi-userland/commit/037383d448ce5ffeade97aba5caccbab7a485677))

### Golang-123

- Update to 1.23.10 ([6b55a56](https://github.com/OpenIndiana/oi-userland/commit/6b55a5645de43bbc225344e3633773f544179ad5))
- Update to 1.23.12 ([6bb0235](https://github.com/OpenIndiana/oi-userland/commit/6bb02354d7e25c44fe4188114080808874c0ef9e))

### Golang-124

- Update to 1.24.4 ([86a46f5](https://github.com/OpenIndiana/oi-userland/commit/86a46f561b7936ab119e4713a1a14bcc60793c72))
- Update to 1.24.5 ([20e3401](https://github.com/OpenIndiana/oi-userland/commit/20e3401a0b32368a3c260fc404903d0e70c3369f))
- Update to 1.24.6 ([8519caa](https://github.com/OpenIndiana/oi-userland/commit/8519caa54f62962a6b211164b575960e8344863e))
- Update to 1.24.7 ([0ae28b0](https://github.com/OpenIndiana/oi-userland/commit/0ae28b089f9dd84c523d67c94e3f7db797553b72))
- Update to 1.24.9 ([b830be1](https://github.com/OpenIndiana/oi-userland/commit/b830be1cd90dbdbdc79e2aa73060469a7f0560f4))

### Gom

- Update to 0.5.4 ([41f917b](https://github.com/OpenIndiana/oi-userland/commit/41f917b010ba442c7fa7f7453e61184146c88876))

### Gphoto2

- Update to 2.5.32; add test results ([8ea42ca](https://github.com/OpenIndiana/oi-userland/commit/8ea42ca970bd9cebf4641c5869f8d8c8a9ea55a6))

### Graphviz

- Rebuild for PHP 8.4 ([7161fe2](https://github.com/OpenIndiana/oi-userland/commit/7161fe287c63633c8fe6b1cd866942cc850234df))
- Force rebuild ([833579e](https://github.com/OpenIndiana/oi-userland/commit/833579e59e9a964214eb60bcc1d53f2f74680cc9))

### Grilo

- Update to 0.3.19 ([8869065](https://github.com/OpenIndiana/oi-userland/commit/8869065c26d1c1cbfef9fbaac2eeaf57521a396e))

### Grilo-plugins

- Update to 0.3.17 ([da7b7dd](https://github.com/OpenIndiana/oi-userland/commit/da7b7dd6d3b1672a1a9a8659a9d8ab74624863fd))
- Update to 0.3.18 ([5c2e6a8](https://github.com/OpenIndiana/oi-userland/commit/5c2e6a824a1e6c9889bdc5fed904142b5ac19a8a))

### Groovy-40

- Update to 4.0.27 ([c274c32](https://github.com/OpenIndiana/oi-userland/commit/c274c32b9653d5d3ddc8c80b030c667ae99d4022))
- Update to 4.0.28 ([ad20ee8](https://github.com/OpenIndiana/oi-userland/commit/ad20ee8f09cda00938e8f3560229cd89fcbaf9f4))
- Update to 4.0.29 ([0de2db7](https://github.com/OpenIndiana/oi-userland/commit/0de2db7ca7377bf8640282eb4bcdd130f0773ec5))

### Groovy-50

- Add 5.0.0 ([dafb0f6](https://github.com/OpenIndiana/oi-userland/commit/dafb0f6ce58d5afde827a6d436d0a57ff5c40850))
- Update to 5.0.1 ([954cb5a](https://github.com/OpenIndiana/oi-userland/commit/954cb5a429498f1e6634d732f27f0f56de460c2b))
- Update to 5.0.2 ([1ba79e8](https://github.com/OpenIndiana/oi-userland/commit/1ba79e88a86ff26ef055c7f7947b186152fb7eda))

### Gsm

- Update to 1.0.23 ([bbf84f9](https://github.com/OpenIndiana/oi-userland/commit/bbf84f9c4a1d8b2b5d202a0bf0786cd6302959fb))

### Gsoap

- Update to 2.8.139 ([4259ca9](https://github.com/OpenIndiana/oi-userland/commit/4259ca9cdef6e9ea344d00decd30abee50f852dd))

### Gst-devtools

- Update to 1.26.2 ([3689f4d](https://github.com/OpenIndiana/oi-userland/commit/3689f4dbd5c35e24476e64c0a28e72bd031975e9))
- Update to 1.26.3 ([1fb95f2](https://github.com/OpenIndiana/oi-userland/commit/1fb95f2fe13a29acd7a7219baf185857dc501130))
- Update to 1.26.4 ([dc5617e](https://github.com/OpenIndiana/oi-userland/commit/dc5617eafa1f7be14433af71198664e9568032ca))
- Update to 1.26.5 ([21d3d2f](https://github.com/OpenIndiana/oi-userland/commit/21d3d2ffc74b53c4998458a335a707ab44b65b03))
- Update to 1.26.6 ([cff3790](https://github.com/OpenIndiana/oi-userland/commit/cff379091adb3ae4fd73f53404cfaf375ccdcea4))
- Update to 1.26.7 ([e6993a1](https://github.com/OpenIndiana/oi-userland/commit/e6993a14c62f00e19477fe58f443c2550b9b3535))

### Gst-editing-services

- Update to 1.26.2 ([35f8ad3](https://github.com/OpenIndiana/oi-userland/commit/35f8ad30ac27aaf1ba03ee7c2b7b6d146043fc5a))
- Update to 1.26.3 ([515aa42](https://github.com/OpenIndiana/oi-userland/commit/515aa42ca0954edbe74bbad7433be5df145de1dc))
- Update to 1.26.4 ([f30f30f](https://github.com/OpenIndiana/oi-userland/commit/f30f30f1156421ad20af6bfb3f8d5ba9d364719a))
- Update to 1.26.5 ([e9c3ac1](https://github.com/OpenIndiana/oi-userland/commit/e9c3ac1e474866eadad8b3be938420b7e2b19b95))
- Update to 1.26.6 ([8f1312e](https://github.com/OpenIndiana/oi-userland/commit/8f1312ef61aad0c4b0d75650150f09348af83b2a))
- Update to 1.26.7 ([38979ee](https://github.com/OpenIndiana/oi-userland/commit/38979ee5d2576b37a5ce4d2f3781fe701fe527b1))

### Gst-libav

- Update to 1.26.2 ([c80aebe](https://github.com/OpenIndiana/oi-userland/commit/c80aebeecd627bd1bde03e0046992be64d2e4fc9))
- Update to 1.26.3 ([59b2de6](https://github.com/OpenIndiana/oi-userland/commit/59b2de64b33bed9def9860f617d5049c8984df1d))
- Update to 1.26.4 ([f9960c8](https://github.com/OpenIndiana/oi-userland/commit/f9960c8dd15fe602c32abc112bbe95d02645548b))
- Update to 1.26.5 ([77a6499](https://github.com/OpenIndiana/oi-userland/commit/77a64994c5475c7fed0cd6cb479d78bc6f995f3d))
- Update to 1.26.6 ([e13545f](https://github.com/OpenIndiana/oi-userland/commit/e13545fa98ef9372da7d4b7dc4f2fd4eeba91c71))
- Update to 1.26.7 ([500c8bf](https://github.com/OpenIndiana/oi-userland/commit/500c8bf2161937b17e5282a93d1ab9702768e200))

### Gst-plugins-bad

- Update to 1.26.3 ([427cfc3](https://github.com/OpenIndiana/oi-userland/commit/427cfc37d7d9f50ebd89b113a1f59cd6d3570ab6))
- Update to 1.26.4 ([e2af104](https://github.com/OpenIndiana/oi-userland/commit/e2af1047bb32129cfd60705d58ccf4f777026c00))
- Update to 1.26.5 ([d13f074](https://github.com/OpenIndiana/oi-userland/commit/d13f0742e63301e47f1bebc3b6ad7a8cb383159f))
- Update to 1.26.6 ([8105ccd](https://github.com/OpenIndiana/oi-userland/commit/8105ccd7ef3f44a2fe0c060d6a8b49cd41de3f53))
- Update to 1.26.7 ([9cf1dd7](https://github.com/OpenIndiana/oi-userland/commit/9cf1dd741a9492157358059796e80cbfbadb2cc8))
- Rebuild again for fixing openexr dependencies ([e571368](https://github.com/OpenIndiana/oi-userland/commit/e57136892f1bf26f1384dcbbb0ca74699004a5de))

### Gst-plugins-base

- Update to 1.26.3 ([c3029ff](https://github.com/OpenIndiana/oi-userland/commit/c3029fff92cc6f70ee6c571dcc463c362453b02b))
- Update to 1.26.4 ([22d7d32](https://github.com/OpenIndiana/oi-userland/commit/22d7d32b6044482e5ba4856c8be6eac41e290a93))
- Update to 1.26.5 ([515b451](https://github.com/OpenIndiana/oi-userland/commit/515b4517baaff8f291d74c3a79ce2f5dc17c3b02))
- Update to 1.26.6 ([f31059b](https://github.com/OpenIndiana/oi-userland/commit/f31059b397c2d2b500280a52f8dd75d7937115b1))
- Update to 1.26.7 ([672cc32](https://github.com/OpenIndiana/oi-userland/commit/672cc3293d3631c10f839586c316f1cf72695f82))

### Gst-plugins-good

- Update to 1.26.3 ([174085f](https://github.com/OpenIndiana/oi-userland/commit/174085f730deaef168271f9defebc68a0e3a1ef3))
- Update to 1.26.4 ([b11ab2f](https://github.com/OpenIndiana/oi-userland/commit/b11ab2f1e74ec30dc35add69e09fafb631b5ef02))
- Update to 1.26.5 ([5d8bcba](https://github.com/OpenIndiana/oi-userland/commit/5d8bcbad6a19396407643dc90a60c5f371914ed6))
- Update to 1.26.6 ([6bb1766](https://github.com/OpenIndiana/oi-userland/commit/6bb1766ea2ebaeb875fded02e2c8c378a73c8e78))
- Update to 1.26.7 ([c996cd4](https://github.com/OpenIndiana/oi-userland/commit/c996cd449168a662e806aa462200466156078c00))

### Gst-plugins-ugly

- Update to 1.26.2 ([b06f062](https://github.com/OpenIndiana/oi-userland/commit/b06f0628e7b585dd44d86e725758f1af85d5067e))
- Update to 1.26.3 ([3e60f97](https://github.com/OpenIndiana/oi-userland/commit/3e60f976333ad341a3c0616ef6b9b14f187a9195))
- Update to 1.26.4 ([962f3c6](https://github.com/OpenIndiana/oi-userland/commit/962f3c6ba0f990bfb20cbcee99e43c1e1952a3ee))
- Update to 1.26.5 ([97c246e](https://github.com/OpenIndiana/oi-userland/commit/97c246e6ea80ed22cca5a3f3ec37cc77a21fa885))
- Update to 1.26.6 ([28631af](https://github.com/OpenIndiana/oi-userland/commit/28631af7fb526e788164ab2997737fff260baf50))
- Update to 1.26.7 ([769a22f](https://github.com/OpenIndiana/oi-userland/commit/769a22f1037413573370027ff4e2537b52a50a59))

### Gst-python

- Update to 1.26.2 ([fb016cc](https://github.com/OpenIndiana/oi-userland/commit/fb016cc146eba4a2cab4c07507592da373a56d90))
- Update to 1.26.3 ([0fdc943](https://github.com/OpenIndiana/oi-userland/commit/0fdc9431450ec6844300d2333197c3527f422bdf))
- Update to 1.26.4 ([ae00223](https://github.com/OpenIndiana/oi-userland/commit/ae00223358b8f40309dbbe61dbe9367e02b76f7d))
- Update to 1.26.5 ([8d3c241](https://github.com/OpenIndiana/oi-userland/commit/8d3c241169446dd1f32d6d702fa65f68bdb28ef2))
- Update to 1.26.5 ([2a9c8dc](https://github.com/OpenIndiana/oi-userland/commit/2a9c8dcb39efee7bb37cd2f8fb687e94192e2c56))

### Gst-rstp-server

- Update to 1.26.2 ([9c0a4c6](https://github.com/OpenIndiana/oi-userland/commit/9c0a4c65b2a869db3334b81e219ddb364e110ef0))

### Gst-rtsp-server

- Update to 1.26.3 ([5a89c4c](https://github.com/OpenIndiana/oi-userland/commit/5a89c4cab6ee4f8e2900d1000ada0a0a02ebc933))
- Update to 1.26.4 ([dc200d7](https://github.com/OpenIndiana/oi-userland/commit/dc200d7b9fb9a850e715fc085c4c7f7d72133ed0))
- Update to 1.26.5 ([8ef042c](https://github.com/OpenIndiana/oi-userland/commit/8ef042c3146b5e440e1ece5f9d0cd46b552a238f))
- Update to 1.26.6 ([6b8b8fe](https://github.com/OpenIndiana/oi-userland/commit/6b8b8fe1f19ce3d045148f2ac3562e6141b9dee6))
- Update to 1.26.7 ([a56921c](https://github.com/OpenIndiana/oi-userland/commit/a56921c5719e1246860324b34853337a2eeecde3))

### Gstreamer

- Update to 1.26.3 ([83747ff](https://github.com/OpenIndiana/oi-userland/commit/83747ff2d083f1e4d28399f5a928802b63382e29))
- Update to 1.26.4 ([a82cdc8](https://github.com/OpenIndiana/oi-userland/commit/a82cdc8296789eec4a0fb704cf7418b9469d89fa))
- Update to 1.26.5 ([779b6bc](https://github.com/OpenIndiana/oi-userland/commit/779b6bc1c13a53aa810f379e0979d0af7ffbe831))
- Update to 1.26.6 ([3843d5f](https://github.com/OpenIndiana/oi-userland/commit/3843d5f0200d6a64e66c7b58a84f1f546d9dcf54))
- Update to 1.26.7 ([24129e3](https://github.com/OpenIndiana/oi-userland/commit/24129e3d47c258ab9b6056dd2a34128b41550709))

### Gtk+3

- Update to 3.24.50 ([06c0b05](https://github.com/OpenIndiana/oi-userland/commit/06c0b052572de5847cb95010362b8788ef90686f))
- Update to 3.24.51 ([d24eb79](https://github.com/OpenIndiana/oi-userland/commit/d24eb7933a51e1bfbe710caa462ab29e3ec69bbe))

### Gtk2-engines-murrine

- Drop 32 bit; move sources to gnome folder ([1fc70db](https://github.com/OpenIndiana/oi-userland/commit/1fc70db12df0c943b298410a4861d4f9d082aeee))

### Gtkam

- Obsolete image/editor/gimp/plugin/gimp-gtkam; update gtkam to 1.1 ([c78fa52](https://github.com/OpenIndiana/oi-userland/commit/c78fa523ac411a6751ac07cb5ac8edf95e20f77a))

### Gtkspell

- Fix build; drop 32 bit ([d9a6d39](https://github.com/OpenIndiana/oi-userland/commit/d9a6d390ee207f2658b93d07758f9e44e0d8337c))

### Guile

- Fix build with gcc-14; update dependencies ([41e634d](https://github.com/OpenIndiana/oi-userland/commit/41e634d53f3393c18efde9f1b9012c6825951bd1))

### Gvfs

- Update to 1.26.3; update metadata ([91d9779](https://github.com/OpenIndiana/oi-userland/commit/91d9779e0aa88aa8b93d93cf1a5ae773ce95ae65))

### Harfbuzz

- Update to 11.3.2 ([2b8724d](https://github.com/OpenIndiana/oi-userland/commit/2b8724d819b71bf155983b98e3f3b61a73ab7e92))
- Update to 10.3.3 ([be4744d](https://github.com/OpenIndiana/oi-userland/commit/be4744d0c1314d4d14421ec164efec90d2e5b074))
- Update to 11.4.1 ([108c45f](https://github.com/OpenIndiana/oi-userland/commit/108c45f467638c900e98419728fcf70a953718c3))
- Update to 11.4.2 ([5a700d1](https://github.com/OpenIndiana/oi-userland/commit/5a700d1c4ada299ebd5a7204bbf7c97458f560b5))
- Update to 11.4.3 ([d005be5](https://github.com/OpenIndiana/oi-userland/commit/d005be51ad8402b63c5b6de25a465c9c6fc7d4b9))
- Update to 11.4.4 ([fd54514](https://github.com/OpenIndiana/oi-userland/commit/fd545146843707ed4cc2811b99d5eb3ec00ac5aa))
- Update to 11.4.5 ([f42455d](https://github.com/OpenIndiana/oi-userland/commit/f42455ddfbde703970937a2b4b1713794a24cc81))
- Update to 11.5.0 ([0558822](https://github.com/OpenIndiana/oi-userland/commit/055882234815f5dac463b78500692ef273aa795a))
- Update to 11.5.1 ([0a890bc](https://github.com/OpenIndiana/oi-userland/commit/0a890bcb20fed520345b0b80d60767aad3821104))
- Update to 12.0.0 ([4e563ec](https://github.com/OpenIndiana/oi-userland/commit/4e563ecbb9fe950748f76e530b53fe674d04f600))
- Update to 12.1.0 ([4d4499b](https://github.com/OpenIndiana/oi-userland/commit/4d4499b04cfced99b6ba14ce33f1a28444d9cccb))

### Hiredis

- Update to 1.3.0 ([0f27bd3](https://github.com/OpenIndiana/oi-userland/commit/0f27bd37926ae792c8a1eedc83fe7a9310b24683))

### History

- Fix php 8.1 obsoletion ([88e9cde](https://github.com/OpenIndiana/oi-userland/commit/88e9cded6de1e5e51c6a95cd83205e65e84ae624))
- Rename system/input-method/ibus/ibus-m17n to system/input-method/ibus/m17n ([6b373f0](https://github.com/OpenIndiana/oi-userland/commit/6b373f080bf4c77501ecafbd2fe9d97c1f941708))
- Do not incorporate library/libmediainfo ([adcc536](https://github.com/OpenIndiana/oi-userland/commit/adcc5368230e77f1cdf476176b28009a9cfc3fb9))

### Hplip

- Update to 3.25.6 ([389bd87](https://github.com/OpenIndiana/oi-userland/commit/389bd8741a173af48f769754a68fd8b83073ca18))

### Htop

- Import version patch from OmniOS ([eb77d2a](https://github.com/OpenIndiana/oi-userland/commit/eb77d2a2ab7acf026e9aff2a0cdde5e7c582e2ab))
- Fix metadata ([d0b76f1](https://github.com/OpenIndiana/oi-userland/commit/d0b76f16857a92713d9fdff9160cb780c0dacc4d))

### Ibus

- Update to 1.5.29 ([b33f4d2](https://github.com/OpenIndiana/oi-userland/commit/b33f4d22166be624fc168817252ca252ca419457))

### Ibus-anthy

- Update to 1.5.17 ([31952a9](https://github.com/OpenIndiana/oi-userland/commit/31952a927e5a05007df6bd6364a554953ba08693))

### Ibus-chewing

- Update to 2.1.5 ([8dfcee3](https://github.com/OpenIndiana/oi-userland/commit/8dfcee3fba306e8078b8df148ed1b8e9117f86f8))
- Update to 2.1.7; add test results ([0fa8d5f](https://github.com/OpenIndiana/oi-userland/commit/0fa8d5f89f2037c2b48bc2e82d28198d7c47b527))

### Ibus-table

- Update to 1.17.13 ([b51705c](https://github.com/OpenIndiana/oi-userland/commit/b51705cbf7e8b530bb272b82f7a1ee789160ab82))
- Update to 1.17.14 ([16eab0f](https://github.com/OpenIndiana/oi-userland/commit/16eab0fe7fcca3fbc9d7f5adebfcc361b820eb02))
- Update to 1.17.15 ([5741556](https://github.com/OpenIndiana/oi-userland/commit/5741556a5771dddde83a93ebbda9287b4226ae04))
- Update to 1.17.16 ([b1acd5e](https://github.com/OpenIndiana/oi-userland/commit/b1acd5e587dda00471a884de132277900ef6604f))

### Ibus-table-chinese

- Update to 1.8.13 ([482fd40](https://github.com/OpenIndiana/oi-userland/commit/482fd40c83b3f42eb279098f75a25078208b293d))
- Update to 1.8.14 ([788040b](https://github.com/OpenIndiana/oi-userland/commit/788040b7dc83ea48eb2dda5f20b0b08f413554d0))

### Ibus-table-others

- Update to 1.8.21 ([1a499e1](https://github.com/OpenIndiana/oi-userland/commit/1a499e188a74a55f107a8c68d4b7dcf27577ec54))

### Icon-naming-utils

- Fix build dependencies; allow libexec folder ([b07c317](https://github.com/OpenIndiana/oi-userland/commit/b07c3178b3f095e7e0d726d7aea88e8c3e98127c))

### Illumos-gate

- Do not run pkglint; do not check for cstyle/hdrchk errors ([a1edd31](https://github.com/OpenIndiana/oi-userland/commit/a1edd3176cb7037ad0bef57b0febbadba9dd04d1))
- Align NIGHTLY_OPTIONS for DEBUG=yes build with non-DEBUG build ([374029f](https://github.com/OpenIndiana/oi-userland/commit/374029f92caf31763db73ec030e9ed82e7c9d162))
- Explicit Python setup for nightly ([b3781b5](https://github.com/OpenIndiana/oi-userland/commit/b3781b599c7b1b76c7b88c61ce829da1787c37e4))

### Imagemagick

- Update to 7.1.2-0 ([d4cb303](https://github.com/OpenIndiana/oi-userland/commit/d4cb30321951ea5c0120d6cf4e7164c2ccb21efc))

### Imath

- Update to 3.2.0 ([d3a6db4](https://github.com/OpenIndiana/oi-userland/commit/d3a6db40ea87f213cd8b49f4eefc8a296628f208))
- Update to 3.2.1 ([8efe6ce](https://github.com/OpenIndiana/oi-userland/commit/8efe6ce94d86bb18aec3ba772287fa3a98fbcf83))
- Update to 3.2.2 ([ba2f224](https://github.com/OpenIndiana/oi-userland/commit/ba2f2248421a3cd30e5c9d70a7a47353bf2bde5b))

### Imlib2

- Add 1.12.5 ([68730f8](https://github.com/OpenIndiana/oi-userland/commit/68730f8ad414eb8a38d611f971ef373984adbb6c))

### Inih

- Update to 61 ([8f62b64](https://github.com/OpenIndiana/oi-userland/commit/8f62b649af3b7a707a3f14f3931955a8ee4668df))
- Update to r62 ([4085283](https://github.com/OpenIndiana/oi-userland/commit/4085283a4f6e1d8870e4e9342bc70f1538a351a8))

### Inkscape

- Rebuild for gsl 2.8 ([d34ca0d](https://github.com/OpenIndiana/oi-userland/commit/d34ca0d1faac61a9a8e91fae35bc4a5d1e3d00a6))

### Install-types

- Add mate support for SPARC ([67f1099](https://github.com/OpenIndiana/oi-userland/commit/67f10992a86f836dd3c17c6df72334fc8f6bf181))
- Remove system/font/truetype/arphic-uming from desktop common ([8436ef7](https://github.com/OpenIndiana/oi-userland/commit/8436ef74e549b2a89eea2135f739e6665d673fa1))
- Add NFS file system SVC to server profile ([d6337f2](https://github.com/OpenIndiana/oi-userland/commit/d6337f2dacfe28246fb70a5a40eecd6fa6059694))

### Ips.mk

- Simpler and versatile PKG_VARS to PKG_OPTIONS transition ([4101e65](https://github.com/OpenIndiana/oi-userland/commit/4101e652f35e05dccd76e1ef4867e2a6ed7337a0))
- Add GENERATE_EXTRA_SED for more ways to mangle generated manifest ([28b1976](https://github.com/OpenIndiana/oi-userland/commit/28b1976e097eb6bd3cdeb1d8277b64a906f793a9))
- Allow to set environment for pkgdepend generate ([94aed61](https://github.com/OpenIndiana/oi-userland/commit/94aed619cd50e0e65e3f1bec9c60622f2c0c62b8))

### Janet

- Update to 1.39.0 ([4cfdc24](https://github.com/OpenIndiana/oi-userland/commit/4cfdc2497097e3e575cb0959ff5b7a00d61f5ce3))
- Update to 1.39.1 ([c4c42dd](https://github.com/OpenIndiana/oi-userland/commit/c4c42dd27e6da31bcd26779f256857cbaf4b73d4))

### Jasper

- Update to 4.2.7 ([cf51478](https://github.com/OpenIndiana/oi-userland/commit/cf514786bdf556ee6e0382243029c73dd429e310))
- Update to 4.2.8 ([7df2a6e](https://github.com/OpenIndiana/oi-userland/commit/7df2a6e06edbb3790d945f3b5d2e4e1e0edc25eb))

### Jenkins-core-lts

- Update to 2.504.3 ([24e71ae](https://github.com/OpenIndiana/oi-userland/commit/24e71ae8bc9d0daff581f1725028d123b8a6a1b1))
- Update to 2.516.1 ([d447a44](https://github.com/OpenIndiana/oi-userland/commit/d447a443b433f10e140637faf94cd2d30215b5bd))
- Update to 2.516.2 ([c4ac067](https://github.com/OpenIndiana/oi-userland/commit/c4ac067025a3a9fd19f17e6f2704e1960da1de7a))
- Update to 2.516.3 ([331c7ee](https://github.com/OpenIndiana/oi-userland/commit/331c7eebcffb1eeb77a4ed693f4541bdf1919ca7))
- Remove mediator-version ([f0a4014](https://github.com/OpenIndiana/oi-userland/commit/f0a40144ca2178dab48f9499a110544199ce0cd3))
- Update to 2.528.1 ([4d214a8](https://github.com/OpenIndiana/oi-userland/commit/4d214a8803531a2e51b1ac49b18b56b3f26c9122))

### Jenkins-core-weekly

- Update to 2.514 ([6bf759a](https://github.com/OpenIndiana/oi-userland/commit/6bf759ac787fc60e8858f68d97ebe9fbb45ebc61))
- Update to 2.516 ([264c672](https://github.com/OpenIndiana/oi-userland/commit/264c672921877bd727fe5b06e152a751f0d75817))
- Update to 2.519 ([0faaf68](https://github.com/OpenIndiana/oi-userland/commit/0faaf683cacbea918ac1a563ae74e03366ff82d2))
- Update to 2.520 ([6c84401](https://github.com/OpenIndiana/oi-userland/commit/6c84401d317b258dd8134a593535c4252ce02180))
- Update to 2.522 ([cc5c06e](https://github.com/OpenIndiana/oi-userland/commit/cc5c06ed752065ee6a656be937014c440f51e5db))
- Update to 2.524 ([70bdee1](https://github.com/OpenIndiana/oi-userland/commit/70bdee1e1d571020bb8fb3d509e26acf56daa576))
- Update to 2.527 ([523f59f](https://github.com/OpenIndiana/oi-userland/commit/523f59f23883aa31e5196c70723f0f2e5cac2f23))
- Update to 2.528 ([94b12f7](https://github.com/OpenIndiana/oi-userland/commit/94b12f7c0565c8fd76ef67bab25ee9d262b0c199))
- Update to 2.530 ([b05369c](https://github.com/OpenIndiana/oi-userland/commit/b05369c92acc09d57a5788e96fdc82c2d138c46f))
- Update to 2.532; remove mediator-version ([daeacd6](https://github.com/OpenIndiana/oi-userland/commit/daeacd6843bb6299438f1ae8a38a378873ec8727))

### Joe

- Fix build ([4fab8c2](https://github.com/OpenIndiana/oi-userland/commit/4fab8c2b614550dfe2b454b43e044f7184b7464f))

### Jq

- Update to 1.8.0; add CVE patch from solaris-userland ([f7b7bcc](https://github.com/OpenIndiana/oi-userland/commit/f7b7bcca7695235d69114b33089084a7f709a5ce))

### Kvm

- Fix build ([812a575](https://github.com/OpenIndiana/oi-userland/commit/812a575c606beec96af4763a683b7f34d1ae0366))

### Less

- Update to 679 ([5ea3a47](https://github.com/OpenIndiana/oi-userland/commit/5ea3a47f2627152b3725ddc69bb88b7d237fe834))
- Update to 685 ([9a48250](https://github.com/OpenIndiana/oi-userland/commit/9a48250d5e58f2366bc7e8b994f986914a4b296b))

### Lft

- Update to 3.93 ([2493d7f](https://github.com/OpenIndiana/oi-userland/commit/2493d7fabae9b75f63275d23d5fad26584dd07a5))

### Lib2geom

- Rebuild for gsl 2.8 ([1dd8f00](https://github.com/OpenIndiana/oi-userland/commit/1dd8f00c9f47aa4de16f0ecadbbfb6f3e54dd87e))

### Libadwaita

- Update to 1.6.8 ([6487f92](https://github.com/OpenIndiana/oi-userland/commit/6487f929c7000eff5c83f3dbc305fc179322cbf1))
- Update to 1.6.9 ([fde43dd](https://github.com/OpenIndiana/oi-userland/commit/fde43ddabe58f35075004685845f95db53bc7a18))
- Update to 1.6.10 ([692d37b](https://github.com/OpenIndiana/oi-userland/commit/692d37b386bffaef7e078d6b27d47079f56afda0))

### Libarchive

- Update to 3.8.2 ([2dad8e8](https://github.com/OpenIndiana/oi-userland/commit/2dad8e8bc24155ad859bf3e014c189f07955b3ed))

### Libass

- Update to 0.17.4 ([987e260](https://github.com/OpenIndiana/oi-userland/commit/987e26066c301229d7793933b56bd8794f864c56))

### Libdiscid

- Update to 0.6.5; drop 32 bit ([be38bb8](https://github.com/OpenIndiana/oi-userland/commit/be38bb8e03c8d1f247b0aaf0bbdc62ddeddfed6d))

### Libetonyek

- Update to 0.1.13 ([741bf79](https://github.com/OpenIndiana/oi-userland/commit/741bf79188ce38dbc53636dccf38e2f32c638a2c))

### Libevent

- Obsolete libevent-1.4.15 ([7d2a7ea](https://github.com/OpenIndiana/oi-userland/commit/7d2a7ea8a1e119ec196d02c55f3f3494e651625b))

### Libevent2

- Normalize includes / add SPARC support ([7f7bd1e](https://github.com/OpenIndiana/oi-userland/commit/7f7bd1ec46935f2f97f7451634512dec46744b65))

### Libexif-gtk

- Drop 32bit library support ([96dd024](https://github.com/OpenIndiana/oi-userland/commit/96dd0244b575d913396d9c65584d5f561609f924))

### Libgcrypt

- Update to 1.11.2 ([be29569](https://github.com/OpenIndiana/oi-userland/commit/be29569b9da0cb49908fd27431f8121fbee2ace2))

### Libgdiplus

- Update to 6.2 ([9fc42c3](https://github.com/OpenIndiana/oi-userland/commit/9fc42c3cf6d4a6658fc5f5e05098a246e9f95610))

### Libgit2

- Update to 1.9.1 ([7fa50d8](https://github.com/OpenIndiana/oi-userland/commit/7fa50d8d6d6b549707829b7fe58b7e9d545d8276))

### Libgnomekbd

- Readd ([9a718f9](https://github.com/OpenIndiana/oi-userland/commit/9a718f90723ff1f0935827ee3e1e75979bbec871))

### Libgpg-error

- Update to 1.56 ([98a5ea0](https://github.com/OpenIndiana/oi-userland/commit/98a5ea0e0a7e2d608c1f935aa01ac217bce9aa58))

### Libheif

- Update to 1.20.0 ([3910603](https://github.com/OpenIndiana/oi-userland/commit/3910603e9189428607bf711edab560505d019813))
- Update to 1.20.1 ([f0524e9](https://github.com/OpenIndiana/oi-userland/commit/f0524e9eda2b65078865f259e0bf109d49268db5))
- Update to 1.20.2 ([17cdf0c](https://github.com/OpenIndiana/oi-userland/commit/17cdf0c018b086afe8c8a9fc3f82eb22406770b8))

### Libjpeg-turbo

- Update to 3.1.1 ([5449e5c](https://github.com/OpenIndiana/oi-userland/commit/5449e5ca963119c9203c5b160e269116fe0506e6))
- Update to 3.1.2 ([8354a3d](https://github.com/OpenIndiana/oi-userland/commit/8354a3de94dd45b6c31fd3f538bfab476b96c3d0))

### Liblouis

- Update to 3.34.0 ([59b21d1](https://github.com/OpenIndiana/oi-userland/commit/59b21d1565a5f917b592621fe02a15c7bb8e17de))
- Update to 3.35.0 ([23f7839](https://github.com/OpenIndiana/oi-userland/commit/23f783988b7a4dc27a8b0ca6c13cf6680a384926))

### Libmad

- Update to 0.16.4 ([744a52d](https://github.com/OpenIndiana/oi-userland/commit/744a52d8e7ab7b042ed748daba82ed858bc26a9c))
- Fix Makefile ([214a97d](https://github.com/OpenIndiana/oi-userland/commit/214a97d35811704b9995bc6a84e4b5f30efd0e6f))

### Libmediainfo

- Update to 25.04 ([e5a588f](https://github.com/OpenIndiana/oi-userland/commit/e5a588f5c6ea5ac22b3cfe0e9b45a8d52dff315a))

### Libmodbus

- Update to 3.1.11 ([71c227b](https://github.com/OpenIndiana/oi-userland/commit/71c227b2eb0ca7219bb728ea2ab660d2dda070b6))

### Libnotify

- Update to 0.8.7 ([a4bdd7c](https://github.com/OpenIndiana/oi-userland/commit/a4bdd7c0db65b5f6eb638e0244a8a51a7a30a52b))

### Libogg

- Update to 1.3.6 ([b077959](https://github.com/OpenIndiana/oi-userland/commit/b077959f7664e166a5a643efd1a2e3d656fc0c31))
- Add SPARC support ([18ff483](https://github.com/OpenIndiana/oi-userland/commit/18ff483ae0c81ff76e436434eb86759347519243))

### Libpng16

- Update to 1.6.49 ([e671084](https://github.com/OpenIndiana/oi-userland/commit/e671084e0bc84dd726025c090b5f1403455d058a))
- Update to 1.6.50 ([2e6e7b8](https://github.com/OpenIndiana/oi-userland/commit/2e6e7b81ebbeee4648a53eb728762c216dfda8a4))

### Libpoppler

- Update to 25.10.0 ([5da680d](https://github.com/OpenIndiana/oi-userland/commit/5da680d2f5fd40b0710f38fd69318d29b621e799))

### Libqb

- Add test results ([110d0be](https://github.com/OpenIndiana/oi-userland/commit/110d0be1dcae36501cf905c4de36cc0d0f3369eb))

### Library/objfw

- Update to 1.3.1 ([a307538](https://github.com/OpenIndiana/oi-userland/commit/a307538ac369f01726e8de50585aee19a4d7475b))
- Update to 1.3.2 ([115d90b](https://github.com/OpenIndiana/oi-userland/commit/115d90b03dc74757361ff1e9951773ca51ff50ec))
- Update to 1.4.1 ([c7c14a5](https://github.com/OpenIndiana/oi-userland/commit/c7c14a5a7b49baa1126fb4e0d007705c3e3d1a17))
- Update to 1.4.2 ([e857848](https://github.com/OpenIndiana/oi-userland/commit/e8578482c3db09ed084a1cc39aca84bfe4d9dfb2))

### Librecad

- Update to 2.2.1.2 ([a520054](https://github.com/OpenIndiana/oi-userland/commit/a5200549176557e7106e63f99c87120e5685377e))

### Libreoffice

- Update to 24.2.4.3 ([0abc8ff](https://github.com/OpenIndiana/oi-userland/commit/0abc8ff49d63d3b5ffc113b2ef61978e0ec8ea9d))
- Update to 25.2.5.1 ([0ebcd90](https://github.com/OpenIndiana/oi-userland/commit/0ebcd901ec5ab51be9795ef8226a40fe7fa006fa))
- Update to 25.2.5.2 (#22856) ([16d9985](https://github.com/OpenIndiana/oi-userland/commit/16d9985c4d9b19c000066934892ed4d1f416037f))
- Update to 25.8.0.4 ([94d6095](https://github.com/OpenIndiana/oi-userland/commit/94d60957e82ba6bdccf77af0fa6ec571eb332fa7))
- Update to 25.8.1.1 ([59f2668](https://github.com/OpenIndiana/oi-userland/commit/59f26682d6a112a23b3dd7a5af5b34d65130ec1f))
- Update to 25.8.2.1 ([f72d2f3](https://github.com/OpenIndiana/oi-userland/commit/f72d2f38a0f5114a4c3fcad633e628e2c219a1ac))
- Libpoppler 25.10.0 fix ([05a21cd](https://github.com/OpenIndiana/oi-userland/commit/05a21cd8d3c21f7a29de0c3ce95fdfa035544cab))

### Librewolf

- Update to 141.0.3-1 ([7aff849](https://github.com/OpenIndiana/oi-userland/commit/7aff849ffd69e33345bedee25864fee0c6ed7cf0))
- Update to 144.0-1 ([213113f](https://github.com/OpenIndiana/oi-userland/commit/213113fb71ef0e072e6ecbe49aeb1764a786523f))

### Libslirp

- Add 4.9.1 ([c05cd5f](https://github.com/OpenIndiana/oi-userland/commit/c05cd5f29c807f25d067b085b3484604609c3c7b))

### Libsndfile

- Add 32bit ([876a71a](https://github.com/OpenIndiana/oi-userland/commit/876a71aa6c7dcc64970ce0f9f582a22fa66632a3))

### Libsoup3

- Fix CVE-2025-4476 ([5b3323a](https://github.com/OpenIndiana/oi-userland/commit/5b3323a4fde59762cd19acf5ae0f7b6ef1ecafea))

### Libstatgrab

- Remove 32 bit ([a1795ff](https://github.com/OpenIndiana/oi-userland/commit/a1795ff6faca2d241643c1754f70fee87ded56c8))

### Libunistring

- Update to 1.4 ([5fffc1a](https://github.com/OpenIndiana/oi-userland/commit/5fffc1a347707078e8da1d43a4ef720dc8571caf))
- Update to 1.4.1 ([c2b4be0](https://github.com/OpenIndiana/oi-userland/commit/c2b4be06df72e9f13346ddc4e3a889990d290009))

### Libupnp

- Update to 1.14.25 ([94ddee8](https://github.com/OpenIndiana/oi-userland/commit/94ddee86c2229177a3554ee660c603f7751cc5bd))

### Libusb-1

- Update to 1.0.29 ([dcdd5c3](https://github.com/OpenIndiana/oi-userland/commit/dcdd5c3eb7769e1973eeeb9f56760e3b25e9ca82))

### Libuv

- Update to 1.51.0 ([78de95d](https://github.com/OpenIndiana/oi-userland/commit/78de95d1ca321de0cc564f86da3cf96e6ba25604))

### Libvisio

- Update to 0.1.10 ([8bf4230](https://github.com/OpenIndiana/oi-userland/commit/8bf42300101e9f8ff199a34d36a44a6f36669c04))

### Libvpx

- Update to 1.15.2 ([1957424](https://github.com/OpenIndiana/oi-userland/commit/195742433f7ff67e7cd44b238c442c23a35c5af6))
- Add SPARC support ([d7d02c9](https://github.com/OpenIndiana/oi-userland/commit/d7d02c9254629980e17b1327abd89707c8acb4b1))

### Libwebp

- Update to 1.6.0 ([dd01976](https://github.com/OpenIndiana/oi-userland/commit/dd019760e4c4928d8784aef28dbe49eb7d4dc810))

### Libwnck

- Update to 43.3 ([0683ac6](https://github.com/OpenIndiana/oi-userland/commit/0683ac6c7fed524515bed564b4d85a91f977df45))

### Libxfixes

- Update to 6.0.2 ([de3c789](https://github.com/OpenIndiana/oi-userland/commit/de3c789fdfa92e7e25443147d2a43a2717395f39))

### Libxml2

- Update to 2.13.9 ([854a8e7](https://github.com/OpenIndiana/oi-userland/commit/854a8e7156ce5ff07167be38fa996983ac3ab4a9))

### Libxmlb

- Update to 0.3.23 ([3cc3a0a](https://github.com/OpenIndiana/oi-userland/commit/3cc3a0a17db694b64af4fa4c3cb87dcf70d5c286))
- Update to 0.3.24 ([edd3435](https://github.com/OpenIndiana/oi-userland/commit/edd34358f174bb9daabee9680f8cd34133aceb80))

### Libxpresent

- Update to 1.0.2 ([48da981](https://github.com/OpenIndiana/oi-userland/commit/48da981697b35b6bd74a0a0caf46e4ca16c03077))

### Libxres

- Update to 1.2.3 ([8d0dcb2](https://github.com/OpenIndiana/oi-userland/commit/8d0dcb2607d93d5e3cb54565651a3371533326ef))

### Libxscrnsaver

- Update to 1.2.5 ([444d39c](https://github.com/OpenIndiana/oi-userland/commit/444d39cdc01f06d2a94f0818b23a69aae51049cb))

### Liibreoffice

- Update to 25.8.2.2 ([cbb290a](https://github.com/OpenIndiana/oi-userland/commit/cbb290ac74601e5884e5fdf2244d35a1e4c064c0))

### Links

- Switch to libevent2 ([dd55fba](https://github.com/OpenIndiana/oi-userland/commit/dd55fba972bf8f9ebd36fae75c25fbb134d44258))

### Lldpd

- Update to 1.0.20 ([71a3bdb](https://github.com/OpenIndiana/oi-userland/commit/71a3bdbdacb629e0c0a81f90af61d6325163395e))

### Luanti

- Update to 5.12.0 ([0f9c8dd](https://github.com/OpenIndiana/oi-userland/commit/0f9c8dde7c0f527b66a891a9bc185927f98d7f89))

### M17n-db

- Update to 1.8.10 ([a6a2e7e](https://github.com/OpenIndiana/oi-userland/commit/a6a2e7e400b85dd272497f571fb05c80c4249249))

### M17n-lib

- Update to 1.8.6 ([85c084c](https://github.com/OpenIndiana/oi-userland/commit/85c084cc006682d290fbb9d659c76a4ff32b64f5))

### Mailutils

- Update to 3.20 ([6951141](https://github.com/OpenIndiana/oi-userland/commit/6951141ecf624830daf4def847c4a77df0b9bfda))

### Make-rules

- BOOTSTRAP_SKIP_REQUIRED_PACKAGES support ([f80494c](https://github.com/OpenIndiana/oi-userland/commit/f80494cf98f972693fdffd3a2f1c60f0df27502c))
- Move runtime/perl and runtime/python to USERLAND_REQUIRED_PACKAGES ([5d87466](https://github.com/OpenIndiana/oi-userland/commit/5d87466c6041f5f86eb184c91229e67f91b16345))
- Add support for REQUIRED_PACKAGES.python and REQUIRED_PACKAGES.perl ([1e0f2d2](https://github.com/OpenIndiana/oi-userland/commit/1e0f2d27e61f9ed7391af68900139312ae660ccc))
- Generic cargo vendor support ([4bd433e](https://github.com/OpenIndiana/oi-userland/commit/4bd433ec40f6306adff18f8b1e24fa8c2ac734e4))
- Convert meson.mk and ninja.mk to use common-rules.mk ([0c52bd7](https://github.com/OpenIndiana/oi-userland/commit/0c52bd7a76694347a35586b5812731f2865a0aed))
- Add site and vendor related macros for Python ([1b40f9a](https://github.com/OpenIndiana/oi-userland/commit/1b40f9a9f6ec24eafd887e28eb7fe9830a4f6b15))
- USERLAND_TEST_REQUIRED_PACKAGES.python and USERLAND_TEST_REQUIRED_PACKAGES.perl ([fa3edb8](https://github.com/OpenIndiana/oi-userland/commit/fa3edb87c98cfcf660bcc39995dfcca4b82c832a))

### Make-rules/environment.mk

- Include skipped required packages when not bootstrapping ([38b1b8b](https://github.com/OpenIndiana/oi-userland/commit/38b1b8bf61309fae8ebf9ba86cefbda3b781b6e6))
- Fix bootstrap support for prep ([fbca6f6](https://github.com/OpenIndiana/oi-userland/commit/fbca6f6317234af4ef41c4c4f7e81e077f98f851))
- Support for BOOTSTRAP=no ([325d907](https://github.com/OpenIndiana/oi-userland/commit/325d90702f8edbd78db51d44e7fb0fa7b31f838a))

### Make-rules/makemaker.mk

- Filter out dependencies during bootstrap ([0adf113](https://github.com/OpenIndiana/oi-userland/commit/0adf1138d283a842286bf1445dd97bdb42bc42f8))

### Mate-panel

- Fix build with gcc-14 ([bf45ba0](https://github.com/OpenIndiana/oi-userland/commit/bf45ba0d124431ebd3a4d0973fa72cc102ed702e))

### Maven

- Update to 3.9.10 ([27d2aa5](https://github.com/OpenIndiana/oi-userland/commit/27d2aa5b1adac4e7b51971879e44d3f90870b62f))
- Update to 3.9.11 ([b5b6eb0](https://github.com/OpenIndiana/oi-userland/commit/b5b6eb098b532a72e316499b1a369a5976bd9e56))

### Maxima

- Update to 5.48.0 ([7ea8c37](https://github.com/OpenIndiana/oi-userland/commit/7ea8c3735484c7acaedee0d08e4438684970d26c))
- Update to 5.48.1 ([2c47536](https://github.com/OpenIndiana/oi-userland/commit/2c475369315aaf60d3e046289992b626583d3cd8))

### Megasync

- Fix build in clean environment ([ddab663](https://github.com/OpenIndiana/oi-userland/commit/ddab663ae348323de8878f32377e926dbbb922c6))

### Memcached

- Fix for rebuild library/libevent2 ([181b693](https://github.com/OpenIndiana/oi-userland/commit/181b693acfcb518760fcf78a0b9b128ae7683040))

### Minio

- Add minio ([6370496](https://github.com/OpenIndiana/oi-userland/commit/6370496903df691b48cf3682e3916fe29231abbb))

### Minio-client

- Add minio-client ([13f92df](https://github.com/OpenIndiana/oi-userland/commit/13f92dfdbde35dd6ef71672ef74736d5cf3df2de))

### Mm-common

- Update to 1.0.7 ([201ea6d](https://github.com/OpenIndiana/oi-userland/commit/201ea6d10c882fb3a9b877e480c53cf67b126451))

### Modulebuild.mk

- Module-Build does not need library/perl-5/module-build ([411da60](https://github.com/OpenIndiana/oi-userland/commit/411da602ed3c0fbf8ddf628d0e61443fca076c24))

### Mosquitto

- Update to 2.0.22 ([78326f9](https://github.com/OpenIndiana/oi-userland/commit/78326f98b4e17affa7e0e8334802d8bf1f5e991a))

### Motif

- Add empty package to satisfy SunRay install requirements ([afac02a](https://github.com/OpenIndiana/oi-userland/commit/afac02ad403de6dd5327ccec367758dbc8b8f438))

### Mpg123

- Update to 1.33.0 ([6203051](https://github.com/OpenIndiana/oi-userland/commit/6203051b93cff0f8321213bd104dc545a81dd777))
- Add 32 bit library package ([781fe7d](https://github.com/OpenIndiana/oi-userland/commit/781fe7d19775a4f199baa935683f6884443b6199))
- Update to 1.33.2 ([ff801df](https://github.com/OpenIndiana/oi-userland/commit/ff801df59547b973c2455d6168f625834e7d6b1d))
- Update to 1.33.3 ([9106df7](https://github.com/OpenIndiana/oi-userland/commit/9106df7206ee959679d334abaa7382ea7f8a7f04))

### Mtr

- Update to 0.96 ([f6cc874](https://github.com/OpenIndiana/oi-userland/commit/f6cc8742358deec86cc507ba94a3e382a4fbab81))

### Multimedia/yt-dlp

- Update to 2025.6.25 ([e10bf82](https://github.com/OpenIndiana/oi-userland/commit/e10bf82feae1c5f95dcec9a79f1bfe1e65403cc3))
- Update to 2025.6.30 ([78ddccf](https://github.com/OpenIndiana/oi-userland/commit/78ddccf0eb4add603105bd2c48542d4ff53a9244))
- Update to 2025.7.21 ([3abaa8c](https://github.com/OpenIndiana/oi-userland/commit/3abaa8cbc46f4f07db435b7b866ed1463795a1c4))
- Update to 2025.8.11 ([e38377d](https://github.com/OpenIndiana/oi-userland/commit/e38377d2f2e0978d7cc7af7d5138e5d426821ecf))
- Update to 2025.8.20 ([c57fe2b](https://github.com/OpenIndiana/oi-userland/commit/c57fe2bde6b4c203f981c22ddc990b05e6e11274))
- Update to 2025.8.22 ([af82261](https://github.com/OpenIndiana/oi-userland/commit/af82261ccce2821ff939553c7a658a243bf0f22f))
- Update to 2025.8.27 ([78b1988](https://github.com/OpenIndiana/oi-userland/commit/78b19881c0435d957e6afbb933a8b45c8977b7f3))
- Update to 2025.9.5 ([934a609](https://github.com/OpenIndiana/oi-userland/commit/934a6093b5f757f76293f4f7d7490cfe26808cc8))
- Update to 2025.9.23 ([4c8fb00](https://github.com/OpenIndiana/oi-userland/commit/4c8fb00b5b4096f3b583bdfc6e69ee293c1e02bb))
- Update to 2025.9.26 ([590804c](https://github.com/OpenIndiana/oi-userland/commit/590804c5d72724863d5d2f26b5330530d3fd0c0d))

### Mutt

- Update to 2.2.15 ([f176342](https://github.com/OpenIndiana/oi-userland/commit/f176342ef9c73e128c88c6add885ff56088f5a69))

### Nano

- Update to 8.5 ([6a871ef](https://github.com/OpenIndiana/oi-userland/commit/6a871efa3d2f495b93a97ed61625ec6ca4be8f41))
- Update to 8.6 ([1a52aef](https://github.com/OpenIndiana/oi-userland/commit/1a52aeffda39fb7c769ed335f9c89a360d50e2f4))

### Ncftp

- Update to 3.3.0 ([f3b90b5](https://github.com/OpenIndiana/oi-userland/commit/f3b90b5c30102e8f83b27040c2be1408b73bbb8f))

### Netbeans

- Update to 26 ([da42c38](https://github.com/OpenIndiana/oi-userland/commit/da42c384d93d7f66c435d3ca567b77fa20b1bf54))
- Update to 27 ([e102255](https://github.com/OpenIndiana/oi-userland/commit/e10225584e73a50af068468327792c6c67ca094c))

### Nettle

- Update to 3.10.2 ([4e44de4](https://github.com/OpenIndiana/oi-userland/commit/4e44de4e20796939ae3ddf496bedcfc9ddfb5b28))

### Nghttp2

- Update to 1.66.0 ([8b6ada7](https://github.com/OpenIndiana/oi-userland/commit/8b6ada760a5272d32c305b171a3dc8759a1f2c24))
- Update to 1.67.0 ([8d927ca](https://github.com/OpenIndiana/oi-userland/commit/8d927caf8177d9e8905034af69e186c28d22f949))
- Update to 1.67.1 ([62a1ee6](https://github.com/OpenIndiana/oi-userland/commit/62a1ee636c30d7aa9c774fe0bd9fcd4026ff1d19))
- Update to 1.68.0 ([2fdb85a](https://github.com/OpenIndiana/oi-userland/commit/2fdb85a343bd44755c645d1a4d8e589abff2215f))

### Nghttp3

- Update to 1.11.0 ([2121659](https://github.com/OpenIndiana/oi-userland/commit/2121659299696d737a6c4bc482e2adbbb34e7109))
- Update to 1.12.0 ([8227c01](https://github.com/OpenIndiana/oi-userland/commit/8227c015676fd291e181b8905b1daa6a499b080e))

### Ngtcp2

- Update to 1.15.1 ([15cfa8b](https://github.com/OpenIndiana/oi-userland/commit/15cfa8b66aafb2d2521823bed91b1d90cc681ab6))
- Update to 1.16.0 ([0e7a927](https://github.com/OpenIndiana/oi-userland/commit/0e7a927c2c894408d034f2c88ec44dcc634f60e5))
- Update to 1.17.0 ([8e44009](https://github.com/OpenIndiana/oi-userland/commit/8e440092335b5bb8f44cf65acaddcfdbb0a43d68))

### Ninja

- Update to 1.13.0 ([486d1a5](https://github.com/OpenIndiana/oi-userland/commit/486d1a5910c8081125e2bbbe97aba86b8970bc7e))
- Update to 1.13.1 ([808cb44](https://github.com/OpenIndiana/oi-userland/commit/808cb44acf97b28eea12f8a4d6df1d4a9b8aa58b))

### Nodejs-20

- Update to 20.19.3 ([0db55bb](https://github.com/OpenIndiana/oi-userland/commit/0db55bb97042cf8f55734e80fd2a5def8a6a08ff))
- Update to 20.19.4 ([ac6aeae](https://github.com/OpenIndiana/oi-userland/commit/ac6aeaee9b1c6cb4f5e7dbb2221a4a72598eab07))
- Update to 20.19.5 ([ee600e4](https://github.com/OpenIndiana/oi-userland/commit/ee600e45e269f04c5e5586cfc0c308c72e5e455e))

### Nodejs-22

- Update to 22.17.0 ([c1e6504](https://github.com/OpenIndiana/oi-userland/commit/c1e6504337053ebad2d2adb1e03c2547a1cfdde6))
- Update to 22.18.0 ([0a2a0a9](https://github.com/OpenIndiana/oi-userland/commit/0a2a0a99f40a85f9713da6879d7878cb83206ee6))
- Update to 22.19.0 ([56e5670](https://github.com/OpenIndiana/oi-userland/commit/56e5670445a982c3cdb63700a7694fe982bd02f1))

### Nodejs-24

- Update to 24.2.0 ([b4f5f85](https://github.com/OpenIndiana/oi-userland/commit/b4f5f85600b7886f9580d59dbc1987084a8b5532))
- Update to 24.3.0 ([f4cbd5d](https://github.com/OpenIndiana/oi-userland/commit/f4cbd5d626ee3327edc797fcbcd5cbc53fb21240))
- Update to 24.4.0 ([41c9149](https://github.com/OpenIndiana/oi-userland/commit/41c914922f1f22729f631898c96a2dc2420e3ff7))
- Update to 24.4.1 ([35cd757](https://github.com/OpenIndiana/oi-userland/commit/35cd757b8d2cd038ba695950e81dcecfcc9f900e))
- Update to 24.5.0 ([ba02a77](https://github.com/OpenIndiana/oi-userland/commit/ba02a77a6b21abf26a0f111936557b8bc7f72b31))
- Update to 24.6.0 ([4b71c99](https://github.com/OpenIndiana/oi-userland/commit/4b71c99445c9d747b0683de05d24fd576f109081))
- Update to 24.7.0 ([6da9f1a](https://github.com/OpenIndiana/oi-userland/commit/6da9f1aca1645584d7f454de3611fac1c597f000))
- Update to 24.8.0 ([c1cb2f9](https://github.com/OpenIndiana/oi-userland/commit/c1cb2f9e93ed29ceb706485067176d4f2a7d0d98))
- Update to 24.9.0 ([4054ff6](https://github.com/OpenIndiana/oi-userland/commit/4054ff670ed9b7377644e6628a88c37f26147636))
- Update to 24.10.0 ([c5a56b4](https://github.com/OpenIndiana/oi-userland/commit/c5a56b4485600362aefa4d9414fd978f3cb45f42))

### Noto-emoji

- Update to 2.048 ([36313ca](https://github.com/OpenIndiana/oi-userland/commit/36313cafbc81c5a487fef6bd0015ce4e93aa7503))
- Update to 2.051 ([11856af](https://github.com/OpenIndiana/oi-userland/commit/11856afc8cc28f191340c41903658e15149cdc00))

### Nspr

- Update to 4.37 ([47d698c](https://github.com/OpenIndiana/oi-userland/commit/47d698c1228ef75529c748e56816a3d3080aa49f))

### Ntp

- Fix build for library/libevent2 ([3f0abaf](https://github.com/OpenIndiana/oi-userland/commit/3f0abafb1156994764c0062cef37758abef8de19))

### Nvidia

- Update to 570.169 ([11221aa](https://github.com/OpenIndiana/oi-userland/commit/11221aa85b529dbc9b07619c23e07f69aba22ca8))
- Update to 570.172.08 ([7ab443d](https://github.com/OpenIndiana/oi-userland/commit/7ab443ddaa5d31078681afed41b5ef600fbfafdc))
- Update to 570.181 ([2dc858a](https://github.com/OpenIndiana/oi-userland/commit/2dc858a24b5e8e705e46246036089eeb39c244c5))
- Update to 580.76.05 ([720c048](https://github.com/OpenIndiana/oi-userland/commit/720c048feae863b88480ebe533263dfbfa037362))
- Update to 580.82.07 ([b89513c](https://github.com/OpenIndiana/oi-userland/commit/b89513c30ebd733afcfc5b869c3161f9d9fd8d4c))
- Update to 580.82.09 ([5d7ec79](https://github.com/OpenIndiana/oi-userland/commit/5d7ec7928596f6f8bef3aae7fe37b1a9f1da018b))
- Update to 580.95.05 ([1c38442](https://github.com/OpenIndiana/oi-userland/commit/1c384424d48813fd36401056c14522e67feb73e0))

### Nvidia-535

- Update to 535.261.03 ([8fafe1a](https://github.com/OpenIndiana/oi-userland/commit/8fafe1acb51b4a58c2781972b830b486fbc2651b))

### Ocaml

- Update to 5.4.0 ([7f33b7d](https://github.com/OpenIndiana/oi-userland/commit/7f33b7d3a239825b459a530038e0c360f139eb09))

### Openblas

- Update to 0.3.30 ([ebd2b27](https://github.com/OpenIndiana/oi-userland/commit/ebd2b2751fbd85d4fb1834b907cf7c72992d97ab))

### Openbox

- Fix dependencies ([b1a96c1](https://github.com/OpenIndiana/oi-userland/commit/b1a96c139e5638995711a88b7b95cc6bee435372))

### Opencolorio

- Update to 2.5.0 ([a354869](https://github.com/OpenIndiana/oi-userland/commit/a354869ea6fbec088330db8f8f712c32848ebfb8))
- Fix build ([92057fc](https://github.com/OpenIndiana/oi-userland/commit/92057fc536f9da3ee0a51c7cbedc340aa2596f34))

### Opendkim

- Fix build using gcc14 / add SPARC support ([993d1e4](https://github.com/OpenIndiana/oi-userland/commit/993d1e448753ea630da1f334940906fea65fddcb))

### Openexr

- Update to 3.3.4 ([49971de](https://github.com/OpenIndiana/oi-userland/commit/49971de7a6b1b7a742fc73beabf3caba559b389c))
- Update to 3.3.5 ([6d041f1](https://github.com/OpenIndiana/oi-userland/commit/6d041f1a2a58cfc625c6f45bab7ee994298a3e9f))
- Update to 3.4.2 ([114b5f6](https://github.com/OpenIndiana/oi-userland/commit/114b5f6b75235dd43f4bc9fee8e08884ba507edb))

### Openindiana/release

- Remove trailing spaces from version ([0df7ea7](https://github.com/OpenIndiana/oi-userland/commit/0df7ea760fd12599d94b2050425b1d2eb64e1f5c))

### Openjdk

- Update to 25 patch 36 ([131218d](https://github.com/OpenIndiana/oi-userland/commit/131218d4d3fa8dda78e4a858283103df7692ab27))

### Openjdk-11

- Update to 11.0.28 ([7e47c5b](https://github.com/OpenIndiana/oi-userland/commit/7e47c5ba59be04d65bdfadacb11c1eb1101a7634))

### Openjdk-17

- Update to 17.0.16 ([abb4440](https://github.com/OpenIndiana/oi-userland/commit/abb444039479e362a0327467a4b070ab904e13a3))

### Openjdk-21

- Update to 21.0.8 ([116f1f7](https://github.com/OpenIndiana/oi-userland/commit/116f1f7d8cde094e8c28fd7276b76cf39f3cdb83))

### Openjpeg

- Update to 2.5.4 ([d916ef6](https://github.com/OpenIndiana/oi-userland/commit/d916ef62d058d20dcb3ceeaa08573ceff1649686))

### Openmpi

- Update to 4.1.8 ([05e3ca1](https://github.com/OpenIndiana/oi-userland/commit/05e3ca1334dc547efe0e570de867334c047c56cf))

### Openssh

- Rebuild after openssl-3 update ([fc3d35f](https://github.com/OpenIndiana/oi-userland/commit/fc3d35f2a157a01a648147cc583f9971580facbb))

### Openssl-1.0.2

- Add patch for CVE-2025-9230 ([d89134b](https://github.com/OpenIndiana/oi-userland/commit/d89134b6ed431b5cba7067d0fcd164b8c7c934a6))

### Openssl-1.1

- Add patch for CVE-2025-9230 ([3444812](https://github.com/OpenIndiana/oi-userland/commit/34448125c61ced4972998ed386c825f55503ba7b))

### Openssl-3

- Update to 3.5.1 ([fdec4a9](https://github.com/OpenIndiana/oi-userland/commit/fdec4a972cf212c17395705551fcfdc30227cd3b))
- Update to 3.5.2 ([49a3156](https://github.com/OpenIndiana/oi-userland/commit/49a315625c183489a2a78993f8d5137ff4a8be16))
- Update to 3.5.3 ([abe0ca7](https://github.com/OpenIndiana/oi-userland/commit/abe0ca7a16d23fb4d58cd61d5c4c902d10c12ffb))
- Update to 3.5.4 ([046506e](https://github.com/OpenIndiana/oi-userland/commit/046506e111a114d0ec9638c41924eb5b8168c542))

### Openvpn

- Update to 2.6.15 ([0c9706b](https://github.com/OpenIndiana/oi-userland/commit/0c9706b13d9ac405946b360e18a67d8c1e117176))

### P11-kit

- Update to 0.25.6 ([696caf1](https://github.com/OpenIndiana/oi-userland/commit/696caf1175e6f1061357f1ce951656dd672e7089))
- Update to 0.25.7 ([6ac76bc](https://github.com/OpenIndiana/oi-userland/commit/6ac76bcdd6c3232a2a2679138369315a06cf292a))
- Update to 0.25.8 ([80c6890](https://github.com/OpenIndiana/oi-userland/commit/80c6890be9eb9a727ccd25d7709359a58758cc19))
- Update to 0.25.9; switch to meson build ([84b5504](https://github.com/OpenIndiana/oi-userland/commit/84b5504a8861be55fe38708c344075bb13487187))
- Update to 0.25.10 ([3a430b0](https://github.com/OpenIndiana/oi-userland/commit/3a430b0adee27784a82cff751fc2b52f917d1288))

### Pacemaker

- Fix build and dependencies ([67735c1](https://github.com/OpenIndiana/oi-userland/commit/67735c1e416c84e25950691b493318499e11bd1d))

### Pan

- Update to 0.164 ([5e95295](https://github.com/OpenIndiana/oi-userland/commit/5e952950714afc7d7377aa0db1c8b5cfe74c3210))

### Pango

- Update to 1.57.0 ([9e52e8e](https://github.com/OpenIndiana/oi-userland/commit/9e52e8e88212a24e90de74ebe4de0c1d7bbe4f49))

### Pari

- Set mediator pari to gmp ([3de10f1](https://github.com/OpenIndiana/oi-userland/commit/3de10f103eb555f104ac1c4f84a5519966be9b2c))

### Pari-native

- Initial version ([5472966](https://github.com/OpenIndiana/oi-userland/commit/5472966ef69cea8bb39269bd8803308065537634))

### Pciutils

- Update to 3.14.0 ([cb19233](https://github.com/OpenIndiana/oi-userland/commit/cb19233c3e65a0bed1916b78a70c1d9d3395ab52))

### Pcre2

- Update to 2.10.46; activate valgrind support ([1dce837](https://github.com/OpenIndiana/oi-userland/commit/1dce8372ca5926af8f2cc19a3e57e300b1773b3b))
- Update to 10.47 ([f0f2f37](https://github.com/OpenIndiana/oi-userland/commit/f0f2f3783de9f01c9466cd23e691d080a9fc45c5))

### Pdns-recursor

- Fix dependencies ([23d1282](https://github.com/OpenIndiana/oi-userland/commit/23d1282f28b3243e3b707b0a9f7a748edbcb1ad0))

### Perl/Algorithm-Diff

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1881aee](https://github.com/OpenIndiana/oi-userland/commit/1881aeee98297081cc0f2d7bdab6e12b6e53b323))

### Perl/Alien-Build

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([90a1328](https://github.com/OpenIndiana/oi-userland/commit/90a132868adfac287e70415fd442219764878fef))
- Add CPU arch support for illumos ([e288ee4](https://github.com/OpenIndiana/oi-userland/commit/e288ee4c338a9f003f7ac0e4a69b6a74c060920c))

### Perl/Alien-Build-Plugin-Download-GitLab

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1d3fbd7](https://github.com/OpenIndiana/oi-userland/commit/1d3fbd731a81b9c74da829fbef78cccce1695410))

### Perl/Alien-Libxml2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1b9caf4](https://github.com/OpenIndiana/oi-userland/commit/1b9caf46144e853c831bfc487b05d6c5243acb1c))
- Depend on library/libxml2 ([f98e65e](https://github.com/OpenIndiana/oi-userland/commit/f98e65e900c4f387bc25222580ba7b5cdc845d09))

### Perl/Alien-cmake3

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4162f5c](https://github.com/OpenIndiana/oi-userland/commit/4162f5c8bf46a7f4c22b48b31bd102e7d918d4a3))
- Update to 0.10 ([de61acd](https://github.com/OpenIndiana/oi-userland/commit/de61acd1f9c1006a8d3815715349aa428211efce))

### Perl/Alt-Crypt-RSA-BigInt

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([546c818](https://github.com/OpenIndiana/oi-userland/commit/546c8183df5a36a073f98e6ff8c4d2cd8ce916a6))

### Perl/AppConfig

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ffa3cdc](https://github.com/OpenIndiana/oi-userland/commit/ffa3cdcb5ea9e50dbb86d2a9f24340b37a1d68d6))

### Perl/Archive-Tar

- Obsolete package for Perl 5.36 ([00bce54](https://github.com/OpenIndiana/oi-userland/commit/00bce545ff24ce99a1eb776d07a0efdcec5ecd0e))

### Perl/Archive-Zip

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1242a58](https://github.com/OpenIndiana/oi-userland/commit/1242a587301c4e7ba31980303fe0337dc1af96d9))

### Perl/Authen-PAM

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ac6f52a](https://github.com/OpenIndiana/oi-userland/commit/ac6f52ada9742dd177db6a73a2f1121215a4965a))

### Perl/Authen-SASL

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0f82c25](https://github.com/OpenIndiana/oi-userland/commit/0f82c259ae649a9eefb40a9e2ea363683520c4b8))
- Update to 2.1900 ([7e07d01](https://github.com/OpenIndiana/oi-userland/commit/7e07d01bddb3e7c35a28c3aff9bc14d755b46096))

### Perl/B-COW

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a5b5c8c](https://github.com/OpenIndiana/oi-userland/commit/a5b5c8c7257cd2932988816f986c15abdcb7d57d))

### Perl/B-Hooks-EndOfScope

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6ad4872](https://github.com/OpenIndiana/oi-userland/commit/6ad487207870278dce99f799a4855940bf1cd6f8))

### Perl/B-Hooks-OP-Check

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([23e1c27](https://github.com/OpenIndiana/oi-userland/commit/23e1c27289e9fc25328034cac1ac959ed561a2bb))

### Perl/B-Keywords

- Update to 1.28; obsolete package for Perl 5.36 ([07d7041](https://github.com/OpenIndiana/oi-userland/commit/07d7041e06b6d7baca309ba847c4dc2c869e0b88))
- Rebuild for Perl 5.42 ([91be6bc](https://github.com/OpenIndiana/oi-userland/commit/91be6bc13db380d601e2be962b6dce4f7e0f2f7f))
- Update to 1.29 ([371b96e](https://github.com/OpenIndiana/oi-userland/commit/371b96e69b8fc2a043be4653f3f919a975e640a7))

### Perl/BSD-Resource

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d9210b2](https://github.com/OpenIndiana/oi-userland/commit/d9210b27b1f37e4d8bb174a422a54367e472f6c2))

### Perl/Bit-Vector

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ad8dbb5](https://github.com/OpenIndiana/oi-userland/commit/ad8dbb5dddc001d7a1fc45cfc990a2ec55ef5ee7))

### Perl/Browser-Open

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fd5ce44](https://github.com/OpenIndiana/oi-userland/commit/fd5ce448e1b0eecdcae252d816e61d283380046e))

### Perl/Bytes-Random-Secure

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cd54a22](https://github.com/OpenIndiana/oi-userland/commit/cd54a2294319abe5be7563b6ec56f7a67f375ba1))

### Perl/Bytes-Random-Secure-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b0705fe](https://github.com/OpenIndiana/oi-userland/commit/b0705fe3bd5ad2dbb0415edd1ff304c55f3caef6))

### Perl/CGI

- Update to 4.69; obsolete package for Perl 5.36 ([d2f5d9d](https://github.com/OpenIndiana/oi-userland/commit/d2f5d9d067cb5792f5f14b43cbe854c0c2ae8746))
- Update to 4.70 ([8639fe6](https://github.com/OpenIndiana/oi-userland/commit/8639fe60ef7c4434bf2e03e2eef7cb644996f666))
- Rebuild for Perl 5.42 ([fa41f15](https://github.com/OpenIndiana/oi-userland/commit/fa41f155d7d674c97f618785fdfb5f726bf29648))
- Update to 4.71 ([b69776b](https://github.com/OpenIndiana/oi-userland/commit/b69776bc545bc297e5198845eb5569a1c8eef1e5))

### Perl/CGI-Fast

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8474c3a](https://github.com/OpenIndiana/oi-userland/commit/8474c3af7499c3f2fbf2bd398bdd21ba62c130c8))

### Perl/CPAN

- Obsolete package for Perl 5.36 ([96526bc](https://github.com/OpenIndiana/oi-userland/commit/96526bcfeafa78c738393cf10fdfce92acd733d1))

### Perl/CPAN-Meta-Check

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([57eb518](https://github.com/OpenIndiana/oi-userland/commit/57eb51863e5d905342af3c4b898908cd45c2a6b5))
- Fix dependency version ([40565a4](https://github.com/OpenIndiana/oi-userland/commit/40565a47449ff1c3494485aeba8256fd71fe6c2c))

### Perl/CPAN-Meta-Requirements

- Obsolete package for Perl 5.36 ([6fffcc5](https://github.com/OpenIndiana/oi-userland/commit/6fffcc54fa0d2016253ad6bd666f789ee4c9f843))

### Perl/CPAN-Meta-YAML

- Obsolete package for Perl 5.36 ([209efd2](https://github.com/OpenIndiana/oi-userland/commit/209efd299317fc60c8426e70be408c9d1cafc742))

### Perl/CPAN-Requirements-Dynamic

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f0757df](https://github.com/OpenIndiana/oi-userland/commit/f0757df36bbe71c2c239121b8f5cb877fbbe1568))

### Perl/Canary-Stability

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([10fbedf](https://github.com/OpenIndiana/oi-userland/commit/10fbedf0d919d6ba97c7bd27b17139b21ba36c89))

### Perl/Capture-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2a06fa4](https://github.com/OpenIndiana/oi-userland/commit/2a06fa466655d4c1dd62b2965f643f9eb2872157))

### Perl/Carp-Clan

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0464443](https://github.com/OpenIndiana/oi-userland/commit/04644432789a49fe3dd4deda6a673a8fbc1aa7f7))

### Perl/Class-Data-Inheritable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([39c22f8](https://github.com/OpenIndiana/oi-userland/commit/39c22f8ff4dbfdd6e89587ddd4d663e34c8270ed))

### Perl/Class-ErrorHandler

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5ac8698](https://github.com/OpenIndiana/oi-userland/commit/5ac86982f186fd3f081a6ac6f584352f3b25e4c0))

### Perl/Class-Inspector

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([efd21f7](https://github.com/OpenIndiana/oi-userland/commit/efd21f79d2e7083318de78c3a129e6e3f0421fb4))

### Perl/Class-Loader

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fa6b77c](https://github.com/OpenIndiana/oi-userland/commit/fa6b77c6781a8a0ef9c93b1953c82a61549f902f))

### Perl/Class-Method-Modifiers

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b728e10](https://github.com/OpenIndiana/oi-userland/commit/b728e107e0018f93333b2ee59314f0b5e91b6f9c))

### Perl/Class-Singleton

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([94e5f6e](https://github.com/OpenIndiana/oi-userland/commit/94e5f6ef09d80fbed12433cd93c92910e1ceac37))

### Perl/Class-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([79dce07](https://github.com/OpenIndiana/oi-userland/commit/79dce07239174d33a2d08e68e1e79dcf768d9f0e))

### Perl/Class-XSAccessor

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([22814f2](https://github.com/OpenIndiana/oi-userland/commit/22814f24ca36bfe169040c9a8cb53d897d2241da))

### Perl/Clone

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f6e4dce](https://github.com/OpenIndiana/oi-userland/commit/f6e4dce7f2629513bd8990d5942db2037c36cca2))

### Perl/Clone-Choose

- Rebuild for Perl 5.42 ([a21abd9](https://github.com/OpenIndiana/oi-userland/commit/a21abd9b4ba59d8a0bc695356a7122c06e12f4ab))

### Perl/Clone-PP

- Rebuild for Perl 5.42 ([629aad1](https://github.com/OpenIndiana/oi-userland/commit/629aad1f6fbbb6539e803f1674323d5851632f33))

### Perl/Compress-Raw-Bzip2

- Obsolete package for Perl 5.36 ([75441ec](https://github.com/OpenIndiana/oi-userland/commit/75441ec68d03fa415f41325568b6fd3dc86a0fa4))
- Update to 2.214 ([aee5c89](https://github.com/OpenIndiana/oi-userland/commit/aee5c89a018f6fd8ddcfa42e50f6f4a638e675ee))

### Perl/Compress-Raw-Lzma

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([138b203](https://github.com/OpenIndiana/oi-userland/commit/138b203804f4eae03185a3e39d0960bf3447ff7e))
- Update to 2.214 ([62b7369](https://github.com/OpenIndiana/oi-userland/commit/62b736992d33ebcef042de5b05d9f874fe6c832e))

### Perl/Compress-Raw-Zlib

- Obsolete package for Perl 5.36 ([cadef27](https://github.com/OpenIndiana/oi-userland/commit/cadef27b46dcc2df125b3a1ae12b473cb045f84c))
- Update to 2.214 ([7708471](https://github.com/OpenIndiana/oi-userland/commit/7708471627134c6a1a81df809519c5e01f83a68a))

### Perl/Compress-Stream-Zstd

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fadd224](https://github.com/OpenIndiana/oi-userland/commit/fadd2241dd26a89e6052e35fa3b189ca363e0502))

### Perl/Config-Perl-V

- Obsolete package for Perl 5.36 ([d22ea54](https://github.com/OpenIndiana/oi-userland/commit/d22ea5429388f2e533482a4ba313ba17d85317b4))

### Perl/Config-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8ad7dcb](https://github.com/OpenIndiana/oi-userland/commit/8ad7dcb2b8c840604d1f74e97ecc31462f77b35c))

### Perl/Convert-ASCII-Armour

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0d329bb](https://github.com/OpenIndiana/oi-userland/commit/0d329bbabed1881775d7e34bc8121c5f8daf50f8))

### Perl/Convert-ASN1

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a1d384c](https://github.com/OpenIndiana/oi-userland/commit/a1d384c77ddef45175b986b2aa9f6d99306a90dd))

### Perl/Convert-PEM

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5498083](https://github.com/OpenIndiana/oi-userland/commit/54980834f82fd1f3b39f4389cf55790775ffc021))

### Perl/Cpanel-JSON-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3fcf3bb](https://github.com/OpenIndiana/oi-userland/commit/3fcf3bbe7d4cb34ef4ceda6fd40eb370b46bc5d4))
- Update to 4.40 ([960b668](https://github.com/OpenIndiana/oi-userland/commit/960b6689ba413955f03624084d416cd869745139))

### Perl/Crypt-Blowfish

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8b9f877](https://github.com/OpenIndiana/oi-userland/commit/8b9f877b3b626211ecd2f359af1b4a924cf8339d))

### Perl/Crypt-CAST5_PP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([292c216](https://github.com/OpenIndiana/oi-userland/commit/292c216a8ee14163866768afd6ea4e75e5bc635b))

### Perl/Crypt-CBC

- Update to 3.07; rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5d0a4d7](https://github.com/OpenIndiana/oi-userland/commit/5d0a4d7ce9228d6d2b4d3414d3ac418de11f84f4))

### Perl/Crypt-DES

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5ffe725](https://github.com/OpenIndiana/oi-userland/commit/5ffe72529472c0b3d9a680eb60cfd355c0eb06d1))

### Perl/Crypt-DES_EDE3

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e1179f0](https://github.com/OpenIndiana/oi-userland/commit/e1179f057692cbb393077673c4bd24d3b9a5bd55))

### Perl/Crypt-DSA

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b5b0f09](https://github.com/OpenIndiana/oi-userland/commit/b5b0f091237e6544360591d9823b7db91aa66c6f))

### Perl/Crypt-IDEA

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([72fed85](https://github.com/OpenIndiana/oi-userland/commit/72fed85ce73c341663e77a55805c38e42b8d5420))

### Perl/Crypt-OpenPGP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([39f4444](https://github.com/OpenIndiana/oi-userland/commit/39f444483fe6c640db8d8d681cc269ab00e6ca61))

### Perl/Crypt-OpenSSL-Bignum

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3ce50d4](https://github.com/OpenIndiana/oi-userland/commit/3ce50d4905a299f13b76d3fe29876eca3c20d3f6))

### Perl/Crypt-OpenSSL-Guess

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([16a4394](https://github.com/OpenIndiana/oi-userland/commit/16a439433ad1f9883de8be9cd93ab8ffaa8cccef))

### Perl/Crypt-OpenSSL-RSA

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ec88a98](https://github.com/OpenIndiana/oi-userland/commit/ec88a988d2cb48ece7c467885c6d17db0c2a2a2d))

### Perl/Crypt-OpenSSL-Random

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8e4b8cc](https://github.com/OpenIndiana/oi-userland/commit/8e4b8cc3d4a43abd88bba507ae31b94f5e43671a))

### Perl/Crypt-PBKDF2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1b352ed](https://github.com/OpenIndiana/oi-userland/commit/1b352ed7de3d8e0ac05ee4fe88d7e44a3edba86a))

### Perl/Crypt-RIPEMD160

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d2d514a](https://github.com/OpenIndiana/oi-userland/commit/d2d514a4fd91287d37574695988a07c9d924b541))

### Perl/Crypt-Random-Seed

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([edec78f](https://github.com/OpenIndiana/oi-userland/commit/edec78fb4545e59c8756fafba57bac5f541c9ea8))

### Perl/Crypt-Random-TESHA2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6727bad](https://github.com/OpenIndiana/oi-userland/commit/6727bad7ea262a3e6596659d913fdf87fc3889a3))

### Perl/Crypt-Rijndael

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5111870](https://github.com/OpenIndiana/oi-userland/commit/5111870103213e3129dd0cb2269edbd94b57dbef))

### Perl/Crypt-Twofish

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bc9c635](https://github.com/OpenIndiana/oi-userland/commit/bc9c63559c8051652389d730bd65f19a4003ed78))

### Perl/Crypt-URandom

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d69c78e](https://github.com/OpenIndiana/oi-userland/commit/d69c78e4af49e24b04106bc1dd2c887f25c85a36))

### Perl/Crypt-X509

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f62cde8](https://github.com/OpenIndiana/oi-userland/commit/f62cde8790a8d665b0bd6cf5abed39e4db980239))

### Perl/CryptX

- Update to 0.087; obsolete package for Perl 5.36 ([51acc23](https://github.com/OpenIndiana/oi-userland/commit/51acc23f9f90279e7895ec3902396f930f75f5cc))
- Rebuild for Perl 5.42 ([ae7ed51](https://github.com/OpenIndiana/oi-userland/commit/ae7ed511f95441fb0011f92508868e4b78d59957))

### Perl/Curses

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ed77b69](https://github.com/OpenIndiana/oi-userland/commit/ed77b698fe8a53d2eeeddc3b60a38da30426c5e5))

### Perl/Curses-UI

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b92d27c](https://github.com/OpenIndiana/oi-userland/commit/b92d27ce7691f27acb96dcde72cc0a20e5329ddf))

### Perl/Cwd-Guard

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([561d85d](https://github.com/OpenIndiana/oi-userland/commit/561d85da1cd2cc7a7eb3e6f00131001cde6e9546))

### Perl/DBD-CSV

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a8805d2](https://github.com/OpenIndiana/oi-userland/commit/a8805d2971c1f286d71eec269e05a7d479087d36))

### Perl/DBD-MariaDB

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9e5db09](https://github.com/OpenIndiana/oi-userland/commit/9e5db099bc69de15ad36d964f9f8270118957c9b))

### Perl/DBD-Pg

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f220349](https://github.com/OpenIndiana/oi-userland/commit/f220349e92a5cbf7e0d7429185b02b5614d3c6f7))

### Perl/DBD-SQLite

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1d6bbc2](https://github.com/OpenIndiana/oi-userland/commit/1d6bbc2e8c16fc00232d50d4f8b6adc8c468daac))

### Perl/DBI

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5dbd5f3](https://github.com/OpenIndiana/oi-userland/commit/5dbd5f3d24f2291b181e02975d3aa6500ea4a890))

### Perl/DBIx-Simple

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([956b0a2](https://github.com/OpenIndiana/oi-userland/commit/956b0a2b4e3469cca5fcf79aa5a1577fa5535302))

### Perl/DB_File

- Obsolete package for Perl 5.36 ([fbd639c](https://github.com/OpenIndiana/oi-userland/commit/fbd639cba02f03693118a0c4f16397cdba93a270))

### Perl/Data-Buffer

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7ef2ed7](https://github.com/OpenIndiana/oi-userland/commit/7ef2ed720785c8a78769a83cda6a73ceca0b8feb))

### Perl/Data-Dump

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5b9c0a7](https://github.com/OpenIndiana/oi-userland/commit/5b9c0a721c61fbef8eca34443697ae920763ce3f))

### Perl/Data-OptList

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cbde90b](https://github.com/OpenIndiana/oi-userland/commit/cbde90b51166099b2da06daa1c7dbb7dac4807f7))

### Perl/Data-Processor

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fec3754](https://github.com/OpenIndiana/oi-userland/commit/fec3754a9d6c3cd1342dcbe4530122c98bda87a2))

### Perl/Date-Calc

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a8e375d](https://github.com/OpenIndiana/oi-userland/commit/a8e375d92cdf9af277cff6078c9d3b80c1065e32))
- Require library/perl-5/date-calc-xs ([8afb0d2](https://github.com/OpenIndiana/oi-userland/commit/8afb0d2f206039938f7e4c67e58286d877e08ca8))

### Perl/Date-Calc-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([17d7245](https://github.com/OpenIndiana/oi-userland/commit/17d7245879afc75f16a13906878bc76a490a2ade))

### Perl/Date-Manip

- Rebuild for Perl 5.42 ([3eabce3](https://github.com/OpenIndiana/oi-userland/commit/3eabce34149b4fc92575c299f35d510a00d5a6e5))

### Perl/DateTime

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e44c98d](https://github.com/OpenIndiana/oi-userland/commit/e44c98d6f8f7441c9b1fd2fbc24e820aa22e35e5))

### Perl/DateTime-Format-Builder

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([85dacab](https://github.com/OpenIndiana/oi-userland/commit/85dacabf4470cdf127e9ebec1c62775be327d32e))

### Perl/DateTime-Format-ISO8601

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([aa0b30a](https://github.com/OpenIndiana/oi-userland/commit/aa0b30a822b26c9205e29733e33046466173c377))

### Perl/DateTime-Format-RFC3339

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([db6e1ff](https://github.com/OpenIndiana/oi-userland/commit/db6e1ff4af8ff7109079cde8f3f7ed0c17e83836))

### Perl/DateTime-Format-Strptime

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2e7fc29](https://github.com/OpenIndiana/oi-userland/commit/2e7fc29484eeafff174e6ab7e47d736ba14b48e6))

### Perl/DateTime-Locale

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0e2bb4d](https://github.com/OpenIndiana/oi-userland/commit/0e2bb4d2e7af78049e3ef62bf807bfc326da75ea))

### Perl/DateTime-TimeZone

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6a1ca9d](https://github.com/OpenIndiana/oi-userland/commit/6a1ca9d593b224a325cd6617e1420af695330a35))

### Perl/Devel-Caller

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([69dc316](https://github.com/OpenIndiana/oi-userland/commit/69dc316d3f5bdd73e8e8209550c0d5b43644599d))

### Perl/Devel-CheckCompiler

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9fb8240](https://github.com/OpenIndiana/oi-userland/commit/9fb82409fb135c3dfdf13504bf043472a8e6d7ac))

### Perl/Devel-CheckLib

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([63e279c](https://github.com/OpenIndiana/oi-userland/commit/63e279c25474d3f0656986def6eafdc5001aa1d2))

### Perl/Devel-Cycle

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0719e1f](https://github.com/OpenIndiana/oi-userland/commit/0719e1fa15c090093164e1c7dbee6a848218e197))

### Perl/Devel-GlobalDestruction

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2f63bbc](https://github.com/OpenIndiana/oi-userland/commit/2f63bbcba2833668c8a0d3847b0b4a2c71c442e1))

### Perl/Devel-Hide

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([745adf4](https://github.com/OpenIndiana/oi-userland/commit/745adf4f62909d448f646473d2dff6d49195b43f))

### Perl/Devel-LexAlias

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c494726](https://github.com/OpenIndiana/oi-userland/commit/c49472641986ad5c26c9a2914f28a1a81892150a))

### Perl/Devel-StackTrace

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([65b1252](https://github.com/OpenIndiana/oi-userland/commit/65b1252a4d438d01688e7c2f7e16178aea5c0e79))

### Perl/Devel-Symdump

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a0ac427](https://github.com/OpenIndiana/oi-userland/commit/a0ac42731df0116b89dcca56c2cbd3fc85dfee95))

### Perl/Digest-BubbleBabble

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([844567f](https://github.com/OpenIndiana/oi-userland/commit/844567f50a03f05a27a53353923c09b95b2060cc))

### Perl/Digest-HMAC

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9f2bd3e](https://github.com/OpenIndiana/oi-userland/commit/9f2bd3e5b27022296027473abbbdcb150f92c4cb))

### Perl/Digest-MD2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([86406a4](https://github.com/OpenIndiana/oi-userland/commit/86406a43efe7a0902a195f737dc9ac073e4177ce))

### Perl/Digest-MD5

- Obsolete package for Perl 5.36 ([7afdff8](https://github.com/OpenIndiana/oi-userland/commit/7afdff85d318e14919d81dcb6432562659a472c6))

### Perl/Digest-SHA

- Obsolete package for Perl 5.36 ([2f403ee](https://github.com/OpenIndiana/oi-userland/commit/2f403ee55c23f4368a5a86fec3de163b26783b0e))

### Perl/Digest-SHA1

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([682e369](https://github.com/OpenIndiana/oi-userland/commit/682e3698a5d637b90c482c0ae1749265d69f3ce8))

### Perl/Digest-SHA3

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([60950d7](https://github.com/OpenIndiana/oi-userland/commit/60950d794fca61ed49625bd076308db55737ca8e))

### Perl/Dist-CheckConflicts

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e4c6947](https://github.com/OpenIndiana/oi-userland/commit/e4c69474e7af366faa07db842f9b1f7b1c4cf4ae))

### Perl/Email-Abstract

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([dc7d9de](https://github.com/OpenIndiana/oi-userland/commit/dc7d9de2917ec545e26f18d8981a80338a29cf20))

### Perl/Email-Address

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7db1bef](https://github.com/OpenIndiana/oi-userland/commit/7db1bef26aaf5e4e5e89a2b16ef55c50de8a8533))

### Perl/Email-Address-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([348c552](https://github.com/OpenIndiana/oi-userland/commit/348c5522e56bb37a313cb96f3b22b30b2f41f5cf))

### Perl/Email-Date-Format

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([821a170](https://github.com/OpenIndiana/oi-userland/commit/821a170784b3d905258f9bb839724e6f9d81d043))

### Perl/Email-MIME

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([47622cf](https://github.com/OpenIndiana/oi-userland/commit/47622cf4b31a4222801acc1e434f6c04436e50e1))

### Perl/Email-MIME-ContentType

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([beb6413](https://github.com/OpenIndiana/oi-userland/commit/beb6413e49e361ad36c5591c4b3cd2c502c06e36))

### Perl/Email-MIME-Encodings

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([111b179](https://github.com/OpenIndiana/oi-userland/commit/111b179b60924fa1799bbdf052f839a71444755e))

### Perl/Email-MessageID

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([60b0312](https://github.com/OpenIndiana/oi-userland/commit/60b0312dd4355bf08f17f68275cc11514f1741aa))

### Perl/Email-Sender

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([58eb1a6](https://github.com/OpenIndiana/oi-userland/commit/58eb1a60ea2ae1436c36a230dd10248d4fc596e7))

### Perl/Email-Simple

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([021c21b](https://github.com/OpenIndiana/oi-userland/commit/021c21b4fc07ab9519efe581bbc10f78cdbd8ef2))

### Perl/Email-Stuffer

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9ceaf40](https://github.com/OpenIndiana/oi-userland/commit/9ceaf40f3084eddc55287cea7e673f68c5c4ef81))

### Perl/Email-Valid

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4cf27a4](https://github.com/OpenIndiana/oi-userland/commit/4cf27a4fd0674855cf4c96a43f56e1a111301f26))

### Perl/Encode

- Obsolete package for Perl 5.36 ([19350f0](https://github.com/OpenIndiana/oi-userland/commit/19350f00161be680d67ce8a00ff9f941296c5197))

### Perl/Encode-Detect

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([611ea8f](https://github.com/OpenIndiana/oi-userland/commit/611ea8f74649c4d491eb009092de9ab2e2933cda))

### Perl/Encode-Locale

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0486b6b](https://github.com/OpenIndiana/oi-userland/commit/0486b6b4b60d7a4d7d12be6bbed8e547069bd523))

### Perl/Error

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b7fdc3f](https://github.com/OpenIndiana/oi-userland/commit/b7fdc3fe2122677b18cd9eb706ffaebe4a634029))

### Perl/Eval-Closure

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2651c61](https://github.com/OpenIndiana/oi-userland/commit/2651c6198d0d50ff92a3776618298791aaa59a02))

### Perl/Exception-Class

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([db943f8](https://github.com/OpenIndiana/oi-userland/commit/db943f8f9740f22f05feb9e430916afdeb6bb5ac))

### Perl/Exporter-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e0b9d5b](https://github.com/OpenIndiana/oi-userland/commit/e0b9d5bd87eb7a71ad151e389f8e98e46a5e995a))

### Perl/ExtUtils-Config

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2ea62fc](https://github.com/OpenIndiana/oi-userland/commit/2ea62fc981f9c85b8e7774188658689aa1d93d46))

### Perl/ExtUtils-Depends

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d8b05e6](https://github.com/OpenIndiana/oi-userland/commit/d8b05e6123f4d3c07a70a5acc6354cbc09a6fdb1))

### Perl/ExtUtils-HasCompiler

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([661c32c](https://github.com/OpenIndiana/oi-userland/commit/661c32c6c401bd22dd4e5a5e99a15218bac4fcc5))

### Perl/ExtUtils-Helpers

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b12e079](https://github.com/OpenIndiana/oi-userland/commit/b12e0791b583751e4191ede190a289eb7a1ae2dd))

### Perl/ExtUtils-Install

- Obsolete package for Perl 5.36 ([e1e8d57](https://github.com/OpenIndiana/oi-userland/commit/e1e8d579265687a0655a2de2328fe88c23dbd143))

### Perl/ExtUtils-InstallPaths

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e77b90e](https://github.com/OpenIndiana/oi-userland/commit/e77b90e6fa1ca6d0f0d0adb397906bc8b2b660ba))
- Update to 0.015 ([1122856](https://github.com/OpenIndiana/oi-userland/commit/11228562ee7c3ede7b814b407dc25a30c2c091bb))

### Perl/ExtUtils-MakeMaker

- Obsolete package for Perl 5.36 ([043b123](https://github.com/OpenIndiana/oi-userland/commit/043b123fd8a15c8aca8248c6f9a847ae725578c3))

### Perl/ExtUtils-Manifest

- Obsolete package for Perl 5.36 ([f97d484](https://github.com/OpenIndiana/oi-userland/commit/f97d4844c0269bca99005fd59c3c03633f51cca1))

### Perl/ExtUtils-PL2Bat

- Obsolete package for Perl 5.36 ([a559944](https://github.com/OpenIndiana/oi-userland/commit/a559944d1312f0d668b056d5b48b0553efc2d8c5))

### Perl/FCGI

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c75c51a](https://github.com/OpenIndiana/oi-userland/commit/c75c51a570b484693f4cd8d4a63c213a26b4fe41))

### Perl/FCGI-Client

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ae25e10](https://github.com/OpenIndiana/oi-userland/commit/ae25e1046a303a0936663dfaf27e455b2c60aac3))

### Perl/FFI-CheckLib

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cdba529](https://github.com/OpenIndiana/oi-userland/commit/cdba529e403fee362b8c6eb07b28ac38fea4e236))

### Perl/File-Copy-Recursive

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e488618](https://github.com/OpenIndiana/oi-userland/commit/e4886182550eddae8b983f49a4d8214c0d487133))

### Perl/File-Copy-Recursive-Reduced

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([006e659](https://github.com/OpenIndiana/oi-userland/commit/006e6599f6f3303dabfee344c3a66f75427b6553))

### Perl/File-Find-Rule

- Update to 0.35; obsolete package for Perl 5.36 ([430db21](https://github.com/OpenIndiana/oi-userland/commit/430db21aae9974e9beb69ec9ad62826a4378f3e6))
- Rebuild for Perl 5.42 ([8304431](https://github.com/OpenIndiana/oi-userland/commit/8304431a1f6a6eb8ebd638e820b4d3a75aeca523))

### Perl/File-HomeDir

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e1c3e3d](https://github.com/OpenIndiana/oi-userland/commit/e1c3e3d4d8b59421d1e97b2931ee4185742c4113))

### Perl/File-Listing

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([61e4235](https://github.com/OpenIndiana/oi-userland/commit/61e4235c2df03d3f4df7d4780640a46690570e58))

### Perl/File-Remove

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([102d07a](https://github.com/OpenIndiana/oi-userland/commit/102d07ac5a3fae08b847744011a7778c3828d2d1))

### Perl/File-ShareDir

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8587cd5](https://github.com/OpenIndiana/oi-userland/commit/8587cd5b41bc6d521e710a4e147babb8e26fc52d))

### Perl/File-ShareDir-Install

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b990f22](https://github.com/OpenIndiana/oi-userland/commit/b990f22cfa4bf749847f0224463bfeced289561b))

### Perl/File-Slurp

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([eee2b48](https://github.com/OpenIndiana/oi-userland/commit/eee2b48b66f2eddcf6e245b99f288306ad43255e))

### Perl/File-Slurper

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([357c063](https://github.com/OpenIndiana/oi-userland/commit/357c0631ea10a3772a9e8ebc6bd19db8632823b1))

### Perl/File-Temp

- Update to 0.2312 ([c457f95](https://github.com/OpenIndiana/oi-userland/commit/c457f95a37b080b2dde127ae38dec09abb226b62))

### Perl/File-Which

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8e89556](https://github.com/OpenIndiana/oi-userland/commit/8e8955682995be133250e85c7cc10df72d4bab20))

### Perl/File-chdir

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([347e36e](https://github.com/OpenIndiana/oi-userland/commit/347e36e29d30f68ebea6f3036e481cab74846902))

### Perl/Filter

- Obsolete package for Perl 5.36 ([ebb8730](https://github.com/OpenIndiana/oi-userland/commit/ebb87309f7e7e82bb340592e19d3810214b20205))
- Update to 1.65 ([0054265](https://github.com/OpenIndiana/oi-userland/commit/0054265a3c5f35c078f2e0ceb30cf6d488d5dd03))

### Perl/Font-AFM

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d32ccf4](https://github.com/OpenIndiana/oi-userland/commit/d32ccf423f5c531b92a93abb6fb881b56298a445))

### Perl/Font-TTF

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5fea02f](https://github.com/OpenIndiana/oi-userland/commit/5fea02f1373527eeac9969927b7bc6647df5f0d6))

### Perl/Geo-IP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a0e669b](https://github.com/OpenIndiana/oi-userland/commit/a0e669bbd204c7632c9a50b4c4de03b8a0be00b6))

### Perl/Geography-Countries

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b329811](https://github.com/OpenIndiana/oi-userland/commit/b3298117945301d90cededc624b0dd4bc6123790))

### Perl/Getopt-Long

- Obsolete package for Perl 5.36 ([fa9a555](https://github.com/OpenIndiana/oi-userland/commit/fa9a555e9aa97d63d98721f087989db4d4f5ff45))

### Perl/HTML-Element-Extended

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([75fcb1b](https://github.com/OpenIndiana/oi-userland/commit/75fcb1b815a08d4fc318e34481268ddf7143680a))

### Perl/HTML-Formatter

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0ffeb8d](https://github.com/OpenIndiana/oi-userland/commit/0ffeb8d945e784f40b7a127d351aaba1668b4f80))

### Perl/HTML-Parser

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8d30053](https://github.com/OpenIndiana/oi-userland/commit/8d3005398e61edf99f4816d603ebfe7362c69d2d))

### Perl/HTML-TableExtract

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bf5c3e9](https://github.com/OpenIndiana/oi-userland/commit/bf5c3e91380f9e69d8f72491a5a7094683b9e874))

### Perl/HTML-Tagset

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2f45b01](https://github.com/OpenIndiana/oi-userland/commit/2f45b01707ad3da03a8b117d05a863aed41e5564))

### Perl/HTML-Template

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e84ebd3](https://github.com/OpenIndiana/oi-userland/commit/e84ebd331b005cd13380dce2a59818cac47e154c))

### Perl/HTML-Tree

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fef8b79](https://github.com/OpenIndiana/oi-userland/commit/fef8b79028751be80b966a7c40aa4d73552ea05a))
- Require library/perl-5/html-formatter ([d586126](https://github.com/OpenIndiana/oi-userland/commit/d586126d07718799d1b6a71faa9960b5c837ba49))

### Perl/HTTP-CookieJar

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d6f1b20](https://github.com/OpenIndiana/oi-userland/commit/d6f1b20f59c2f88664492d83b27e6edde2175b75))

### Perl/HTTP-Cookies

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b7fc5c4](https://github.com/OpenIndiana/oi-userland/commit/b7fc5c454b1a253c638b53a05a9af86cd0b04ec7))

### Perl/HTTP-Daemon

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([acab653](https://github.com/OpenIndiana/oi-userland/commit/acab65368c5e9dbab947e42863d4a36269ebc1f8))

### Perl/HTTP-Date

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([534e622](https://github.com/OpenIndiana/oi-userland/commit/534e62219bdb1d7d130ac4dcaf42a95872ff6dd4))

### Perl/HTTP-Message

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ee9862f](https://github.com/OpenIndiana/oi-userland/commit/ee9862fc00c0dd6fbe82dbfd6b2a01b0a0a72011))
- Update to 7.01 ([c07e1e2](https://github.com/OpenIndiana/oi-userland/commit/c07e1e2392ec30a3afd4f174a5627cbb03407a20))

### Perl/HTTP-Negotiate

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c225307](https://github.com/OpenIndiana/oi-userland/commit/c22530768ed0bc78b3297140eb20eaadd427d2a4))

### Perl/HTTP-Tiny

- Obsolete package for Perl 5.36 ([3a5aa2f](https://github.com/OpenIndiana/oi-userland/commit/3a5aa2fa1c6b81f51411ea1419a07da5ec1a21cc))

### Perl/Hook-LexWrap

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8829e96](https://github.com/OpenIndiana/oi-userland/commit/8829e96781e6ab058cf009fb6a8d934399c3b47b))

### Perl/IO-Compress

- Obsolete package for Perl 5.36 ([2dd7519](https://github.com/OpenIndiana/oi-userland/commit/2dd751912a45b10169354f897c8c28521f57f4a7))
- Update to 2.214 ([24abfb6](https://github.com/OpenIndiana/oi-userland/commit/24abfb67317c14e49ff686beaeca2828d6570d84))

### Perl/IO-Compress-Brotli

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5971238](https://github.com/OpenIndiana/oi-userland/commit/5971238fb59e034289d3ae5fdbde6046e93546ee))

### Perl/IO-Compress-Lzma

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([64db037](https://github.com/OpenIndiana/oi-userland/commit/64db037bc404f26497fec57cd3c1711312b5b002))

### Perl/IO-Compress-Zstd

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1d5ba39](https://github.com/OpenIndiana/oi-userland/commit/1d5ba3918d8d12f48306812e566bf06f3ea95119))

### Perl/IO-HTML

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bbea4fc](https://github.com/OpenIndiana/oi-userland/commit/bbea4fcc33de58387faf6f980305f231582ad670))

### Perl/IO-Pipely

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([10979ff](https://github.com/OpenIndiana/oi-userland/commit/10979ff55745e68793f89fa709e6e2d8c4169e91))

### Perl/IO-Socket-IP

- Obsolete package for Perl 5.36 ([dfdec19](https://github.com/OpenIndiana/oi-userland/commit/dfdec195df8304e3f63333464ba4d0666d05b2fe))

### Perl/IO-Socket-SSL

- Update to 2.091 ([7953da9](https://github.com/OpenIndiana/oi-userland/commit/7953da91de76dac948e26e5a42bd688c69027427))
- Update to 2.094 ([2487db5](https://github.com/OpenIndiana/oi-userland/commit/2487db5ecc2ab8faca55843422045fd6ce295d53))
- Update to 2.095 ([8f12847](https://github.com/OpenIndiana/oi-userland/commit/8f12847c507ee2b822503bf05997f892696c478f))
- Rebuild for Perl 5.42 ([25e5156](https://github.com/OpenIndiana/oi-userland/commit/25e51561f934e560915bf845cf879ba7144aabd6))

### Perl/IO-String

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d671189](https://github.com/OpenIndiana/oi-userland/commit/d671189e245bd46cd03b655b0faf02eb05485758))

### Perl/IO-Tty

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3482ba4](https://github.com/OpenIndiana/oi-userland/commit/3482ba41875f25c6848df93fa51227868f47bcf5))

### Perl/IO-Zlib

- Obsolete package for Perl 5.36 ([2330aa5](https://github.com/OpenIndiana/oi-userland/commit/2330aa55683a962b8972afde4dbc12b41792df01))

### Perl/IP-Country

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f92e3a3](https://github.com/OpenIndiana/oi-userland/commit/f92e3a339333bc4589c072b01e43dc157c521496))

### Perl/IP-Country-DB_File

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([46adccd](https://github.com/OpenIndiana/oi-userland/commit/46adccd6df028ed12eca011c72817febcdbef152))

### Perl/IPC-Run

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7740018](https://github.com/OpenIndiana/oi-userland/commit/77400186bda94b73a4daf7fc264de1028dcb5c42))
- Update to 20250809.0 ([fbd87a6](https://github.com/OpenIndiana/oi-userland/commit/fbd87a66445c3c2e060f41c31e1481b780633b42))

### Perl/IPC-Run3

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c169950](https://github.com/OpenIndiana/oi-userland/commit/c16995080d4f01c696bd3be87cb04ac6907f22e3))

### Perl/IPC-System-Simple

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cd511f9](https://github.com/OpenIndiana/oi-userland/commit/cd511f974717a33aa767a3b61dbe1a0fed83a36a))

### Perl/Image-ExifTool

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([410e3a6](https://github.com/OpenIndiana/oi-userland/commit/410e3a674ba0ecefdd40dd232b8757873875e931))
- Update to 13.35 ([3fb656d](https://github.com/OpenIndiana/oi-userland/commit/3fb656d45aafc76c80ace1be8a13f1a4557b7009))
- Update to 13.36 ([337976b](https://github.com/OpenIndiana/oi-userland/commit/337976b05cbf11fb5ba4c8fc4fe819172c6d1acd))

### Perl/Import-Into

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d61696b](https://github.com/OpenIndiana/oi-userland/commit/d61696bc17ccc411ee4d976c8cf212ad123a78df))

### Perl/Importer

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b56670e](https://github.com/OpenIndiana/oi-userland/commit/b56670e33c21f0b451ba303be2a8f61ef5ec8a0e))

### Perl/JSON

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9ec0e96](https://github.com/OpenIndiana/oi-userland/commit/9ec0e96f29de46b26059151f91a3b87c8c8754cb))

### Perl/JSON-MaybeXS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4f2ba42](https://github.com/OpenIndiana/oi-userland/commit/4f2ba424f14f7f3b3040390fbf04b79525e0ae61))

### Perl/JSON-PP

- Obsolete package for Perl 5.36 ([6ea10bf](https://github.com/OpenIndiana/oi-userland/commit/6ea10bf747d6392ae5aa89f38c011af08bbedb8a))

### Perl/JSON-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([edd7ca3](https://github.com/OpenIndiana/oi-userland/commit/edd7ca3b43ea87c49d8802b6dadba0b077bc09d1))
- Update to 4.04 ([dc23159](https://github.com/OpenIndiana/oi-userland/commit/dc231590edf68daf483f8324bf65d3e29ac25e93))

### Perl/LWP-MediaTypes

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ff49072](https://github.com/OpenIndiana/oi-userland/commit/ff49072702e2f542a53a8a889d14995ae94dd3fa))

### Perl/LWP-Protocol-https

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c08d3bd](https://github.com/OpenIndiana/oi-userland/commit/c08d3bd4e3e3c7430dd05adfb8a921ced7bad01e))

### Perl/Lingua-EN-Inflect

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b1bdc2d](https://github.com/OpenIndiana/oi-userland/commit/b1bdc2df81386bfb3c475cc55aea97b421fbabf7))

### Perl/List-MoreUtils

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8f0f3de](https://github.com/OpenIndiana/oi-userland/commit/8f0f3dedd0dccf562d8fae1c113e12a40d27cbc8))

### Perl/List-MoreUtils-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a377695](https://github.com/OpenIndiana/oi-userland/commit/a377695e7d98670d9fb8225b8390060f78337924))

### Perl/List-SomeUtils

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b2aebc6](https://github.com/OpenIndiana/oi-userland/commit/b2aebc6a019edd9605a3dd0cdd1cbc29eba12c39))

### Perl/List-SomeUtils-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([643e63f](https://github.com/OpenIndiana/oi-userland/commit/643e63f2d2608a18f8d48feac292a86774cef360))

### Perl/Log-Dispatch

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1e6646c](https://github.com/OpenIndiana/oi-userland/commit/1e6646c44d165d245ad3e444ec3f30f7aa1f4ed1))

### Perl/Log-Dispatch-FileRotate

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5c00dc1](https://github.com/OpenIndiana/oi-userland/commit/5c00dc1fed124075d2f82849eefae06f260825d3))

### Perl/Log-Log4perl

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([16a429b](https://github.com/OpenIndiana/oi-userland/commit/16a429bca99f02d01a6c01f55c5a336fdb1b1965))

### Perl/MIME-Base32

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([24ab153](https://github.com/OpenIndiana/oi-userland/commit/24ab153ac0fac978846555c68c5375e886232316))

### Perl/MIME-Charset

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([186b26e](https://github.com/OpenIndiana/oi-userland/commit/186b26e7ad9f5d8f7e6bfd2fd8f7c6c6ddde5b00))

### Perl/MIME-Lite

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7fc9dbb](https://github.com/OpenIndiana/oi-userland/commit/7fc9dbbf58a043195eea0d4a77a6671e910dbbff))

### Perl/MIME-Types

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d34a56e](https://github.com/OpenIndiana/oi-userland/commit/d34a56ea83f52a38d0839cf9a0261ee9b5d4e6d4))
- Update to 2.29 ([f69087f](https://github.com/OpenIndiana/oi-userland/commit/f69087f2414984d5273f8292ff55046105a53d66))

### Perl/MRO-Compat

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bd28ed7](https://github.com/OpenIndiana/oi-userland/commit/bd28ed7f543545d988fe3fbcd60333dfdad9d29a))

### Perl/Mail-AuthenticationResults

- Update to 2.20250709; obsolete package for Perl 5.36 ([57d0536](https://github.com/OpenIndiana/oi-userland/commit/57d0536c4ebf0acce9738fa6e1292386196f5cb2))
- Rebuild for Perl 5.42 ([f50fe0c](https://github.com/OpenIndiana/oi-userland/commit/f50fe0c828a3b87adc8be402c5adb99f5b4e2297))

### Perl/Mail-DKIM

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5b864a3](https://github.com/OpenIndiana/oi-userland/commit/5b864a3f57ac96c75b5227d2637ecf1eab14d2ee))

### Perl/Mail-DMARC

- Update to 1.20250610; obsolete package for Perl 5.36 ([ff45c82](https://github.com/OpenIndiana/oi-userland/commit/ff45c823e24c97d756388e11b6753848bc370900))
- Update to 1.20250805; rebuild for Perl 5.42 ([3691b2d](https://github.com/OpenIndiana/oi-userland/commit/3691b2d1e3b52d5cdbd88b42557c98754efc8413))

### Perl/Mail-SPF

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b4acf98](https://github.com/OpenIndiana/oi-userland/commit/b4acf98c5006fb8533d7c256e57b1eac460b0657))

### Perl/Mail-SpamAssassin

- Update to 4.000002; rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([88de058](https://github.com/OpenIndiana/oi-userland/commit/88de0584c26e2f855382beda0d1e5c52249d51df))

### Perl/MailTools

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([49aa8c0](https://github.com/OpenIndiana/oi-userland/commit/49aa8c03f3841058e645d02638c58b7ce7117097))

### Perl/Math-Base-Convert

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b49ba8f](https://github.com/OpenIndiana/oi-userland/commit/b49ba8f9cc22b9b0f225699d352374b7b25844f5))
- Update to 0.13 ([6ba5ad0](https://github.com/OpenIndiana/oi-userland/commit/6ba5ad02446bde62478089ec28dc1faf1e9d8cf6))

### Perl/Math-BigInt

- Update to 2.005003 for Perl 5.42; obsolete package for Perl 5.36 ([ab29da6](https://github.com/OpenIndiana/oi-userland/commit/ab29da6763f4d181bd11295a3d11392ff1aa6aa7))
- Obsolete library/perl-5/math-bigrat-536 ([9b131ea](https://github.com/OpenIndiana/oi-userland/commit/9b131ea7c9913f9039bd358ab30402e818502608))

### Perl/Math-BigInt-FastCalc

- Obsolete package for Perl 5.36 ([4302985](https://github.com/OpenIndiana/oi-userland/commit/43029852a8ea0721c6739433d8b024b1dd841f75))

### Perl/Math-BigInt-GMP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([972ce3b](https://github.com/OpenIndiana/oi-userland/commit/972ce3bd33fb25a197c92e917a5e8fde6eda6339))

### Perl/Math-Int64

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([42d3e0c](https://github.com/OpenIndiana/oi-userland/commit/42d3e0c90597bb0e274c7450873225251d921c97))

### Perl/Math-Prime-Util

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([056b871](https://github.com/OpenIndiana/oi-userland/commit/056b8718f825960d119d4400c680e8bedb306026))

### Perl/Math-Prime-Util-GMP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([776b253](https://github.com/OpenIndiana/oi-userland/commit/776b25343c0ced88cbed9675bfbb823978c7a3c6))

### Perl/Math-Random-ISAAC

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a737ad9](https://github.com/OpenIndiana/oi-userland/commit/a737ad95c9a69b951fb1fe8f84ba7166c8417f32))
- Require library/perl-5/math-random-isaac-xs ([9ee2615](https://github.com/OpenIndiana/oi-userland/commit/9ee26150bf0a0473d807be65b9e7b0722210ecff))

### Perl/Math-Random-ISAAC-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([85deb8b](https://github.com/OpenIndiana/oi-userland/commit/85deb8b19d8d797d54222ea24117e0687452099f))

### Perl/Math-Round

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([23821e8](https://github.com/OpenIndiana/oi-userland/commit/23821e826f0583224730c9b812632cdfce3cf1a1))

### Perl/Memoize

- Obsolete package for Perl 5.36 ([7e63fa4](https://github.com/OpenIndiana/oi-userland/commit/7e63fa4955e82f573cac7fd2f421efffc42dab63))

### Perl/Mixin-Linewise

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([85ab137](https://github.com/OpenIndiana/oi-userland/commit/85ab137d65e3d365e33154040d68afbf6c42df1c))

### Perl/Mock-Config

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1aeb466](https://github.com/OpenIndiana/oi-userland/commit/1aeb466c0fa876ce7dfc536374cdc3dcb7eaef41))
- Update to 0.05 ([e655cc3](https://github.com/OpenIndiana/oi-userland/commit/e655cc3497b82b623cbef394e9917f10e15de7e2))

### Perl/Module-Build

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([795097c](https://github.com/OpenIndiana/oi-userland/commit/795097cf57767b2112a8f9818e4348dbdff0cc7d))

### Perl/Module-Build-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b351f7c](https://github.com/OpenIndiana/oi-userland/commit/b351f7cdb19876e8f6aa2ef1eeca183d54c90b9f))

### Perl/Module-Build-XSUtil

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([af79fc2](https://github.com/OpenIndiana/oi-userland/commit/af79fc27b5a5039eb05939d49f523b6a5bf5188f))

### Perl/Module-Implementation

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ec88f4b](https://github.com/OpenIndiana/oi-userland/commit/ec88f4b773b83463d7be79c8a569f58ad52e4670))

### Perl/Module-Install

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([22f4205](https://github.com/OpenIndiana/oi-userland/commit/22f42052373d76fca881c3961c8d4706bb7a6076))

### Perl/Module-Metadata

- Obsolete package for Perl 5.36 ([32b804a](https://github.com/OpenIndiana/oi-userland/commit/32b804a4de0cb7e6deb405a2b953f7a123977b0c))

### Perl/Module-Pluggable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9c2139b](https://github.com/OpenIndiana/oi-userland/commit/9c2139b48121c44f2a3226880b7ab2e3bcec219e))

### Perl/Module-Runtime

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([34f4885](https://github.com/OpenIndiana/oi-userland/commit/34f4885809a787d0b6f0e6397e2044ce344dc1bd))

### Perl/Module-ScanDeps

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([78ccf5a](https://github.com/OpenIndiana/oi-userland/commit/78ccf5ae41a58006a32f942182edf1c094663fbc))

### Perl/Module-Signature

- Update to 0.90; obsolete package for Perl 5.36 ([0d9ccea](https://github.com/OpenIndiana/oi-userland/commit/0d9ccea8fa33f2cfa8cf1ad4f80d33cd3ccc6f85))
- Update to 0.92 ([3760b02](https://github.com/OpenIndiana/oi-userland/commit/3760b02bc70474f64820ea21ad01024639487e29))
- Update to 0.93 ([8148676](https://github.com/OpenIndiana/oi-userland/commit/814867653818dfda8ab3fe8c0157faa0834fdddb))
- Rebuild for Perl 5.42 ([3147d10](https://github.com/OpenIndiana/oi-userland/commit/3147d1041e9deb4148219cdb8235f74315f787f4))

### Perl/Mojo-Log-Clearable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([78fafba](https://github.com/OpenIndiana/oi-userland/commit/78fafbaabacd4e7aaca245fe835ec05d90689552))

### Perl/Mojolicious

- Update to 9.41; obsolete package for Perl 5.36 ([38be1d5](https://github.com/OpenIndiana/oi-userland/commit/38be1d5140ce008ba48023708eec68868ae9434f))
- Rebuild for Perl 5.42 ([5acaa04](https://github.com/OpenIndiana/oi-userland/commit/5acaa048c64be1b1d93353ed0f8519d61788d208))
- Update to 9.42 ([2d12f41](https://github.com/OpenIndiana/oi-userland/commit/2d12f418ffc2626fe73882f04f982e92381066bf))

### Perl/Moo

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e00888e](https://github.com/OpenIndiana/oi-userland/commit/e00888e1ebdb4f01df9ad6192ce352a194d37209))

### Perl/MooX-Types-MooseLike

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([94d8d28](https://github.com/OpenIndiana/oi-userland/commit/94d8d28b6ddab0d4c8ddd7672e851c49ad0bc13d))

### Perl/Mouse

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0bc0207](https://github.com/OpenIndiana/oi-userland/commit/0bc0207f748a8d02c7c349dd7e5c70336bf0ae10))

### Perl/Mozilla-CA

- Rebuild for Perl 5.42 ([acc87ff](https://github.com/OpenIndiana/oi-userland/commit/acc87fff3100a77abd07d5e3991e5fcf938e753b))

### Perl/Mozilla-PublicSuffix

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3a2d3b2](https://github.com/OpenIndiana/oi-userland/commit/3a2d3b23bc4e964555297b6ea64d2b7ec288d931))

### Perl/Net-CIDR-Lite

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4b9e368](https://github.com/OpenIndiana/oi-userland/commit/4b9e368ad63f2c417d3a80a3d2d5a82e9880ba46))

### Perl/Net-DNS

- Update to 1.51; obsolete package for Perl 5.36 ([ff0890d](https://github.com/OpenIndiana/oi-userland/commit/ff0890d57cda136ad4267ade45b3f5dc08a4862d))
- Update to 1.52; rebuild for Perl 5.42 ([c4ad19e](https://github.com/OpenIndiana/oi-userland/commit/c4ad19e00ea9705064c9136251aa5633387d8e05))
- Update to 1.53 ([cd9665a](https://github.com/OpenIndiana/oi-userland/commit/cd9665aadbde436eaa8e8892dce2116ec95f3488))

### Perl/Net-DNS-Resolver-Mock

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d89af7c](https://github.com/OpenIndiana/oi-userland/commit/d89af7cbdc8b0f74312d1d071846c01155828579))

### Perl/Net-DNS-Resolver-Programmable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8dd7e57](https://github.com/OpenIndiana/oi-userland/commit/8dd7e570b7b3a9a9952439f6ef4f28d78513daf4))

### Perl/Net-Domain-TLD

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f81e3e1](https://github.com/OpenIndiana/oi-userland/commit/f81e3e182d5ffc8bb0df85a158bfffdd6f4be488))

### Perl/Net-HTTP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6f02114](https://github.com/OpenIndiana/oi-userland/commit/6f02114a3b70d9aa737591816c274dd052d1e475))
- Update to 6.24 ([3f27dd3](https://github.com/OpenIndiana/oi-userland/commit/3f27dd3fb84f9bc2b213646576acbd21dd108c9b))

### Perl/Net-IDN-Encode

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([00d094c](https://github.com/OpenIndiana/oi-userland/commit/00d094cf664b4989752cbebfc59400c3f8f0faab))

### Perl/Net-IMAP-Simple

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3cc0896](https://github.com/OpenIndiana/oi-userland/commit/3cc0896bdc4a41b23431619647aba7e047a90776))

### Perl/Net-IP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d9008c7](https://github.com/OpenIndiana/oi-userland/commit/d9008c737b4d42dc01b0e65561dc3cadbd8c9229))

### Perl/Net-LibIDN

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([871f277](https://github.com/OpenIndiana/oi-userland/commit/871f2776aae4ffa5d7d19c3b03371ede0cc99a33))

### Perl/Net-LibIDN2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3e7129a](https://github.com/OpenIndiana/oi-userland/commit/3e7129a5be6d8522e950f1954ac4369c44766093))

### Perl/Net-Patricia

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8c1ec61](https://github.com/OpenIndiana/oi-userland/commit/8c1ec613fbe8c51e5193173107b2c43534eec1b3))
- Update to 1.24 ([0f91ef6](https://github.com/OpenIndiana/oi-userland/commit/0f91ef6d3753e2b44f8025931a62bb8e93d0f0cf))

### Perl/Net-SMTPS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3ec71be](https://github.com/OpenIndiana/oi-userland/commit/3ec71be74891d2e8c21ca31fd041143f400cab0f))

### Perl/Net-SNMP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b98a2bc](https://github.com/OpenIndiana/oi-userland/commit/b98a2bce8fce5aa0157aafd18be1028af4199435))

### Perl/Net-SSLeay

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([dc7d8ba](https://github.com/OpenIndiana/oi-userland/commit/dc7d8ba1d84bc37f7bf9c46df12d8d4d8410f37d))

### Perl/Net-Server

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7f6e1f6](https://github.com/OpenIndiana/oi-userland/commit/7f6e1f6d597fe7d7b10c86fbb8e48ee548e3e846))

### Perl/NetAddr-IP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9777472](https://github.com/OpenIndiana/oi-userland/commit/97774727b8cd166fc4d95449ea06bff50cc7c2e4))

### Perl/Number-Compare

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b9d8bbb](https://github.com/OpenIndiana/oi-userland/commit/b9d8bbbbfcf9ac8703eb03c8112b3fb13d0d2b25))

### Perl/PAR-Dist

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4a54298](https://github.com/OpenIndiana/oi-userland/commit/4a542986a6ca99f3e42ea795c6eb687ffaf3f83d))

### Perl/PDF-API2

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([91cc186](https://github.com/OpenIndiana/oi-userland/commit/91cc18607d19e1527ffa72b3e24ac5cc75e42ba7))
- Update to 2.048 ([8656924](https://github.com/OpenIndiana/oi-userland/commit/865692455cc0ee14156da9d15efc81972fa73c33))

### Perl/POSIX-strptime

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([43e2181](https://github.com/OpenIndiana/oi-userland/commit/43e2181c80b966f2631765723f09384f45ff0055))

### Perl/PPI

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2ed4d52](https://github.com/OpenIndiana/oi-userland/commit/2ed4d52446034310951abc98a793b315bafea9f0))

### Perl/PPIx-QuoteLike

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([45dbae8](https://github.com/OpenIndiana/oi-userland/commit/45dbae8c61f80215a223c90243e0add44f861a54))

### Perl/PPIx-Regexp

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6372ef9](https://github.com/OpenIndiana/oi-userland/commit/6372ef993c87e9e6f495ed3b4c9b89b53fd7dd8b))
- Update to 0.090 ([21664b6](https://github.com/OpenIndiana/oi-userland/commit/21664b6a7dfb8bd7cd4587df054ac7c548cd8262))
- Update to 0.091 ([8480048](https://github.com/OpenIndiana/oi-userland/commit/8480048a5a3f74434c9fae4554468f1e698be3c5))

### Perl/PPIx-Utils

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8920f2f](https://github.com/OpenIndiana/oi-userland/commit/8920f2fca4a08cb5ac7dd181626310dc7eea127e))

### Perl/Package-DeprecationManager

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([baa0d20](https://github.com/OpenIndiana/oi-userland/commit/baa0d201823955f0853006ee093bd339af45ec87))

### Perl/Package-Stash

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([73a10a8](https://github.com/OpenIndiana/oi-userland/commit/73a10a856a9ad487451da9daddb786f4fe49951d))

### Perl/Package-Stash-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([75a694a](https://github.com/OpenIndiana/oi-userland/commit/75a694a289f50f8c2dc189b2e257d13aecacffef))

### Perl/PadWalker

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d69994b](https://github.com/OpenIndiana/oi-userland/commit/d69994b9cd179ca242e0135c89b2ef85405a9199))

### Perl/Parallel-Iterator

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([17b2897](https://github.com/OpenIndiana/oi-userland/commit/17b28975947c3cf062dac9baeb868a5fbcaed889))

### Perl/Params-Util

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4af16a8](https://github.com/OpenIndiana/oi-userland/commit/4af16a83ef882934b1694235bfc820e3f2974960))

### Perl/Params-Validate

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c8f61d2](https://github.com/OpenIndiana/oi-userland/commit/c8f61d277ae7c72a9b24d7dd755a0fc36cb69954))

### Perl/Params-ValidationCompiler

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0c06736](https://github.com/OpenIndiana/oi-userland/commit/0c067365b0303b4519cfcccaaf75b458a322c127))

### Perl/Parse-RecDescent

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([152828c](https://github.com/OpenIndiana/oi-userland/commit/152828c7c9f93316c1dbb3a6586668c0772e935f))

### Perl/Parse-Yapp

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7994d6a](https://github.com/OpenIndiana/oi-userland/commit/7994d6aede8b9ed32fd5a1fdfc78bc9ab952134f))

### Perl/Path-Class

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8ad5307](https://github.com/OpenIndiana/oi-userland/commit/8ad5307e4316c2805c484997ad4e90e0a5ef7568))

### Perl/Path-Tiny

- Update to 0.150; rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6bfbc4c](https://github.com/OpenIndiana/oi-userland/commit/6bfbc4c99d66c219d50f88852069f40243b96cb9))

### Perl/Perl-Critic

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([979ee8f](https://github.com/OpenIndiana/oi-userland/commit/979ee8f5296c007103a295bb10d9f6f3501c0f3f))

### Perl/Perl-Critic-Policy-Perlsecret

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([14debba](https://github.com/OpenIndiana/oi-userland/commit/14debbacd38f3040b7d3eeea9634d55175d7e26e))

### Perl/Perl-Tidy

- Update to 20250616; obsolete package for Perl 5.36 ([80d2b3f](https://github.com/OpenIndiana/oi-userland/commit/80d2b3fabd9214946f90e782fb796a7cf5788fa1))
- Update to 20250711 ([f66015b](https://github.com/OpenIndiana/oi-userland/commit/f66015b2f4517773df1cae5db28ad77a2785013d))
- Rebuild for Perl 5.42 ([f646371](https://github.com/OpenIndiana/oi-userland/commit/f646371be5f9fb5b09bb30c15a9ae1155a439e05))
- Update to 20250912 ([d342303](https://github.com/OpenIndiana/oi-userland/commit/d3423035a152e1de40af9018ef4a0987d574e506))

### Perl/PerlIO-utf8_strict

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([778c1ab](https://github.com/OpenIndiana/oi-userland/commit/778c1abf0b5373d78c1a47f0235086c67ac508b9))

### Perl/PerlIO-via-QuotedPrint

- Obsolete package for Perl 5.36 ([95d30e2](https://github.com/OpenIndiana/oi-userland/commit/95d30e20f97c6b74f14c92acd7357d6b11d945a7))

### Perl/PkgConfig

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4f5f078](https://github.com/OpenIndiana/oi-userland/commit/4f5f078fc717392bb3a45719550d5ec1dd5907f8))

### Perl/Pod-Checker

- Obsolete package for Perl 5.36 ([722acac](https://github.com/OpenIndiana/oi-userland/commit/722acac89ad705cb89419e36ba4edf8507c577d8))

### Perl/Pod-Coverage

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6c73354](https://github.com/OpenIndiana/oi-userland/commit/6c73354e399c07fb2cfc0f81ef67f6b81e7efc9c))

### Perl/Pod-Coverage-TrustPod

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a9eb32a](https://github.com/OpenIndiana/oi-userland/commit/a9eb32a0ac8cb24ed81318fa05aefd8afc2c3cc7))

### Perl/Pod-Eventual

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f858c41](https://github.com/OpenIndiana/oi-userland/commit/f858c416a7a5e020b54d420bc8cf5f48adbaf91a))

### Perl/Pod-Parser

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([882dcd9](https://github.com/OpenIndiana/oi-userland/commit/882dcd96f2dccc32e998b54495198c36e5d440df))

### Perl/Pod-Simple

- Update to 3.47 for Perl 5.42; obsolete package for Perl 5.36 ([1e7c63b](https://github.com/OpenIndiana/oi-userland/commit/1e7c63be30a153c589f253dff69fd0288ce61f17))

### Perl/Pod-Spell

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b31cdf8](https://github.com/OpenIndiana/oi-userland/commit/b31cdf8309689dda24a1fc6b1cc46e999eeb5215))

### Perl/Pod-Usage

- Obsolete package for Perl 5.36 ([aca97b4](https://github.com/OpenIndiana/oi-userland/commit/aca97b407421b71198f129d0f8eae3844c8088de))

### Perl/Proc-ProcessTable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c6cef05](https://github.com/OpenIndiana/oi-userland/commit/c6cef05b9f6b9199871fab8de49a27746ceaf5dc))
- Update to 0.637 ([12984f2](https://github.com/OpenIndiana/oi-userland/commit/12984f2ddb64e9d1258872bbe321cf4de47eb48a))

### Perl/Razor2-Client-Agent

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b033885](https://github.com/OpenIndiana/oi-userland/commit/b0338853d080e02d5ee69fff32c26777c31e7ded))

### Perl/Readonly

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([029ed74](https://github.com/OpenIndiana/oi-userland/commit/029ed7410b3fceaeeb7ad36b746462afcaeda1b1))

### Perl/Ref-Util

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9b2058a](https://github.com/OpenIndiana/oi-userland/commit/9b2058a0551ff08590fb8ca0dd93ef0d6f9cfe12))

### Perl/Ref-Util-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0460451](https://github.com/OpenIndiana/oi-userland/commit/046045141e394f68730c142860f1fab8683a97c2))

### Perl/Regexp-Common

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e3aeb6a](https://github.com/OpenIndiana/oi-userland/commit/e3aeb6a6244396e93aa730eb399537ef55c1f28c))

### Perl/Regexp-IPv4

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([927ba50](https://github.com/OpenIndiana/oi-userland/commit/927ba5085a056d20b0c57f98ecd19d0a9221f8e9))

### Perl/Regexp-IPv6

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0e8e376](https://github.com/OpenIndiana/oi-userland/commit/0e8e37631649bb45ac9c0a0cd722ffbd6af2eac7))

### Perl/Regexp-Util

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f10460b](https://github.com/OpenIndiana/oi-userland/commit/f10460b372f435b13c5753be22cd965b78e06885))

### Perl/Role-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([80cb5cc](https://github.com/OpenIndiana/oi-userland/commit/80cb5cc5b2a843b82a71300adce646c2f994ed9d))

### Perl/SQL-Statement

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9ee3683](https://github.com/OpenIndiana/oi-userland/commit/9ee368395e384306190de3c25e874825ee328d75))

### Perl/Safe-Isa

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([be73fcf](https://github.com/OpenIndiana/oi-userland/commit/be73fcfd790e6ada8ee3dc9b9f4106719fe17391))

### Perl/Scalar-List-Utils

- Update to 1.70; obsolete package for Perl 5.36 ([75ea247](https://github.com/OpenIndiana/oi-userland/commit/75ea247ef26ebb2e0513683f4e4c2222bcbc8140))

### Perl/Scope-Guard

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([880bc4e](https://github.com/OpenIndiana/oi-userland/commit/880bc4e5f657ff97d2858f990b6fe32e436c3455))

### Perl/Sereal-Decoder

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b7c62f3](https://github.com/OpenIndiana/oi-userland/commit/b7c62f3e4cbdb8b53685597a3d74ed7d9d5018de))

### Perl/Sereal-Encoder

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1c88128](https://github.com/OpenIndiana/oi-userland/commit/1c88128bc9e42478e2e5c8571c00fa0da9c91eef))

### Perl/Socket

- Update to 2.039; obsolete package for Perl 5.36 ([a8db880](https://github.com/OpenIndiana/oi-userland/commit/a8db8801375ebaa41981cce40a04293018e3bd51))
- Update to 2.040 ([9c99c00](https://github.com/OpenIndiana/oi-userland/commit/9c99c006c47c1db5e1b0fba532c33ec9f81f6b7f))

### Perl/Socket6

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0d1d078](https://github.com/OpenIndiana/oi-userland/commit/0d1d0788ae9e9e6e012ff219a67df653f990cef3))

### Perl/Sort-Versions

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c05c0eb](https://github.com/OpenIndiana/oi-userland/commit/c05c0eb6cf674f29bd298955ce9fd412aae11340))

### Perl/Specio

- Update to 0.51; obsolete package for Perl 5.36 ([9782db0](https://github.com/OpenIndiana/oi-userland/commit/9782db0c386d25b21a7b55d54198b9f396e9c907))
- Rebuild for Perl 5.42 ([e1edf13](https://github.com/OpenIndiana/oi-userland/commit/e1edf13367b8fb2f4730d6a19d9f08be3a79c3a6))
- Update to 0.52 ([933aaee](https://github.com/OpenIndiana/oi-userland/commit/933aaee66f503b9e016f046347bde478b837d853))
- Update to 0.53 ([32799ef](https://github.com/OpenIndiana/oi-userland/commit/32799efa728bac39477333d58f8a80ed5f673d73))

### Perl/Statistics-ChiSquare

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([30d085b](https://github.com/OpenIndiana/oi-userland/commit/30d085b12a351c9424d9348e4039392d7cd5a2d6))

### Perl/String-Format

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e8084fb](https://github.com/OpenIndiana/oi-userland/commit/e8084fbc8e92e8fd55ed9889588b5b0982d1da68))

### Perl/Sub-Exporter

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([92bc2b4](https://github.com/OpenIndiana/oi-userland/commit/92bc2b488c3bff37b82af3175ec65c8e5fd7aa09))

### Perl/Sub-Exporter-Progressive

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9225c44](https://github.com/OpenIndiana/oi-userland/commit/9225c441dd937d3a772d9a41f44d9a26ed4b4f59))

### Perl/Sub-Identify

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1244085](https://github.com/OpenIndiana/oi-userland/commit/1244085f6686f9622e2e718adb7a130e1d92beff))

### Perl/Sub-Info

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([dcb7f9a](https://github.com/OpenIndiana/oi-userland/commit/dcb7f9aafd7a8df76e13da6f55fd376c4a324ec1))

### Perl/Sub-Install

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([292c0d2](https://github.com/OpenIndiana/oi-userland/commit/292c0d286e344dcd8921f2121da714ace53db5db))

### Perl/Sub-Name

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bdc7c87](https://github.com/OpenIndiana/oi-userland/commit/bdc7c87ede2f7e3b3bec8bee2f293e9ce5192ca8))

### Perl/Sub-Quote

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([1d11901](https://github.com/OpenIndiana/oi-userland/commit/1d119010e9c52c9df1b2e3a7ed617ff15f1cea05))
- Update to 2.006009 ([a717ffa](https://github.com/OpenIndiana/oi-userland/commit/a717ffaaed2e06e780157ed9a3ffc7497140a2c0))

### Perl/Sub-Uplevel

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f203b50](https://github.com/OpenIndiana/oi-userland/commit/f203b508400c890ae0c376eed01c2e5cc855be29))

### Perl/Switch

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d062e2a](https://github.com/OpenIndiana/oi-userland/commit/d062e2a067cf73585eee61d0ef22970dd7cb9fe5))

### Perl/TOML-Parser

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([effc68c](https://github.com/OpenIndiana/oi-userland/commit/effc68c1887dd908106c05b96b4255e92e3d835f))

### Perl/TOML-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([92508f3](https://github.com/OpenIndiana/oi-userland/commit/92508f37e591672f6555a6deb44a048d9e20fe71))

### Perl/Task-Weaken

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([da435b7](https://github.com/OpenIndiana/oi-userland/commit/da435b71e043b5f444b9bf670cf33ba682b9d84a))

### Perl/Template-Toolkit

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2a6cae0](https://github.com/OpenIndiana/oi-userland/commit/2a6cae00d763e49fc894673a32fef8fdd5e85645))

### Perl/Term-Cap

- Obsolete package for Perl 5.36) ([b8a274a](https://github.com/OpenIndiana/oi-userland/commit/b8a274aa287ac61e4a686783e6775875c5f97a32))

### Perl/Term-Size-Any

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a040290](https://github.com/OpenIndiana/oi-userland/commit/a040290eb88470bc995d10d2db3132f37e3edbd6))

### Perl/Term-Size-Perl

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([672db4e](https://github.com/OpenIndiana/oi-userland/commit/672db4e2e1ecc289148177d5a1d65d0303acbc8c))

### Perl/Term-Table

- Obsolete package for Perl 5.36 ([544fa6b](https://github.com/OpenIndiana/oi-userland/commit/544fa6bdd6909f7fcf0dd917b17864ff6dc9f44c))
- Update to 0.025 ([047d6b7](https://github.com/OpenIndiana/oi-userland/commit/047d6b7b5d246ca3ebca3e5142221b243d36cfe5))

### Perl/TermReadKey

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e99477a](https://github.com/OpenIndiana/oi-userland/commit/e99477a5ed3fb519a9c585325ad9e493f3c9325c))

### Perl/Test-Deep

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([daab5a7](https://github.com/OpenIndiana/oi-userland/commit/daab5a73e100f9225b3ed79eefb50790837c8fd8))

### Perl/Test-Deep-Fuzzy

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a569c33](https://github.com/OpenIndiana/oi-userland/commit/a569c3367c683ad9f55e0fb20eae696e19442325))

### Perl/Test-Differences

- Update to 0.72; obsolete package for Perl 5.36 ([4024985](https://github.com/OpenIndiana/oi-userland/commit/40249857976644dab7d4e4c9627c387521172fe2))
- Rebuild for Perl 5.42 ([a13e571](https://github.com/OpenIndiana/oi-userland/commit/a13e5713fefd97541526eee1af1246beb3cac72d))

### Perl/Test-Exception

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([eb6e960](https://github.com/OpenIndiana/oi-userland/commit/eb6e960092f9f44530fd7b5ec5b9b7183f7ba9b6))

### Perl/Test-FailWarnings

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f0607e1](https://github.com/OpenIndiana/oi-userland/commit/f0607e10769c528e12aace05271754ac90e0d2a2))

### Perl/Test-Fatal

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2d22c77](https://github.com/OpenIndiana/oi-userland/commit/2d22c779a7865748e480088c5d9f0f3b17cf358b))

### Perl/Test-File

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([eb52941](https://github.com/OpenIndiana/oi-userland/commit/eb52941e5fb3cb8ded18c855feff6b0d95113596))

### Perl/Test-File-ShareDir

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([82ea53e](https://github.com/OpenIndiana/oi-userland/commit/82ea53ebb2cb12bc6af528fc4a19b46a9325767b))

### Perl/Test-Harness

- Update to 3.52 for Perl 5.42; obsolete package for Perl 5.36 ([cbadd16](https://github.com/OpenIndiana/oi-userland/commit/cbadd1636315d0958417e59df761837bbb19f8a0))

### Perl/Test-Inter

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([55baf50](https://github.com/OpenIndiana/oi-userland/commit/55baf50ff934152390692d3c3f64909144e27c37))

### Perl/Test-LeakTrace

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5782581](https://github.com/OpenIndiana/oi-userland/commit/5782581db850495b39582dac19e5c0714af1508b))

### Perl/Test-LongString

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([31fa730](https://github.com/OpenIndiana/oi-userland/commit/31fa730d6580ce8a741a6462108fea7616c17cc7))

### Perl/Test-Memory-Cycle

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([241b80d](https://github.com/OpenIndiana/oi-userland/commit/241b80d77774babddfcdb5cef406efd7df4f2565))

### Perl/Test-MockRandom

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([23f8ba0](https://github.com/OpenIndiana/oi-userland/commit/23f8ba07507107c2a66408ff0fe79811fc347d15))

### Perl/Test-Most

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([db2ed85](https://github.com/OpenIndiana/oi-userland/commit/db2ed85198ee123bbaec8e3f50598e94167b8974))

### Perl/Test-Needs

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([8e169e3](https://github.com/OpenIndiana/oi-userland/commit/8e169e30f850daa201433c8a1bbc73be5a395f29))

### Perl/Test-NoWarnings

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d9359b1](https://github.com/OpenIndiana/oi-userland/commit/d9359b1b1c3558e4227fc3a51549dffe2a9c9655))

### Perl/Test-Number-Delta

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([bb5f822](https://github.com/OpenIndiana/oi-userland/commit/bb5f822a2084c3c8a6649e0702332bcff9cb2308))

### Perl/Test-Object

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e2972af](https://github.com/OpenIndiana/oi-userland/commit/e2972afa102bdbe15b256f4a6b777e9453cb3f4a))

### Perl/Test-Output

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([54151e6](https://github.com/OpenIndiana/oi-userland/commit/54151e61a0b569f83db0148693666f64258492b1))

### Perl/Test-Pod

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([394b674](https://github.com/OpenIndiana/oi-userland/commit/394b674364f75eca819798fcf022bacf59819a43))

### Perl/Test-Pod-Coverage

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([753e272](https://github.com/OpenIndiana/oi-userland/commit/753e2721a97e8ded66c17d45f35915c203f6282f))

### Perl/Test-Regexp

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f911463](https://github.com/OpenIndiana/oi-userland/commit/f91146319cdb39ec9a761ba383b519a3018bbc08))

### Perl/Test-Requires

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0b833be](https://github.com/OpenIndiana/oi-userland/commit/0b833be2214c096f0e7de871faa766b01781e6a5))

### Perl/Test-RequiresInternet

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([77f3a3c](https://github.com/OpenIndiana/oi-userland/commit/77f3a3cf9fb89f61322aacbb8419a41f45332f7c))

### Perl/Test-SharedFork

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c71dd9d](https://github.com/OpenIndiana/oi-userland/commit/c71dd9dd9ba9e9ee780549d81539f677980dc6fa))

### Perl/Test-Simple

- Update to 1.302214 for Perl 5.42; obsolete package for Perl 5.36 ([c379a04](https://github.com/OpenIndiana/oi-userland/commit/c379a0433d3f59692f1d642420c150d0af5cf7c2))

### Perl/Test-SubCalls

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2e65f6f](https://github.com/OpenIndiana/oi-userland/commit/2e65f6f4b8cfd9e789f73730424b3d1c855f5cf4))

### Perl/Test-Warn

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([42c4b85](https://github.com/OpenIndiana/oi-userland/commit/42c4b85764aabb452246f33db4debd4355b72072))

### Perl/Test-Warnings

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([091bd05](https://github.com/OpenIndiana/oi-userland/commit/091bd053f9baa3ce18a45de2f11588f9f09d5f5e))

### Perl/Test-Without-Module

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([63dae72](https://github.com/OpenIndiana/oi-userland/commit/63dae7263e795cf74dc899a7cf3bfade8a5f067b))

### Perl/Test2-Plugin-NoWarnings

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ff6eda3](https://github.com/OpenIndiana/oi-userland/commit/ff6eda30584f97d0a649ac79fbc4cdcefd6032fd))

### Perl/Text-Balanced

- Fix undefined $unkpos; obsolete package for Perl 5.36 ([459956e](https://github.com/OpenIndiana/oi-userland/commit/459956ea009c6d08778afdc3af859a15228a53bf))
- Update to 2.07 ([67356d9](https://github.com/OpenIndiana/oi-userland/commit/67356d9f8fd6f5dfd4d06450c45720cb04912362))

### Perl/Text-CSV_XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b323e22](https://github.com/OpenIndiana/oi-userland/commit/b323e22c6d398c33e59cf137935f42257eb2080d))
- Update to 1.61 ([4a2ca6c](https://github.com/OpenIndiana/oi-userland/commit/4a2ca6cc3e5f177905db4c5dec916e4dc8bed613))

### Perl/Text-Diff

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([6467a9f](https://github.com/OpenIndiana/oi-userland/commit/6467a9ff6c931bb72cd1ce61429646e41d587720))

### Perl/Text-Glob

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c72f31b](https://github.com/OpenIndiana/oi-userland/commit/c72f31bc4e299c68c8adb791fdb87a35d211ace5))

### Perl/Text-Soundex

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([935aef0](https://github.com/OpenIndiana/oi-userland/commit/935aef07e51a06503d088c311daf47a692484f45))

### Perl/Text-Tabs+Wrap

- Obsolete package for Perl 5.36 ([5ef67c8](https://github.com/OpenIndiana/oi-userland/commit/5ef67c88f4d2e2eac80ae6dfc22ce94e199b8459))

### Perl/Text-Unidecode

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3d66306](https://github.com/OpenIndiana/oi-userland/commit/3d6630603d309217152ad7c253df79e44ccac72c))

### Perl/Throwable

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7c9a37b](https://github.com/OpenIndiana/oi-userland/commit/7c9a37b26cf7ec53a76cc41b4b50962eb8b04804))

### Perl/Tie-EncryptedHash

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([7361cfe](https://github.com/OpenIndiana/oi-userland/commit/7361cfe25157d86cf3fe16100f1e4114724c6d1e))

### Perl/Tie-RefHash

- Obsolete package for Perl 5.36 ([1f0437f](https://github.com/OpenIndiana/oi-userland/commit/1f0437fdeb91d196f2dbda2e170b6ee2a36d8e26))

### Perl/Time-Duration

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([c866f3c](https://github.com/OpenIndiana/oi-userland/commit/c866f3cb168be67deaa4540a558b623802ae9173))

### Perl/Time-Local

- Obsolete package for Perl 5.36 ([e150551](https://github.com/OpenIndiana/oi-userland/commit/e150551c99bd2d52c7be41bd8d2859ff40a521bb))

### Perl/Time-Piece

- Update to 1.37; obsolete package for Perl 5.36 ([67f54e6](https://github.com/OpenIndiana/oi-userland/commit/67f54e60fe89963648a1375da3faa69336889a9c))
- Update to 1.3701 ([630f5a2](https://github.com/OpenIndiana/oi-userland/commit/630f5a2872ff99b213956649f01c3fc78732e80b))
- Update to 1.38 ([ba6ba06](https://github.com/OpenIndiana/oi-userland/commit/ba6ba06f78741981b4564e176fc61f83bf878b89))
- Update to 1.39 ([4e3be99](https://github.com/OpenIndiana/oi-userland/commit/4e3be998dd78c1a394627f74dcfbb833d4ec168d))

### Perl/TimeDate

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([764353f](https://github.com/OpenIndiana/oi-userland/commit/764353fbcbc6754f68807ededd788c0d512f0068))

### Perl/Tk

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b161556](https://github.com/OpenIndiana/oi-userland/commit/b161556d61bb17c26ad48a471560b75391387f65))

### Perl/Tree-DAG_Node

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([90f27a8](https://github.com/OpenIndiana/oi-userland/commit/90f27a86a31ee136c8c38c630d70a17a81d53190))

### Perl/Try-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4695f22](https://github.com/OpenIndiana/oi-userland/commit/4695f224b8829515c7a8f5ce88925065eaeae648))

### Perl/Type-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([ad2ec38](https://github.com/OpenIndiana/oi-userland/commit/ad2ec382dac35fa89aa8aecc1acf0c934da56f24))
- Update to 2.008003 ([f4c5123](https://github.com/OpenIndiana/oi-userland/commit/f4c5123ec53d293c78b077b18562a10a823a7be5))
- Update to 2.008004 ([9e3f342](https://github.com/OpenIndiana/oi-userland/commit/9e3f342b732bd1b25ada6c6510fcba7c761427b4))

### Perl/Type-Tiny-XS

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([b8e6467](https://github.com/OpenIndiana/oi-userland/commit/b8e64671d45a821472808cd12cdcca46181371a5))

### Perl/Types-Serialiser

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cecbcaf](https://github.com/OpenIndiana/oi-userland/commit/cecbcafb5181d1ccef1b897fa7935a4c8ebd6c7e))

### Perl/URI

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([5192bd0](https://github.com/OpenIndiana/oi-userland/commit/5192bd09afc0af518892b4e9430b342863c4d737))
- Update to 5.33 ([154009e](https://github.com/OpenIndiana/oi-userland/commit/154009e6aa72baf3441649e9460c0b27b44b020d))
- Update to 5.34 ([8f41156](https://github.com/OpenIndiana/oi-userland/commit/8f411567911f53d4c920020e18fb91110e415407))

### Perl/Unicode-LineBreak

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([393a971](https://github.com/OpenIndiana/oi-userland/commit/393a9717179954d8133f946f6016edcf5b701025))

### Perl/Unicode-UTF8

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([78c9f07](https://github.com/OpenIndiana/oi-userland/commit/78c9f073e00916919d80305f65629b039dd20ead))

### Perl/Variable-Magic

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([cfda10f](https://github.com/OpenIndiana/oi-userland/commit/cfda10f73f4a9336e546246c72f7150da5a30126))

### Perl/Variable-OnDestruct

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([588c0b2](https://github.com/OpenIndiana/oi-userland/commit/588c0b23a747f406b00ce54708197a2d1054795b))

### Perl/WWW-RobotRules

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e039af2](https://github.com/OpenIndiana/oi-userland/commit/e039af241000db054e325909982c910166927765))

### Perl/XML-DOM

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2fcbb98](https://github.com/OpenIndiana/oi-userland/commit/2fcbb98495106a35806aecc7c0e1f1f69faa8455))

### Perl/XML-LibXML

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([87255ab](https://github.com/OpenIndiana/oi-userland/commit/87255ab394e8925fbeb7dc964ee01764215c4289))

### Perl/XML-NamespaceSupport

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([59b4ff1](https://github.com/OpenIndiana/oi-userland/commit/59b4ff102a6fd95f3b5b81a9cef54f09a290b7ad))

### Perl/XML-Parser

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([4a047c4](https://github.com/OpenIndiana/oi-userland/commit/4a047c4a2e5ffcdaf05c1ed3dd95a6ba3881fa98))

### Perl/XML-RegExp

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([9584d82](https://github.com/OpenIndiana/oi-userland/commit/9584d828e187862a74a9bae9bf630961dc37d21b))

### Perl/XML-SAX

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([a7b9cda](https://github.com/OpenIndiana/oi-userland/commit/a7b9cda4279e39ccae493f7d5b311d67d042c146))

### Perl/XML-SAX-Base

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([63ae25e](https://github.com/OpenIndiana/oi-userland/commit/63ae25e272972509622075ce66dd1900c233e2df))

### Perl/XML-SAX-Expat

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([048d6c9](https://github.com/OpenIndiana/oi-userland/commit/048d6c94181ff6b1f41103542418c8e0e00448d2))

### Perl/XML-Simple

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2d475b6](https://github.com/OpenIndiana/oi-userland/commit/2d475b6e9b04abfa2a5352392516eae4ed34262f))

### Perl/XString

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([0e114dd](https://github.com/OpenIndiana/oi-userland/commit/0e114dd7798a3125d32c27b87af6ea10edc7833d))

### Perl/YAML-LibYAML

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([aff8917](https://github.com/OpenIndiana/oi-userland/commit/aff89178fd42618ae9a680d8db3a65676c645832))

### Perl/YAML-PP

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2e6eafa](https://github.com/OpenIndiana/oi-userland/commit/2e6eafa3ce75e975e591e21c90bc4a53f78d09b8))

### Perl/YAML-Tiny

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2692b9d](https://github.com/OpenIndiana/oi-userland/commit/2692b9da51772cff03cd420695d558545af5eac6))

### Perl/autodie

- Obsolete package for Perl 5.36 ([c937bb5](https://github.com/OpenIndiana/oi-userland/commit/c937bb5980bda6f3f6eb271397f5e8f871ea5715))

### Perl/bareword-filehandles

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([fc51e94](https://github.com/OpenIndiana/oi-userland/commit/fc51e944f6e31b626136e9aef56dba84f89b2304))

### Perl/bignum

- Obsolete package for Perl 5.36 ([a04d9d8](https://github.com/OpenIndiana/oi-userland/commit/a04d9d8e86455bbb49346ce07ca173a4ef0c2967))

### Perl/common-sense

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([43a85aa](https://github.com/OpenIndiana/oi-userland/commit/43a85aa969e676a8de75a81595ce36b4bb8b6505))

### Perl/experimental

- Update to 0.036; obsolete package for Perl 5.36 ([c609f36](https://github.com/OpenIndiana/oi-userland/commit/c609f3614594b5198ecbd548b634cadcc2fee8b3))

### Perl/inc-latest

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([d3bd4fd](https://github.com/OpenIndiana/oi-userland/commit/d3bd4fd3fde5df849a103e86485c6759a9a4da0f))

### Perl/indirect

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([83d39c5](https://github.com/OpenIndiana/oi-userland/commit/83d39c507c071cc9c3384830268155dd26089941))

### Perl/libnet

- Obsolete package for Perl 5.36 ([123a460](https://github.com/OpenIndiana/oi-userland/commit/123a460c924958e7fa4a1090f366f98e18189b22))

### Perl/libwww-perl

- Update to 6.79; obsolete package for Perl 5.36 ([05f9078](https://github.com/OpenIndiana/oi-userland/commit/05f9078893d816158c0a4f4ef95af46204b45b01))
- Rebuild for Perl 5.42 ([d70091c](https://github.com/OpenIndiana/oi-userland/commit/d70091cbe47f145599d3c3a4fde3a990a5a2e4ae))
- Update to 6.80 ([4a54887](https://github.com/OpenIndiana/oi-userland/commit/4a5488781310ff44c88de644b0d2339134576a4c))
- Update to 6.81 ([a153368](https://github.com/OpenIndiana/oi-userland/commit/a1533682db46f9a11dde5177eef14bd0a93745b3))

### Perl/libxml-perl

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([36c4470](https://github.com/OpenIndiana/oi-userland/commit/36c4470a2e29c0072e21ed4df574ba49abc6cd2e))

### Perl/multidimensional

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([e050b39](https://github.com/OpenIndiana/oi-userland/commit/e050b392f10ef5f5b570e88862dc2c34b3c34bcf))

### Perl/namespace-autoclean

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([2088d98](https://github.com/OpenIndiana/oi-userland/commit/2088d986490cbe66872fb447c7ad5cf5fe60fdea))

### Perl/namespace-clean

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([3601513](https://github.com/OpenIndiana/oi-userland/commit/3601513364b3915743ed9120ba553c18a800680e))

### Perl/parent

- Obsolete package for Perl 5.36 ([8fe9f4e](https://github.com/OpenIndiana/oi-userland/commit/8fe9f4e2b290562cb7a199646518c61ca342ac87))

### Perl/perlfaq

- Update to 5.20250619; obsolete package for Perl 5.36 ([97959a7](https://github.com/OpenIndiana/oi-userland/commit/97959a7613ca6ae3e2aeb0c5f78e96f9c7b47189))

### Perl/pmtools

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([04ea653](https://github.com/OpenIndiana/oi-userland/commit/04ea65370b6592fc7f0d0e7893c876382217ba43))

### Perl/podlators

- Obsolete package for Perl 5.36 ([d19b20d](https://github.com/OpenIndiana/oi-userland/commit/d19b20d5ff88c517346851c8396407cf593a24d4))

### Perl/strictures

- Rebuild for Perl 5.42 and obsolete package for Perl 5.36 ([f9db073](https://github.com/OpenIndiana/oi-userland/commit/f9db073ea6bbabde9df127dc5280919ee6c9ae26))

### Perl/version

- Obsolete package for Perl 5.36 ([44fb6d6](https://github.com/OpenIndiana/oi-userland/commit/44fb6d6f062a194d433448caaa7af7b87333d6dd))

### Pgpool-II

- Update to 4.6.3 ([3f9eca7](https://github.com/OpenIndiana/oi-userland/commit/3f9eca72039d18fc53713a1eb057cd8923e7da71))

### Php-84

- Fix COMPONENT_REVISION ([67b647e](https://github.com/OpenIndiana/oi-userland/commit/67b647e311e1850f349474984bca8b1ff5d5d190))

### Pinentry

- Update to 1.3.2 ([0bd833b](https://github.com/OpenIndiana/oi-userland/commit/0bd833b1ae0e8c9d2a0f6675134b31f97a0f02ba))

### Pixman

- Update to 0.46.2 ([0100108](https://github.com/OpenIndiana/oi-userland/commit/01001088cc706c9f1e678bf37c69426157aa5562))
- Update to 0.46.4 ([bcc6ca2](https://github.com/OpenIndiana/oi-userland/commit/bcc6ca273fedea48dde53bd97fd86e900e151f9c))

### Pkgconf

- Update to 2.5.0 ([ecf07be](https://github.com/OpenIndiana/oi-userland/commit/ecf07be553df3f55f00ff660e8975e5ea621df69))
- Update to 2.5.1 ([2bc3ec3](https://github.com/OpenIndiana/oi-userland/commit/2bc3ec374dc0a956eb141b87567ee916831c6209))

### Postfix

- Update to 3.10.3 ([9c51aba](https://github.com/OpenIndiana/oi-userland/commit/9c51aba048b308f32f514aa001e4982da3ef5446))
- Update to 3.10.4; import patch from OmniOS ([ceed6a7](https://github.com/OpenIndiana/oi-userland/commit/ceed6a7248d14f117429e28b1f2835105ff02928))

### Postgresql-14

- Update to 14.18 ([5afb6d9](https://github.com/OpenIndiana/oi-userland/commit/5afb6d9b178ff49274ac9a267b97eb9e5348c24e))

### Postgresql-14-mysql_fdw

- Fix dependencies ([c385fb9](https://github.com/OpenIndiana/oi-userland/commit/c385fb927b0210e05378d9ea84fdbcf9eda70498))
- Fix build ([49bbcf0](https://github.com/OpenIndiana/oi-userland/commit/49bbcf0e5853716c18737bc40257af55dcf482e6))

### Postgresql-15

- Update to 15.14 ([7406741](https://github.com/OpenIndiana/oi-userland/commit/74067419d527a729097edadf6f7b3202810d8869))

### Postgresql-15-citus

- Update to 13.1.0 ([2b09a4e](https://github.com/OpenIndiana/oi-userland/commit/2b09a4efe09fd56589e5e37920b24eaf4d2b50a6))

### Postgresql-15-mysql_fdw

- Fix build ([19b172e](https://github.com/OpenIndiana/oi-userland/commit/19b172ef62344af6e15e4b7dc03c690d1a7ea321))

### Postgresql-16

- Update to 16.10 ([222cda0](https://github.com/OpenIndiana/oi-userland/commit/222cda093149f40d24ba88dd92e9756b45ef929b))

### Postgresql-16-citus

- Update to 13.1.0 ([bdbd2f9](https://github.com/OpenIndiana/oi-userland/commit/bdbd2f94a760983c58c2fd124fff435ab5d7f01e))
- Update to 13.2.0 ([e6c5813](https://github.com/OpenIndiana/oi-userland/commit/e6c5813e43a5ab90bc5626c44730bb3b0ba8295a))

### Postgresql-16-timescaledb

- Update to 2.20.2 ([4b447ac](https://github.com/OpenIndiana/oi-userland/commit/4b447ac3b40185f6cf61b2ad9bb13f60891aed15))
- Update to 2.20.3 ([864816f](https://github.com/OpenIndiana/oi-userland/commit/864816f6107c205d34ab3b2eba66d9be4c610bc2))
- Update to 2.21.0 ([1637f29](https://github.com/OpenIndiana/oi-userland/commit/1637f2975cfa49d17fdfe5d6574f1956497147f1))
- Update to 2.21.1 ([b72304d](https://github.com/OpenIndiana/oi-userland/commit/b72304d57671432decf8950109d639ffbf36182e))
- Update to 2.21.2 ([5ed2486](https://github.com/OpenIndiana/oi-userland/commit/5ed2486b78f884d76eb73afb15025fa027802700))
- Update to 2.21.3 ([ea1ef42](https://github.com/OpenIndiana/oi-userland/commit/ea1ef4298e529deae5d4a5c2bb8ad405a7c58fb9))
- Update to 2.22.0 ([d677247](https://github.com/OpenIndiana/oi-userland/commit/d677247db38098ae5b8b2bfb14f1dff03c6b60e9))
- Update to 2.22.1 ([49ec05b](https://github.com/OpenIndiana/oi-userland/commit/49ec05b6cd2f5e5d2d8c039db07dc8f52d25c4c4))

### Postgresql-jdbc

- Update to 42.7.6 ([e1835ad](https://github.com/OpenIndiana/oi-userland/commit/e1835adc154fa73964a4d3e0b57e3e37527f21a3))
- Update to 42.7.7 ([57ada23](https://github.com/OpenIndiana/oi-userland/commit/57ada23d243748014914f21813e649865b05d167))
- Update to 42.7.8 ([cfc6ad0](https://github.com/OpenIndiana/oi-userland/commit/cfc6ad03c55acf6803fabe146298ee0f04cf7adc))

### Prep-patch.mk

- Remove duplicate target ([2e66fb8](https://github.com/OpenIndiana/oi-userland/commit/2e66fb8db4c2943b6d63bf21ddfb09134b5d5ec2))

### Prep-svn.mk

- Fix CLOBBER_PATHS ([c1e9312](https://github.com/OpenIndiana/oi-userland/commit/c1e93127d4441795f2bc810191400845dcf53e9c))

### Proj

- Update to 9.6.2 ([964bb26](https://github.com/OpenIndiana/oi-userland/commit/964bb261f8864e80d71cdc4db175247c3fa541a3))
- Update to 9.7.0 ([a064ff2](https://github.com/OpenIndiana/oi-userland/commit/a064ff24666249eec4ba7e987b3831af22f3a934))

### Pulseaudio

- Add 32-bit ([60b829b](https://github.com/OpenIndiana/oi-userland/commit/60b829b7dacc062aa0e2b9931c0ae9ab72ce31d0))

### Puri

- Update to 1.5.7.2; fix metadata ([37db82f](https://github.com/OpenIndiana/oi-userland/commit/37db82fc83d40e817220af494a542b39feee57f7))

### Python-313

- Add 3.13.5 ([a728bfa](https://github.com/OpenIndiana/oi-userland/commit/a728bfacff50844b163c904441119a8f20a65c1e))
- Update to 3.13.6 ([9ee010b](https://github.com/OpenIndiana/oi-userland/commit/9ee010bdd6f0a63ba9d18b0fee98450f60471c9d))
- Update to 3.13.7 ([c327b8d](https://github.com/OpenIndiana/oi-userland/commit/c327b8d49e81f409d18914eaa7245728b51261e9))
- Update to 3.13.8 ([2bb7c93](https://github.com/OpenIndiana/oi-userland/commit/2bb7c93c16c6eacf6d521bd1ce947dcab7229d06))
- Fix dependencies ([3b908e6](https://github.com/OpenIndiana/oi-userland/commit/3b908e677edbd040c617b68765cd4f2fcb191b96))

### Python-314

- Fix vendor-packages directory path ([d21442b](https://github.com/OpenIndiana/oi-userland/commit/d21442b00132a375f2de63e1279fd0d16b87a761))
- Fix build of local modules; depend on runtime/python ([3542d38](https://github.com/OpenIndiana/oi-userland/commit/3542d38e7397eed4ee7345598d1345875ed36269))

### Python-39

- Update to 3.9.23 ([647f5f6](https://github.com/OpenIndiana/oi-userland/commit/647f5f6ce9cf967e3c66dd0671fadcc0a2d950b0))
- Update to 3.9.24 ([ce4457a](https://github.com/OpenIndiana/oi-userland/commit/ce4457ae6374bbc8a9437ed54dad62a6e4ef9356))

### Python/Brotli

- Rebuild for Python 3.14 ([e1ce036](https://github.com/OpenIndiana/oi-userland/commit/e1ce0362cdd655fc5dcba6b1b89fc3a26c76767c))

### Python/CJKwrap

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([bfa31c1](https://github.com/OpenIndiana/oi-userland/commit/bfa31c1e9f458c573988ca5daf3b3c77a35e384c))

### Python/Cython

- Update to 3.1.3 ([437b914](https://github.com/OpenIndiana/oi-userland/commit/437b914c382064bf869293ccb4dc5a379239f223))
- Update to 3.1.4 ([0c091c6](https://github.com/OpenIndiana/oi-userland/commit/0c091c6a636fc1c9760745daad49347f1987c235))

### Python/Faker

- Update to 37.4.0 ([fbf2df0](https://github.com/OpenIndiana/oi-userland/commit/fbf2df01332ba60ba24504c7dfdcacc111139805))
- Update to 37.4.2 ([1256681](https://github.com/OpenIndiana/oi-userland/commit/12566812a0aef41d96d9e5f9438d102daca571c4))
- Update to 37.5.3 ([70ebcb5](https://github.com/OpenIndiana/oi-userland/commit/70ebcb57dd14895f0822a4eb897e12ec4ce5f7ad))
- Update to 37.6.0 ([23e94a9](https://github.com/OpenIndiana/oi-userland/commit/23e94a9557b7c662a908525793fcba75615243ca))
- Update to 37.8.0 ([01434fe](https://github.com/OpenIndiana/oi-userland/commit/01434febb864dfc941a53c4c122b78fcf7a76fe1))

### Python/GitPython

- Update to 3.1.45 ([79e70c0](https://github.com/OpenIndiana/oi-userland/commit/79e70c0bf43d2b9c4c160eac258965859edecc52))

### Python/Markdown

- Update to 3.8.1 ([40bafcd](https://github.com/OpenIndiana/oi-userland/commit/40bafcdf9bfcb602870fd9b81f9e8753c08cd6d3))
- Update to 3.8.2 ([c36c9ed](https://github.com/OpenIndiana/oi-userland/commit/c36c9edb344d76b6676aa5c9ea851c475a8b3cea))
- Update to 3.9 ([d0cc80c](https://github.com/OpenIndiana/oi-userland/commit/d0cc80c431aec0fba963b4fb5494ee5940ee8127))

### Python/MarkupSafe

- Update to 3.0.3 ([b71b9fa](https://github.com/OpenIndiana/oi-userland/commit/b71b9faed92aef274ffe8c4695251da4869c3ec7))

### Python/PyGObject

- Update to 3.54.0; obsolete package for Python 2.7 ([da8f5df](https://github.com/OpenIndiana/oi-userland/commit/da8f5dfbe21b1d8404a7ead60e1efac51481087f))
- Update to 3.54.2 ([d30576a](https://github.com/OpenIndiana/oi-userland/commit/d30576a973006fbecf494c279818480f65a0f42b))
- Update to 3.54.3 ([8ce68ce](https://github.com/OpenIndiana/oi-userland/commit/8ce68ceacb737e0374648653bcc990cd1ae8b8f3))

### Python/PyNaCl

- Update to 1.6.0 ([8db00f8](https://github.com/OpenIndiana/oi-userland/commit/8db00f86c4d38286079c532bc9206c36f32c2cbf))

### Python/PyQt-builder

- Update to 1.19.0 ([e3f1115](https://github.com/OpenIndiana/oi-userland/commit/e3f11154094f4db56687d837eb1aeed0a5b40b2e))

### Python/PyQt5_sip

- Update to 12.17.1 ([359c1f7](https://github.com/OpenIndiana/oi-userland/commit/359c1f7b9dfff126427c05dd224181b7cf77bb8c))
- Rebuild for Python 3.14 ([6cb1e90](https://github.com/OpenIndiana/oi-userland/commit/6cb1e90ca90ff6c88c4465d68e6ae18c58d3c681))

### Python/PySocks

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([fc8caf0](https://github.com/OpenIndiana/oi-userland/commit/fc8caf05f43d180786fddf8910aba4ca9e335b7e))

### Python/PyYAML

- Update to 6.0.3 ([7b18c8c](https://github.com/OpenIndiana/oi-userland/commit/7b18c8c2d7512faa4f9f09bc6bb4dd2a3b31c6f3))

### Python/UkPostcodeParser

- Rebuild for Python 3.14 ([8fc2a68](https://github.com/OpenIndiana/oi-userland/commit/8fc2a6832a788d9a43eadf2a3624168744041d26))

### Python/WebTest

- Update to 3.0.6 ([5ad2faa](https://github.com/OpenIndiana/oi-userland/commit/5ad2faa5473326ad24854b47586378f7c6e2ef80))
- Update to 3.0.7 ([8eb729f](https://github.com/OpenIndiana/oi-userland/commit/8eb729fe68829a8cdffbef5555605032e89dd2ee))

### Python/ZODB

- Update to 6.1 ([63dafb5](https://github.com/OpenIndiana/oi-userland/commit/63dafb588fa4403181cb5ea1dc1b649798c81ecf))

### Python/aiohttp

- Update to 3.12.11 ([dd3582f](https://github.com/OpenIndiana/oi-userland/commit/dd3582f913e573683b52a9582a14ec58c47db7b8))
- Update to 3.12.13 ([1931d2a](https://github.com/OpenIndiana/oi-userland/commit/1931d2a37ada337f37056660552e13223cb08920))
- Update to 3.12.14 ([4f96bc9](https://github.com/OpenIndiana/oi-userland/commit/4f96bc953371e919d4f0a63b88f3694cc4441828))
- Update to 3.12.15 ([7d291ae](https://github.com/OpenIndiana/oi-userland/commit/7d291aef1ee9d2ce213b7537716037f3e5c7bfe5))
- Update to 3.13.0 ([b842b05](https://github.com/OpenIndiana/oi-userland/commit/b842b05cd1be60a2c20cd82cf226ba373abdc108))

### Python/alabaster

- Rebuild for Python 3.14 ([7463713](https://github.com/OpenIndiana/oi-userland/commit/746371345078abc53732630e789021d746573921))

### Python/aniso8601

- Rebuild for Python 3.14 ([0d34db2](https://github.com/OpenIndiana/oi-userland/commit/0d34db243b9c52b2a643789392e77fc44ad94ca9))

### Python/annotated_types

- Rebuild for Python 3.14 ([a238087](https://github.com/OpenIndiana/oi-userland/commit/a238087411ffb3adb5092579564246e8243b32e2))

### Python/anyio

- Update to 4.11.0 ([319d819](https://github.com/OpenIndiana/oi-userland/commit/319d81920182f149764c334765b3455075f94113))

### Python/appdirs

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([6135d2f](https://github.com/OpenIndiana/oi-userland/commit/6135d2f0f52eaa4d9643628ebc5d8fefec1e4976))

### Python/argon2-cffi-bindings

- Update to 25.1.0 ([2391009](https://github.com/OpenIndiana/oi-userland/commit/2391009196ea6cefc63b58b2b440e41253dbec49))

### Python/argon2_cffi

- Update to 25.1.0 ([e0d9cf4](https://github.com/OpenIndiana/oi-userland/commit/e0d9cf489976dd58ea7c50347ce5fb30538de9d7))

### Python/asgiref

- Update to 3.9.1 ([49792d7](https://github.com/OpenIndiana/oi-userland/commit/49792d77dc240493aee317b8f494b701744399eb))
- Update to 3.9.2 ([b976ef8](https://github.com/OpenIndiana/oi-userland/commit/b976ef88d477c974df7486ea73d62f1b085dd0db))
- Update to 3.10.0 ([89ccc9e](https://github.com/OpenIndiana/oi-userland/commit/89ccc9eabdecf376cf66e57ed74d6c1cd33e9b41))

### Python/assertpy

- Rebuild for Python 3.14 ([61b4a46](https://github.com/OpenIndiana/oi-userland/commit/61b4a46dcf4c7aefe8792ff248de3befa97e1b38))

### Python/attrs

- Update to 25.4.0 ([cd39c6d](https://github.com/OpenIndiana/oi-userland/commit/cd39c6d6b5507b9a35aa35c4fc061f0e8aaff7a0))

### Python/autocommand

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([af62553](https://github.com/OpenIndiana/oi-userland/commit/af62553535795c1e9508d0e4553915cda137ca6c))

### Python/backcall

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([b0f5f41](https://github.com/OpenIndiana/oi-userland/commit/b0f5f41f288f5e36e2fe0dc7e92bb6f27d7feb04))

### Python/barman

- Update to 3.14.1 ([61d8a75](https://github.com/OpenIndiana/oi-userland/commit/61d8a7594d58c13defff4108b90e75609d8cc359))
- Update to 3.15.0 ([a27003a](https://github.com/OpenIndiana/oi-userland/commit/a27003a1d6a28619bab5c391539d4b812df8c355))
- Update to 3.16.0 ([d664178](https://github.com/OpenIndiana/oi-userland/commit/d66417805e60e40bdfefdd9eef9b4dcd935c4acf))
- Update to 3.16.1 ([edc27e9](https://github.com/OpenIndiana/oi-userland/commit/edc27e9a6cf7d312dbf69afff5c4fc3be374642b))

### Python/bcrypt

- Update to 5.0.0 ([c9d64d6](https://github.com/OpenIndiana/oi-userland/commit/c9d64d6d1921165320043389e6b88fb783902418))

### Python/beautifulsoup4

- Update to 4.13.5 ([7a2b3cd](https://github.com/OpenIndiana/oi-userland/commit/7a2b3cd3b4491d01298d0478df1cf43d3b9c4bfa))
- Update to 4.14.0 ([5e1a01d](https://github.com/OpenIndiana/oi-userland/commit/5e1a01dcebe32969f482502d41785da5d2ff1327))
- Update to 4.14.2 ([a27c0ac](https://github.com/OpenIndiana/oi-userland/commit/a27c0ac28b66eeafa633533b82abf1c11ebe44b7))

### Python/black

- Update to 25.9.0 ([59d52a0](https://github.com/OpenIndiana/oi-userland/commit/59d52a0609394aedcfbbf0cb55220506f8432a0b))

### Python/bottle

- Update to 0.13.4 ([370a6d0](https://github.com/OpenIndiana/oi-userland/commit/370a6d032728f512f9022bf43a863c819c570393))

### Python/bracex

- Update to 2.6 ([01c5c11](https://github.com/OpenIndiana/oi-userland/commit/01c5c11c5d87454cbf469d88dec18c2057bb66c2))

### Python/build

- Update to 1.3.0 ([2acb273](https://github.com/OpenIndiana/oi-userland/commit/2acb2735377498ce4f26a0643a6a6b4eaa200285))
- Rebuild for Python 3.14 ([c7325b5](https://github.com/OpenIndiana/oi-userland/commit/c7325b56ccb9e39e469319296fc871c4882b7adf))

### Python/cachetools

- Update to 6.1.0 ([6e54798](https://github.com/OpenIndiana/oi-userland/commit/6e54798ad5a6b49dbc5a8249af059e239a3c533b))
- Update to 6.2.0 ([8bd936f](https://github.com/OpenIndiana/oi-userland/commit/8bd936f79f4ef3bdc3ba513054c312443d2f25b6))
- Update to 6.2.1; rebuild for Python 3.14 ([0cfac43](https://github.com/OpenIndiana/oi-userland/commit/0cfac430943d78b7978cebe2e19e7f88de90fbba))

### Python/calver

- Rebuild for Python 3.14 ([4b7378c](https://github.com/OpenIndiana/oi-userland/commit/4b7378c3ec5390701e23278de481c3681dbd5d01))
- Update to 2025.10.20 ([c2d34a5](https://github.com/OpenIndiana/oi-userland/commit/c2d34a5da5708db79dd70256ac22f4fbf2f41325))

### Python/cattrs

- Update to 25.1.1 ([24e078d](https://github.com/OpenIndiana/oi-userland/commit/24e078dbabaace323b861d6652445579b088de78))
- Update to 25.2.0 ([9ed286e](https://github.com/OpenIndiana/oi-userland/commit/9ed286e426d41a94046d18b1205ddacb445682a6))
- Update to 25.3.0 ([9fad96a](https://github.com/OpenIndiana/oi-userland/commit/9fad96a51860f063fe9cea63b7a5c06e00c13c26))

### Python/certifi

- Update to 2025.6.15 ([11e2622](https://github.com/OpenIndiana/oi-userland/commit/11e26225f97729eaf5582b09c3a84f9f2f144cd6))
- Update to 2025.7.9 ([10bc2b2](https://github.com/OpenIndiana/oi-userland/commit/10bc2b2151a047350539219b7a55d6a92b8c2800))
- Update to 2025.7.14 ([2f76af5](https://github.com/OpenIndiana/oi-userland/commit/2f76af58ba56e891db8b2a830b87253c7cdd8093))
- Update to 2025.8.3 ([1c93fdd](https://github.com/OpenIndiana/oi-userland/commit/1c93fdd47027c4bac1ea0b3cebae19811ad4f994))
- Update to 2025.10.5 ([9539af3](https://github.com/OpenIndiana/oi-userland/commit/9539af3c210398e0f8a98049e7fde10bf43cf76b))
- Rebuild for Python 3.14 ([4d30741](https://github.com/OpenIndiana/oi-userland/commit/4d307412fea43396aea1451660b44f207ac053fd))

### Python/chardet

- Rebuild for Python 3.14 ([b189a24](https://github.com/OpenIndiana/oi-userland/commit/b189a2475c85b0de85512b84503f66e9b9f97343))

### Python/charset-normalizer

- Update to 3.4.3 ([d729694](https://github.com/OpenIndiana/oi-userland/commit/d72969451279623781d201cd4bfbc00723696b3e))

### Python/check-manifest

- Update to 0.51; rebuild for Python 3.14 ([31d1b7e](https://github.com/OpenIndiana/oi-userland/commit/31d1b7e5855e185ee623b0dcf85323911a9d3efa))

### Python/cheroot

- Update to 11.0.0 ([40247e8](https://github.com/OpenIndiana/oi-userland/commit/40247e81d4060512199b87627b2e1bb99718af84))

### Python/cmd2

- Update to 2.6.1 ([f07868d](https://github.com/OpenIndiana/oi-userland/commit/f07868d322060ded5730f15453840c2d51349a56))
- Update to 2.6.2 ([19d0583](https://github.com/OpenIndiana/oi-userland/commit/19d0583d657b33212f9f7c446ed51c455c7828b1))

### Python/coherent.licensed

- Rebuild for Python 3.14 ([d88d111](https://github.com/OpenIndiana/oi-userland/commit/d88d1112c3b2e90949a9db57ba83531184dab71c))

### Python/colorama

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([3496581](https://github.com/OpenIndiana/oi-userland/commit/3496581ee525c420f4c04d4b15fef36ee78f391e))

### Python/colorlog

- Update to 6.10.1; rebuild for Python 3.14 ([e79be92](https://github.com/OpenIndiana/oi-userland/commit/e79be922bf84485010183012cef6a380c11f470e))

### Python/configobj

- Rebuild for Python 3.14 ([b5af552](https://github.com/OpenIndiana/oi-userland/commit/b5af5521662f899003cae84de99bf105cba0fc0b))

### Python/consolekit

- Update to 1.9.0 ([0f3115e](https://github.com/OpenIndiana/oi-userland/commit/0f3115ebd447bcc5734a1718a9d93efc4eeb5003))

### Python/coverage

- Update to 7.9.0 ([757d4dd](https://github.com/OpenIndiana/oi-userland/commit/757d4ddde6c7e9f33bbac9d5ffe8725ad81aae81))
- Update to 7.9.1 ([0c79246](https://github.com/OpenIndiana/oi-userland/commit/0c79246bf82e0feed385b7130962f2b1594c43f2))
- Update to 7.10.4 ([b55d979](https://github.com/OpenIndiana/oi-userland/commit/b55d9791c6a20adec125c587774c0b023e2e75e3))
- Update to 7.10.6 ([d8fded0](https://github.com/OpenIndiana/oi-userland/commit/d8fded08bd5109787df59047e28927cecee19d49))
- Update to 7.10.7 ([c19c50e](https://github.com/OpenIndiana/oi-userland/commit/c19c50e3a287cd78d9af95d90a2339ac9502c4c2))

### Python/cryptography

- Update to 45.0.4 ([3b2aaa1](https://github.com/OpenIndiana/oi-userland/commit/3b2aaa1a6f80627fd296c6f63f0c4fecb26b7572))
- Update to 45.0.5 ([961558b](https://github.com/OpenIndiana/oi-userland/commit/961558bb0806b8a098b29f5f8162747784ef78cc))
- Update to 45.0.6 ([fd8768f](https://github.com/OpenIndiana/oi-userland/commit/fd8768faba6e02620cdd19329add782e847dab54))
- Update to 45.0.7 ([4a23375](https://github.com/OpenIndiana/oi-userland/commit/4a233758ad8e9a196f76fd77ca3e6ff2a15beac8))

### Python/cryptography_vectors

- Update to 45.0.4 ([7923713](https://github.com/OpenIndiana/oi-userland/commit/7923713b2a8e0b47af7dc49808068badd7c76407))
- Update to 45.0.5 ([9ebb501](https://github.com/OpenIndiana/oi-userland/commit/9ebb50166f15de33168b176d27dbac86e72dc563))
- Update to 45.0.6 ([b17305e](https://github.com/OpenIndiana/oi-userland/commit/b17305e105dba84850df62dff617d4cf1d8033e4))
- Update to 45.0.7 ([24915b5](https://github.com/OpenIndiana/oi-userland/commit/24915b544b5f054223b8757146b884ef7a102566))

### Python/diff_cover

- Update to 9.4.0 ([fe9ae3f](https://github.com/OpenIndiana/oi-userland/commit/fe9ae3fc30295fe7a683d253f0959106f26581d2))
- Update to 9.4.1 ([8ad033f](https://github.com/OpenIndiana/oi-userland/commit/8ad033fb370b9d8f08a5ff4d16bafebce34cff24))
- Update to 9.5.0 ([64587b4](https://github.com/OpenIndiana/oi-userland/commit/64587b4656fb024afa09e3eff4973a597c9f1870))
- Update to 9.6.0 ([17c2465](https://github.com/OpenIndiana/oi-userland/commit/17c24654ff6f79c62f85a2fb5cb78d449dd3cdfc))
- Update to 9.7.1 ([1c7c063](https://github.com/OpenIndiana/oi-userland/commit/1c7c063e2d4542af71b6dc594cbf2e8d454332c2))

### Python/dirty_equals

- Update to 0.10.0 ([5a66d90](https://github.com/OpenIndiana/oi-userland/commit/5a66d90878ffedcfa3996d56386818f35c49a9ba))
- Rebuild for Python 3.14 ([5a1d13d](https://github.com/OpenIndiana/oi-userland/commit/5a1d13d1ef1d663677b6354b242c2e727305c87d))

### Python/distlib

- Update to 0.4.0 ([e2219b7](https://github.com/OpenIndiana/oi-userland/commit/e2219b74df961c3fccc156a04c82e0c47d6c9801))
- Rebuild for Python 3.14 ([f7ee02e](https://github.com/OpenIndiana/oi-userland/commit/f7ee02e33755edea3e59bae19247c4724008d969))
- Add test results for Python 3.14 ([ff023a5](https://github.com/OpenIndiana/oi-userland/commit/ff023a52fecfbf30af47971d797209d1691c20fa))

### Python/distro

- Rebuild for Python 3.14 ([0a61f27](https://github.com/OpenIndiana/oi-userland/commit/0a61f27c53de174030a6fb644fd6324a65f263cd))

### Python/docutils

- Update to 0.22 ([4058ccd](https://github.com/OpenIndiana/oi-userland/commit/4058ccd956f613919853c92939a8900278a7a5cf))
- Update to 0.22.2 ([f5a0389](https://github.com/OpenIndiana/oi-userland/commit/f5a0389f26a474613a0ea42990179aaff714117c))
- Rebuild for Python 3.14 ([8210516](https://github.com/OpenIndiana/oi-userland/commit/82105167a88faf9fe140c1b3a2ba160ced4923f0))

### Python/dogpile.cache

- Update to 1.4.1 ([c2eb25c](https://github.com/OpenIndiana/oi-userland/commit/c2eb25c40e28cd8eb5785d36ae1af82770c955f7))

### Python/dom-toml

- Update to 2.1.0 ([e771b2c](https://github.com/OpenIndiana/oi-userland/commit/e771b2cf398fb1dc96a74a6e9e472e1967942078))

### Python/dunamai

- Update to 1.25.0 ([4f84595](https://github.com/OpenIndiana/oi-userland/commit/4f845957ed623f17c110662be9d65b6560633982))

### Python/editables

- Rebuild for Python 3.14 ([bf897ab](https://github.com/OpenIndiana/oi-userland/commit/bf897abf7aec6deb651f905cf79062d740825a72))

### Python/elasticsearch

- Update to 9.0.2 ([08f6f2e](https://github.com/OpenIndiana/oi-userland/commit/08f6f2eb70ed240d05c9663d4cfb6ae57e9a1a22))

### Python/elementpath

- Update to 5.0.2 ([c2d4c3e](https://github.com/OpenIndiana/oi-userland/commit/c2d4c3e52a9058abe941d5c3a649fc2d5e3ec0db))
- Update to 5.0.3 ([a0041b3](https://github.com/OpenIndiana/oi-userland/commit/a0041b3f9c15da24207bdb250670c6d14c7bf5c6))
- Update to 5.0.4 ([85a86db](https://github.com/OpenIndiana/oi-userland/commit/85a86db4baa479cae7aa6b0a9e6fb406296f76bc))

### Python/email_validator

- Update to 2.3.0 ([b89022e](https://github.com/OpenIndiana/oi-userland/commit/b89022ea3a9eaf6914242de6b1f6865dae820d02))

### Python/exceptiongroup

- Rebuild for Python 3.14 ([9b602ec](https://github.com/OpenIndiana/oi-userland/commit/9b602ec6bb1f2df02493af97e7f8e0173b3d9895))
- Add test results for Python 3.14 ([8505038](https://github.com/OpenIndiana/oi-userland/commit/850503846e7a5c7c8505f49daa6be11809577987))

### Python/executing

- Update to 2.2.1 ([ec0234a](https://github.com/OpenIndiana/oi-userland/commit/ec0234aa3ffa9b344d6f1c06a72ab0e22115bb5b))

### Python/expandvars

- Update to 1.1.1 ([ec7f051](https://github.com/OpenIndiana/oi-userland/commit/ec7f0511fbf748382aab48367436bdd2455e669b))
- Update to 1.1.2 ([26678ab](https://github.com/OpenIndiana/oi-userland/commit/26678ab4a11fe558af83ff2f0b2cbd6858e56fe1))

### Python/fastjsonschema

- Update to 2.21.2 ([785d6d2](https://github.com/OpenIndiana/oi-userland/commit/785d6d2caac587b6c7e52d6b8c3651290e0e2eaf))
- Rebuild for Python 3.14 ([fed4065](https://github.com/OpenIndiana/oi-userland/commit/fed4065149e76558809e4e20296317f3656cd3d9))

### Python/filelock

- Rebuild for Python 3.14 ([0898475](https://github.com/OpenIndiana/oi-userland/commit/08984753df075157b1614cf664500ac03ce5e883))
- Update to 3.19.1 ([48047eb](https://github.com/OpenIndiana/oi-userland/commit/48047eb3c3a2a666e790b575b43dcd8755de1416))
- Update to 3.20.0 ([18c8777](https://github.com/OpenIndiana/oi-userland/commit/18c87770e6ad9ec6f2af26f9a722d7acdd39536a))

### Python/findpython

- Update to 0.7.0 ([4803559](https://github.com/OpenIndiana/oi-userland/commit/4803559ae86c9587bbe2220bf0cd49b3f5c6c37e))
- Rebuild for Python 3.14 ([3051df3](https://github.com/OpenIndiana/oi-userland/commit/3051df365dc7e6361f326049de749632d90a72d6))

### Python/first

- Rebuild for Python 3.14 ([8970591](https://github.com/OpenIndiana/oi-userland/commit/8970591ec527e472a060bb7efedde513fa1014ea))

### Python/fixtures

- Update to 4.2.6 ([2eef6dd](https://github.com/OpenIndiana/oi-userland/commit/2eef6dd360b2fed8b5e2e554756dc55132ec7a4e))
- Rebuild for Python 3.14 ([629a088](https://github.com/OpenIndiana/oi-userland/commit/629a088fd92108f00724ad2c299884564c5dc446))
- Fix streams extra ([7a9a16e](https://github.com/OpenIndiana/oi-userland/commit/7a9a16ee4acc68b3f94f05cbc6fd4682498620ba))

### Python/flake8

- Update to 7.3.0 ([e51b022](https://github.com/OpenIndiana/oi-userland/commit/e51b022f5da3e41eea0d1b49b7ee230f2baf6ce6)), Co-authored-by:Marcel Telka <marcel@il-bld.in.telka.sk>

### Python/flake8_typing_imports

- Update to 1.17.0 ([566b6b8](https://github.com/OpenIndiana/oi-userland/commit/566b6b891655479d36fbd14c089c73938103350d))

### Python/flamegraph

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([fea21ec](https://github.com/OpenIndiana/oi-userland/commit/fea21ecef64e6065154158e0dcba732adcb7a9a7))

### Python/flask

- Update to 3.1.2 ([bdc5d78](https://github.com/OpenIndiana/oi-userland/commit/bdc5d78c86789d043fb95d845acd5ccf2b06698d))

### Python/flit_core

- Rebuild for Python 3.14 ([b38f881](https://github.com/OpenIndiana/oi-userland/commit/b38f88125a1a75af01536a62e1d2f7a006a9a1d6))
- Add test results for Python 3.14 ([3f56f5f](https://github.com/OpenIndiana/oi-userland/commit/3f56f5ffee0cd4688e5d2cb81558b3772140e95f))

### Python/flit_scm

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([b355d44](https://github.com/OpenIndiana/oi-userland/commit/b355d446ca253af8df50b9375eb3d7a37a7841a7))

### Python/freezegun

- Update to 1.5.3 ([39a8ba1](https://github.com/OpenIndiana/oi-userland/commit/39a8ba1d34538ba2599880ded4de83538333ad6b))
- Update to 1.5.4 ([0fd4fd6](https://github.com/OpenIndiana/oi-userland/commit/0fd4fd61ff39c9fdca5dd4c2fdd5ba47cacb6b7a))
- Update to 1.5.5 ([359ed70](https://github.com/OpenIndiana/oi-userland/commit/359ed70dbafb833373c2a59469e952217a483d60))

### Python/frozenlist

- Update to 1.7.0 ([6b12e85](https://github.com/OpenIndiana/oi-userland/commit/6b12e85e935c6ce81d35704e0b19fde6afc7f717))
- Update to 1.8.0 ([4c934bc](https://github.com/OpenIndiana/oi-userland/commit/4c934bc6f6fab2c069e74544970feb1469da5ec3))

### Python/funcy

- Rebuild for Python 3.14 ([40bddbc](https://github.com/OpenIndiana/oi-userland/commit/40bddbc4be94336f4eb9707f348b3b1de99578f2))

### Python/gi-docgen

- Update to 2025.4 ([e680f55](https://github.com/OpenIndiana/oi-userland/commit/e680f557dbdffbc2506b051ed91437df939e5819))

### Python/gitdb

- Rebuild for Python 3.14 ([300ad33](https://github.com/OpenIndiana/oi-userland/commit/300ad33bc7e2be4627751b8315f4462310f30283))

### Python/gprof2dot

- Rebuild for Python 3.14 ([2dd7e0b](https://github.com/OpenIndiana/oi-userland/commit/2dd7e0b29628ad4b171452bee7654cf1d9e7d6d9))

### Python/graphviz

- Update to 0.21 ([c38be83](https://github.com/OpenIndiana/oi-userland/commit/c38be8390409b9a86c8558cc5f40113e4a46a000))

### Python/greenlet

- Update to 3.2.3 ([8a2559c](https://github.com/OpenIndiana/oi-userland/commit/8a2559cc22191cf44665235ce7783560c63b05be))
- Update to 3.2.4 ([270785f](https://github.com/OpenIndiana/oi-userland/commit/270785fbad467fd4a6a3d4bb20271bdb9b55fcfa))

### Python/h2

- Update to 4.3.0 ([6383c38](https://github.com/OpenIndiana/oi-userland/commit/6383c3815bc3f260cf5fff447ae6e7dbb992fa40))

### Python/hatch_fancy_pypi_readme

- Rebuild for Python 3.14 ([30eeb5a](https://github.com/OpenIndiana/oi-userland/commit/30eeb5a985f2eefbe93b0dd6a81d20def2fc8729))

### Python/hatch_nodejs_version

- Update to 0.4.0 ([a38a6d7](https://github.com/OpenIndiana/oi-userland/commit/a38a6d7ad5eb9e1578383c026b18ea6378a6365e))
- Rebuild for Python 3.14 ([6d122d9](https://github.com/OpenIndiana/oi-userland/commit/6d122d91ba32b85df232b5bad1fc51736737a1a9))

### Python/hatch_vcs

- Rebuild for Python 3.14 ([8647c48](https://github.com/OpenIndiana/oi-userland/commit/8647c48b76ab779dc6d5d94ff6db8dbf4cb09d06))

### Python/hatchling

- Rebuild for Python 3.14 ([e22ed3c](https://github.com/OpenIndiana/oi-userland/commit/e22ed3ca15575e5bf59e58df8110a813607806ec))

### Python/housekeeping

- Rebuild for Python 3.14 ([ebdbbef](https://github.com/OpenIndiana/oi-userland/commit/ebdbbef19ae9a6df3ca06276e13fce235dc4dab4))

### Python/httplib2

- Update to 0.30.0 ([a113cee](https://github.com/OpenIndiana/oi-userland/commit/a113ceeb4f3da6b7f040404081be4e27a0674754))
- Update to 0.30.2 ([f193601](https://github.com/OpenIndiana/oi-userland/commit/f193601be7a5e7a4d0f97aac5daea00e62749077))

### Python/humanize

- Update to 4.13.0 ([ba9c25b](https://github.com/OpenIndiana/oi-userland/commit/ba9c25bc9336c81957e330e0f561d99987d54a33))

### Python/hypothesis

- Update to 6.135.4 ([ebdf312](https://github.com/OpenIndiana/oi-userland/commit/ebdf312b0e839fdd1317259f793f5677d8bf1de5))
- Update to 6.135.7 ([68b6330](https://github.com/OpenIndiana/oi-userland/commit/68b6330a1e01dcb2bc3c77bbe6d258d1fa87baec))
- Update to 6.135.10 ([877567e](https://github.com/OpenIndiana/oi-userland/commit/877567eb07b07a401d51ac0970108603ea00d7d5))
- Update to 6.135.11 ([fdcb3ff](https://github.com/OpenIndiana/oi-userland/commit/fdcb3ffb7ffcf4e691b36cba217b6e27e14b56e3))
- Update to 6.135.12 ([32bfb4a](https://github.com/OpenIndiana/oi-userland/commit/32bfb4ae39ba63cae4b7b926a70e8dac89ee4357))
- Update to 6.135.14 ([6f2e9a4](https://github.com/OpenIndiana/oi-userland/commit/6f2e9a42f011a6708a06c8e35a0cae8606b8af8a))
- Update to 6.135.16 ([6251489](https://github.com/OpenIndiana/oi-userland/commit/625148994df89b41627ebf26d0cf45f214cc5e26))
- Update to 6.135.17 ([bbb2fc1](https://github.com/OpenIndiana/oi-userland/commit/bbb2fc1fdf836f9cedd5a8bc584d7fb55af492a1))
- Update to 6.135.20 ([0292b94](https://github.com/OpenIndiana/oi-userland/commit/0292b945f0c3b0c7b961db0ce3ee7e38b1efcec0))
- Update to 6.135.24 ([3160c7c](https://github.com/OpenIndiana/oi-userland/commit/3160c7c1a041a1484a0a91c622d652d93124d1f2))
- Update to 6.135.26 ([a7c4432](https://github.com/OpenIndiana/oi-userland/commit/a7c4432d8d3bb91706b8ff23743441eca583053b))
- Update to 6.135.29 ([836b032](https://github.com/OpenIndiana/oi-userland/commit/836b03257c681dbd62eeae379bd16745bed486f9))
- Update to 6.135.32 ([cf1d6cc](https://github.com/OpenIndiana/oi-userland/commit/cf1d6ccdc123d19fb4dbf6f458e27625c5d4b79a))
- Update to 6.136.0 ([1b23513](https://github.com/OpenIndiana/oi-userland/commit/1b23513cfe7e0eb105761c4c01f41b93c5313899))
- Update to 6.136.1 ([e7010ab](https://github.com/OpenIndiana/oi-userland/commit/e7010abce61ff549aba58730949804fe59d81ea6))
- Update to 6.136.2 ([d2688a2](https://github.com/OpenIndiana/oi-userland/commit/d2688a2fffef0907e36d1640678dc4b71f825aa0))
- Update to 6.136.4 ([01c353c](https://github.com/OpenIndiana/oi-userland/commit/01c353c27e67a61e4351246a2597031bc9970a02))
- Update to 6.136.5 ([c60ffcf](https://github.com/OpenIndiana/oi-userland/commit/c60ffcf5327f9b04fc3184cb164d3adf4ecd382b))
- Update to 6.136.6 ([e0d18b6](https://github.com/OpenIndiana/oi-userland/commit/e0d18b629826df34269f93a1c24931ea7400b45d))
- Update to 6.136.7 ([1a91602](https://github.com/OpenIndiana/oi-userland/commit/1a91602445ef02824725edb2d8c39638fc2512b7))
- Update to 6.137.1 ([f803278](https://github.com/OpenIndiana/oi-userland/commit/f8032788b76e45c295f2c367aae4462477f6e273))
- Update to 6.137.2 ([c8d9087](https://github.com/OpenIndiana/oi-userland/commit/c8d90878d889b0a8a73f0455aa5d14879557e645))
- Update to 6.138.0 ([f848173](https://github.com/OpenIndiana/oi-userland/commit/f848173207dc26eda0857209c222861918bdbdbc))
- Update to 6.138.2 ([a28c7d8](https://github.com/OpenIndiana/oi-userland/commit/a28c7d86ae5eec8527771fd0da34e4fb97bf4914))
- Update to 6.138.3 ([f405303](https://github.com/OpenIndiana/oi-userland/commit/f40530355743b35468cd0ad0269407ff16a9085a))
- Update to 6.138.6 ([0cc5e0d](https://github.com/OpenIndiana/oi-userland/commit/0cc5e0d6f7ed9755b638c55085e68b39ba9520f8))
- Update to 6.138.7 ([f355fcf](https://github.com/OpenIndiana/oi-userland/commit/f355fcf643fd4686d9060642735e25da389b46ee))
- Update to 6.138.8 ([2ddac04](https://github.com/OpenIndiana/oi-userland/commit/2ddac04733c890e88db91c36904babcea28f7acd))
- Update to 6.138.11 ([cbdaf0c](https://github.com/OpenIndiana/oi-userland/commit/cbdaf0cdc2e317c66e7d657dc7fb2a885c8b2180))
- Update to 6.138.13 ([e27ee9d](https://github.com/OpenIndiana/oi-userland/commit/e27ee9ddde2d2b3482db443288abbf9efc816c3b))
- Update to 6.138.14 ([d4a4b24](https://github.com/OpenIndiana/oi-userland/commit/d4a4b2440425331df342936309cbca4366bc7eda))
- Update to 6.138.15 ([b9ec003](https://github.com/OpenIndiana/oi-userland/commit/b9ec0034d34f3271b73cb323525cb7114e449648))
- Update to 6.138.16 ([3ccbf68](https://github.com/OpenIndiana/oi-userland/commit/3ccbf6896baf320c9968d7c7ba81567ef4cd151c))
- Update to 6.138.17 ([26a4527](https://github.com/OpenIndiana/oi-userland/commit/26a4527699ae6053a759685478223501613e12de))
- Update to 6.139.2 ([22c81b5](https://github.com/OpenIndiana/oi-userland/commit/22c81b53765852547a6ef84064504b9b6b874e66))
- Update to 6.139.3 ([1c37253](https://github.com/OpenIndiana/oi-userland/commit/1c37253c01da224869cfd3576d1ae0dfc4fc5d4f))
- Update to 6.140.2 ([5b1bcaf](https://github.com/OpenIndiana/oi-userland/commit/5b1bcafffaa083ad1cf2706953fc0ffff85c2003))
- Update to 6.140.3 ([0e8cc99](https://github.com/OpenIndiana/oi-userland/commit/0e8cc99211eff7d93a3f84b890d974386d62d50d))

### Python/icecream

- Update to 2.1.5 ([36e0b93](https://github.com/OpenIndiana/oi-userland/commit/36e0b93be455f72dc76fabf5d4b09078873fb6fc))
- Update to 2.1.6 ([92719bd](https://github.com/OpenIndiana/oi-userland/commit/92719bd02c77cd9c1730dac4869fc1981423cb84))
- Update to 2.1.7 ([d1108ca](https://github.com/OpenIndiana/oi-userland/commit/d1108ca3a3c33b197d283695fb5c9773aa583143))
- Update to 2.1.8 ([d3c7303](https://github.com/OpenIndiana/oi-userland/commit/d3c73034e709973eb78b221c9922b80f9ea85d89))

### Python/identify

- Update to 2.6.13 ([24b0ca4](https://github.com/OpenIndiana/oi-userland/commit/24b0ca47c7ebaac77988c58c38b97440b946a39a))
- Update to 2.6.14 ([9508d40](https://github.com/OpenIndiana/oi-userland/commit/9508d40720db4fc6e6792525d0d02861beb5b5c1))
- Update to 2.6.15 ([817b2cf](https://github.com/OpenIndiana/oi-userland/commit/817b2cf1d20aa60c1414c35fd56337315a7bac94))

### Python/idna

- Update to 3.11; rebuild for Python 3.14 ([7f8d673](https://github.com/OpenIndiana/oi-userland/commit/7f8d67352ca1fad8d7c7d150c044118db2b2cb1a))

### Python/importlib_metadata

- Rebuild for Python 3.14 ([d5d63e1](https://github.com/OpenIndiana/oi-userland/commit/d5d63e13fdbeae8ca343777fbefe18ffeeddbf79))
- Drop test dependency on flufl.flake8 ([efa1a60](https://github.com/OpenIndiana/oi-userland/commit/efa1a6073e8a7203b1483ee60c988cb8b035930e))

### Python/iniconfig

- Rebuild for Python 3.14 ([58a64f7](https://github.com/OpenIndiana/oi-userland/commit/58a64f7d5b8606bf9edb04c7e78d06a382ad6bc9))
- Update to 2.3.0 ([3df76bf](https://github.com/OpenIndiana/oi-userland/commit/3df76bf7996b0df9fe69eae43dc236dff4b87707))

### Python/inline-snapshot

- Update to 0.24.0 ([3302761](https://github.com/OpenIndiana/oi-userland/commit/33027616917efd76ed35c81caa15f7e64de4199f))
- Update to 0.25.2 ([9e525e9](https://github.com/OpenIndiana/oi-userland/commit/9e525e9d897a8ad95d8e7d265916c06cbaf36dca))
- Update to 0.25.3 ([b4bf5b6](https://github.com/OpenIndiana/oi-userland/commit/b4bf5b63c68a6fe79d6172a753081db379161fb3))
- Update to 0.26.0 ([3339df1](https://github.com/OpenIndiana/oi-userland/commit/3339df1a2fae4f86647493c2b374c2763db70ae0))
- Update to 0.27.0 ([fcd1c51](https://github.com/OpenIndiana/oi-userland/commit/fcd1c51d277a18809ce615329919b58276a8df8f))
- Update to 0.27.1 ([be00be0](https://github.com/OpenIndiana/oi-userland/commit/be00be0dba36de105fa1820a6a1688b3045d82cb))
- Update to 0.27.2 ([7eee0c1](https://github.com/OpenIndiana/oi-userland/commit/7eee0c1f177ea7252d809b1a9b1ebe667677c523))
- Update to 0.28.0 ([30f00b4](https://github.com/OpenIndiana/oi-userland/commit/30f00b49b5b8296eb2235a1e8f6295ea285d7240))
- Update to 0.29.0 ([c1a10cc](https://github.com/OpenIndiana/oi-userland/commit/c1a10cc3957b85df459ff416ae00b62ad89cc55a))
- Update to 0.29.1 ([0025501](https://github.com/OpenIndiana/oi-userland/commit/0025501445c50c9d1f2c69aeddbfe1b66dacaed3))
- Update to 0.29.2 ([ebbbadb](https://github.com/OpenIndiana/oi-userland/commit/ebbbadb1e1318cfb3346f71a3a87b9c6d2ebf86f))
- Update to 0.29.3 ([b845b60](https://github.com/OpenIndiana/oi-userland/commit/b845b6064c6b9bc7f31b7d7a849eb3d9a43e3e93))

### Python/installer

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([195a23a](https://github.com/OpenIndiana/oi-userland/commit/195a23a8b5186797a526ff2c27865509b1369d6b))

### Python/invocations

- Update to 4.0.2 ([b502876](https://github.com/OpenIndiana/oi-userland/commit/b5028766dcede05fae8d7c757f8d8ef193678a83))

### Python/jaraco.collections

- Update to 5.2.1 ([87abc34](https://github.com/OpenIndiana/oi-userland/commit/87abc347c1902833db7f47bec2dc67ae1dff53e9))

### Python/jaraco.functools

- Update to 4.2.1 ([ce00a62](https://github.com/OpenIndiana/oi-userland/commit/ce00a62f81027cf620553cb7e626125c0a053cc4))
- Update to 4.3.0 ([b46f765](https://github.com/OpenIndiana/oi-userland/commit/b46f765a0590d474c184062862178e311c725fc4))
- Rebuild for Python 3.14 ([0434247](https://github.com/OpenIndiana/oi-userland/commit/0434247d96c149d11c87d100ab3d64ce54153759))

### Python/jaraco.logging

- Update to 3.4.0 ([fa91ea9](https://github.com/OpenIndiana/oi-userland/commit/fa91ea902e4901d5a3386369af4745b477c45c02))

### Python/jmespath

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([cb0dbca](https://github.com/OpenIndiana/oi-userland/commit/cb0dbca543451c5b0766954797b3f314edc041e7))

### Python/jsonpointer

- Rebuild for Python 3.14 ([0bbfd1c](https://github.com/OpenIndiana/oi-userland/commit/0bbfd1cf486b107c08ad77c0d5f7eeea7562c96e))

### Python/jsonschema

- Update to 4.25.1 ([6575338](https://github.com/OpenIndiana/oi-userland/commit/6575338d171cd3c090b5f13c3d359c2b4432bd9f))

### Python/jsonschema_specifications

- Update to 2025.9.1 ([cfe1ae0](https://github.com/OpenIndiana/oi-userland/commit/cfe1ae092ca920ca5c47300a3360d2d858bd55d0))

### Python/kgb

- Rebuild for Python 3.14 ([14cbd9f](https://github.com/OpenIndiana/oi-userland/commit/14cbd9fe2fe22e72b1dfb43d66931fcfafa0d318))

### Python/lazy-object-proxy

- Update to 1.12.0 ([aa09db5](https://github.com/OpenIndiana/oi-userland/commit/aa09db545f9b334cad835bbc2447750136aab554))

### Python/libcst

- Update to 1.8.1 ([667d4d5](https://github.com/OpenIndiana/oi-userland/commit/667d4d5df453c6761a77550fc0250c48ea48e98e))
- Update to 1.8.2 ([1cfa08a](https://github.com/OpenIndiana/oi-userland/commit/1cfa08a41e0479ba173f3d59aee16b3356aba383))
- Update to 1.8.4 ([f1fb005](https://github.com/OpenIndiana/oi-userland/commit/f1fb005f96718fc0af3850302a6a6b4691a9536d))
- Update to 1.8.5 ([39a03d9](https://github.com/OpenIndiana/oi-userland/commit/39a03d926039920422bb1d1c8f5cb67cffd182bb))

### Python/looseversion

- Rebuild for Python 3.14 ([51f9b6e](https://github.com/OpenIndiana/oi-userland/commit/51f9b6e3084e083d2066f588d902793e966916cf))

### Python/lxml

- Update to 6.0.1 ([65bfeff](https://github.com/OpenIndiana/oi-userland/commit/65bfeff11d9072c5f75bff7b44cc9a5bd9314865))
- Update to 6.0.2 ([a3a074a](https://github.com/OpenIndiana/oi-userland/commit/a3a074a2f616e529c712cddc8e4283c54f5c1493))

### Python/markdown2

- Update to 2.5.4 ([2c94cdc](https://github.com/OpenIndiana/oi-userland/commit/2c94cdc4793d8dc1dc37040a29b96f83f2b8556c))

### Python/marshmallow

- Update to 4.0.1 ([17c2eb8](https://github.com/OpenIndiana/oi-userland/commit/17c2eb8cb27d144ab06e899514aee3d97d1376e1))
- Rebuild for Python 3.14 ([865b2bc](https://github.com/OpenIndiana/oi-userland/commit/865b2bce7f303dc0eaa730e2e7c875793bb5b453))

### Python/maturin

- Update to 1.8.7 ([4c5b7df](https://github.com/OpenIndiana/oi-userland/commit/4c5b7df0effd79f8e9e1cf4fc2ce8b4e9793aa44))
- Update to 1.9.0 ([646fa26](https://github.com/OpenIndiana/oi-userland/commit/646fa26e89009ebc5d0a9797753243c01ead3073))
- Update to 1.9.1 ([4e15a5d](https://github.com/OpenIndiana/oi-userland/commit/4e15a5dbf1f60b72ae886ed257d3f6e0257b8dc7))
- Update to 1.9.2 ([c300452](https://github.com/OpenIndiana/oi-userland/commit/c3004523d5f04598434a854ea35c7fc88329964c))
- Update to 1.9.3 ([4f0e718](https://github.com/OpenIndiana/oi-userland/commit/4f0e718ef2551948a07cf1c2b1349163b3ca57d2))
- Update to 1.9.4 ([c4cbaf7](https://github.com/OpenIndiana/oi-userland/commit/c4cbaf7dc631b6dc0e0317121d431e99a37e6827))
- Update to 1.9.5 ([7d398cd](https://github.com/OpenIndiana/oi-userland/commit/7d398cd76885d018826858de576608f62643a9bf))
- Update to 1.9.6 ([159c7aa](https://github.com/OpenIndiana/oi-userland/commit/159c7aa2213d1924f176ebda289043b1771c36a3))

### Python/mistune

- Update to 3.1.4 ([e0a8908](https://github.com/OpenIndiana/oi-userland/commit/e0a8908a890a42c0249d3b9cf0c4da2a7858105a))
- Rebuild for Python 3.14 ([5e25a4a](https://github.com/OpenIndiana/oi-userland/commit/5e25a4a69fd010dc182f2ceace586593fcc7664a))

### Python/mock

- Rebuild for Python 3.14 ([9a8433c](https://github.com/OpenIndiana/oi-userland/commit/9a8433c6c013b399b460292b5d686c9e158f0095))

### Python/more-itertools

- Update to 10.8.0 ([5889361](https://github.com/OpenIndiana/oi-userland/commit/5889361940c20d3b83db3a8845cdeca9afaa9120))
- Rebuild for Python 3.14 ([f8839aa](https://github.com/OpenIndiana/oi-userland/commit/f8839aa17f04be3e42fc318fa25c6f661b3567bd))

### Python/msgpack

- Update to 1.1.1 ([50b0832](https://github.com/OpenIndiana/oi-userland/commit/50b0832fae2a87ae879f6ee0f06cd93b410d2e38))
- Update to 1.1.2 ([7578496](https://github.com/OpenIndiana/oi-userland/commit/7578496cc46567b25a48cc18ddc1528742075e6c))
- Rebuild for Python 3.14 ([adec3c7](https://github.com/OpenIndiana/oi-userland/commit/adec3c748aca00db0ad7a00a6817afdec76953e2))

### Python/multidict

- Update to 6.5.0 ([10156b8](https://github.com/OpenIndiana/oi-userland/commit/10156b8748e1c49fa70eae777730678889aa06d4))
- Update to 6.6.0 ([d4ad209](https://github.com/OpenIndiana/oi-userland/commit/d4ad209c59f12f9f855428e4f8fe2f8e76fc1605))
- Update to 6.6.2 ([f75e7ba](https://github.com/OpenIndiana/oi-userland/commit/f75e7bad51a0ec744406d87207832e0182eb75f0))
- Update to 6.6.3 ([21ed3ee](https://github.com/OpenIndiana/oi-userland/commit/21ed3eeccf7b7ca9021423091eb35a492808c53a))
- Update to 6.6.4 ([8506ff2](https://github.com/OpenIndiana/oi-userland/commit/8506ff2ff872c9b2e35b7bebe226f077f6735e50))
- Update to 6.7.0 ([97bc2c6](https://github.com/OpenIndiana/oi-userland/commit/97bc2c6dbb2544a7cc2250618289ccca42cce1bb))

### Python/mypy

- Update to 1.16.1 ([3d22fde](https://github.com/OpenIndiana/oi-userland/commit/3d22fdee3aba020c33162cae9761b1dcb9066530))
- Update to 1.17.0 ([37b7f46](https://github.com/OpenIndiana/oi-userland/commit/37b7f46ba09c1d8023cfb59cf14817855355cae4))
- Update to 1.17.1 ([de67a3b](https://github.com/OpenIndiana/oi-userland/commit/de67a3b872c2557a77bacf03b6898f74601676ad))
- Update to 1.18.1 ([c917473](https://github.com/OpenIndiana/oi-userland/commit/c917473ca762429f48246b8b32e8fbe3ef235d7c))
- Update to 1.18.2 ([fbc5371](https://github.com/OpenIndiana/oi-userland/commit/fbc53715dd3ea01006935384fa90e053687d5dc6))

### Python/mysqlclient

- Rebuild for Python 3.14 ([d9e58c2](https://github.com/OpenIndiana/oi-userland/commit/d9e58c27ad84a24a48ca8ae8142be09eb042e2a5))

### Python/nh3

- Update to 0.2.22 ([c523a3b](https://github.com/OpenIndiana/oi-userland/commit/c523a3b6d2406b4fa037aafdecf7fbcbacaaa6b7))
- Update to 0.3.0 ([56a4e60](https://github.com/OpenIndiana/oi-userland/commit/56a4e60be436226e458f978e63e8dda4bd193fa6))
- Update to 0.3.1 ([cd45543](https://github.com/OpenIndiana/oi-userland/commit/cd4554337068e101c7ecdb25513d6ae09aa55d31))

### Python/olefile

- Rebuild for Python 3.14 ([af12a26](https://github.com/OpenIndiana/oi-userland/commit/af12a269806a51c412fe75408093f9e590755390))

### Python/packaging

- Rebuild for Python 3.14 ([1f810b1](https://github.com/OpenIndiana/oi-userland/commit/1f810b14003c03633abd3612ae5106b391ab193e))
- Add test results for Python 3.14 ([cafd0e3](https://github.com/OpenIndiana/oi-userland/commit/cafd0e354ca98233615249563e70b17ce2c3a2e4))

### Python/parso

- Update to 0.8.5 ([5db76e5](https://github.com/OpenIndiana/oi-userland/commit/5db76e5024081bd71890e60579b4535bdf8df74e))

### Python/pathspec

- Rebuild for Python 3.14 ([027a0af](https://github.com/OpenIndiana/oi-userland/commit/027a0af63e03c069691b7fa672ce512ae4883194))
- Add test results for Python 3.14 ([bcd36af](https://github.com/OpenIndiana/oi-userland/commit/bcd36afde16e0644da23c1d6a833bf4ef7eae500))

### Python/pbr

- Update to 7.0.0 ([50718e1](https://github.com/OpenIndiana/oi-userland/commit/50718e170fac032dedb681e2ef4c4e559dbdf10e))
- Update to 7.0.1 ([968ecae](https://github.com/OpenIndiana/oi-userland/commit/968ecaef8fa702d4827feb85cc1ee81654109791))

### Python/pdm_backend

- Update to 2.4.5 ([c8c5994](https://github.com/OpenIndiana/oi-userland/commit/c8c59947130df7dabdf04e0730880ae34e55c5f8))
- Rebuild for Python 3.14 ([6277dfd](https://github.com/OpenIndiana/oi-userland/commit/6277dfdda62cbfd3d0b6d8064afcaaa3a55dc5ef))

### Python/persistent

- Update to 6.2 ([45b052c](https://github.com/OpenIndiana/oi-userland/commit/45b052ca215dfdec208e91dd5d105eed4b061f48))
- Update to 6.3 ([bcbaad1](https://github.com/OpenIndiana/oi-userland/commit/bcbaad180d2324a2b9b5f214675f1d3c286d8387))

### Python/pillow

- Update to 11.3.0 ([de6d9f5](https://github.com/OpenIndiana/oi-userland/commit/de6d9f58d68b85d6878fb4ba364adc29a5a7b8ab))

### Python/pip

- Update to 25.2 ([49083ba](https://github.com/OpenIndiana/oi-userland/commit/49083ba28bcefaa69fda5d2a291501368ac58b45))

### Python/pipenv

- Update to 2025.0.4 ([e686131](https://github.com/OpenIndiana/oi-userland/commit/e6861316b12343f9d9acde4717ce288d5cb5a23e))

### Python/platformdirs

- Update to 4.4.0 ([1f189f8](https://github.com/OpenIndiana/oi-userland/commit/1f189f8e38f35db0599dfea188139da9d8987e49))
- Update to 4.5.0 ([e06954c](https://github.com/OpenIndiana/oi-userland/commit/e06954cf1008749ff999c30ab9c0dde232c47a1b))
- Rebuild for Python 3.14 ([543cb31](https://github.com/OpenIndiana/oi-userland/commit/543cb314f0da6e4b73d84009d791822c0e9bfb15))

### Python/pluggy

- Rebuild for Python 3.14 ([b30b82b](https://github.com/OpenIndiana/oi-userland/commit/b30b82b6c844f1f216266095367df5707418bc16))

### Python/poetry_core

- Update to 2.2.0 ([3c36e2b](https://github.com/OpenIndiana/oi-userland/commit/3c36e2b95c87df4ccc5a5adf19c87502430fb040))
- Update to 2.2.1 ([f28c6a6](https://github.com/OpenIndiana/oi-userland/commit/f28c6a6821fb40ac9b21edf8171d7a5490783f46))

### Python/poetry_dynamic_versioning

- Update to 1.9.1 ([2bb9f86](https://github.com/OpenIndiana/oi-userland/commit/2bb9f86844cb9190584131579da7c6cc71365289))

### Python/pretend

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([497d80b](https://github.com/OpenIndiana/oi-userland/commit/497d80b70272ffd65af9bef015c8fbce6321ef52))

### Python/prompt_toolkit

- Update to 3.0.52 ([892d41b](https://github.com/OpenIndiana/oi-userland/commit/892d41befc378d122c86ef9fdf555f42f97d639f))

### Python/propcache

- Update to 0.3.2 ([9c18fc9](https://github.com/OpenIndiana/oi-userland/commit/9c18fc91fb64b42df26aae7d87de7ae75a6cbcb0))
- Update to 0.4.0 ([0cdf0d4](https://github.com/OpenIndiana/oi-userland/commit/0cdf0d4546736137dffb410251f81ad29e42c94c))
- Update to 0.4.1 ([d966bba](https://github.com/OpenIndiana/oi-userland/commit/d966bbaca9624eefb84ba4312bef43ce4dfab98b))

### Python/psutil

- Update to 7.0.0 ([3220c22](https://github.com/OpenIndiana/oi-userland/commit/3220c220a387b49436b9a3dc00170f97109f3cdb))

### Python/psycopg2

- Update to 2.9.11 ([049a999](https://github.com/OpenIndiana/oi-userland/commit/049a99965a252e56272cd5bac78275a56a03e4a5))
- Rebuild for Python 3.14 ([fcf8e82](https://github.com/OpenIndiana/oi-userland/commit/fcf8e82cfa8c16373e7ef72768dc1983738c6f94))

### Python/ptyprocess

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([9250aa4](https://github.com/OpenIndiana/oi-userland/commit/9250aa479fd09ce694ae556ec07541b1e3ddc128))

### Python/pure_eval

- Rebuild for Python 3.14 ([4721bd0](https://github.com/OpenIndiana/oi-userland/commit/4721bd0e2da244561077e7a81adffda80bc8b3af))

### Python/puremagic

- Update to 1.30 ([9fee4d8](https://github.com/OpenIndiana/oi-userland/commit/9fee4d82259acdcec646c3ef0b7a0c2f48824608))
- Rebuild for Python 3.14 ([ed0b4c3](https://github.com/OpenIndiana/oi-userland/commit/ed0b4c32c790cb249ba6d9caac5d8484db615ef7))

### Python/pyOpenSSL

- Update to 25.2.0 ([6a52e10](https://github.com/OpenIndiana/oi-userland/commit/6a52e100c0a3a5f3e27143df2f949729aff464fa))
- Update to 25.3.0 ([90b0613](https://github.com/OpenIndiana/oi-userland/commit/90b06130d86c7fe6cfb527d5a2f4a26e4c12ebf1))

### Python/pyasn1

- Rebuild for Python 3.14 ([9ae5157](https://github.com/OpenIndiana/oi-userland/commit/9ae51579a1a960f4eaa060443edb8b4733267ae4))

### Python/pyasn1_modules

- Rebuild for Python 3.14 ([4eae449](https://github.com/OpenIndiana/oi-userland/commit/4eae44975865f11c4315a49df49cff3d5fd0cb52))

### Python/pybind11

- Update to 3.0.0 ([775a357](https://github.com/OpenIndiana/oi-userland/commit/775a357706d87bde4a084aaa944aeab281d3591c))
- Update to 3.0.1 ([d0b8381](https://github.com/OpenIndiana/oi-userland/commit/d0b8381e2106457f09fa69cf3e435d7a85e6963d))

### Python/pycodestyle

- Update to 2.14.0 ([ddde51b](https://github.com/OpenIndiana/oi-userland/commit/ddde51b8434771ea67932d5779f31891ea784bc4))

### Python/pycparser

- Update to 2.23 ([71be092](https://github.com/OpenIndiana/oi-userland/commit/71be09270a3db4436296ac060172a7d496c55265))
- Rebuild for Python 3.14 ([48ae549](https://github.com/OpenIndiana/oi-userland/commit/48ae5492be2b0041d3cecbc9b4a7fe54acfec704))

### Python/pycryptodome

- Rebuild for Python 3.14 ([84fe6ee](https://github.com/OpenIndiana/oi-userland/commit/84fe6eef869f7c8c4fba116e281e868bcbbb61ce))

### Python/pycryptodome-test-vectors

- Rebuild for Python 3.14 ([948db03](https://github.com/OpenIndiana/oi-userland/commit/948db035562a9167d37f4a0eab9127df32a0f501))

### Python/pycryptodomex

- Rebuild for Python 3.14 ([fe93081](https://github.com/OpenIndiana/oi-userland/commit/fe93081f1d161b8c9b0077fcf34ac7b41cbd1b79))

### Python/pycups

- Rebuild for Python 3.14 ([d240d0c](https://github.com/OpenIndiana/oi-userland/commit/d240d0cf353ada342472d29841c5516afaa12fb6))

### Python/pycurl

- Update to 7.45.7 ([768d321](https://github.com/OpenIndiana/oi-userland/commit/768d3216853c428bec725e750c23f23623e577e2))

### Python/pydiffx

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([aa4d192](https://github.com/OpenIndiana/oi-userland/commit/aa4d1922128fc0aaad37b731a9f77eda24e304a8))

### Python/pyfakefs

- Update to 5.9.1 ([451dc0e](https://github.com/OpenIndiana/oi-userland/commit/451dc0e1eb39b3347e67f6883f17b305dc6f15bc))
- Update to 5.9.2 ([7c6468b](https://github.com/OpenIndiana/oi-userland/commit/7c6468ba83927bd29344838ef0e6ceb3c85be569))

### Python/pyflakes

- Update to 3.4.0 ([51f1578](https://github.com/OpenIndiana/oi-userland/commit/51f157843c394e0ba473c576f6d3d90167920bf9))
- Rebuild for Python 3.14 ([2d0e796](https://github.com/OpenIndiana/oi-userland/commit/2d0e796ec988eb3628e2185a62a2039695c08ba2))

### Python/pyftpdlib

- Update to 2.1.0 ([022ed22](https://github.com/OpenIndiana/oi-userland/commit/022ed22dae4f33f6faf949445d61a30b79b8d1e0))

### Python/pygments

- Update to 2.19.2 ([1f071ba](https://github.com/OpenIndiana/oi-userland/commit/1f071bacd3c773dba389c25faba89074172b7a42))
- Rebuild for Python 3.14 ([dd27a3b](https://github.com/OpenIndiana/oi-userland/commit/dd27a3b5609b3eb69485e1e698b417923888e380))

### Python/pylint

- Update to 3.3.8 ([1b339e2](https://github.com/OpenIndiana/oi-userland/commit/1b339e290ccc341bb5ce59f8b14e1b598badeae9))
- Update to 3.3.9 ([c5da8a9](https://github.com/OpenIndiana/oi-userland/commit/c5da8a97bd790fd8a4dfaf810687a08a327b1377))

### Python/pymongo

- Update to 4.13.1 ([8bb5543](https://github.com/OpenIndiana/oi-userland/commit/8bb5543c2f956e9e4e7316ef8e855233e9d40d9e))
- Update to 4.13.2 ([1593e9c](https://github.com/OpenIndiana/oi-userland/commit/1593e9cd4a528da1ae2f2c2c2635e8aafc98422a))
- Update to 4.14.0 ([aa28b42](https://github.com/OpenIndiana/oi-userland/commit/aa28b42801c7fd4d451e38a4a7664334c12ac862))
- Update to 4.14.1 ([0b885fb](https://github.com/OpenIndiana/oi-userland/commit/0b885fbbfd0bebc46c81a4d448a660f0c500c71c))
- Update to 4.15.0 ([3bfe745](https://github.com/OpenIndiana/oi-userland/commit/3bfe745e2e18623dcbcf787e1205f73a4c0007a5))
- Update to 4.15.1 ([a575c12](https://github.com/OpenIndiana/oi-userland/commit/a575c12439368c05a4a967d2322c91c5d770513f))
- Update to 4.15.2 ([5e67d1a](https://github.com/OpenIndiana/oi-userland/commit/5e67d1ad825a8053ce8c9a2ec54d90d52ba41c43))
- Update to 4.15.3 ([d505470](https://github.com/OpenIndiana/oi-userland/commit/d5054702451c56b8d3e595702649127b25b8bd74))

### Python/pyparsing

- Update to 3.2.4 ([deb27d0](https://github.com/OpenIndiana/oi-userland/commit/deb27d07f67b8f3b37db91d38dc73c3e04c0632d))
- Update to 3.2.5 ([4df88a1](https://github.com/OpenIndiana/oi-userland/commit/4df88a1fd1f713ea0ae839a9ec763945451e6139))

### Python/pyperclip

- Update to 1.10.0 ([74ec726](https://github.com/OpenIndiana/oi-userland/commit/74ec726dd4351afa70932a86e1c3ce865779ef11))
- Update to 1.11.0 ([d3196f1](https://github.com/OpenIndiana/oi-userland/commit/d3196f1ff3ced3f30d803f90979b94ceb1dc82dd))

### Python/pyproject-metadata

- Rebuild for Python 3.14 ([d698471](https://github.com/OpenIndiana/oi-userland/commit/d69847138f99751c19fcb4589463248124f53aa0))

### Python/pyproject_api

- Rebuild for Python 3.14 ([4776b10](https://github.com/OpenIndiana/oi-userland/commit/4776b10f9f913670a985d43a0517f1c4eaa33a7e))
- Update to 1.10.0 ([0bdf4d7](https://github.com/OpenIndiana/oi-userland/commit/0bdf4d7988d48b1e7973a08e31ad6eacab49f5df))

### Python/pyproject_fmt

- Update to 2.7.0 ([6fc6900](https://github.com/OpenIndiana/oi-userland/commit/6fc69007c7c8145817d7d34fb38555a6fe42ec28))

### Python/pyproject_hooks

- Rebuild for Python 3.14 ([f9cee3c](https://github.com/OpenIndiana/oi-userland/commit/f9cee3c03b805d548619f51fc211d4d62ff059b1))

### Python/pyproject_installer

- Rebuild for Python 3.14 ([942268a](https://github.com/OpenIndiana/oi-userland/commit/942268ad25f1dd231c8489de701ff414ac535554))

### Python/pytest

- Update to 8.4.2; rebuild for Python 3.14 ([c70a88c](https://github.com/OpenIndiana/oi-userland/commit/c70a88cf80446e56e71ca484ef4e0d1cbc258a7f))

### Python/pytest-cov

- Update to 6.2.1 ([b42a680](https://github.com/OpenIndiana/oi-userland/commit/b42a680b1344dde5f3fff88dca31f4ff600b8e3a))
- Update to 6.3.0 ([3a07835](https://github.com/OpenIndiana/oi-userland/commit/3a078357acd91d45b4fab1cbb66d6ab2a4da3e6d))

### Python/pytest-custom_exit_code

- Rebuild for Python 3.14 ([8743f9d](https://github.com/OpenIndiana/oi-userland/commit/8743f9de5a457c5989b8b3c39b7928857ce8bf3f))

### Python/pytest-datadir

- Update to 1.7.2 ([7d2294b](https://github.com/OpenIndiana/oi-userland/commit/7d2294bc5f8c51b7647cb63d1e7bb9d8ef409b34))
- Update to 1.8.0 ([b040c7f](https://github.com/OpenIndiana/oi-userland/commit/b040c7f4c275a027ca6c66760ac94d3ee5fef277))
- Rebuild for Python 3.14 ([579cf35](https://github.com/OpenIndiana/oi-userland/commit/579cf35da5194d5c79ed9387ecb6dba9b6ccbab5))

### Python/pytest-dependency

- Rebuild for Python 3.14 ([e4ab97b](https://github.com/OpenIndiana/oi-userland/commit/e4ab97b2f0761e5914e0ef5445f1160b8dfbaf75))

### Python/pytest-mock

- Update to 3.15.1 ([6ea217e](https://github.com/OpenIndiana/oi-userland/commit/6ea217e9d9105490af994fcad7016b2eccb0c0f5))

### Python/pytest-randomly

- Update to 4.0.1 ([57270c2](https://github.com/OpenIndiana/oi-userland/commit/57270c26009a8a3e3c9ccc398822995bf206082c))

### Python/pytest-regressions

- Update to 2.8.0 ([11de598](https://github.com/OpenIndiana/oi-userland/commit/11de59843e7c329f758f351b66b1ede9d499471d))
- Update to 2.8.1 ([904caf6](https://github.com/OpenIndiana/oi-userland/commit/904caf69f9740974efd94b38a01d339a40d9703c))
- Update to 2.8.2 ([a3f333a](https://github.com/OpenIndiana/oi-userland/commit/a3f333a7ae33cb7537762ceeb7017dcb9040ff55))
- Update to 2.8.3 ([4a3d27e](https://github.com/OpenIndiana/oi-userland/commit/4a3d27ec70c0607e7c157dcf3194b058e7625678))

### Python/pytest-rerunfailures

- Update to 16.0 ([4fd78e1](https://github.com/OpenIndiana/oi-userland/commit/4fd78e19ed37ef233e99fdbe77b6aa5071d9d3ee))
- Update to 16.0.1 ([dbcbd2f](https://github.com/OpenIndiana/oi-userland/commit/dbcbd2f4036dd9f2c297e163d62359f069ea059e))
- Update to 16.1 ([6053e60](https://github.com/OpenIndiana/oi-userland/commit/6053e602a6c9483dd7b1f81d5dc6b7e2d52812d1))

### Python/pytest-run-parallel

- Update to 0.5.0 ([4fcecbe](https://github.com/OpenIndiana/oi-userland/commit/4fcecbef8bfd5bf09a55edf5d069fef9ec4abe65))
- Update to 0.6.0 ([a9fd5f8](https://github.com/OpenIndiana/oi-userland/commit/a9fd5f8311f347d9acc6d09ddc93d47c853d4838))
- Update to 0.6.1 ([3804c9b](https://github.com/OpenIndiana/oi-userland/commit/3804c9bbf65a29fb4be35416b242d5a8e25bc5fc))
- Update to 0.7.0 ([8026d17](https://github.com/OpenIndiana/oi-userland/commit/8026d17dd85ac40614134e7bd157ca2c8bfdb907))

### Python/pytest-subtests

- Update to 0.14.2 ([da21696](https://github.com/OpenIndiana/oi-userland/commit/da216968511eee295b7e90019c0bfcdb605f59c1))

### Python/pytest-xdist

- Update to 3.8.0 ([5b91c9c](https://github.com/OpenIndiana/oi-userland/commit/5b91c9c45ee8de2f5688ea8a8646604396df9136))

### Python/pytest_check

- Update to 2.5.4 ([15f4f97](https://github.com/OpenIndiana/oi-userland/commit/15f4f97dfd5a098470fce31535fd4ca992439877))
- Update to 2.6.0 ([af1c0b5](https://github.com/OpenIndiana/oi-userland/commit/af1c0b5467e6d8019dc54836f72663b8cc4296bd))
- Rebuild for Python 3.14 ([3abfee0](https://github.com/OpenIndiana/oi-userland/commit/3abfee0cd3b6b88940bcbdde753ce3cc35ce2217))

### Python/python-dbusmock

- Update to 0.37.1 ([a008ca4](https://github.com/OpenIndiana/oi-userland/commit/a008ca4e40c1b2b0844b952d9de91b092d999e7a))

### Python/python-dotenv

- Update to 1.1.1 ([9074957](https://github.com/OpenIndiana/oi-userland/commit/90749571ef0099002797763060facc79cef7d1f3))

### Python/python-rapidjson

- Update to 1.21 ([fc76e82](https://github.com/OpenIndiana/oi-userland/commit/fc76e823cabbeddfe8591fd3fdc2f068d42192d1))

### Python/pytz

- Rebuild for Python 3.14 ([f5ad95c](https://github.com/OpenIndiana/oi-userland/commit/f5ad95c0fbead4698172a6c68e652a22016909e6))

### Python/pyzmq

- Update to 27.0.0 ([a4e8c35](https://github.com/OpenIndiana/oi-userland/commit/a4e8c35ea7cd5ac23101746cfd4a88e10353f8f9)), Co-authored-by:Marcel Telka <marcel@il-bld.in.telka.sk>
- Update to 27.0.1 ([933782c](https://github.com/OpenIndiana/oi-userland/commit/933782ce66039823a6284c8d0b0f6c17050bf71b))
- Update to 27.0.2 ([8ff8b93](https://github.com/OpenIndiana/oi-userland/commit/8ff8b9303ffd1c4e303a1a272558b69fa006dadf))
- Update to 27.1.0 ([7b84d7d](https://github.com/OpenIndiana/oi-userland/commit/7b84d7ddd30ee9316068a838795cf96368f0d2dd))

### Python/railroad-diagrams

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([8d9ae7f](https://github.com/OpenIndiana/oi-userland/commit/8d9ae7ff713cc2707edf7c32c649e01b7b9cbc0f))

### Python/rapidfuzz

- Update to 3.14.0 ([d412eff](https://github.com/OpenIndiana/oi-userland/commit/d412eff569484c8ca2032cf73a41db44a7308f06))
- Update to 3.14.1 ([f4a5689](https://github.com/OpenIndiana/oi-userland/commit/f4a5689cf8bb69c0949ffea4d94661626a5e0dfa))

### Python/regex

- Update to 2025.7.31 ([345ba8c](https://github.com/OpenIndiana/oi-userland/commit/345ba8c7849060858bde529aa0df2d93dc2e2f16))
- Update to 2025.7.34 ([d6ce331](https://github.com/OpenIndiana/oi-userland/commit/d6ce3315d4b02c6454bc455446ad01289caa344c))
- Update to 2025.8.29 ([71f9ef3](https://github.com/OpenIndiana/oi-userland/commit/71f9ef355c348e3a239bdf8e3eda098cad3405ab))
- Update to 2025.9.1 ([2816735](https://github.com/OpenIndiana/oi-userland/commit/28167354b60bcbc0303067c56ed7d7d74dfe02ed))
- Update to 2025.9.18 ([3c51f97](https://github.com/OpenIndiana/oi-userland/commit/3c51f97b57e6e0d4a76092b1234f634ce744f1d9))
- Update to 2025.10.23; rebuild for Python 3.14 ([133982a](https://github.com/OpenIndiana/oi-userland/commit/133982a90c34e6c94debd697e4fc94f8c194546b))

### Python/requests

- Update to 2.32.4 ([430a105](https://github.com/OpenIndiana/oi-userland/commit/430a1055837090834a100380ed0650176366348d))
- Update to 2.32.5 ([da604d1](https://github.com/OpenIndiana/oi-userland/commit/da604d17d63d701d904d28d284f103351932da85))

### Python/resolvelib

- Update to 1.2.0 ([7dd216a](https://github.com/OpenIndiana/oi-userland/commit/7dd216a8ece7f89cda06a1e6964a00ab9b96f6b2))
- Update to 1.2.1 ([0cca624](https://github.com/OpenIndiana/oi-userland/commit/0cca624478f66abf82b9fce4db69d6736e28cdc6))

### Python/rich

- Update to 14.1.0 ([f407e4b](https://github.com/OpenIndiana/oi-userland/commit/f407e4b486f6fefc29e5f136a1b928caefecb329))
- Update to 14.2.0 ([6d88de8](https://github.com/OpenIndiana/oi-userland/commit/6d88de80387e63c22e925eb03fdce9ba454f0d3b))

### Python/roman-numerals

- Rebuild for Python 3.14 ([8b21752](https://github.com/OpenIndiana/oi-userland/commit/8b21752f421227b9720ee4dfafb0d76834d0c5ec))

### Python/rpds_py

- Update to 0.26.0 ([028076a](https://github.com/OpenIndiana/oi-userland/commit/028076a0489b16922758dd94499a34a0bfebe9f7))
- Update to 0.27.0 ([baa6466](https://github.com/OpenIndiana/oi-userland/commit/baa6466d03bbe50f3b251d18b722ce9c63ee8e15))
- Update to 0.27.1 ([9ecada8](https://github.com/OpenIndiana/oi-userland/commit/9ecada8ed1fcdefc312755a2a1e81ffacf8cff57))

### Python/ruamel.yaml

- Update to 0.18.13 ([dea2430](https://github.com/OpenIndiana/oi-userland/commit/dea2430495a34dc62961a02ed4c61fcf68e27a27))
- Update to 0.18.14 ([5193594](https://github.com/OpenIndiana/oi-userland/commit/51935942af09151aa1df162a0ab27ba240744265))
- Update to 0.18.15 ([3339eee](https://github.com/OpenIndiana/oi-userland/commit/3339eeecba59dc2a1e1673a215f8e3ed9e4825e2))
- Update to 0.18.16; rebuild for Python 3.14 ([e9828b2](https://github.com/OpenIndiana/oi-userland/commit/e9828b24840abce42396b3f1867fab60d0314607))

### Python/ruamel.yaml.clib

- Update to 0.2.14 ([35238c3](https://github.com/OpenIndiana/oi-userland/commit/35238c306c49d63d398f217eb557140bad544356))

### Python/schema

- Update to 0.7.8; rebuild for Python 3.14 ([febf0aa](https://github.com/OpenIndiana/oi-userland/commit/febf0aa8e9cb1f5906482d2938ce9635ea2f99e6))

### Python/scikit-build-core

- Update to 0.11.5 ([cec32ef](https://github.com/OpenIndiana/oi-userland/commit/cec32ef29898a380e363b0fbe2c6669cad944c6c))
- Update to 0.11.6 ([7ee236a](https://github.com/OpenIndiana/oi-userland/commit/7ee236a2c5538932f71c66ab0f8c804b47d6a1b6))

### Python/scripttest

- Rebuild for Python 3.14 ([fd31a27](https://github.com/OpenIndiana/oi-userland/commit/fd31a2754a93c7ab69863ac11722473cc8ef8c75))

### Python/setuptools

- Rebuild for Python 3.14 ([609ebf7](https://github.com/OpenIndiana/oi-userland/commit/609ebf783a349f23ba14b29cc81b160c4912dc07))

### Python/setuptools-rust

- Update to 1.12.0 ([9415f18](https://github.com/OpenIndiana/oi-userland/commit/9415f18df5ac88025b1dfa27cf667b5fc612610a))

### Python/setuptools-scm

- Update to 9.2.0 ([75f11e0](https://github.com/OpenIndiana/oi-userland/commit/75f11e040065094683f9802a311c0df6e9c072f1))
- Remove annoying warning ([48fe2ef](https://github.com/OpenIndiana/oi-userland/commit/48fe2efc835005acf4a7463bff61bbdfa1aa84aa))
- Update to 9.2.1; rebuild for Python 3.14 ([6f95545](https://github.com/OpenIndiana/oi-userland/commit/6f95545abba34896b8a2c36ea45c9911f16dcfae))
- Update to 9.2.2 ([b9af1fd](https://github.com/OpenIndiana/oi-userland/commit/b9af1fd7417e0eb07f61c5cf5fbce9be7217766f))

### Python/simplejson

- Update to 3.20.2 ([b7bb8a8](https://github.com/OpenIndiana/oi-userland/commit/b7bb8a86ce10a9310f55f447212b3ac5ac6f90f1))
- Rebuild for Python 3.14 ([72f9728](https://github.com/OpenIndiana/oi-userland/commit/72f97282d9a69afc2f33ae9de2a3b179e33511f3))

### Python/sip

- Update to 6.13.0 ([6e02e51](https://github.com/OpenIndiana/oi-userland/commit/6e02e51dc92e9d62782bd3f266816a39bc449a74))
- Update to 6.13.1 ([8914881](https://github.com/OpenIndiana/oi-userland/commit/8914881e121f0767e4d68215377ba8098f1e9b7b))
- Update to 6.14.0; rebuild for Python 3.14 ([8c8cd27](https://github.com/OpenIndiana/oi-userland/commit/8c8cd275b918695cb7daae029ef6c73871baef89))

### Python/six

- Rebuild for Python 3.14 ([2ec7577](https://github.com/OpenIndiana/oi-userland/commit/2ec75773fc79f701ec43640e83e290c60872da7f))

### Python/smartypants

- Update to 2.0.2 ([766769e](https://github.com/OpenIndiana/oi-userland/commit/766769eabd0052ea4adbef9d38842dee6ce03bd6))

### Python/smmap

- Rebuild for Python 3.14 ([1f87daf](https://github.com/OpenIndiana/oi-userland/commit/1f87dafc07e9c209a81cfb30dbacda76857bb4aa))

### Python/soupsieve

- Update to 2.8 ([0db48f8](https://github.com/OpenIndiana/oi-userland/commit/0db48f8edf21d872ab5bb7a153d80a019f362294))
- Rebuild for Python 3.14 ([528b5fe](https://github.com/OpenIndiana/oi-userland/commit/528b5fe9c2deec7b508c7c1fbc27f499a12a82d0))

### Python/sphinx

- Switch to roman-numerals ([3f03f02](https://github.com/OpenIndiana/oi-userland/commit/3f03f02df0049ac82dd6dd9baccda0233acc9c45))

### Python/sphinxcontrib-jsmath

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([835a05c](https://github.com/OpenIndiana/oi-userland/commit/835a05cdad29ebcd5d47d4cf5025656c0063046a))

### Python/sphinxcontrib_applehelp

- Rebuild for Python 3.14 ([4324d74](https://github.com/OpenIndiana/oi-userland/commit/4324d740e0214c637f4aa5320f55477c042fb68d))

### Python/sphinxcontrib_devhelp

- Rebuild for Python 3.14 ([10bda1a](https://github.com/OpenIndiana/oi-userland/commit/10bda1a948e070e0a9e66460b293eb9cc237671a))

### Python/sphinxcontrib_htmlhelp

- Rebuild for Python 3.14 ([f10a374](https://github.com/OpenIndiana/oi-userland/commit/f10a374006824b95c6a1932e43c368158766a9a2))

### Python/sphinxcontrib_qthelp

- Rebuild for Python 3.14 ([65bb5a4](https://github.com/OpenIndiana/oi-userland/commit/65bb5a46993f7ef4bd3f0637d25228a4b66fabae))

### Python/sphinxcontrib_serializinghtml

- Rebuild for Python 3.14 ([56dc03c](https://github.com/OpenIndiana/oi-userland/commit/56dc03ced9b2ba501c52278d5ec0d5324a397615))

### Python/sqlparse

- Rebuild for Python 3.14 ([03222c2](https://github.com/OpenIndiana/oi-userland/commit/03222c29bfe6aa63b429ed486009ebc2a5c41db1))

### Python/stevedore

- Update to 5.5.0 ([0edce1b](https://github.com/OpenIndiana/oi-userland/commit/0edce1b187f9be91054934714b0f5cf64f29e053))

### Python/sybil

- Update to 9.2.0 ([c460330](https://github.com/OpenIndiana/oi-userland/commit/c46033022d35ab2fd808f7f0eef3b03f93656c3b))
- Rebuild for Python 3.14 ([73fe449](https://github.com/OpenIndiana/oi-userland/commit/73fe44996614466c0ca1ed653a13a55c18da93cb))

### Python/tempora

- Update to 5.8.1 ([e5365a9](https://github.com/OpenIndiana/oi-userland/commit/e5365a965e687e387d43a4a0fb1ba3a730cc0d87))

### Python/testpath

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([4e28c39](https://github.com/OpenIndiana/oi-userland/commit/4e28c393c5e1f2c0f81b1d69f8961e3141dc5de2))

### Python/time-machine

- Update to 2.17.0 ([89eae7a](https://github.com/OpenIndiana/oi-userland/commit/89eae7a511e698f8640e99d223083d20c6fe65fe))

### Python/tomli

- Update to 2.3.0 ([a03805b](https://github.com/OpenIndiana/oi-userland/commit/a03805ba8e4b040eaca83ef7337ecb979de29e10))
- Rebuild for Python 3.14 ([3e300cd](https://github.com/OpenIndiana/oi-userland/commit/3e300cda9cae8d617dbe9bf7f8f88496444d7168))
- Add test results for Python 3.14 ([48f9f06](https://github.com/OpenIndiana/oi-userland/commit/48f9f06ba24c2db62b36ac2ce8901ef0a9f2b7d3))

### Python/tomlkit

- Update to 0.13.3 ([437a072](https://github.com/OpenIndiana/oi-userland/commit/437a072ff8eb9b29039a5aab14c9efac191430a1))

### Python/tornado

- Update to 6.5.2 ([83f29f4](https://github.com/OpenIndiana/oi-userland/commit/83f29f45b828a301b0b1d165da0072443bf6ebe6))

### Python/tox

- Update to 4.30.3; rebuild for Python 3.14 ([2be7717](https://github.com/OpenIndiana/oi-userland/commit/2be77171a3332662e6494672c573ec071568304d))
- Update to 4.31.0 ([202c2d4](https://github.com/OpenIndiana/oi-userland/commit/202c2d4a9e4fab8ff09ced922905e8c45309e2a5))
- Try setup.cfg as a last resort only ([5946b94](https://github.com/OpenIndiana/oi-userland/commit/5946b9434f13af847e0713a996007f0e1b443d1c))
- Update to 4.32.0 ([0a34dc3](https://github.com/OpenIndiana/oi-userland/commit/0a34dc304f523a28d5eda44fb9af7e479e92c5e3))

### Python/tox-current-env

- Rebuild for Python 3.14 ([3663297](https://github.com/OpenIndiana/oi-userland/commit/36632979e2d48d1fb2923eb84a6b0bdfb644e3c1))

### Python/trove-classifiers

- Update to 2025.8.6.13 ([5416ae7](https://github.com/OpenIndiana/oi-userland/commit/5416ae7512e03d0fcd264ae7736348a5fc17ecda))
- Update to 2025.8.26.11 ([c665017](https://github.com/OpenIndiana/oi-userland/commit/c6650171e47cba5d718b20e49376070b7fe01711))
- Update to 2025.9.8.13 ([c52b8a1](https://github.com/OpenIndiana/oi-userland/commit/c52b8a1de74bdc31b166bdf6bc67d57f87695e08))
- Update to 2025.9.9.12 ([51dc690](https://github.com/OpenIndiana/oi-userland/commit/51dc690e916e037aede167e9e75d0b8b271a7d7a))
- Update to 2025.9.11.17 ([bd8006a](https://github.com/OpenIndiana/oi-userland/commit/bd8006a098dfd2d624543d9267cbc36196b8aeca))
- Rebuild for Python 3.14 ([2963798](https://github.com/OpenIndiana/oi-userland/commit/296379846949de9bdfd7934c15c1d73a4c16bca2))

### Python/twine

- Update to 6.2.0 ([59b6a95](https://github.com/OpenIndiana/oi-userland/commit/59b6a956173afb041ee66672807f1780443c65ae))

### Python/typeguard

- Update to 4.4.3 ([81d96f0](https://github.com/OpenIndiana/oi-userland/commit/81d96f02a329d769d5dbeb86fdd2fad688fbe863))
- Update to 4.4.4 ([4004665](https://github.com/OpenIndiana/oi-userland/commit/4004665d0f750b63c7355f6dfec6ec54a1d1831b))

### Python/types-PyYAML

- Update to 6.0.12.20250809 ([56d3406](https://github.com/OpenIndiana/oi-userland/commit/56d3406a50b328e75725418399c554edd7b70347))
- Update to 6.0.12.20250822 ([ded9108](https://github.com/OpenIndiana/oi-userland/commit/ded9108d9f212e7e21ee3be8c78c2ab46e01abfb))
- Update to 6.0.12.20250915 ([030db39](https://github.com/OpenIndiana/oi-userland/commit/030db39d2e172cc6bfaf3f7e1ca9e8856e0375c8))
- Rebuild for Python 3.14 ([1836b36](https://github.com/OpenIndiana/oi-userland/commit/1836b36515c1ec63fc0e5984856a2dd83f024cd6))

### Python/types-decorator

- Rebuild for Python 3.14 ([34188cf](https://github.com/OpenIndiana/oi-userland/commit/34188cfff8dd10cb0530ee3368cd4509dbc85b76))

### Python/types-docutils

- Update to 0.21.0.20250708 ([2186f8a](https://github.com/OpenIndiana/oi-userland/commit/2186f8ae421d93d1230722078b1d6c9e080ae288))
- Update to 0.21.0.20250710 ([7219d19](https://github.com/OpenIndiana/oi-userland/commit/7219d19e48b217a8aa18558c5f6aa8341e0350f8))
- Update to 0.21.0.20250715 ([789a989](https://github.com/OpenIndiana/oi-userland/commit/789a9891d3ae7bc9550376e32c2d6506ba6e60d3))
- Update to 0.21.0.20250722 ([8b3edb7](https://github.com/OpenIndiana/oi-userland/commit/8b3edb716a60f817288dd1e30cf0bdf1092cdd28))
- Update to 0.21.0.20250727 ([3c4032c](https://github.com/OpenIndiana/oi-userland/commit/3c4032cc0ed5edc75ba0fdb9d2b57b367e0c67ab))
- Update to 0.21.0.20250728 ([25ee9f0](https://github.com/OpenIndiana/oi-userland/commit/25ee9f09ee5204ee806501da25b36dff9e028dda))
- Update to 0.21.0.20250809 ([cdc5076](https://github.com/OpenIndiana/oi-userland/commit/cdc5076b4a40c0ff72daeceaf96ec247fd52a477))
- Update to 0.22.0.20250814 ([cf53a0e](https://github.com/OpenIndiana/oi-userland/commit/cf53a0ed1982b93f35c6a93e0f661246b7ad8543))
- Update to 0.22.0.20250822 ([165caea](https://github.com/OpenIndiana/oi-userland/commit/165caeafe0923664217e8f4c2ec4ab6fc80e1c49))
- Update to 0.22.0.20250914 ([771bb4f](https://github.com/OpenIndiana/oi-userland/commit/771bb4f9070f9d534a1e4f39dc46c9e943679a51))
- Update to 0.22.0.20250919 ([da5c9a6](https://github.com/OpenIndiana/oi-userland/commit/da5c9a69c94305cabf1fb71666a55eed9462f9f5))
- Update to 0.22.1.20250923 ([22517a9](https://github.com/OpenIndiana/oi-userland/commit/22517a9ab5e812d3243aed7dd573d21c0569ea60))
- Update to 0.22.2.20250924 ([873c151](https://github.com/OpenIndiana/oi-userland/commit/873c15154aafcdfd4e834bec052458e32db906cc))
- Update to 0.22.2.20251006 ([0eeaefc](https://github.com/OpenIndiana/oi-userland/commit/0eeaefcf466b95cff7cbab045fc5da41bad4260a))
- Rebuild for Python 3.14 ([35c8467](https://github.com/OpenIndiana/oi-userland/commit/35c8467bdedfb4548c2891550dabbfbb67c7ac99))

### Python/types-mock

- Update to 5.2.0.20250809 ([61fdb20](https://github.com/OpenIndiana/oi-userland/commit/61fdb206518af232505b491407073b7d20038021))
- Update to 5.2.0.20250924 ([1d4eb0a](https://github.com/OpenIndiana/oi-userland/commit/1d4eb0a4f76fefd71c1bab9e79b2c3ee0dc12fbc))
- Rebuild for Python 3.14 ([ac1eb3b](https://github.com/OpenIndiana/oi-userland/commit/ac1eb3bff90fa591994a8a8713e12e1344f4d4e2))

### Python/types-paramiko

- Update to 3.5.0.20250708 ([436abb5](https://github.com/OpenIndiana/oi-userland/commit/436abb5f1bcda56ce2decb3c09af66d4ba7abfe5))
- Update to 3.5.0.20250801 ([812c8bd](https://github.com/OpenIndiana/oi-userland/commit/812c8bd4ab56313d9436b9ff19be0d41dd95483b))
- Update to 4.0.0.20250806 ([814823f](https://github.com/OpenIndiana/oi-userland/commit/814823f134b4b501729e8d19c5e7c621d6347b3c))
- Update to 4.0.0.20250809 ([0ce9cca](https://github.com/OpenIndiana/oi-userland/commit/0ce9cca6e6f6e192dba5e31f65bfc0ec8323c1dd))
- Update to 4.0.0.20250821 ([e1cfa81](https://github.com/OpenIndiana/oi-userland/commit/e1cfa81cc377f67b345a39f5f27eefdde319a0c8))
- Update to 4.0.0.20250822 ([2bcc271](https://github.com/OpenIndiana/oi-userland/commit/2bcc271106c85871d7ba4e43ae2dccc71d64a0cd))

### Python/types-psutil

- Update to 7.0.0.20250801 ([37002f8](https://github.com/OpenIndiana/oi-userland/commit/37002f88972b54d5f591f765e203add5ae9583e4))
- Update to 7.0.0.20250822 ([f4a697c](https://github.com/OpenIndiana/oi-userland/commit/f4a697c6f9323758cdfb4cec855236c798009f36))
- Update to 7.0.0.20251001 ([d24e9a5](https://github.com/OpenIndiana/oi-userland/commit/d24e9a5a9a682d0fed745827d8ab31195275cdd1))
- Rebuild for Python 3.14 ([a41a85f](https://github.com/OpenIndiana/oi-userland/commit/a41a85f0ee15b0f587d3304629de5caa1175d0ca))

### Python/types-python-dateutil

- Update to 2.9.0.20250708 ([836778e](https://github.com/OpenIndiana/oi-userland/commit/836778eb1dc00ee016fbc1b2860953c957e9015f))
- Update to 2.9.0.20250809 ([c8b9bed](https://github.com/OpenIndiana/oi-userland/commit/c8b9bed400ef4ae13df9a69768cb5b946378e70a))
- Update to 2.9.0.20250822 ([457013c](https://github.com/OpenIndiana/oi-userland/commit/457013c60b5a16a47268bb790ea905268ba5dc59))
- Update to 2.9.0.20251008 ([a71cbc2](https://github.com/OpenIndiana/oi-userland/commit/a71cbc21b58e4265d17469f59b29fa79a37c855d))
- Rebuild for Python 3.14 ([58b0f9a](https://github.com/OpenIndiana/oi-userland/commit/58b0f9a865bd0362eedbac4693da60388a9c5d8a))

### Python/types-pytz

- Update to 2025.2.0.20250809 ([3d80ec4](https://github.com/OpenIndiana/oi-userland/commit/3d80ec413655b93a36116fb77475513468474b67))
- Rebuild for Python 3.14 ([45f6f3b](https://github.com/OpenIndiana/oi-userland/commit/45f6f3bb50a2db7b48d58bb09b4ea2910710b851))

### Python/types-requests

- Update to 2.32.4.20250611 ([f24cefb](https://github.com/OpenIndiana/oi-userland/commit/f24cefb11357cbae786d70138799b0de80d0091f))
- Update to 2.32.4.20250809 ([1420311](https://github.com/OpenIndiana/oi-userland/commit/1420311de6a8620a5192b6868512ba7b621cb5d7))
- Update to 2.32.4.20250913 ([5afb25c](https://github.com/OpenIndiana/oi-userland/commit/5afb25ca45ba0b205036602a81b560a3bfe674bd))

### Python/types-setuptools

- Update to 80.9.0.20250801 ([799af1b](https://github.com/OpenIndiana/oi-userland/commit/799af1b1ba7e1251bfa65fa2a8749f5a04d2defb))
- Update to 80.9.0.20250809 ([d4d600e](https://github.com/OpenIndiana/oi-userland/commit/d4d600e706eb8d32b31e28843dc4c05a33c21268))
- Update to 80.9.0.20250822 ([0271e76](https://github.com/OpenIndiana/oi-userland/commit/0271e768fa07b80b6e88ecdea299c557fb398820))
- Rebuild for Python 3.14 ([135a4e4](https://github.com/OpenIndiana/oi-userland/commit/135a4e4f5225bff76f337993518da12fca363e51))

### Python/types-six

- Update to 1.17.0.20251009 ([cf115ae](https://github.com/OpenIndiana/oi-userland/commit/cf115ae309ada867c71990134b257e2847b19231))
- Rebuild for Python 3.14 ([8171a01](https://github.com/OpenIndiana/oi-userland/commit/8171a011c6bd4c527878b045ee58c11819c959a7))

### Python/types-toml

- Rebuild for Python 3.14 ([fb14dde](https://github.com/OpenIndiana/oi-userland/commit/fb14dde5693e82d9cc97434d8f2a9f5f786b6d9d))

### Python/typing-inspection

- Update to 0.4.2 ([4e52ea8](https://github.com/OpenIndiana/oi-userland/commit/4e52ea8653969cbec65a62571adbb357d1cfb3d5))
- Rebuild for Python 3.14 ([90d168e](https://github.com/OpenIndiana/oi-userland/commit/90d168e73d7aca20e8088dd06d81dfc537b5f31a))

### Python/typing_extensions

- Update to 4.14.1 ([db5b907](https://github.com/OpenIndiana/oi-userland/commit/db5b9073ea5a9ec1481da5967525e142fb4f1aac))
- Update to 4.15.0 ([b92ae92](https://github.com/OpenIndiana/oi-userland/commit/b92ae92109105296daf26541a16a5efc44f390b9))
- Rebuild for Python 3.14 ([28f1141](https://github.com/OpenIndiana/oi-userland/commit/28f11419dc935dbf399ad23e319ee9c3760bd67b))
- Add test results for Python 3.14 ([bda99b2](https://github.com/OpenIndiana/oi-userland/commit/bda99b26a410c7a2ab775ae13ba6bfd642c6fa25))

### Python/u-msgpack-python

- Rebuild for Python 3.14 and obsolete package for Python 3.7 ([01e9302](https://github.com/OpenIndiana/oi-userland/commit/01e930292fbff69d803f68b015fc62196db693f9))

### Python/urllib3

- Update to 2.5.0 ([5e870f5](https://github.com/OpenIndiana/oi-userland/commit/5e870f53932db8588e577a831866cf98c3191002))

### Python/validators

- Rebuild for Python 3.14 ([12b9817](https://github.com/OpenIndiana/oi-userland/commit/12b9817c45d5d02c2a565f1bdd19da75b7e7597e))

### Python/virtualenv

- Update to 20.31.2; rebuild for Python 3.14 ([c5a2602](https://github.com/OpenIndiana/oi-userland/commit/c5a260210f0b2dbe35210596828fa95b59cc99ce))
- Update to 20.35.3 ([65da858](https://github.com/OpenIndiana/oi-userland/commit/65da8585da0271dec5cf5af6784d68428195cc32))

### Python/wcmatch

- Update to 10.1 ([576b093](https://github.com/OpenIndiana/oi-userland/commit/576b093369e629180b0e26219091c01d811b0f44))

### Python/wcwidth

- Update to 0.2.14 ([aeb4b7f](https://github.com/OpenIndiana/oi-userland/commit/aeb4b7f54f1989073f1d7eebeb1b0e967017e1b0))

### Python/whatever

- Rebuild for Python 3.14 ([21c8628](https://github.com/OpenIndiana/oi-userland/commit/21c8628269628cfa87257f226c44e02577f4c3db))

### Python/wheel

- Downgrade to 0.45.1 ([2b193fd](https://github.com/OpenIndiana/oi-userland/commit/2b193fd60ebcdd1d44864e30e3e3e5735dc49dec))
- Rebuild for Python 3.14 ([028b8b3](https://github.com/OpenIndiana/oi-userland/commit/028b8b34b81e2250a9c0cb81159b30e2f8abac24))

### Python/wrapt

- Update to 1.17.3 ([08925bb](https://github.com/OpenIndiana/oi-userland/commit/08925bb184af6e449d3d019cd9ac7c710aaabdd0))

### Python/xmlschema

- Update to 4.1.0 ([5adec52](https://github.com/OpenIndiana/oi-userland/commit/5adec52286a195eb5fe6524b5f8a2c3c31d422b2))

### Python/xmltodict

- Update to 0.15.0 ([867b1cf](https://github.com/OpenIndiana/oi-userland/commit/867b1cf9c82542f6fa36be263451fdd2e72fae0f))
- Update to 0.15.1 ([197fc39](https://github.com/OpenIndiana/oi-userland/commit/197fc392f09c9be35d82c88a414f7867f1626957))
- Update to 1.0.0 ([713be59](https://github.com/OpenIndiana/oi-userland/commit/713be598498730181dfbc1cd5c341c85b3d91cca))
- Update to 1.0.1 ([9f579ea](https://github.com/OpenIndiana/oi-userland/commit/9f579ea3135073329951612faeb7d4a8e03d34aa))
- Update to 1.0.2 ([9158fab](https://github.com/OpenIndiana/oi-userland/commit/9158fabd33f1daac21efa7403e874fd445c011af))
- Rebuild for Python 3.14 ([16e6bc9](https://github.com/OpenIndiana/oi-userland/commit/16e6bc956a7a5095beb453dc87ece9cc36f89a54))

### Python/yamlfix

- Update to 1.18.0 ([9ecf0db](https://github.com/OpenIndiana/oi-userland/commit/9ecf0dbc17dd7417c0f352da48fd06e983b85a0b))
- Update to 1.19.0 ([be5f1e7](https://github.com/OpenIndiana/oi-userland/commit/be5f1e79481428441eb4f97ede1c049600ad5e0a))

### Python/yarl

- Update to 1.20.1 ([0d6fb47](https://github.com/OpenIndiana/oi-userland/commit/0d6fb4784b7ee8eb68a9c2f5225ebe19faa97ece))
- Update to 1.21.0 ([83f2599](https://github.com/OpenIndiana/oi-userland/commit/83f259957919125805dd204ba6909776246fdc13))
- Update to 1.22.0 ([ee73011](https://github.com/OpenIndiana/oi-userland/commit/ee73011a2b201cee2e7eca3ba8fda7c17fe0a4ea))

### Python/zc.lockfile

- Update to 4.0; obsolete package for Python 3.7 ([b3d1234](https://github.com/OpenIndiana/oi-userland/commit/b3d123489af357c143feb904d1c5d98663c59140))

### Python/zipp

- Update to 3.23.0 ([81a6a39](https://github.com/OpenIndiana/oi-userland/commit/81a6a396679d751eb5106b4c66edfbefb7f95fc1))
- Rebuild for Python 3.14 ([8dcdd80](https://github.com/OpenIndiana/oi-userland/commit/8dcdd804673ab9bb640c273af9f28fc5efb552e4))

### Python/zope.component

- Update to 6.1 ([94c8f73](https://github.com/OpenIndiana/oi-userland/commit/94c8f739a7bb52089e52f9bfe1d3070a7ca3494d))
- Update to 7.0 ([b5a2bdc](https://github.com/OpenIndiana/oi-userland/commit/b5a2bdcef8abc40651e9c633dd42ea1f75b05354))

### Python/zope.configuration

- Update to 7.0 ([93233dd](https://github.com/OpenIndiana/oi-userland/commit/93233ddc1481ca7ad714aa9ca788684570b659f9))

### Python/zope.copy

- Update to 6.0 ([1cc7e0c](https://github.com/OpenIndiana/oi-userland/commit/1cc7e0cacd1ee6a6d0bf9daaa3854a680704d4e3))

### Python/zope.deferredimport

- Update to 5.1 ([94511c5](https://github.com/OpenIndiana/oi-userland/commit/94511c52a2e5bad30d87872d10a1836a96e30ec8))
- Update to 6.0 ([7841ae1](https://github.com/OpenIndiana/oi-userland/commit/7841ae15f76b95baa52a989f6a536ccd15bfd846))

### Python/zope.deprecation

- Update to 6.0 ([5f1a7fa](https://github.com/OpenIndiana/oi-userland/commit/5f1a7fa6ca936b09367868109e44bedec76b1da6))

### Python/zope.event

- Update to 5.1; obsolete package for Python 3.7 ([879fd47](https://github.com/OpenIndiana/oi-userland/commit/879fd47634dd8f63fcb9db3063d6be98dbf1001f))
- Update to 5.1.1 ([8b064b9](https://github.com/OpenIndiana/oi-userland/commit/8b064b9a937463de1a4e9368e620773707f2ca71))
- Update to 6.0 ([4d0be73](https://github.com/OpenIndiana/oi-userland/commit/4d0be73df71ab76a7a408dc0a8cf3fee6f929bb9))

### Python/zope.exceptions

- Update to 6.0 ([f25e3ca](https://github.com/OpenIndiana/oi-userland/commit/f25e3cacce320cf19f1d52558c736d02ad3b4a79))

### Python/zope.hookable

- Update to 8.0 ([9563e99](https://github.com/OpenIndiana/oi-userland/commit/9563e99ae2751548813e9dcc84325181146fd09b))

### Python/zope.i18nmessageid

- Update to 8.0 ([e543c7f](https://github.com/OpenIndiana/oi-userland/commit/e543c7f17f3169b071a3714e1dc4beaedbc0dca1))

### Python/zope.interface

- Update to 8.0 ([9162226](https://github.com/OpenIndiana/oi-userland/commit/91622265ea533110a783ca66911b0afe0207df73))
- Update to 8.0.1 ([65e8c15](https://github.com/OpenIndiana/oi-userland/commit/65e8c15090af717c38cbb862fd74e65620a24506))

### Python/zope.location

- Update to 6.0 ([1989c12](https://github.com/OpenIndiana/oi-userland/commit/1989c120740ec8608d2af2d458763569381d8a33))

### Python/zope.proxy

- Update to 7.0 ([2aa2248](https://github.com/OpenIndiana/oi-userland/commit/2aa2248905a07fed6e3dd67bd7472d47607ec5e2))

### Python/zope.schema

- Update to 7.1 ([436ce71](https://github.com/OpenIndiana/oi-userland/commit/436ce71527a7e03b16e72691b346f28d64566363))
- Update to 8.0 ([32584e7](https://github.com/OpenIndiana/oi-userland/commit/32584e79b9888087c754cb4e8782cc0abe8f68ad))

### Python/zope.security

- Update to 8.0 ([959cbf3](https://github.com/OpenIndiana/oi-userland/commit/959cbf394c6619604de55ba7f1732c9eb4c4755f))
- Update to 8.1 ([7cf4de6](https://github.com/OpenIndiana/oi-userland/commit/7cf4de67655a10c0a49845caaf3dc8f4c902c014))

### Python/zope.testing

- Update to 6.0 ([d37d4b5](https://github.com/OpenIndiana/oi-userland/commit/d37d4b502dde8922e9b9e2d348f36d5767313d25))

### Python/zope.testrunner

- Update to 7.4 ([a373f95](https://github.com/OpenIndiana/oi-userland/commit/a373f95dc60cfaa97ed4894e17f327108abf3922))
- Update to 8.0 ([ab6b1f8](https://github.com/OpenIndiana/oi-userland/commit/ab6b1f8a7bd884261a6fe1d079fa74734b9d35df))
- Update to 8.1 ([bc2a633](https://github.com/OpenIndiana/oi-userland/commit/bc2a633238eef6a3bea3907af83d590878ddf65c))

### Python/zstandard

- Update to 0.24.0 ([44e7e6f](https://github.com/OpenIndiana/oi-userland/commit/44e7e6f636966bada4ed30b945e24c2550d8859d))
- Update to 0.25.0 ([79b353f](https://github.com/OpenIndiana/oi-userland/commit/79b353f7fd482411fb9947680668f9f40f98695b))

### Python/zstd

- Update to 1.5.7.1 ([ad03747](https://github.com/OpenIndiana/oi-userland/commit/ad03747f8a1313a73a082e0611431ccb6fe5ea66))
- Update to 1.5.7.2 ([f536760](https://github.com/OpenIndiana/oi-userland/commit/f53676026ba1e9bc5d16c15f816b0a07fa3aaedd))
- Rebuild for Python 3.14 ([7dae8c1](https://github.com/OpenIndiana/oi-userland/commit/7dae8c163e90bcc45dddb68fbb635e9b9d2c75aa))

### Python312

- Add python 3.12.11 ([a9cda5d](https://github.com/OpenIndiana/oi-userland/commit/a9cda5d8929376e649f59ec8602384e9c76c91f1))
- Update to 3.12.12 ([990414e](https://github.com/OpenIndiana/oi-userland/commit/990414ee4b37b6b576a5a42d1d8cd6b71f763723))

### Qemu

- Update to 10.0.2 ([e465afb](https://github.com/OpenIndiana/oi-userland/commit/e465afb9320fe034ff33455a232e33066d6b4aa8))
- Update to 10.0.3 ([1c684d5](https://github.com/OpenIndiana/oi-userland/commit/1c684d58828b5a1feefc7ec12034c78d63394b5e))
- Update to 10.1.0 ([68c174b](https://github.com/OpenIndiana/oi-userland/commit/68c174bc7b13bc14a577c28bde349b0d0c6d795d))
- Update to 10.1.1 ([926692a](https://github.com/OpenIndiana/oi-userland/commit/926692a1eacc1b9abf8514564aad11720f8232a4))

### Qt5

- Update to 5.15.17; note that libxml2 is not being used as it is ([2536d49](https://github.com/OpenIndiana/oi-userland/commit/2536d49a8e11db5049f46746922ca545514cf8df))

### Rage

- Modernize Makefile ([aeb9819](https://github.com/OpenIndiana/oi-userland/commit/aeb981959615add5956918f8038478e7b57fee2c))

### Raptor2

- Drop 32 bit ([0c1917a](https://github.com/OpenIndiana/oi-userland/commit/0c1917ac389c713ac5f05d8c83f64d497ec8f314))

### Rdesktop

- Fix build with gcc-14 ([fab41b3](https://github.com/OpenIndiana/oi-userland/commit/fab41b3640ca87679bb254ec0dbaa5be2801aff1))

### Re2

- Update to 2025.07.22; add test results ([d93215f](https://github.com/OpenIndiana/oi-userland/commit/d93215ffd254888d9604656b9a6f1ff47905b2a1))
- Update to 2025.08.12 ([26ced25](https://github.com/OpenIndiana/oi-userland/commit/26ced25544c148fcab1453d367ce86c4b6e055e1))

### Re2c

- Update to 4.3 ([794ad35](https://github.com/OpenIndiana/oi-userland/commit/794ad350729816d8033bdd33458be2f7c9f141ae))

### Redis

- Update to 6.2.18 ([f605bf1](https://github.com/OpenIndiana/oi-userland/commit/f605bf19e99973823254786ad267af3f5a11ebd8))

### Rlwrap

- Update to 0.47 ([ae66d0a](https://github.com/OpenIndiana/oi-userland/commit/ae66d0af8a50b044622b9d52c6948ff44f6b81c6))
- Update to 0.47.1 ([c391ad2](https://github.com/OpenIndiana/oi-userland/commit/c391ad29eebfe521ac7fd8aea70f7e2e55e0b208))

### Ruby-32

- Update to 3.2.9 ([9bda903](https://github.com/OpenIndiana/oi-userland/commit/9bda9035d335ccc53891479ffb7be3d4a0580257))

### Ruby-34

- Update to 3.4.5 ([d2db1b7](https://github.com/OpenIndiana/oi-userland/commit/d2db1b7e8d64c888b3227f0628bb97cbcf000cb1))
- Update to 3.4.6 ([a81c779](https://github.com/OpenIndiana/oi-userland/commit/a81c779b8cf266d895cf7080333171b99507eaf5))
- Update to 3.4.7 ([9874f2c](https://github.com/OpenIndiana/oi-userland/commit/9874f2c8bf1977f6d0b8896dbd0bcf076c38a06d))

### Runtime/perl

- Switch to Perl 5.42 ([67bbef2](https://github.com/OpenIndiana/oi-userland/commit/67bbef2ae8c6082b39459395e106455c49c2976f))

### Rust

- Fix 1.89.0 build ([3860b5f](https://github.com/OpenIndiana/oi-userland/commit/3860b5f4fd79b575605fa2c0f9818afb91a5bd10))

### Rust/cargo-c

- Update to 0.10.14+cargo-0.89.0 ([e2080f5](https://github.com/OpenIndiana/oi-userland/commit/e2080f5c000b4975f95d210794969f88ffde131d))
- Update to 0.10.15+cargo-0.90.0 ([698b93f](https://github.com/OpenIndiana/oi-userland/commit/698b93fdaa917e13ff2a0d1de3a072f7e65005d3))
- Update to 0.10.16+cargo-0.91.0 ([67ee1d6](https://github.com/OpenIndiana/oi-userland/commit/67ee1d62828ca47e84b27a7bda886f74957655c2))

### Rust/cbindgen

- Update to 0.29.0 ([cfdb521](https://github.com/OpenIndiana/oi-userland/commit/cfdb521b7fc3e275c03441301ac851322c37f5ed))

### Rustc

- Force rebuild ([32052e3](https://github.com/OpenIndiana/oi-userland/commit/32052e394d6e202c906853b514cdc9c3cf04110b))

### Samba

- Fix dependencies ([4937bb7](https://github.com/OpenIndiana/oi-userland/commit/4937bb775ee81c4af2396223a84cabd183f6c6b8))

### Samqfs

- Update 5.64.10 ([5bd0d62](https://github.com/OpenIndiana/oi-userland/commit/5bd0d62f1c725008cc67d21d11d436ae4d82840f))

### Sbcl

- Update to 2.5.6 ([1b64694](https://github.com/OpenIndiana/oi-userland/commit/1b646940e68c535f85706cca50b6694af44314b5))
- Update to 2.5.7 ([d0965d3](https://github.com/OpenIndiana/oi-userland/commit/d0965d3772d0c49d8ed0dd56a2168962eb175abc))
- Update to 2.5.8 ([ed8dac0](https://github.com/OpenIndiana/oi-userland/commit/ed8dac08c40c600b47743f72d2525a93e1aabf27))
- Update to 2.5.9 ([9b94881](https://github.com/OpenIndiana/oi-userland/commit/9b94881701ae9fb07e3e8c6214a35483c3611b2a))

### Sdl2

- Add 32-bit library ([35d522e](https://github.com/OpenIndiana/oi-userland/commit/35d522e249db3ca4d49acea79dca06b1132a8a98))
- Update to 2.32.10 ([880c3ff](https://github.com/OpenIndiana/oi-userland/commit/880c3ff926771849d2b1a236dd0db825eb1c5eec))

### Sdl3

- Update to 3.2.20 ([a418268](https://github.com/OpenIndiana/oi-userland/commit/a4182683307fae588e556a5b623b7bbfd4392e3c))
- Update to 3.2.24 ([d0e2834](https://github.com/OpenIndiana/oi-userland/commit/d0e2834dca97e2682e432b1f8495d21a33bb21fc))

### Seaweedfs

- Add seaweedfs ([9cd9a92](https://github.com/OpenIndiana/oi-userland/commit/9cd9a92a4620e2b09e65f94c05b9a275c25df0ed))
- Update to 3.98 ([6d7e83b](https://github.com/OpenIndiana/oi-userland/commit/6d7e83b2022817db0587288be1b6810499776ae9))

### Service-hacluster-remote

- Fix dependencies ([887c26b](https://github.com/OpenIndiana/oi-userland/commit/887c26b3ec8d0411a8cdbadbe91f11e3cf076dec))

### Setup.py.mk

- Py.test should be called indirectly as pytest ([29f62d8](https://github.com/OpenIndiana/oi-userland/commit/29f62d826c6e766eea89067810a6ed9570a910cc))
- Tox dependency listing needs tox and tox-current-env ([ea8a5eb](https://github.com/OpenIndiana/oi-userland/commit/ea8a5eb67734516480fdc4cf58a34c610597fa88))

### Shared-macros.mk

- Simplify Python definitions ([82982f4](https://github.com/OpenIndiana/oi-userland/commit/82982f459ce0101f219207c84c15b646a3d4fd20))

### Slim_source

- Force publishing ([c4d8a20](https://github.com/OpenIndiana/oi-userland/commit/c4d8a204afa6b38a72afb9ebbcb7c3b9482136be))

### Soundtouch

- Update to 2.4.0 ([9fd1754](https://github.com/OpenIndiana/oi-userland/commit/9fd17548513b194cb9c5ce8039fb9aa718ff4dc8))

### Spdlog

- Update to 1.16.0 ([03c2157](https://github.com/OpenIndiana/oi-userland/commit/03c215769aad716cd27a16cc575874db63ce0856))

### Sqlite

- Update to 3.50.1 ([380c7bb](https://github.com/OpenIndiana/oi-userland/commit/380c7bbc92ddc922b61e9ddb81b79e43f6dc867d))
- Update to 3.50.2 ([44a27bd](https://github.com/OpenIndiana/oi-userland/commit/44a27bd9963937df484a3ca128abbc767d9a3bd2))
- Update to 3.50.3 ([f28b66f](https://github.com/OpenIndiana/oi-userland/commit/f28b66f0f451cbd87a73413ca2faafe902b777bc))
- Update to 3.50.4 ([9d2efbc](https://github.com/OpenIndiana/oi-userland/commit/9d2efbcfffe8c2c3a6225a39d600dc425e757a1c))

### Squeak

- Update to subversion revision 3834 - regenerate patches for subdirs ([714236a](https://github.com/OpenIndiana/oi-userland/commit/714236a18aa8f7a90e9043337c80a30eb9c33a78))
- 4.20.10 with patch for cmake 4.0.3 ([0ef5eb5](https://github.com/OpenIndiana/oi-userland/commit/0ef5eb5cd953ef4a33e6dcd4470f5d702209d341))
- Add .prep and .patched to clean targets ([d0e4db3](https://github.com/OpenIndiana/oi-userland/commit/d0e4db3147f7dd0973f67d6b054935b6fba5b95c))
- Update to VMMaker 4.21.3 ([7cd4665](https://github.com/OpenIndiana/oi-userland/commit/7cd46653a930f5764ef8768e4cff2feeaafec4ed))

### Srain

- Update to 1.8.1 ([7a2e7ab](https://github.com/OpenIndiana/oi-userland/commit/7a2e7abeab10e6a70f874ad29253b4243f5fe9ec))

### Stack-spur

- Update to VMMaker.oscog-eem.3581 ([dd0d098](https://github.com/OpenIndiana/oi-userland/commit/dd0d09858c88623f2614db63829e648bcee52503))
- Update to VMMaker.oscog-eem.3610 ([efb2388](https://github.com/OpenIndiana/oi-userland/commit/efb23880e343e6f4e6e1b74b1c27021b3529c9fb))

### Stalonetray

- Fix build with gcc-14 ([d01377e](https://github.com/OpenIndiana/oi-userland/commit/d01377e8d30a5d4d829881b737349585c106fcb2))

### Stellarium

- Update to 25.2 ([acd9187](https://github.com/OpenIndiana/oi-userland/commit/acd918794ebe076984ef6f2693260a081aeb6581))
- Update to 25.3 ([56a32d8](https://github.com/OpenIndiana/oi-userland/commit/56a32d888a37386f21257c84ade4b64e877b9404))

### Stunnel

- Update to 5.75 ([92d3213](https://github.com/OpenIndiana/oi-userland/commit/92d3213e26ec39916cf2ed698b9f37e00450f531))
- Update to 5.76 ([1032683](https://github.com/OpenIndiana/oi-userland/commit/1032683583197527e78c7af2aa5d1a2ed323da3d))

### Sudo

- Update to 1.9.17; import patches from OmniOS; adapt settings from OmniOS ([3f33c7e](https://github.com/OpenIndiana/oi-userland/commit/3f33c7ec0451c35b30ce1d5881acf4d5023586d9))
- Update to 1.9.17p1 ([25db68a](https://github.com/OpenIndiana/oi-userland/commit/25db68a8d97b37188e67438f7f57ddafdc183e65))
- Update to 1.9.17p2 ([47d2c72](https://github.com/OpenIndiana/oi-userland/commit/47d2c72d4d8c2e05308030c00498da055c9cbbb5))

### Sunray

- Add meta-package for required packages ([fe8258f](https://github.com/OpenIndiana/oi-userland/commit/fe8258ff4d1e24366849d652cd031ff5809d9d54))
- Add patchs for OI ([881835a](https://github.com/OpenIndiana/oi-userland/commit/881835ab09bd54a85984b3f316b3bb6e46f7ec30))
- Update patches for OI ([e936bf7](https://github.com/OpenIndiana/oi-userland/commit/e936bf7953e871fd9c9ea4fc06c6558daf73d92b))

### Sunray-essential

- Improve recipe ([f5b94c5](https://github.com/OpenIndiana/oi-userland/commit/f5b94c5cd393daaf310e39e25cb007d101eb3d07))
- Fix pkg5 file ([5c65280](https://github.com/OpenIndiana/oi-userland/commit/5c652800371d00620d8e018f018225e59655c3dd))

### Swi-prolog

- Add patch to fix path for ca-certificates file ([61fe9e1](https://github.com/OpenIndiana/oi-userland/commit/61fe9e12a798b5d47e29358346faa4c3fa8a3da4))

### Swi-prolog-dev

- Add patch to fix path for ca-certificates file ([1f0ff0b](https://github.com/OpenIndiana/oi-userland/commit/1f0ff0b9c4995cda867273663d5eff821aec0118))

### Swipl-dev

- Update to 9.3.25 ([4daa69b](https://github.com/OpenIndiana/oi-userland/commit/4daa69b31becff96b2342b30bcbba6ad9976deac))

### Sxhkd

- Fix build with gcc-14 ([dc5b8de](https://github.com/OpenIndiana/oi-userland/commit/dc5b8de082d40fbe09bdbd285ffa82507fcb2df6))
- Update to 0.6.3 ([752c799](https://github.com/OpenIndiana/oi-userland/commit/752c799dc050e0b578b12579abf9ae24bff78b33))

### Tcl

- Update to 8.6.17 ([107a3a6](https://github.com/OpenIndiana/oi-userland/commit/107a3a6901efcc91ef1c9e5374f652757b242cc0))

### Tcsh

- Update to 6.24.16 ([82dfad7](https://github.com/OpenIndiana/oi-userland/commit/82dfad70dd5f6895cb087bffe698777862537974))

### Tdb

- Update to 1.4.14 ([0565027](https://github.com/OpenIndiana/oi-userland/commit/056502763f2a7c051db5ca9cd0c14fe3f0fa15a1))

### Terminology

- Modernize Makefile; fix download ([25cb3ce](https://github.com/OpenIndiana/oi-userland/commit/25cb3ce1b6b6632d67362ac974608af79343ecbc))

### Thunderbird

- Update to 139.0.2 ([2096d8a](https://github.com/OpenIndiana/oi-userland/commit/2096d8a11fe22dfc496be0ec18ad99351f9082d3))
- Update to 140.0 ([e775737](https://github.com/OpenIndiana/oi-userland/commit/e77573701cdae0f11e22259a6cbbf38ff0d6ead1))
- Update to 140.0.1 ([0a05327](https://github.com/OpenIndiana/oi-userland/commit/0a05327d7596d30c50f131cd1a60001e99abdbf9))
- Update to 141.0 ([dc5ca37](https://github.com/OpenIndiana/oi-userland/commit/dc5ca37fa5a576ad9bd2d6b3d24a05ea217203c3))
- Update to 142.0 ([554e5ec](https://github.com/OpenIndiana/oi-userland/commit/554e5ec252cfded16313b73ab6528ef1a8ef655f))
- Update to 143.0 ([ae19587](https://github.com/OpenIndiana/oi-userland/commit/ae19587537c18350fcde8aaccce42235874653e3))
- Update to 143.0.1 ([128eeaa](https://github.com/OpenIndiana/oi-userland/commit/128eeaa90da23ebc298f48c0a752b4fa12aeb4d8))
- Update to 144.0.1 ([96280ff](https://github.com/OpenIndiana/oi-userland/commit/96280ffe7e16393965c70ceae152779c6472ec42))

### Tiff

- Update to 4.7.1; drop 32 bit apps ([781fcc4](https://github.com/OpenIndiana/oi-userland/commit/781fcc4636b4adc7c565056b5075b0f812ab8193))

### Tig

- Update to 2.6.0 ([6875233](https://github.com/OpenIndiana/oi-userland/commit/6875233314ce0abd5ce7da541debe7cde0822d01))

### Time-slider

- Update runtime dependencies to follow package renames ([bc217f3](https://github.com/OpenIndiana/oi-userland/commit/bc217f3b4f2670e4449b1590e3346360819989e8))

### Tk

- Update to 8.6.17 ([d25d389](https://github.com/OpenIndiana/oi-userland/commit/d25d3897ddc9fee7cdc426ffccc0d3cc87b71e1b))

### Tomcat-11

- Update to 11.0.8 ([6a27b97](https://github.com/OpenIndiana/oi-userland/commit/6a27b97b2fbd9fddacfc18f45e01da6cf6bce534))
- Update to 11.0.9 ([78ff1ef](https://github.com/OpenIndiana/oi-userland/commit/78ff1efffd1a054fbf4a341e7ce391cfda43bee4))
- Update to 11.0.10 ([3504571](https://github.com/OpenIndiana/oi-userland/commit/350457108cad598e5a25094eb3955948146cd533))
- Update to 11.0.11 ([78b4b8e](https://github.com/OpenIndiana/oi-userland/commit/78b4b8e630609ba7030910622593762d4073361a))
- Update to 11.0.12 ([8d2ed40](https://github.com/OpenIndiana/oi-userland/commit/8d2ed40289558817c9850680ee20fbbe55a46438))
- Update to 11.0.13 ([0fe40b7](https://github.com/OpenIndiana/oi-userland/commit/0fe40b700d973ff7a3a86b02795d66ce51e38763))

### Tools/license-detector

- Use https in MPL-2.0 header ([377bbeb](https://github.com/OpenIndiana/oi-userland/commit/377bbebb59ce29f20ca498a69c3f635cb26bed60))

### Tools/perl-integrate-module

- Cleanup bundled CPAN ([12b21f6](https://github.com/OpenIndiana/oi-userland/commit/12b21f645e8d0534709d0693eb6ee53bcb9c9804))
- Consult bundled CPAN for upgrade-only check ([5754d16](https://github.com/OpenIndiana/oi-userland/commit/5754d16bd2045ef053edd49ca18ac6a43ac3568a))
- Fix bundled CPAN version check ([a4fda71](https://github.com/OpenIndiana/oi-userland/commit/a4fda71316dc09ae95c1e7ced7e721bd5c71bac5))
- Bootstrap support ([504fb94](https://github.com/OpenIndiana/oi-userland/commit/504fb94a2e64261b4419aaed47619d1100f3736e))
- Sanitize # in summary ([18ca5d1](https://github.com/OpenIndiana/oi-userland/commit/18ca5d179198880a9e26e793cb8ea373ff7f84e9))
- Force to skip DLC server ([112577c](https://github.com/OpenIndiana/oi-userland/commit/112577c885d550fa68895ee5d6351e6ea130d63b))

### Tools/python-integrate-project

- Disable all pytest plugins for test style discovery ([205d054](https://github.com/OpenIndiana/oi-userland/commit/205d054aba6a2cc5ff7448f03a829c6966ec0fa8))
- Detect CARGO_VENDOR ([8b71d7f](https://github.com/OpenIndiana/oi-userland/commit/8b71d7f9f8f7f88dd008700a144e2a04901d8c03))
- Force to skip DLC server ([9f8d2b9](https://github.com/OpenIndiana/oi-userland/commit/9f8d2b94ae2bddba6f2954341c1a9d1d4ab007c6))
- Unittest test style detection ([db51b3f](https://github.com/OpenIndiana/oi-userland/commit/db51b3f39b9464bc8847a3743a2049365bba54e2))
- Use oldest supported Python version for test style detection ([06f6b58](https://github.com/OpenIndiana/oi-userland/commit/06f6b58d0ba7a8580619d836f4e1c53aaa7180f3))

### Tooltalk

- Add empty package to satisfy SunRay install requirements ([5ff2d82](https://github.com/OpenIndiana/oi-userland/commit/5ff2d82c67271fcd28d99472e82290c83ce2b979))

### Tor

- Rebuild for library/libevent2 ([96bc601](https://github.com/OpenIndiana/oi-userland/commit/96bc601aa0d4cbee627d3c4f937753e452a981a4))
- Update to version 0.4.8.17 ([d7c97e4](https://github.com/OpenIndiana/oi-userland/commit/d7c97e4dfb712eb79759a0561ab6315cd81d40ce))
- Update to version 0.4.8.18 ([77c635a](https://github.com/OpenIndiana/oi-userland/commit/77c635a7e23fb01f2a4cf297f43befc734c7f8ce))
- Update to version 0.4.8.19 ([0b56e0e](https://github.com/OpenIndiana/oi-userland/commit/0b56e0e84713c9593d17db9b373f2caca94fd0f0))

### Traella-prolog

- Update to 2.83.24 ([e877827](https://github.com/OpenIndiana/oi-userland/commit/e877827980b8b5823f132208a3289e57625af157))

### Transforms

- Remove support for Python 2 ([ec9ccc7](https://github.com/OpenIndiana/oi-userland/commit/ec9ccc75ecb5be68de46d3c90f1b3951b7016f4c))

### Transforms/defaults

- Drop vendor mediator priority for Python ([90dd6da](https://github.com/OpenIndiana/oi-userland/commit/90dd6da49bea3046c9c153860b047dea10dd9b42))

### Trealla

- Add missing dependency on vim ([eb7f72b](https://github.com/OpenIndiana/oi-userland/commit/eb7f72b6499ca525b9eee59b2e7966034dcba3bd))
- Update to 2.82.28 ([8d22602](https://github.com/OpenIndiana/oi-userland/commit/8d226026ec8b8371609893e063d509c2e9676bb7))
- Update to 2.82.29 ([b30a54e](https://github.com/OpenIndiana/oi-userland/commit/b30a54e8adce0d640bb5a28530f79d1c9976f1a3))
- Update to 2.82.32 ([47ed260](https://github.com/OpenIndiana/oi-userland/commit/47ed2602f164a7b80c415292a4a20020e3779ff5))
- Update to 2.82.33 ([d0afe68](https://github.com/OpenIndiana/oi-userland/commit/d0afe68cb7371d1b14292e313198867ff263a1ad))
- Update to 2.82.40 ([d55f841](https://github.com/OpenIndiana/oi-userland/commit/d55f841d6d36f41dc454a3ac84faebc6c351c503))
- Update to 2.83.10 ([c8cc34c](https://github.com/OpenIndiana/oi-userland/commit/c8cc34c0a2c19c2680c24d36c23219701bde8267))
- Update to 2.83.11 ([f16043f](https://github.com/OpenIndiana/oi-userland/commit/f16043f385854d7bf4440b387738e90c3db6636c))
- Update to 2.83.13 ([4c5be4e](https://github.com/OpenIndiana/oi-userland/commit/4c5be4ec1d40f19864521e03982dc5028e02988f))
- Update to 2.83.15 ([3ba0ba7](https://github.com/OpenIndiana/oi-userland/commit/3ba0ba72906ad27e66dd2e6af0ff592bf8cc6aa0))
- Update to 2.83.17 ([0b76dbd](https://github.com/OpenIndiana/oi-userland/commit/0b76dbdf0130ff37f0a184d6a21746b7fd02c95b))

### Trealla-prolog

- Update to 2.83.21 ([ae83a1a](https://github.com/OpenIndiana/oi-userland/commit/ae83a1a59778f69117f8ef23c801c4a7e2a96afe))
- Update to 2.84.1 ([9ee43f3](https://github.com/OpenIndiana/oi-userland/commit/9ee43f3e8caff43421e5215957a4d389fa9df1f9))

### Tree-sitter

- Update to 0.25.6; enhance test results ([4bbb6e6](https://github.com/OpenIndiana/oi-userland/commit/4bbb6e6875300d13db6e4291608c2243910214d9))
- Update to 0.25.7 ([604fca6](https://github.com/OpenIndiana/oi-userland/commit/604fca61ccd3da5c8f96363d9be547c11c0e9370))
- Update to 0.25.8 ([d22c152](https://github.com/OpenIndiana/oi-userland/commit/d22c152aa3ffc7962067147fc8711b28040bc728))
- Update to 0.25.9 ([c4f2922](https://github.com/OpenIndiana/oi-userland/commit/c4f2922989ae4659e66010ebe2d0bd2b82957153))
- Update to 0.25.10 ([7304181](https://github.com/OpenIndiana/oi-userland/commit/7304181b640d5e0faecbd4ea1d3e34dfcd76c932))

### Trousers

- Move 32 bit support to separate package ([76da123](https://github.com/OpenIndiana/oi-userland/commit/76da123d53e0ad88268b23385efe14cb08afffb0))

### Unbound

- Fix for library/libevent2 ([3aeefe5](https://github.com/OpenIndiana/oi-userland/commit/3aeefe5d5f9ded06471c5a5320407b1d920299b6))
- Update to 1.23.1 ([d013457](https://github.com/OpenIndiana/oi-userland/commit/d0134573447e622d08c03d9ed7e37d89faa54603))
- Update to 1.24.0 ([49636d2](https://github.com/OpenIndiana/oi-userland/commit/49636d2efe59383a50cf1c135064449be49d07fe))
- Update to 1.24.1 ([3ef25e1](https://github.com/OpenIndiana/oi-userland/commit/3ef25e121f50caf02cc4fc2fa8ac3f8e1c8757b2))

### Unixodbc

- Fix build with gcc-14 ([1c82985](https://github.com/OpenIndiana/oi-userland/commit/1c82985baa1d9d2227266e880eb8389bea6320d9))
- Update to 2.3.13 ([066fb72](https://github.com/OpenIndiana/oi-userland/commit/066fb72e643a0d6fd35ab3db821a04ed4f058b54))
- Update to 2.3.14 ([bcf3053](https://github.com/OpenIndiana/oi-userland/commit/bcf30538cedc63af866ab432e48275e4f04fe4e9))

### Unrar

- Update to 7.1.7 ([a92200c](https://github.com/OpenIndiana/oi-userland/commit/a92200cc410a964e56ee366d0a06ad4c758a573c))
- Update to 7.1.8 ([dfa186b](https://github.com/OpenIndiana/oi-userland/commit/dfa186b591bf73d87cb958e8740d9e08a55c9f69))
- Update to 7.1.10 ([8acdc7a](https://github.com/OpenIndiana/oi-userland/commit/8acdc7aa0fb851971ec1e6644a74d7643a334093))

### Util-macros

- Update to 1.20.2 ([d36f31e](https://github.com/OpenIndiana/oi-userland/commit/d36f31e7d0ce15a624332a14c4d83c517ace0984))

### Valgrind

- Update to 3.26.0 ([aaa8f65](https://github.com/OpenIndiana/oi-userland/commit/aaa8f65b6481b7e7bdd8ffa574a5048b5c06166d))

### Vim

- Update to 9.1.1435 ([6c55e0b](https://github.com/OpenIndiana/oi-userland/commit/6c55e0b014c74f1a17ee91c2a8aa3bbaadc48562))
- Update to 9.1.1457 ([d5115f6](https://github.com/OpenIndiana/oi-userland/commit/d5115f6a2a671a74c76bf23f34f3c450683f6b77))
- Update to 9.1.1473 ([4e51b48](https://github.com/OpenIndiana/oi-userland/commit/4e51b48fac6967d6a3f3a5fdef15a3506ee67fc3))
- Update to 9.1.1481 ([6cbc353](https://github.com/OpenIndiana/oi-userland/commit/6cbc353778d2268b37c305e30e31ce004fc8be75))
- Update to 9.1.1492 ([01329c4](https://github.com/OpenIndiana/oi-userland/commit/01329c49baf3ab50b5ec8dac6a3bab5e7ee7d0ee))
- Update to 9.1.1500 ([1f07d1a](https://github.com/OpenIndiana/oi-userland/commit/1f07d1a0982800d419e331a90241aa52ed333fd6))
- Update to 9.1.1533 ([32e80b0](https://github.com/OpenIndiana/oi-userland/commit/32e80b08a9b5460aa2b6bbda43806d5df8a243c8))
- Update to 9.1.1538 ([a961310](https://github.com/OpenIndiana/oi-userland/commit/a9613105e1659acf20c4c31d32af474b823c267e))
- Update to 9.1.1550 ([b036900](https://github.com/OpenIndiana/oi-userland/commit/b036900b5517cff055df76f25753566b6efd4df2))
- Update to 9.1.1566 ([6ed5438](https://github.com/OpenIndiana/oi-userland/commit/6ed5438a908ab05e61f5765acf6e7cc9713dff47))
- Update to 9.1.1591 ([a96aed7](https://github.com/OpenIndiana/oi-userland/commit/a96aed745128cd9621f9a382b8f1b71dc64ee863))
- Update to 9.1.1623 ([78505c8](https://github.com/OpenIndiana/oi-userland/commit/78505c8b6d18b4cbe1417313d91cc883bffbaf67))
- Update to 9.1.1634 ([36552be](https://github.com/OpenIndiana/oi-userland/commit/36552be88b2ff2be05b24127caaf0f0880401d2f))
- Update to 9.1.1652 ([c9ae8c2](https://github.com/OpenIndiana/oi-userland/commit/c9ae8c24581252cc01e2376e26761ff1a74d6966))
- Update to 9.1.1663 ([0b3e7cd](https://github.com/OpenIndiana/oi-userland/commit/0b3e7cdb0c4fb890078f09a16a0a2317cf837f15))
- Update to 9.1.1678 ([a63704b](https://github.com/OpenIndiana/oi-userland/commit/a63704b39bd8eb4cc3d6c7fc0149fa3046151d91))
- Update to 9.1.1700 ([5b6da46](https://github.com/OpenIndiana/oi-userland/commit/5b6da46a637b9d3c89352185a94f4446b16f0e45))
- Update to 9.1.1706 ([4ca7516](https://github.com/OpenIndiana/oi-userland/commit/4ca751607935cdb8883f5a46c2458b4731b3703b))
- Update to 9.1.1713 ([1ad8ba3](https://github.com/OpenIndiana/oi-userland/commit/1ad8ba3df6d7f0bc9ef142626c23a4c3a30f5a00))
- Update to 9.1.1723 ([7717cc8](https://github.com/OpenIndiana/oi-userland/commit/7717cc8bc41de24e3d048ac58520010068b1aed2))
- Update to 9.1.1730 ([2f7acca](https://github.com/OpenIndiana/oi-userland/commit/2f7accae22408a259574d999fb15e2d02d48fdb5))
- Update to 9.1.1738 ([9348b62](https://github.com/OpenIndiana/oi-userland/commit/9348b62cc9f9ab82291d140d67004edf3d039dc9))
- Update to 9.1.1752 ([898cfc2](https://github.com/OpenIndiana/oi-userland/commit/898cfc29a401f6b143c7c4f92ab73bbd5d53f140))
- Update to 9.1.1754 ([e25d727](https://github.com/OpenIndiana/oi-userland/commit/e25d7279230906a4098a34a19fba41dcfb20b6e1))
- Update to 9.1.1766 ([18c09fb](https://github.com/OpenIndiana/oi-userland/commit/18c09fb3a430c98e5cfa505c4ba513028cf67657))
- Update to 9.1.1782 ([d1789d8](https://github.com/OpenIndiana/oi-userland/commit/d1789d86dd12c8887e0bfcf5d5f6b466908a65d5))
- Update to 9.1.1813 ([b5967ec](https://github.com/OpenIndiana/oi-userland/commit/b5967ec59695f9cef49016bda60098ddb3dc87bf))
- Update to 9.1.1815 ([c205a50](https://github.com/OpenIndiana/oi-userland/commit/c205a50d087d89959a74498a014fa8a36ba1ad8d))
- Update to 9.1.1825 ([f5bf0ef](https://github.com/OpenIndiana/oi-userland/commit/f5bf0eff71be1bf814406f4bde378264831894ff))
- Update to 9.1.1831 ([5dc181d](https://github.com/OpenIndiana/oi-userland/commit/5dc181d4f92a11026430bd98d1e871e7ea601374))
- Update to 9.1.1837 ([a63c60d](https://github.com/OpenIndiana/oi-userland/commit/a63c60d466d317d082a56140ff06712000cc1e82))
- Update to 9.1.1846 ([73fabbc](https://github.com/OpenIndiana/oi-userland/commit/73fabbcb6f284529de98f52b4625b6fecc90eb14))
- Update to 9.1.1854 ([ba35940](https://github.com/OpenIndiana/oi-userland/commit/ba3594018d9bfc5b6ca8d92e4b69d7f1831b9015))
- Update to 9.1.1864 ([b76da4e](https://github.com/OpenIndiana/oi-userland/commit/b76da4ebb6b1e2502e5c1717aff7e3f6d722a58c))
- Update to 9.1.1868 ([b86a1d3](https://github.com/OpenIndiana/oi-userland/commit/b86a1d37c25f772d8fa049be64fc3f7f2868022d))
- Update to 9.1.1971 ([c071bf1](https://github.com/OpenIndiana/oi-userland/commit/c071bf1a333e5ae8c92b602cfab2e0e492c57f35))

### Virtualbox

- Update 7.1.10 ([d5d1168](https://github.com/OpenIndiana/oi-userland/commit/d5d1168e6ad2b0277d36924d326d7a36645f246d))
- Enable VBoxSDL ([0d70c05](https://github.com/OpenIndiana/oi-userland/commit/0d70c058839dd080bea392b3cdbb0cb8822b3da2))

### Vte-291

- Update to 0.80.3 ([c07a03a](https://github.com/OpenIndiana/oi-userland/commit/c07a03a9ad54908eacc27959759173cbbb0b6d93))
- Update to 0.82.0 ([b326536](https://github.com/OpenIndiana/oi-userland/commit/b32653621c12210d10df94d088fcaea1dc545963))
- Update to 0.82.1 ([03c5b3b](https://github.com/OpenIndiana/oi-userland/commit/03c5b3b58ced8d9ac35d55c5e1b16654dc942145))

### W3m

- Update to 0.5.5 ([d4efc11](https://github.com/OpenIndiana/oi-userland/commit/d4efc11fa15040be94ead7b97d148f8d3948bdaf))

### Webkitgtk

- Update to 2.48.5; remove unused or unneeded build options ([810c684](https://github.com/OpenIndiana/oi-userland/commit/810c6847b5945f5eae9bb96adaebd0a8b756ccbb))
- Update to 2.48.6 ([8d479c9](https://github.com/OpenIndiana/oi-userland/commit/8d479c96b3e8c573ddf5d31362bbcbf97e2ea2e2))
- Update to 2.48.7 ([188b173](https://github.com/OpenIndiana/oi-userland/commit/188b1735c11558dc015494a7e178c5035101af1c))

### Weechat

- Update to 4.7.0 ([11dcc33](https://github.com/OpenIndiana/oi-userland/commit/11dcc335835b5e58f66b6b7d318746673aa23fe2))
- Update to 4.7.1 ([f20bfdd](https://github.com/OpenIndiana/oi-userland/commit/f20bfdd8643002e6eeee3a4e6fa010560d09e506))

### Wireshark

- Update to 4.4.8 ([e6b45b9](https://github.com/OpenIndiana/oi-userland/commit/e6b45b9567dcc930bd9bd9844fca8c8dcd8524d2))
- Update to 4.4.9 ([28f1dea](https://github.com/OpenIndiana/oi-userland/commit/28f1dea510604c7c3a9851f7c5507e690d3b87da))
- Update to 4.6.0 ([2c7f36d](https://github.com/OpenIndiana/oi-userland/commit/2c7f36d0644a6d53f3c0e9510cda5436a6d63b70))

### Wmname

- Fix build; drop 32 bit ([118bd48](https://github.com/OpenIndiana/oi-userland/commit/118bd48a97c6cbe8b1219690e2b600b1abc63572))

### X11

- Readd empty compatibility package SUNWxwplt ([60ccaa9](https://github.com/OpenIndiana/oi-userland/commit/60ccaa95a287c34a07ba74f2372f308e2c558ff2)), Co-authored-by:Aurelien Larcher <aurelien.larcher@gmail.com>

### Xcb-util-cursor

- Update to 0.1.6 ([09309a0](https://github.com/OpenIndiana/oi-userland/commit/09309a01146d15192427018df4b33e1655708952))

### Xdpyinfo

- Update to 1.4.0 ([8453ffb](https://github.com/OpenIndiana/oi-userland/commit/8453ffb359c7eb8a95447eee3318f0d3e7a4df36))

### Xdriinfo

- Update to 1.0.8 ([09503bf](https://github.com/OpenIndiana/oi-userland/commit/09503bfda58e4407c28c99a695644b4d67d9186b))

### Xeyes

- Update to 1.3.1 ([6509269](https://github.com/OpenIndiana/oi-userland/commit/6509269fdc3152d6eeb0c87cd6f12d0ffd9ef4a5))

### Xfsinfo

- Update to 1.0.8 ([21e8a09](https://github.com/OpenIndiana/oi-userland/commit/21e8a0936d4057c3d5b9b548d8a8b2f23591dba5))

### Xgamma

- Update to 1.0.8 ([5778381](https://github.com/OpenIndiana/oi-userland/commit/577838109962cd0d542fec0ba7628dc07127c8b6))

### Xgc

- Update to 1.0.7 ([b5a9c9c](https://github.com/OpenIndiana/oi-userland/commit/b5a9c9c0a7e5dd51614e5b8480b79775dab1a889))

### Xterm

- Update to 400 ([c96edc7](https://github.com/OpenIndiana/oi-userland/commit/c96edc7bc16e9f3165bab2a9389ca51899b475b4))
- Update to 401 ([86e752d](https://github.com/OpenIndiana/oi-userland/commit/86e752deb806609f61a592e8e24b33af685ca364))
- Update to 402 ([f00f76d](https://github.com/OpenIndiana/oi-userland/commit/f00f76dcf2c091d4df2438e78e21e1649183ecc5))
- Update to 403 ([1f6650d](https://github.com/OpenIndiana/oi-userland/commit/1f6650d88d1192b1b2c89aec88bdfdb4e00aea1a))

### Zabbix-server

- Update to 7.2.7 / add SPARC support ([a85ef12](https://github.com/OpenIndiana/oi-userland/commit/a85ef12450dcd9c5e6f78d13e66e00ad17133b07))
