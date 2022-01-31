# arch-repo

This Arch repo is used to seed custom Arch iso's.

Add following lines to `/etc/pacman.conf`

```
[tereius]
SigLevel = Optional TrustAll
Server = https://tereius.github.io/arch-repo/$arch/
```

Then run

```
pacman -Sy
```
