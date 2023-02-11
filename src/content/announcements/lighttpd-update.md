---
title: "lighttpd 1.4.64 update"
description: "lighttpd 1.4.64 update"
pubDate: "2022-06-08"
---

With merge of PR #8390 we updated lighttpd to the latest version 1.4.64 which removed support for the deprecated option **server.set-v6only**.
This option’s default was **true** in upstream since our update to version 1.4.46 but we **disabled** it with a patch to prevent breaking existing lighttpd installations.
The new update doesn’t allow to disable it anymore, meaning we break existing installs which used **server.set-v6only**.
If you’re affected, please change your lighttpd configuration to use different sockets for ipv4 and ipv6 connections.
