FROM scratch
ADD centos-7-docker.tar.xz /

LABEL name="CentOS Base Image" \
    vendor="CentOS" \
    license="GPLv2" \
    build-date="20170605"

# Add a work directory
RUN mkdir -p /work

VOLUME /work
WORKDIR /work

EXPOSE 80
EXPOSE 3000


CMD ["/bin/bash"]
