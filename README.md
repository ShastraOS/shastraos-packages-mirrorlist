#### Packages required for Shastra from Shastra Repository

- Brave bin also inculded in db

##### To add other packages
- Clone the repo
- Open repo in your Linux Terminal (Arch recommended)
- Run this command to add other pkgs

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

##### To get the pkg in .pkg.tar.zst format
- Go to your home directory and find hidden file '.yay'
- To turn on your hidden files 
<img src="https://i.ibb.co/NC8jVcZ/hiddenfiles.png" width="200px">
- Open your pkg folder
- Copy the pkg to shastra-repo
- You will also find PKGBUILD, copy it to PKGBUILD github repository
