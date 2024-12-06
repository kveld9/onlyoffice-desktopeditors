# onlyoffice-desktopeditors
Template file for OnlyOffice for Void Linux distribution.


## Installation steps.
1. Download this repo as a zip.
2. Extract the content.
3. Rename the folder ```onlyoffice-desktopeditors-main``` to ```onlyoffice-desktopeditors```.
4. Move the folder to ```void-packages/srcpkgs```.
5. Execute ```./xbps-src pkg -j$(nproc) onlyoffice-desktopeditors```. # remember to stay in the void-packages directory.
6. Install the package by executing ```xi onlyoffice-desktopeditors```. # remember to have installed "xtools" package for "xi" command.


## Credits.
- [OnlyOffice](https://github.com/ONLYOFFICE/DesktopEditors)
- [template from which I was inspired.](https://www.reddit.com/r/voidlinux/comments/mm108y/onlyofficedesktopeditors_template_for_void_linux/?rdt=55366)
- [xbps-src](https://github.com/void-linux/void-packages)
