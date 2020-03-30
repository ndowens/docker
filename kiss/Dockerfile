FROM scratch 
ADD https://github.com/ndowens/docker/raw/master/kiss/kiss.tar.xz /kiss.tar.xz
ADD /kiss.tar.xz /
LABEL name="KISS Linux"
ENV KISS_PATH=/var/db/kiss/repo/core:/var/db/kiss/repo/extra:/var/db/kiss/repo/xorg
CMD ["/usr/bin/sh"]
