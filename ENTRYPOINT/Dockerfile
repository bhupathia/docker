FROM almalinux:8 
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "hello welcome to dockerfile , a way of own images" > /usr/share/nginx/html/index.html
## daemon off command makes our container running snd attached to screen
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]

