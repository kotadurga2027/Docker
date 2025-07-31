FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://chatgpt.com/c/688acf69-a360-8005-90e2-12a39f5ab2e1 /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-2.tar /tmp/
CMD ["nginx", "-g","daemong off;"]