# Maintainer: Elohim <jbdsjunior@live.com>

pkgname=partitionmanager_lang
_pkgname=partitionmanager-lang
pkgver=1.0.3_2.6
_pkgver=1.0.3-2.6
pkgrel=1
pkgdesc="Latest openSUSE Factory version of lang partitionmanager."
arch=('any')
url=http://www.opensuse.org/
license=('custom')
depends=(partitionmanager-svn)
groups=(kde)
source=("http://download.opensuse.org/repositories/KDE:/Extra/openSUSE_Factory/noarch/$_pkgname-$_pkgver.noarch.rpm")
md5sums=('eee029de500ef33f6292ca44cb44efb5')

package() {
  cd $srcdir
#  mkdir -p $pkgdir/usr/share/{apps/desktoptheme,licenses/$pkgname}
  cp -R ./usr $pkgdir/
}