FROM archlinux
ADD https://raw.githubusercontent.com/ndowens/docker/master/arch-pkgfile/pacman.conf /etc/pacman.conf
ADD https://raw.githubusercontent.com/ndowens/docker/master/arch-pkgfile/mirrorlist /etc/pacman.d
ARG PKG=
RUN pacman -Sy
RUN pacman -S --noconfirm pkgfile
