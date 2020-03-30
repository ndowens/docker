FROM archlinux:latest
ADD https://raw.githubusercontent.com/ndowens/docker/master/arch-pkgfile/mirrorlist /etc/pacman.d/mirrorlist
ADD https://raw.githubusercontent.com/ndowens/docker/master/arch-pkgfile/pacman.conf /etc/pacman.conf
RUN pacman -Sy
RUN pacman -S --noconfirm pkgfile

