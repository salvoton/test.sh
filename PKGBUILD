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
sha256sums=("ce1f341f59a8881f897088a22daf67932174f946b2c274fb842693e62e301994")

package() {
	install -Dm775 "$srcdir/$pkgname-$pkgver/test.sh" "$pkgdir/usr/bin/test.sh"
}
