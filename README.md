# deb-service-template
simple service template for deb package

### usage
buid dpkg package: `dpkg -b deb-service-template`
extract dpkg package: `dpkg -x deb-service-template.deb deb-service-template`
install package: `dpkg -i deb-service-template.deb`

### linting
apt install lintian
lintian deb-service-template.deb
