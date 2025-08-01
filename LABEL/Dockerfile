FROM almalinux:9
RUN dnf install nginx
RUN rm -rf usr/share/nginx/html/index.html
ADD https://docs.docker.com usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
ADD sample-2.tar /tmp/
CMD ["nginx" "-g" "daemon off;"]