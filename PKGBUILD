# Maintainer: Agnésa Théo <seigneurfuo@gmail.com>

pkgname=logitech-m560-buttons-support
pkgver=1.1
pkgrel=8
pkgdesc="Support des boutons suivant et précédent pour la souris Logitech M560"
arch=('x86_64')
url=""
license=('NONE')
groups=("★ seigneurfuo: Paquets persos")
depends=("xbindkeys")
makedepends=()
optdepends=()
source=("${pkgname}.conf" "${pkgname}.desktop")
md5sums=('e14c9b776945c8a3261e1f936e49f6f4'
         '501e11d02edc551d804097bfd7df53d9')

package() 
{	
	install -Dm644 "${pkgname}.conf" "${pkgdir}/etc/xbindkeys/${pkgname}.conf"
	install -Dm644 "${pkgname}.desktop" "${pkgdir}/etc/xdg/autostart/${pkgname}.desktop"
}
