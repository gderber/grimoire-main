./autogen.sh &&
./configure     --prefix=${INSTALL_ROOT}/ \
            --sysconfdir=${INSTALL_ROOT}/etc \
         --localstatedir=${INSTALL_ROOT}/var \
                --mandir=${INSTALL_ROOT}/usr/share/man \
               --infodir=${INSTALL_ROOT}/usr/share/info \
            --includedir=${INSTALL_ROOT}/usr/include \
             --localedir=${INSTALL_ROOT}/usr/share/locale \
           --with-distro=other \
          --with-rootdir=${INSTALL_ROOT}/ \
	    --enable-split-usr       \
            --disable-firstboot      \
            --disable-ldconfig       \
            --disable-sysusers       \
            --with-default-dnssec=no \
            --docdir=/usr/share/doc/systemd-231
                           $OPTS

make
