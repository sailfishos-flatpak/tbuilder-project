# TBuilder project

This project is archived as we have OBS functioning again. Use instructions from the [main repository](https://github.com/sailfishos-flatpak/main).

_Original README below:_

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
