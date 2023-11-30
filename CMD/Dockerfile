FROM almalinux:8 
RUN yum install nginx -y
RUN echo "hello welcome to dockerfile , a way of own images" > /usr/share/nginx/hello.html
## daemon off command makes our container running snd attached to screen
CMD [ "nginx", "-g", "daemonoff" ]

