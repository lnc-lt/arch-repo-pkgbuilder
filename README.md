### A PKGBUILD builder as a Docker image

This Docker image is a base Arch Linux with a custom builduser, a few dependencies and config tweaks
so it's ready out-of-the box to build Arch Linux packages and add them to a custom repository.
Its primary use is for the [lnclt packages](https://github.com/lnc-lt/arch-lnclt-pkgbuilds) but
it can easily be tweaked for any other automated package building - be it AUR packages or your own 
custom meta packages.
