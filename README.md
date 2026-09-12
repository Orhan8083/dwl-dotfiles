# dwl-dotfiles
This is my build of the dwl, dynamic window manager for Wayland. It is made <br>
for personal use and it is deployed here for archival purpouses. I am not the <br>
creator nor a devoloper working at the dwl project, so they deserve the credit. <br>
Here is their original repository over at [Codeberg.](https://codeberg.org/dwl/dwl) The build also contains [slstatus.](https://tools.suckless.org/slstatus/) <br>
a tool developed by the [Suckless team,](https://tools.suckless.org/slstatus/) the developers of the original dynamic window <br>
manager, [dwm.](https://dwm.suckless.org/)) <br>
<br>
<br> 
<h2> Dependencies: </h2>
<hr></hr>

In order for dwl to function propperly, you need <br>
to install the dependencies listed bellow. <br>
<br>
```
- wayland <br>
- wayland-protocols <br>
- wlroots_0_19 <br>
- foot <br>
- base-devel <br>
- git <br>
- wmenu <br>
- wl-clipboard <br>
- grim <br>
- slurp <br>
- swaybg <br>
- brightnessctl <br>
- alsa-utils <br>
- nerd-fonts* <br>

```
<br>
* (Technically, only the ttf-jetbrains-mono-nerd package would <br>
   also do fine but I prefer to install the whole font library) <br>
<br>
If you are on Debian (or any other distro that uses the apt package manager like:Ubuntu, Mint, Pop etc.) <br>
```sudo apt install wayland wayland-protocols wlroots foot build-essential git wmenu wl-clipboard grim slurp swaybg brightnessctl alsa-utils fonts-nerd-fonts ```
<br>
If you are on Arch (or any other distro that uses pacman package manager like: Artix* Manjaro, Endevour, Garuda etc.) <br>
``` sudo pacman -S wayland wayland-protocols wlroots foot base-devel git wmenu wl-clipboard grim slurp swaybg brightnessctl alsa-utils nerd-fonts ```

* Note: Artix users must enable Arch packages in their pacman.conf file. If you do not pursue to do that, you can build
the missing packages from source.

IF you are on Fedora (or any other distro that uses the dnf package manager like: Red Hat Enterprise, CentOS, Alpine Linux etc.)
```sudo dnf install wayland wayland-protocols wlroots foot @development-tools git wmenu wl-clipboard grim slurp swaybg brightnessctl alsa-utils nerd-fonts ```


<h2> Installation: </h2>
<hr>


<h2> Patches: </h2>
<hr>
The build contains 


<h2> Default Keybinds: </h2>
<hr>
