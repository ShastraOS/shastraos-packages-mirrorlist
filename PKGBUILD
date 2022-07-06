# Maintainer: Vivek Pal <31vivekpal@gmail.com>

pkgname="shastrarepo"
pkgver=0.1
pkgrel=1
pkgdesc='ShastraOS Repo'
url="https://github.com/shastra-os/shastrarepo"
arch=('any')
license=('GPL3')

source=($pkgname)

sha512sums=('53d134c6857dd405750a3fbae9feb6d4376b9e91f1c6b8236df35eeb02be3d0618722aa6ff790e02a42c0e5aa38325214376827c2a2e9894b012055224b8804e')

package() {
	install -Dm644 ${pkgname}  ${pkgdir}/etc/pacman.d/${pkgname}
}
