# Maintainer: Marcus Weinhold <marcus at weinhold dot org>
pkgname=mkinitcpio-encrypt-multi
pkgver=0.3
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
sha256sums=('0db1bdabeb2cd85804386fb8167febc6f533736a93387fadf02351b82f924313'
            '8b7f3648dfcd69e01a61d3ca5ac5f7fbf391200c03f23589611c8a71a59dc198')
