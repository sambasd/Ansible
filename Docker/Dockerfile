FROM redhat/ubi10:latest

RUN dnf install -y nginx curl wget vim \
    && dnf clean all

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]