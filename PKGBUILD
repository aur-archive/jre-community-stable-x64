# Maintainer: Oleg Chiruhin <hedin.pr AT gmail DOT com>
# Category: devel

pkgname=jre-community-stable-x64
shortname=jre
pkgver="6u26"
pkgrel="1"
pkgdesc="64bit version of J2SE Runtime Environment from stable community repo"
arch=("i686" "x86_64")
depends=(glibc)
makedepends=()
url="http://java.sun.com/javase/"
license="custom"
source=(ftp://ftp.archlinux.org/community/os/x86_64/$shortname-$pkgver-$pkgrel-x86_64.pkg.tar.xz)
md5sums=('eba3f1ae8364e791f74c4b05903d6a06')

build() {
 mkdir -p $pkgdir/opt/java-community-stable-x64
 cp -R $srcdir/opt/java/jre $pkgdir/opt/java-community-stable-x64
}
