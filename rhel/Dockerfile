FROM registry.redhat.io/rhel10/rhel-bootc:10.0-1750931659

RUN echo "%wheel        ALL=(ALL)       NOPASSWD: ALL" > /etc/sudoers.d/wheel-sudo

RUN dnf -y install \
    cockpit \
    ; dnf -y clean all

RUN systemctl enable cockpit.socket

RUN bootc container lint
