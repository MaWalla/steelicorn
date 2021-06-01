# Steelicorn Plymouth Theme

I drew this the other day

The script is borrowed from [here](https://www.deviantart.com/love2spooge/art/PAW-OS-X-Plymouth-Theme-173974024).

## Installation

(Note that all the commands below must be run as root/with sudo. Its also assumed that plymouth is installed already.)

Copy the `steelicorn/` folder in this repo to `/usr/share/plymouth/themes/`, then change the line `Theme=...` to `Theme=steelicorn` in `/etc/plymouth/plymouthd.conf`

Finally regenerate your initramfs (example for Arch Linux: `mkinitcpio -P`).
