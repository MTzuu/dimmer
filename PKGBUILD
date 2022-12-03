# Maintainer: Matthias Antony <matthias.antony@tum.de>
pkgname=dimmer
pkgver=0.1
pkgrel=1
pkgdesc="Bash script to control brightness of a notebook screen"
arch=('any')
url=""
license=('GPL')
depends=('bash')
source=("brightness_up"
        "brightness_down")
noextract=()
md5sums=("SKIP"
         "SKIP")

package() {
  local installopts='--mode 0755 -D --target-directory'
  install $installopts "$pkgdir/usr/bin" "brightness_up"
  install $installopts "$pkgdir/usr/bin" "brightness_down"
}
