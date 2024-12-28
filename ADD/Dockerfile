FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD sample-1.zip /tmp/
CMD ["nginx","-g","daemon off;"]