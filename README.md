# Gaming on Linux Guide (Fedora Linux)

## Step 1: Upgrade System 
```
[Username@fedora ~]$ sudo dnf update

```
## Step 2: Download GPU Drivers

- [Download GPU Driver Guide (NVIDIA)](https://www.linuxcapable.com/how-to-install-the-latest-nvidia-graphic-drivers-on-fedora-35-gnome-41/)
- [Download GPU Driver Guide (AMD)](https://www.amd.com/en/support/kb/faq/amdgpu-installation)


## Step 3: Download and Configure LibreGaming using pip

```
[Username@fedora ~]$ pip3 install LibreGaming   # Installs LibreGaming 
[Username@Fedora ~]$ LibreGaming -h   # This shows what would you download 
usage: LibreGaming <arguments>

Install Gaming Packages with ease

options:
  -h, --help         show this help message and exit
  -g, --gaming       Install Gaming Packages
  -b, --basic        Install Basic Gaming Packages
  -ath, --athenaeum  Install Athenaeum Launcher
  -o, --overlays     Install Mangohud & Goverlay
  -p, --proton       Install/Update ProtonGE(You must run Steam once before
                     installing ProtonGE)
  -l, --list         List installed ProtonGE Releases
  -t TAG, --tag TAG  Install a specific ProtonGE Release
  -r TAG, --rem TAG  remove a specific ProtonGE Release
  --releases         List ProtonGE Releases
  --tui              use a Terminal User Interface to install Packages
  --heroic           Install Heroic Launcher
  --lutris           Install lutris Launcher
  --itch             Install itch.io Launcher
  --stl              Install Steam Tinker Launch(For Arch Linux only)

GPLv3 - Repo : https://github.com/Ahmed-Al-Balochi/LibreGaming.git
[Username@fedora ~]$ LibreGaming -g   # Downloading all gaming packages
```

## Step 4: Configure wine
```
[Username@fedora ~]$ winecfg # Then change Windows version to Windows 10 press apply and quit
```

## Step 5: Configure Steam

Steam --> Settings --> Steam Play ---> Advanced ---> Enable Steam Play for all other titles
### I'm using Proton Experimental becouse using more stable than original proton and can see play game on [Discord](https://discord.com/download)

Library --> Proton Experimental --> Properties --> Betas --> bleeding-edge - lastest and untested dxvk, vkd3d-proton and wine changes; backup your prefixes before using

### If your game not optimize for all try [ProtonGECustom](https://github.com/GloriousEggroll/proton-ge-custom/tags)

### You can look is your game compatible with linux [ProtonDB](https://www.protondb.com/)

## Step 6: Download your game and enjoy!!
