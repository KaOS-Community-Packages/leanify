pkgname=leanify
pkgver=0.4.2
pkgrel=1
pkgdesc="lightweight lossless file minifier/optimizer"
arch=('x86_64')
url="https://github.com/JayXon/Leanify"
license=('MIT')
source=(https://github.com/JayXon/Leanify/releases/download/v${pkgver}/leanify_linux64.tgz)
md5sums=('8e57cfb818d14b942e6fda4b5d224b31')

package() {
 
  cd "$pkgdir"
    install -dm 755 "$pkgdir/usr/bin/"
    install -m755 "$srcdir/leanify" "$pkgdir/usr/bin/"

}