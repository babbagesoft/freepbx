FROM debian:13.3

RUN su root && \
    wcurl -o /tmp/sng_freepbx_debian_install.sh https://github.com/FreePBX/sng_freepbx_debian_install/raw/master/sng_freepbx_debian_install.sh
RUN bash /tmp/sng_freepbx_debian_install.sh