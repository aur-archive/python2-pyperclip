# Maintainer: Jim Bridgewater <jwbwater at gmail dot com>
# Contributor: delta48 <dark.magician.48[at]gmail[dot]com> 


pkgname=python2-pyperclip
_pkgname=pyperclip
pkgver=1.5.9
pkgrel=1
pkgdesc="A cross-platform clipboard module for Python 2."
arch=('any')
url="http://coffeeghost.net/2010/10/09/pyperclip-a-cross-platform-clipboard-module-for-python/"
license=('BSD')
depends=('python2' 'xclip')
makedepends=('python2-setuptools')
source=("https://pypi.python.org/packages/source/p/$_pkgname/$_pkgname-$pkgver.zip")
md5sums=('aae99dd8d46e45197ac013350f691591')

package() {
  cd $srcdir/$_pkgname-$pkgver
  python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
