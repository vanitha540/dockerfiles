FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/vanitha540/expense-infra-dev.git/refs/heads/main/readme.MD /usr/share/nginx/html/index.html


CMD ["nginx", "-g", "daemon off;"]