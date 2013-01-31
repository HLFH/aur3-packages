# Contributor: Stefan Tatschner <stefan.tatschner@gmail.com>
# Maintainer: Stefan Tatschner <stefan.tatschner@gmail.com>

_pkgname=gitflow
pkgname=gitflow-avh
pkgver=1.4.2
pkgrel=1
pkgdesc="Extend git with Vincent Driessen's branching model. The AVH Edition adds more functionality to the existing git-flow."
arch=('any')
url='https://github.com/petervanderdoes/gitflow/'
license=('BSD', 'LGPL')
depends=('git')
source=("https://github.com/petervanderdoes/gitflow/archive/${pkgver}.tar.gz")
md5sums=('3631d5a5616c957730527481f6a31462')
changelog="changelog"

package(){
   cd "$srcdir/$_pkgname-$pkgver"
   make prefix="$pkgdir/usr" install
}
