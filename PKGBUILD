# Maintainer: Steffen Schneider <stes94@ymail.com>
pkgname=BACKPY
pkgver=1.0
pkgrel=1
pkgdesc="A simply backup utility written in python"
arch=('x86_64')
url=""
license=('Simplified BSD')
groups=()
depends=(python2)
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
noextract=()
md5sums=() #generate with 'makepkg -g'

build() {
  mkdir -p ${pkgdir}/usr/bin
  cp backpy.py ${pkgdir}/usr/bin/backpy
  cp backpy.man ${pkgdir}/usr/share/man/man1/backpy.1
}