pkgname=2gis-gornoaltaysk
pkgver=36
pkgrel=1
pkgdesc="Map of Gorny Altai for 2GIS, April 2013"
arch=('i686' 'x86_64')
url="http://altai.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.2.2')
source=("http://download.2gis.ru/arhives/2GISData_Gornoaltaysk-36.orig.zip")
md5sums=('fa89425e03c41bf986a8c9b5bd38886c')

package() {
  install -D -m 644 ${srcdir}/2gis/3.0/Data_Gorny Altai.dgdat "${pkgdir}/opt/2gis/city.dgdat" || return 1
  install -D -m 644 ${srcdir}/2gis/3.0/Plugins/DGisLan/Gorny Altai.dglf "${pkgdir}/opt/2gis/Plugins/DGisLan/Gorny Altai.dglf" || return 1
}
