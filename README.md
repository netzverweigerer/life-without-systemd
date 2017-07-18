# life-without-systemd
How to survive the systemd hype (without using systemd, obviously)


## Lists of systemd-free Linux distributions
There are actually a lot of systemd-free linux distributions, and there's a good chance you can live on your desktop and server systems without it.

### Distrowatch
To search distrowatch for distributions without systemd, you can try:

http://distrowatch.com/search.php?ostype=All&category=All&origin=All&basedon=All&notbasedon=None&desktop=All&architecture=All&package=All&rolling=All&isosize=All&netinstall=All&language=All&defaultinit=Not+systemd&status=Active#simple

Please note that this also lists init-hybrids, e.g. Linux Mint, which is shown there as "Init: systemd,SysV", as well as non-linux operating systems, such as various BSDs.

### without-systemd.org
without-systemd.org has a Wiki that lists various options of sane systemd-free distributions:

http://without-systemd.org/wiki/index.php/Main_Page


## Personal choices
There are various distributions that I prefer to choose currently when having to decide for some sane systemd-free distribution:

### Void Linux
https://www.voidlinux.eu/
A rolling-release distribution built around the XBPS binary package manager. Uses [runit](http://smarden.org/runit/) as an init scheme.

### Devuan GNU+Linux
https://devuan.org/
A Debian fork without systemd.




