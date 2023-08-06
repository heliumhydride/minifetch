# minifetch
set the env variable COLOR for color (ex: COLOR="1;34" minifetch)
this script requires:
  - coreutils/busybox  : id, hostname, tr, tty, seq, uname...
  - procps-ng/busybox  : uptime
  - util-linux/busybox : lscpu, nproc
  - pciutils/busybox   : lspci (for gpu)
  - grep/busybox       : grep
optionally, this script use (if installed):
  - xrandr : screen res

# compatibility:
  - bash          : full
  - zsh           : no cpu with cores?
  - busybox       : full?
  - busybox-w32   : things like lscpu, lspci, xrandr don't work
