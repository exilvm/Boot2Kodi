# Boot2Kodi

Run Kodi on a headless Debian.

#### Installation of Kodi into Ubuntu Server:

#### Tested in:
  - [x] Debian GNU/Linux 11 (bullseye) (Proxmox host) (headless)

Please let me know if you have tested this and if something failed.

Shell script to install Kodi on a Ubuntu Server and at boot, go straight to Kodi.

The following instructions are based on the lastest version of Ubuntu.

#### What you need to do:

1. Install Debian (headless).
2. Make sure git is installed or install git: `sudo apt install git -y`.
3. Clone this repo and execute the installation: `git clone https://github.com/exilvm/Boot2Kodi.git && cd Boot2Kodi && sudo sh ./install.sh`.
6. Reboot.
