FROM almalinux:9
RUN dnf install nginx -y
RUN useradd Kotadurga
USER Kotadurga
CMD ["nginx","-g","daemon off;"]