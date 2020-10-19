FROM scratch
ADD adelie.txz /
RUN apk update
RUN apk add git abuild gcc zsh bash
RUN useradd -mG wheel,abuild abuilder -p pass
RUN git clone https://code.foxkit.us/adelie/packages.git /home/abuilder/packages
RUN cd /home/abuilder/packages
WORKDIR /home/abuilder/packages
RUN su abuilder -c "abuild-keygen -ain"
CMD su abuilder -c "abuild -r"
