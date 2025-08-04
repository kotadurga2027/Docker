FROM almalinux:9
#CMD ["ping","google.com"] we can override the CMD instaruction  while we are runing the container
ENTRYPOINT ["ping","facebook.com"] 
# we can't override the ENTRYPOINT command while we are running the container
CMD ["google.com"]
ENTRYPOINT ["ping"]
# Using both instructions we can override the google.com with facebook.com , because here we have give the ping command in entrypoint