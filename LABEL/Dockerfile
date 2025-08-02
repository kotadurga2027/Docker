FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
RUN https://freefrontend.com/ usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
LABEL  COURSE ="dEVOPS" \
       NAME ="Kotadurga" \
       DURATION="120HRS"
CMD ["nginx","-g","daemon off;"]
