# Maintainer: BlueTheDuck <hello@perezv.ar>
pkgname="usbblaster-udev"
pkgver=1
pkgrel=1
epoch=
pkgdesc=""
arch=('any')
url=""
license=('unknown')
groups=()
depends=('systemd')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=install
changelog=
source=("51-usbblaster.rules")
noextract=()
sha256sums=("3b94497be15709cdaf3c80083e7f6ff044da8707499292c7f890091952291f6e")
validpgpkeys=()

package() {
	# cd "$pkgname-$pkgver" make DESTDIR="$pkgdir/" install
	install -D --mode=644 "51-usbblaster.rules" "$pkgdir/etc/udev/rules.d/51-usbblaster.rules"
}
