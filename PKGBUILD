# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=alphaos-ux
pkgver=20140908
pkgrel=1
pkgdesc="This provides to Alpha OS UX."
arch=('i686' 'x86_64')
url="https://github.com/g97iulio1609/alphaos-ux"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('git')
replaces=('gnome-shell')
_repanthalver=0.3.1
provides=('alphaos-ux')
_fileurl=https://github.com/g97iulio1609/alphaos-ux/blob/master/alphaosux.tar.gz
source=("${_fileurl}")
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/themes
    cp -R usr/share/themes "${pkgdir}"/usr/share/

    mkdir -p "${pkgdir}"/usr/share/gnome-shell
    cp -R usr/share/gnome-shell "${pkgdir}"/usr/share/

}
