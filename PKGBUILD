# Maintainer: Vivek Pal <31vivekpal@gmail.com>

pkgname="shastrarepo"
pkgver=0.1.2
pkgrel=2
pkgdesc='ShastraOS Repo'
url="https://github.com/shastra-os/shastrarepo"
arch=('any')
license=('GPL3')

source=($pkgname)

sha512sums=('b0bafda28ac84ad225c77e9331eaa9f266969cfced972907bea2f02862c80376899b15a7c36d901326d65040ae4d09ac10e4b3ad5e63bf3c247b4de397e71be5')

package() {
	install -Dm644 ${pkgname}  ${pkgdir}/etc/pacman.d/${pkgname}
}
