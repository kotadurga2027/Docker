FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/shre/nginx/html/index.html
ADD https://docs.docker.com/engine/install/rhel/ usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
LABEL COURSE="devops" \
      NAME="KOTADURGA" \
      DURATION="120HRS"
CMD ["nginx", "-g","daemon off;"]