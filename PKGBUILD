# Dhivehi-fonts

# Maintainer: Ali Aafee
pkgname=divehi-fonts
pkgver=0.1
pkgrel=3
pkgdesc="Divehi(thaana) fonts for archlinux"
arch=('any')
url="https://launchpad.net/~mvishah/+archive/ttf-dhivehi-fonts"
license=('unknown')
groups=()
depends=('xorg-fonts-encodings' 'xorg-font-utils' 'fontconfig')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=divehi-fonts.install
changelog=
source=("https://launchpad.net/~mvishah/+archive/ttf-dhivehi-fonts/+files/ttf-thaana-fonts_1.0-1_i386.deb")
noextract=()
md5sums=('81c32e76e82b17fc61f90da20b40569d')

build() {
  cd "$srcdir"
  tar -xvzf data.tar.gz
  mkdir -p ${pkgdir}/usr/share/fonts/divehi-fonts
  cp ${srcdir}/usr/share/fonts/truetype/ttf-thaana-fonts/* ${pkgdir}/usr/share/fonts/divehi-fonts/
  
}
