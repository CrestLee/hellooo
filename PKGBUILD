# Maintainer: Crest Lee <crest@selefra.io>
pkgname=hellooo
pkgver=0.1
pkgrel=1
pkgdesc='hellooo'
arch=('any')
url=''
license=('GPL3')
depends=('bash')
source=("https://gitlab.com/eathtespagheti/$pkgname/raw/v$pkgver/$pkgname")
md5sums=('f24a67449d5650cae67b9273cff62358')

package() {
	cd $srcdir
	mkdir -p $pkgdir/usr/bin
	install screen-sleep $pkgdir/usr/bin/$pkgname
}
