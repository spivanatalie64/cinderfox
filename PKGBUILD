pkgname=cinderfox
pkgver=1.0.0
pkgrel=1
pkgdesc='A branded Firefox wrapper for AcreetionOS'
arch=('any')
url='https://acreetionos.org'
license=('custom')
depends=('bash' 'firefox')
source=()
noextract=()
sha256sums=()

package() {
  install -Dm755 "$startdir/bin/cinderfox" "$pkgdir/usr/bin/cinderfox"
  install -Dm644 "$startdir/share/cinderfox/start.html" "$pkgdir/usr/share/cinderfox/start.html"
  install -Dm644 "$startdir/share/cinderfox/profile/user.js" "$pkgdir/usr/share/cinderfox/profile/user.js"
  install -Dm644 "$startdir/share/cinderfox/profile/chrome/userChrome.css" "$pkgdir/usr/share/cinderfox/profile/chrome/userChrome.css"
  install -Dm644 "$startdir/share/cinderfox/profile/chrome/userContent.css" "$pkgdir/usr/share/cinderfox/profile/chrome/userContent.css"
  install -Dm644 "$startdir/share/applications/cinderfox.desktop" "$pkgdir/usr/share/applications/cinderfox.desktop"
  install -Dm644 "$startdir/share/icons/hicolor/scalable/apps/cinderfox.svg" "$pkgdir/usr/share/icons/hicolor/scalable/apps/cinderfox.svg"
}
