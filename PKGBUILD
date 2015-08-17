# Maintainer: GordonGR <ntheo1979@gmail.com>
pkgname=ttf-asea
pkgver=4.14
pkgrel=2
pkgdesc="An étude on the dominant typeface of greek typography: Didot, Απλά, Monotype Greek 90… (part of Unicode Fonts for Ancient Scripts)."
arch=('any')
url="http://users.teilar.gr/~g1951d/"
license=('custom')
depends=('fontconfig' 'xorg-font-utils')
source=("http://users.teilar.gr/~g1951d/Asea.zip" "LICENSE")
md5sums=('c09440cf95377c716f9a96de0a1b4dd5'
         '312d2effc6b57a205f1a0a48aa0345b8')
install=$pkgname.install

package()
{
install -m 644 -D $srcdir/AseaB.ttf $pkgdir/usr/share/fonts/TTF/AseaB.ttf
install -m 644 -D $srcdir/AseaI.ttf $pkgdir/usr/share/fonts/TTF/AseaI.ttf
install -m 644 -D $srcdir/AseaJ.ttf $pkgdir/usr/share/fonts/TTF/AseaJ.ttf
install -m 644 -D $srcdir/AseaR.ttf $pkgdir/usr/share/fonts/TTF/AseaR.ttf
install -m 644 -D $srcdir/AseaB_hint.ttf $pkgdir/usr/share/fonts/TTF/AseaB_hint.ttf
install -m 644 -D $srcdir/AseaI_hint.ttf $pkgdir/usr/share/fonts/TTF/AseaI_hint.ttf
install -m 644 -D $srcdir/AseaJ_hint.ttf $pkgdir/usr/share/fonts/TTF/AseaJ_hint.ttf
install -m 644 -D $srcdir/AseaR_hint.ttf $pkgdir/usr/share/fonts/TTF/AseaR_hint.ttf
install -m 644 -D $srcdir/LICENSE $pkgdir/usr/share/licenses/$pkgname/LICENSE
}

