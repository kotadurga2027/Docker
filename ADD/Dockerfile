FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://getsamplefiles.com/sample-archive-files/tar#google_vignette /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-2.tar /tmp/
CMD ["nginx", "-g","daemong off;"]