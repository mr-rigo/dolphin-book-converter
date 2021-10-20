pkgname='dolphin-book-converter'
pkgver=0.2.3
pkgrel=1
pkgdesc="Converter of images and books for dolphin"
arch=(any)
url='https://github.com/mr-rigo/dolphin-book-converter'
depends=(img2pdf python zip xdg-utils pdf2djvu poppler imagemagick djvulibre texlive-core pdf2svg ghostscript xonsh)
package() {
    install -d $pkgdir/usr/bin/
    install -t $pkgdir/usr/bin/ -m775 $startdir/bin/*
    install -d $pkgdir/usr/share/kservices5
    install -t $pkgdir/usr/share/kservices5/ -m644 $startdir/kservices5/*
}