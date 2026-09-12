# dwl-dotfiles
This is my build of the dwl, dynamic window manager for Wayland. It is made
for personal use and it is deployed here for archival purpouses. I am not the 
creator nor a devoloper working at the dwl project, so they deserve the credit. 
Here is their original repository over at [Codeberg.](https://codeberg.org/dwl/dwl) . The build also contains [slstatus.](https://tools.suckless.org/slstatus/)
a tool developed by the [Suckless team,](https://tools.suckless.org/slstatus/) the developers of the original dynamic window
manager, [dwm.]([https://tools.suckless.org/slstatus/](https://dwm.suckless.org/))

<h1> Dependencies: </h1>
- wayland
- wayland-protocols
- wlroots_0_19
- foot
- base-devel
- git
- wmenu
- wl-clipboard
- grim
- slurp
- swaybg
- brightnessctl
- alsa-utils
- nerd-fonts* 

* (Technically, only the ttf-jetbrains-mono-nerd package would
   also do fine but I prefer to install the whole font library)

If you are on Debian (or any other distro that uses the apt package manager like:Ubuntu, Mint, Pop etc.)
sudo apt install 

If you are on Arch (or any other distro that uses pacman package manager like: Artix* Manjaro, Endevour, Garuda etc.)
sudo pacman -S 

* Note: Artix users must enable Arch packages in their pacman.conf file. If you do not pursue to do that, you can build
the missing packages from source.

IF you are on Fedora (or any other distro that uses the dnf package manager like: Red Hat Enterprise, CentOS, Alpine Linux etc.)
sudo dnf install 


<h2> Patches: </h2>
The
