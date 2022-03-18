# Gaming on Linux Guide (Fedora Linux)

## Step 1: Upgrade System 
```
[Username@fedora ~]$ sudo dnf update

```
## Step 2: Download GPU Drivers

- [Download GPU Driver Guide](https://www.linuxcapable.com/how-to-install-the-latest-nvidia-graphic-drivers-on-fedora-35-gnome-41/)


## Step 3: Download and Configure LibreGaming using pip

```
[Username@fedora ~]$ pip3 install LibreGaming   #installs LibreGaming 
[Username@Fedora ~]$ LibreGaming -h   #This shows what would you download 
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
[Username@fedora ~]$ LibreGaming -g   #downloading all gaming packages
```

