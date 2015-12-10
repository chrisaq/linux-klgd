# HOWTO

**Clone the repo**

git clone https://github.com/chrisaq/linux-klgd.git

`cd linux-klgd`

**Build package**

`makepkg -s`

Press 'm' when asked about adding klgd during build

`sudo pacman -U linux-klgd-4.3-1-x86_64.pkg.tar.xz`

**Used the default kernel image package as base:**

https://projects.archlinux.org/svntogit/packages.git/tree/trunk?h=packages/linux

**If build fails because of missing public key, add this:**

gpg --keyserver pgp.mit.edu --recv-keys 79BE3E4300411886

