# Maintainer: Marcus Weinhold <marcus at weinhold dot org>
pkgname=mkinitcpio-encrypt-multi
pkgver=0.2
pkgrel=1
pkgdesc='mkinitcpio hook to decrypt multiple LUKS-devices'
arch=('any')
url="http://www.archlinux.org/"
license=('GPL')
depends=('mkinitcpio' 'cryptsetup')
source=("encrypt-multi_hook" "encrypt-multi_install")

package() {
        install -D -o0 -g0 -m644 ${srcdir}/encrypt-multi_hook ${pkgdir}/usr/lib/initcpio/hooks/encrypt-multi
        install -D -o0 -g0 -m644 ${srcdir}/encrypt-multi_install ${pkgdir}/usr/lib/initcpio/install/encrypt-multi
}
sha256sums=('2b3f9893af2e4bb906ed6ab5c38dd7014e2750d6e8e154648f33dc55d90a5959'
            '8b7f3648dfcd69e01a61d3ca5ac5f7fbf391200c03f23589611c8a71a59dc198')
