FROM redhat/ubi10

RUN dnf install -y nginx nfs-utils curl wget vim \
    && dnf clean all

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]