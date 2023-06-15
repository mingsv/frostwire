# Maintainer: Manifest0
# Contributor: Dimitris Kiziridis <ragouel at outlook dot com>
# Contributor: Frederic Bezies <fredbezies at gmail dot com>
# Contributor: liberodark
# Modified by Rafael from azul

pkgname=frostwire
pkgver=6.12.0
pkgrel=1
buildn=build-318
pkgdesc='Cloud Downloader, BitTorrent Client and Media Player'
arch=('x86_64')
url='http://www.frostwire.com'
urldown='https://github.com/frostwire/frostwire/releases/download'
license=('GPL')
depends=('hicolor-icon-theme' 'java-environment' 'bash' 'zlib')
optdepends=('mplayer: Media playback support')
source=(${urldown}/${pkgname}-desktop-${pkgver}-${buildn}/${pkgname}-${pkgver}.amd64.deb)
sha256sums=('093fa48978aab168ff72d399e7bfa141bf5e7c491938be1940061726d323f20d')


 
package() {
  tar xvf data.tar.zst -C "${pkgdir}"
}
