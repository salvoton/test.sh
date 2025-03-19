# Maintainer: Furkan Bekçi (salvoton) <furo@tuta.io>
pkgname=test.sh
pkgver=1.0.0
pkgrel=1
pkgdesc="to test something"
arch=("any")
url="https://github.com/salvoton/test.sh"
license=("GPL")
depends=("bash" "skim" "paru")
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/$pkgver.tar.gz")
sha256sums=("SKIP")

package() {
	install -Dm775 "$srcdir/$pkgname-$pkgver/parus" "$pkgdir/usr/bin/parus"
}
