# TBuilder project

This allows to build Flatpak support for Sailfish using TBuilder.

Compiled packages available at https://sailfishos-flatpak.s3-website.pl-waw.scw.cloud/

To use, add repository

```
zypper ar https://sailfishos-flatpak.s3-website.pl-waw.scw.cloud/SailfishOS-4.0.1.48-aarch64 flatpak
```

install

```
zypper ref
zypper in flatpak-runner
```

and reboot the device. Follow instructions in main [README](https://github.com/sailfishos-flatpak/main)
on how to use.
