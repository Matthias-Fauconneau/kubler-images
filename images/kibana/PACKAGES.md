### kubler/kibana:20200430

Built: Thu 07 May 2020 10:59:46 AM CEST
Image Size: 409MB

#### Installed
Package | USE Flags
--------|----------
app-admin/su-exec-0.2 | `-static`
www-apps/kibana-bin-7.6.2 | `-x-pack`
#### Inherited
Package | USE Flags
--------|----------
**FROM kubler/nodejs** |
dev-libs/icu-65.1-r1 | `-debug -doc -examples -static-libs`
dev-libs/libuv-1.35.0 | `-static-libs`
net-dns/c-ares-1.15.0 | `-static-libs`
net-libs/http-parser-2.9.3 | `-static-libs`
net-libs/nghttp2-1.40.0 | `threads -cxx -debug -hpack-tools -jemalloc -libressl -static-libs -test -utils -xml`
net-libs/nodejs-12.16.1 | `icu npm snapshot ssl system-ssl -debug -doc -inspector -systemtap -test`
sys-apps/yarn-1.22.4 | ``
**FROM kubler/openssl** |
app-misc/ca-certificates-20190110.3.43 | `-cacert`
app-misc/c_rehash-1.7-r1 | ``
dev-libs/openssl-1.1.1g | `asm zlib -bindist -rfc3779 -sctp -sslv3 -static-libs -test -tls-heartbeat -vanilla`
sys-apps/debianutils-4.9.1 | `installkernel -static`
sys-kernel/installkernel-gentoo-2 | ``
sys-libs/zlib-1.2.11-r2 | `(split-usr) -minizip -static-libs`
**FROM kubler/s6** |
app-admin/entr-4.4 | `-test`
dev-lang/execline-2.5.3.0 | `-static -static-libs`
dev-libs/skalibs-2.9.1.0 | `-doc -ipv6 -static-libs`
sys-apps/s6-2.9.0.1 | `-static -static-libs`
**FROM kubler/glibc** |
dev-libs/libunistring-0.9.10 | `-doc -static-libs`
net-dns/libidn2-2.3.0 | `-static-libs`
sys-apps/gentoo-functions-0.12 | ``
sys-libs/glibc-2.30-r8 | `(crypt) multiarch (ssp) (static-libs) -audit -caps (-cet) -compile-locales -custom-cflags -doc -gd -headers-only (-multilib) -nscd -profile (-selinux) -suid -systemtap -test (-vanilla)`
sys-libs/timezone-data-2019c | `nls -leaps-timezone`
**FROM kubler/busybox** |
sys-apps/busybox-1.31.1-r2 | `make-symlinks static -debug -ipv6 -livecd -math -mdev -pam -savedconfig (-selinux) -sep-usr -syslog -systemd`
sys-apps/sed-4.7 | `static -acl -nls (-selinux)`
#### Purged
- [x] Headers
- [x] Static Libs
