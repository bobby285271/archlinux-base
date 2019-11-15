# Arch Linux 原 base 软件包组备份

## 使用
```
# pacman -S wget nano
# wget https://raw.githubusercontent.com/bobby285271/archlinux-base/master/pkglist
# nano pkglist #可选，可剔除自己不想装的软件包。
# pacman -Syu $(cat pkglist)
# rm pkglist
```
