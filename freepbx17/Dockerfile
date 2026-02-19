FROM debian:13.3

RUN apt-get update && \
    apt-get install --no-install-recommends -y curl gnupg ca-certificates wget

RUN wget https://github.com/FreePBX/sng_freepbx_debian_install/raw/master/sng_freepbx_debian_install.sh -O /tmp/sng_freepbx_debian_install.sh && \
    bash /tmp/sng_freepbx_debian_install.sh

