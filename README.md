# Maaki's pipa-alarm Pacman Repository

Repository of Arch Linux packages for pipa.

## Installation

Add the following code snippet to your `/etc/pacman.conf`:

```conf
[pipa-alarm]
SigLevel = Optional
Server = https://maakiopus.github.io/pipa-alarm/repo/
```

Then, run `sudo pacman -Sy` to update repository.
