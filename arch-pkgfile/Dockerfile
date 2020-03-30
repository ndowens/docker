FROM archlinux
COPY pacman.conf /etc/pacman.conf
COPY mirrorlist /etc/pacman.d
ARG PKG=
RUN pacman -Sy
RUN pacman -S --noconfirm pkgfile
