FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
RUN useradd kotadurga
USER kotadurga
CMD ["facebook.com"]
ENTRYPOINT ["ping"]