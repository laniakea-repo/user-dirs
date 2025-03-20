# Maintainer: Aspen Schneider <rendezvous71@outlook.com>

pkgname=user-dirs
pkgver=0.1
pkgrel=2
pkgdesc="Keep user directories like ~/Downloads and ~/Music in English"
url="https://www.laniakeaos.com"
arch=(any)
license=(MIT)
depends=(xdg-user-dirs)
install=user-dirs.install
options=(!emptydirs)
source=(user-dirs-update.service)
sha256sums=(
            'fc275abc9ba49138d9a35c3374aeafee6e12e3203bcfe7f65841c5d4ff1d5c3e')

package() {
  install -Dt "$pkgdir/usr/lib/systemd/user" -m644 user-dirs-update.service
}

