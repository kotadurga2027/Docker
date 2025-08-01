FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
ADD https://www.google.com/ usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
ADD sample-2.tar /tmp/
LABEL COURSE="Devops" \
      TRAINER="Kota durga" \
      DURATION="120hrs"
CMD ["nginx","-g","daemon off;"]