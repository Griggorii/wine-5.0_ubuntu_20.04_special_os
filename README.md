# wine-5.0_ubuntu_20.04_special_os
wine-5.0 , ubuntu 20.04

special os https://github.com/Griggorii/Linux_OS20.04_V4_X64_By_Griggorii.iso_ubuntu_focal_fossa-linux-image-kernel-5.9.3

Download wine-5.0 https://github.com/Griggorii/wine-5.0_ubuntu_20.04_special_os/releases/download/wine-5.0/wine.tar.xz

install 

$ sudo tar xvpf wine.tar.xz -C /

special os x32  check notepad

$ sudo rm -rf /usr/share/doc/libc6/NEWS.gz /usr/share/doc/libc6/changelog.Debian.gz && sudo apt update && sudo apt --reinstall install libc6:i386 libcrypt1:i386 libfreetype6:i386 libgcc-s1:i386 libidn2-0:i386 libpng16-16:i386 libunistring2:i386 zlib1g:i386 lib32z1 lib32z1-dev zlib1g zlib1g-dev libc6:i386 libidn2-0:i386 libunistring2:i386 -y

$ sudo apt --reinstall install libfreetype6:i386 libxext6:i386 -y

$ wine-stable notepad

check

$ wine regedit

Audio support install

$ sudo rm -rf rm -rf /usr/share/doc/libfaudio0/changelog.Debian.gz /usr/share/doc/libfaudio0/copyright && sudo apt update && sudo apt --reinstall install i965-va-driver:i386 intel-media-va-driver:i386 libaom0:i386 libavcodec58:i386 libavutil56:i386 libblkid1:i386 libcairo-gobject2:i386 libcairo2:i386 libcodec2-0.9:i386 libdatrie1:i386 libdrm-intel1:i386 libdrm2:i386 libexpat1:i386 libfontconfig1:i386 libfribidi0:i386 libgdk-pixbuf2.0-0:i386 libglib2.0-0:i386 libgomp1:i386 libgraphite2-3:i386 libgsm1:i386 libharfbuzz0b:i386 libicu66:i386 libigdgmm11:i386 libjbig0:i386 libjpeg-turbo8:i386 libjpeg8:i386 libmount1:i386 libmp3lame0:i386 libnuma1:i386 libopenjp2-7:i386 libopus0:i386 libpango-1.0-0:i386 libpangocairo-1.0-0:i386 libpangoft2-1.0-0:i386 libpciaccess0:i386 libpcre2-8-0:i386 libpcre3:i386 libpixman-1-0:i386 librsvg2-2:i386 librsvg2-common:i386 libselinux1:i386 libshine3:i386 libsnappy1v5:i386 libsoxr0:i386 libspeex1:i386 libstb0:i386 libstdc++6:i386 libswresample3:i386 libthai0:i386 libtheora0:i386 libtiff5:i386 libtwolame0:i386 libuuid1:i386 libva-drm2:i386 libva-x11-2:i386 libva2:i386 libvdpau1:i386 libvpx6:i386 libwavpack1:i386 libwebp6:i386 libwebpmux3:i386 libx264-155:i386 libx265-179:i386 libxcb-render0:i386 libxcb-shm0:i386 libxml2:i386 libxvidcore4:i386 libzstd1:i386 libzvbi0:i386 ocl-icd-libopencl1:i386 libfaudio0:i386 libgdk-pixbuf2.0-0 libgdk-pixbuf2.0-common

support libmpg

$ sudo apt install libmpg123-0:i386

x64 check notepad

$ wine notepad

and alternative command

$ wine64-stable notepad

$ winefile-stable

$ winemaker-stable

$ wineconsole-stable

Setting + download dll

$ winetricks

$ env WINEPREFIX=~/.wine WINEARCH=win64

run explorer nautilus and nemo , thunar folder check enter :z

~/.wine/dosdevices/z:

$ env WINEPREFIX=~/.wine/dosdevices/z: WINEARCH=win64

uninstall

$ sudo rm -rf /usr/lib/x86_64-linux-gnu/wine /usr/lib/i386-linux-gnu/wine /usr/lib/wine /usr/bin/wine /usr/bin/wine64-stable /usr/bin/wineboot-stable /usr/bin/winebuild-stable /usr/bin/winecfg-stable /usr/bin/wineconsole-stable /usr/bin/winecpp-stable /usr/bin/winedbg-stable /usr/bin/winedump-stable /usr/bin/winefile-stable /usr/bin/winegcc-stable /usr/bin/wineg++-stable /usr/bin/winemaker-stable /usr/bin/winepath-stable /usr/bin/wineserver-stable /usr/bin/wine-stable /usr/bin/winetricks /etc/alternatives/wine /usr/share/man/man1/wine.1.gz /usr/share/man/man1/wine64.1.gz /usr/share/man/man1/wine64-stable.1.gz /usr/share/man/man1/wineboot.1 /usr/share/man/man1/wineboot.1.gz /usr/share/man/man1/wineboot-stable.1.gz /usr/share/man/man1/winebuild.1 /usr/share/man/man1/winebuild.1.gz /usr/share/man/man1/winebuild-stable.1.gz /usr/share/man/man1/winecfg.1 /usr/share/man/man1/winecfg.1.gz /usr/share/man/man1/winecfg-stable.1.gz /usr/share/man/man1/wineconsole.1 /usr/share/man/man1/wineconsole.1.gz /usr/share/man/man1/wineconsole-stable.1.gz /usr/share/man/man1/winecpp.1 /usr/share/man/man1/winecpp.1.gz /usr/share/man/man1/winecpp-stable.1.gz /usr/share/man/man1/winedbg.1 /usr/share/man/man1/winedbg.1.gz /usr/share/man/man1/winedbg-stable.1.gz /usr/share/man/man1/winedump.1 /usr/share/man/man1/winedump.1.gz /usr/share/man/man1/winedump-stable.1.gz /usr/share/man/man1/winefile.1 /usr/share/man/man1/winefile.1.gz /usr/share/man/man1/winefile-stable.1.gz /usr/share/man/man1/wineg++.1 /usr/share/man/man1/wineg++.1.gz /usr/share/man/man1/winegcc.1 /usr/share/man/man1/winegcc.1.gz /usr/share/man/man1/winegcc-stable.1.gz /usr/share/man/man1/wineg++-stable.1.gz /usr/share/man/man1/winemaker.1 /usr/share/man/man1/winemaker.1.gz /usr/share/man/man1/winemaker-stable.1.gz /usr/share/man/man1/winemine.1 /usr/share/man/man1/winepath.1 /usr/share/man/man1/winepath.1.gz /usr/share/man/man1/winepath-stable.1.gz /usr/share/man/man1/wineserver.1 /usr/share/man/man1/wineserver.1.gz /usr/share/man/man1/wineserver-stable.1.gz /usr/share/man/man1/wine-stable.1.gz /usr/share/man/man1/winetricks.1.gz

________________________________________________________________________________________________________________________________________________________________

All command wine module + compilators

wine 

wine64-stable 

wineboot-stable 

winebuild-stable 

winecfg-stable 

wineconsole-stable 

winecpp-stable 

winedbg-stable 

winedump-stable 

winefile-stable 

winegcc-stable 

wineg++-stable 

winemaker-stable 

winepath-stable 

wineserver-stable 

wine-stable winetricks

_________________________________________________________________________________________________________________________________________________________________

quantum rebuild wine build wine-5.0 download inpack to /tmp cd /tmp/wine-5.0

./configure --with-gnutls --without-hal --without-mingw --without-netapi --disable-tests --enable-maintainer-mode --libdir=/usr/lib/x86_64-linux-gnu/wine --bindir=/usr/lib/wine --mandir=/usr/share/man --includedir=/usr/include/wine --datarootdir=/usr/share/wine CFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security -fcommon -Wno-shift-overflow -Wno-unused-function -Wno-deprecated-declarations CPPFLAGS=-Wdate-time CXXFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security FCFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong FFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong GCJFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong LDFLAGS=-Wl,-Bsymbolic-functions -Wl,-z,relro -Wl,-z,now -Wl,-rpath,/usr/lib/x86_64-linux-gnu/wine OBJCFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security OBJCXXFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security --without-oss --enable-win64

x32

./configure --with-gnutls --without-hal --without-mingw --without-netapi --disable-tests --enable-maintainer-mode --libdir=/usr/lib/x86_64-linux-gnu/wine --bindir=/usr/lib/wine --mandir=/usr/share/man --includedir=/usr/include/wine --datarootdir=/usr/share/wine CFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security -fcommon -Wno-shift-overflow -Wno-unused-function -Wno-deprecated-declarations CPPFLAGS=-Wdate-time CXXFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security FCFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong FFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong GCJFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong LDFLAGS=-Wl,-Bsymbolic-functions -Wl,-z,relro -Wl,-z,now -Wl,-rpath,/usr/lib/x86_64-linux-gnu/wine OBJCFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security OBJCXXFLAGS=-g -O2 -fdebug-prefix-map=/tmp/wine-5.0=. -fstack-protector-strong -Wformat -Werror=format-security --without-oss --enable-win32

