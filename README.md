# Maaki's pipa-alarm Pacman Repository

Repository of Arch Linux packages for pipa.

## Installation

Add the following code snippet to your `/etc/pacman.conf`:

```conf
[pipa-alarm]
SigLevel = Optional
Server = https://raw.github.com/maakiopus/pipa-alarm/master/repo
```

Then, run `sudo pacman -Sy` to update repository.
