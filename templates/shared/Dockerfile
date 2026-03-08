ARG VER=10
FROM quay.io/almalinuxorg/almalinux:$ARG
COPY hello.txt /hello.txt
RUN dnf install -y ipmitool && cat /hello.txt
