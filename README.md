### Packages required for Shastra from Shastra Repository

- brave-bin and onlyoffice-bin also inculded in db

##### To add other packages
- Clone the repo
- Open repo in your Linux Terminal (Arch recommended)
- Run this command to add packages to database

```sh
repo-add ./shastrarepo.db.tar.gz package-name.pkg.tar.zst
```

These pkgs are shipped from AUR repo.

To get packages install ['yay'](https://github.com/Jguer/yay) in your arch linux.
Yay is Yet Another Yogurt - An AUR Helper
To install AUR pkgs run
```sh
yay -S package-name
```
###### Refer [AUR](https://aur.archlinux.org/packages) to get pkgs names.

##### To get the package in .pkg.tar.zst format
- Go to your home directory and find hidden file '.cache'
- Turn on your hidden files
<img src="https://i.ibb.co/NC8jVcZ/hiddenfiles.png" width="200px">

- Find 'yay' folder
- Open your package folder
- Copy the package to shastra-repo
- You will also find PKGBUILD, copy it to [PKGBUILDS github repository](https://github.com/Shastra-OS/PKGBUILDS)
