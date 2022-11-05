# dotfiles

----------------------------------------------------------------------

<img src="https://raw.githubusercontent.com/khaos152/dotfiles/main/preview.png" alt="img" align="right" width="550px">


| Program           | Name                                                                                   |
|-------------------|----------------------------------------------------------------------------------------|
| 🪟 **WM**         | [Bspwm](https://github.com/baskerville/bspwm)                                          |
| 💾 **OS**         | [Arch Linux](https://archlinux.org)                                                    |
| 🖥 **DM**          | [LightDM](https://github.com/canonical/lightdm)                                        |
| 🐚 **Shell**      | [ZSH](https://github.com/zsh-users/zsh)                                                |
| 🛑 **Icons**      | [Zafiro](https://github.com/zayronxio/Zafiro-icons)                                    |
| 🚦 **Theme**      | [Nordic](https://github.com/EliverLara/Nordic)                                         |
| 🍫 **Bar**        | [Polybar](https://github.com/polybar/polybar)                                          |
| 🖼 **Background** | [Pexels](https://www.pexels.com/collections/best-of-wallpapers-ja61psj/)               |
| ⌨ **Terminal**    | [Kitty](https://github.com/kovidgoyal/kitty)                                           |
| ✨ **Compositor** | [Picom](https://github.com/yshui/picom)                                                |
| 🌐 **Browser**    | [Qutebrowser](https://github.com/qutebrowser/qutebrowser)                              |
| 🌐 **Browser 2**  | [Librewolf](https://gitlab.com/librewolf-community)                                    |

----------------------------------------------------------------------

# additional packages


fonts
`pacman -S noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra gsfonts ttf-nerd-fonts-symbols-common ttf-nerd-fonts-symbols-2048-em-mono`

dm & wm
`pacman -S sxhkd lightdm-gtk-greeter light-locker feh rofi unclutter lxappearance pcmanfm gvfs gvfs-smb`


consooming
`pacman -S mpv streamlink yt-dlp`


shell
`pacman -S zsh-completions pacman -S zsh-theme-powerlevel10k`


for notebooks
`pacman -S netctl dialog dhcpcd dhcp wpa_supplicant light`
`yay -S rofi-wifi-menu-git`


# printing
`pacman -S --needed --noconfirm cups extra/system-config-printer simple-scan`
`systemctl enable cups`
`pacman -S --needed --noconfirm hplip python-pyqt5 python-qtpy`


# KVM
`pacman -S --needed --noconfirm qemu virt-manager virt-viewer dnsmasq vde2 bridge-utils openbsd-netcat libguestfs qemu-block-gluster`
`systemctl enable libvirtd`
`systemctl start libvirtd`
