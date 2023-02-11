---
title: "Package Respositories"
layout: ../layouts/Page.astro
---

# Packages

Package management on OpenIndiana relies on pkg(5), the Image Packaging System (IPS).

## OpenIndiana repositories
Packages are delivered by one main publisher named ‘openindiana.org’ together with one additional publisher ‘encumbered’ for multimedia codecs and other components which may be subject to software patents.

**Hipster**
|PUBLISHER|	URI|
|-|-|
|openindiana.org|	http://pkg.openindiana.org/hipster|
|hipster-encumbered|	http://pkg.openindiana.org/hipster-encumbered|

Hipster packages are built from oi-userland: introductory steps for adding or fixing a package can be found in the Docs.

## Third-party repositories
**SFE**
The Spec Files Extra project (SFE) kindly provides additional software for illumos distributions including OpenIndiana: multimedia software, web stack, LibreOffice 4.

|PUBLISHER|	URI|
|-|-|
|localhostoih|	http://sfe.opencsw.org/localhostoih|

## Quick start
To list existing publishers on your system:

```
pkg publisher
```

To add a publisher to your system (requires privileges):

```
pkg set-publisher -g http://path/to/repo_uri publisher
```


