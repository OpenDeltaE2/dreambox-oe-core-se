## Build environment based on OpenPLi-homebuild(develop branch). 

Update 29-07-2026
---

https://github.com/OpenPLi/openpli-oe-core/commits/develop<br>
https://github.com/Hains<br>

Thanks to OpenPLi & Hains .

In comparison to OpenPLi this repository has:<br>
-Submodules bitbake, openembedded-core and meta-openembedded from scarthgap branch,<br>
-GCC 13.4.0<br>
-Glibc 2.39<br>
-GStreamer 1.26.8<br>
-Python 2.7.18<br>
-OpenSSL 3.2.6<br>
-Busybox 1.36.1<br>
-Linux OS 3.2/3.4/3.14

******************************************************

Tested with Ubuntu 18.04.06 & 22.04<br><br>

1. Dependencies:
```
sudo apt install dialog autoconf automake bison bzip2 cvs diffstat \
flex g++ gawk gcc gettext git git-lfs gzip help2man ncurses-bin lib32ncurses-dev \
libc6-dev libtool make texinfo patch perl pkg-config subversion tar texi2html \
zlib1g-dev chrpath libxml2-utils lz4 xsltproc libglib2.0-dev python-setuptools \
libc6-i386 genromfs guile-2.2-libs quilt zstd

