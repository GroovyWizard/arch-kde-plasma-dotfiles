# Arch Linux Kde Plasma Dotfiles/Setup <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fseeklogo.com%2Fimages%2FA%2Farchlinux-logo-1159446C2C-seeklogo.com.png&f=1&nofb=1&ipt=f350c973f4a3ea3dd6c40b7bc5ef65d0cf23017e5d3333ad8cdde1a31c5cfabe&ipo=images" width="50" height="50" />


My personal dotfiles and config for KDE plasma with Arch Linux. Since i finally felt that i hit the stability nirvana of Arch, after some hard distro hopping in the last week because new nvidia drivers borked my system (RTX 3050 is not playing very well with new drivers) i want to keep this here for future reference when i decide to do some fresh arch installation again or something breaks. Anyway i just cant use anything besides arch anymore (after 1 year as my daily driver).

### Screenshot: 
![](https://github.com/GroovyWizard/arch-kde-plasma-dotfiles/blob/main/screenshots/2022-10-08_00-17.png)

## General Stuff:
- Neofetch (Fancy terminal thing)
- Neovim / Vim (Editor)
- Kitty (Terminal Emulator)
- Zsh (Shell)
- Oh My Zsh (Zsh framework) 
- POWERLEVEL10K (Zsh Theme)
- Monero GUI (Monero Wallet)
- Lutris 

## System Stuff:
- BTRFs (File System for snapshots)
- Timeshift (For managing snapshots) 
- Grub-btrfs (Display Snapshots on grub)
- Timeshift-AutoSnap (Automatic snapshots on pacman updates)
- Yay (AUR helper and wrapper for pacman)
- Downgrade (To downgrade packages based on ALA when nvidia drivers just die after some update) 
- LTS Kernel 
- NVIDIA-DKMS 
- NetworkManager-iwd (NM with iwd backend because wpa_supplicant just doesnt work well with my WI-FI adapter)
- Luxtorpeda -> https://github.com/luxtorpeda-dev/luxtorpeda (for running old games natively on steam without proton)

## Kde Configs and Scripts:
- Global Theme -> https://github.com/vinceliuice/WhiteSur-kde
- Kvantum Theme -> https://github.com/vinceliuice/WhiteSur-kde
- Splash Screen -> https://store.kde.org/p/1498608/ 
- Icons -> https://store.kde.org/p/1359276/

## Some useful guides:
 - BTRFS snapshots configuration -> https://www.lorenzobettini.it/2022/07/timeshift-and-grub-btrfs-in-linux-arch/
 - Downgrading for Arch, when something borks your system with no workaround -> https://github.com/archlinux-downgrade/downgrade
